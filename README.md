This repo is being installed as a submodule in the folder named "public" of the source code repo.
In case something happens, this can be fully overriden.
1. Delete the folder "public"
2. Edit .gitmodules and remove this submodule
3. Edit .git/config and remove this submodule
4. Delete the folder "public" from .git/modules
5. Run command: git rm -r --cached public
6. Run command: git submodule add -b main <repo> public
7. After cloning, delete entire content but the .git file
8. Regenerate content in public using hugo.
