Installation:

```bash
  git clone https://github.com/davidbl/dotvim ~/.vim
````

Create symlinks:

```bash
  ln -s ~/.vim/vimrc ~/.vimrc
  ln -s ~/.vim/gvimrc ~/.gvimrc #optional
````

Switch to the `~/.vim` directory, and fetch submodules:

```bash
  cd ~/.vim
  git submodule init
  git submodule update
````


To install plugin as a git submodule, take the following steps:
```bash
  cd ~/.vim
  mkdir ~/.vim/bundle
  git submodule add http://github.com/<user_name>/<bundle_name>.git bundle/<bundle_name>
  git add .
  git commit -m "Install <bundle_name>.vim bundle as a submodule."
````
