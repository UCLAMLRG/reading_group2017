# Week 1 Summary

## git: a brief overview of forks and pull requests

As an exercise to learn git, let's fork the reading group repository, edit the readme file and then do a pull request to put back the changes.

1. Fork the reading group repository: click on the fork button at the right side of the main repository page: https://github.com/UCLAMLRG/reading_group2017
2. Once the repository has been forked, you should see it in your list of repositories: ``https://github.com/USERNAME/reading_group2017``
3. Clone YOUR repository to your computer
  - ``git clone git@github.com:USERNAME/reading_group2017.git``
4. Go into the directory ``cd reading_group2017``
5. See what repository it is connected to. Your repoistory should be under ``origin``
  - ``git remote -v``
6. Add the original repository as a link called ``upstream``
  - ``git remote add upstream https://github.com/UCLAMLRG/reading_group2017``
7. Do ``git remote -v`` again. There should be a new link called ``upstream``
8. Make add your github username line next to your name in the README file under Participants section
  - ``A. Name [@USERNAME](https://github.com/USERNAME)``
9. Save your file and then add it to the staging area
  - ``git add README.md``
10. Commit your staged changes
  - ``git commit -m "added username link to readme"``
11. Push your changes to YOUR github repository
  - ``git push origin master``
12. Click on the pull request button on YOUR repository webpage
13. Submit the pull request to the master branch of the https://github.com/UCLAMLRG/reading_group2017 repository
14. Once your pull request is merged, you can pull the changes back into your repository
  - ``git pull upstream master``

## Notes on machine learning terminology
- Features - this is usually known as parameters for physicists when we do parameter estimation.
- 
