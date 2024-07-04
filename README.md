# covid-19-US-county-level-data
This repository combines infectious disease data (COVID-19 cases, deaths, vaccinations) with county-level characteristics (income, demographics, comorbidities)
# Tips for working with this repository
There are a few data files in this repository that exceed github's size limit. If you are making changes to these files, you will need to install the Git Large File Storage before you can push changes to the main branch. Install instructions can be found here: [Git Large File Storage Install Instructions](https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage)
## Pushing changes to large files
Once you've made your edits to the large file, push your changes with the installed commands
```
git lsf push --all origin main
```
Then, proceed with the usual git commands:

1. To add file contents to the index
```
git add <filename.ext>(-A adds all changes in the current directory)
```
2. To record changes to the repository
```
git commit -m "[commit message]"
```
3. To update the main branch with your changes
```
git push
```
