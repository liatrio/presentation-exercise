# DevOps Engineering Exercise

![alt text](screenshot.png)

In this exercise, you will be acting as a developer in an Enterprise level
organization.

For your first task, you will be fixing code another developer wrote, a
common occurance at a typical developer job. You and the developer have been
working on different features for the application but began at the same time.
The developer had written his code on the branch, "feature_A", 
and has already merged his code into master. You will be fixing his code 
on your own branch labeled, "feature_B", which already has some commits.

Take the following steps to fix the dev's code:
1. Fork the repository to your own account on Github.
  <https://github.com/liatrio/presentation-exercise>
2. Clone the repo onto your machine.
3. Change from the "master" branch to your "feature_B" branch.
4. Fix the developer's mistake on line 272 of the index.html file to increment
time correctly.
5. Commit your changes and push them up to GitHub.
6. Merge your branch into master and fix any merge conflicts.
7. Goto to Travis-CI <https://travis-ci.org/> and sign in with Github.
8. Navigate to your profile, and switch on the presentation-exercise repository. The repository may take a few seconds to show up.
9. Now head back to Github to generate an access token under __PROFILE ICON__ -> __Settings__ -> __Developer settings__ -> __Personal access tokens__
10. Enter your access token in Travis-CI by opening the presentation-exercise repository settings (look for the ![alt text](https://github.com/liatrio/presentation-exercise/blob/master/Icon.png "travis-icon") icon) and enter your auth token under Environemnt Variables. Use the name
`GITHUB_TOKEN` and make sure that "Display value in build log" is inactivate. 
11. Head back to the Dashboard and trigger a build for presentation-exercise.
12. If your build succeeded, head over back to your fork of your Github repo,
go to your environment tab, and click on view deployment to view the web page!
13. (OPTIONAL) Make a change to the index file and redeploy it to your changes
on your web page. The change may take some time after committing due to
Travis-CI. You can also navigate to your Travis-CI build status from your
Github repo commit history.
