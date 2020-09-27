steps for installing
1.) create folder 
2.) go to folder and clone this repo
3.)open git bash in folder and type git submodules init 
4.)then type git submodules update

submodules
1.)go to submodule folder (charlesFront/Backend)
2.) at start there are 2 branches, HEAD and master
3.)switch to master (git checkout master)
4.) now this operates like a normal git repo except. But everytime u push, the repo 
of chosen submodule will be updated. Like the actual git repo and not the charlesMEAN
5.) so everytime u commit in a submodule, git add and commit the files for changes to
be saved in main folder(charlesMEAN). Then evertime u push, the git repo would be 
updated
6.) dont forget to use branches when u plan on making a change, applies to submodules too.

