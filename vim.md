## change base directory
* http://vim.wikia.com/wiki/Set_working_directory_to_the_current_file
```bash
:pwd
:cd %:p:h
```
## search and replace in project
* http://stackoverflow.com/questions/4804405/search-and-replace-in-vim-across-all-the-project-files 
```bash
:args **/*.sh # opens all files ending with .sh
:argdo %s/pattern/pattern/gce # replaces
```
* g: global
* c: confirm every file
* e: do not show error message when search pattern not found
