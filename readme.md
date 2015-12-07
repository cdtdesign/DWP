1. New feature branch: first make sure local master branch is up-to-date with the remote master branch, then create new feature branch for dev of new feature.

	git checkout master

	git branch [new feature branch name]

2. Testing: test out newly developed feature and resolve any errors/conflicts then commit to Git staging server.

	git commit -am ‘[detailed msg here]’
	
	git push [remote link name] master

3. Testing: test new feature on local server and make sure no conflicts exist with other developers features and allow other devs to review your new feature.

4. Tag your new feature: 

	git tag -a VerX.X.X -m ‘[new feature name]’

	git push [remote link name] —tags

5. Advise dev team that your new feature is ready for staging to prevent overlap.

6. Deploy to staging server.

	git push [staging server] master

7. Testing: further testing to see new feature behavior on remote staging server and among other dev features.

8. Communicate with dev team of successful deployment