![vim master](https://i.imgur.com/WXVNDX0.png) 

# This project is being ported to Neovim

### Install
The process below will write/change the `.vimrc` file content.

During the install process you will be asked about features support. For now you can enable or
disable support for:
* Syntax and Colorscheme (RECOMMENDED)
* Python
* Javascript
* Frontend
* Autocomplete
* Beta features

```
$ git clone https://github.com/ThiagoLopes/vim-master.git ~/.vimconfigs
$ cd ~/.vimconfigs
$ sh install.sh
```
Start your Neovim.

### Update
To update your vim-master with latest features, just run the following command:
```$ cd ~/.vimconfigs && sh update.sh```


### Uninstall
To disable the configs from vim-master project, just rewrite your `.vimrc` file with your own
configs, or keep it empty.

To completly uninstall plugins:
```
$ rm -r ~/.vimconfigs/plugged
```

### Requeriments

* [Hack](https://github.com/chrissimpkins/Hack) Fonts!
* `exuberant-ctags` on DEB/RPM distros
* Make sure you have `vim-gtk` or `vim-gnome` package installed so copy and paste can work well
with system's clipboard
* flake8 is needed to Python checks.

#### Thanks: 
* [Inspiration in amix repo](https://github.com/amix/vimrc) 
* [Vim Bootstrap, reference of most used plugins](https://github.com/avelino/vim-bootstrap)
* [Vim awesome for the top list plugins](http://vimawesome.com)
* For all who contributed
