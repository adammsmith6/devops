# DevOps
![workflow](https://github.com/adammsmith6/devops/actions/workflows/main.yml/badge.svg)
[![LICENSE](https://img.shields.io/github/license/adammsmith6/devops.svg?style=flat-square)](https://github.com/adammsmith6/devops/blob/master/LICENSE)
[![Releases](https://img.shields.io/github/release/adammsmith6/devops/all.svg?style=flat-square)](https://github.com/adammsmith6/devops/releases)

# Our Current Process
We have expanded our process at the start and the end to incorporate our Sprint methodology:

1. Decide which user story/stories to work on for the next Sprint.
2. Create a new Sprint on Zube.
3. Add the user story card(s) to the Ready column in Zube.
4. Add any additional task cards to Zube and put in priority order.
5. Pull the latest develop branch.
6. Start a new feature branch for the task(s) or user story.
7. Select task to work on in Zube.
8. Work on task.
9. Repeat 7-8 until feature is complete.
10. Once feature is finished, create JAR file.
11. Update and test Docker configuration with Travis.
12. Update feature branch with develop to ensure feature is up-to-date.
13. Check feature branch still works.
14. Merge feature branch into develop.
15. Repeat 5-14 until Sprint is complete.
16. Merge develop branch into release and create release.
17. Merge release into master and develop.
18. Close the Sprint.


This is our main process now, and although we might add a few small additions (e.g. around testing), we are in a good place for the remainder of the module.