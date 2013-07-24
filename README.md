## Installed Packages

-	**via Package Control**

	I'm using [Package Control][] to add packages that don't have a Git 
	Repository.

	-	[Nettuts+ Fetch][Fetch]

-	**via Git Submodules**

	Git is much less exciting and only updates when I tell it to, but I can 
	also try out my own changes on submodules without worrying about them 
	being lost on an update.

	-	[ApacheConf](https://github.com/colinta/ApacheConf.tmLanguage)
	-	[AutoFileName](https://github.com/BoundInCode/AutoFileName)
	-	[Color Scheme - Daylerees](https://github.com/daylerees/colour-schemes)
	-	[Emmet](https://github.com/sergeche/emmet-sublime)
	-	[Git](https://github.com/kemayo/sublime-text-2-git)
	-	[JsFormat](https://github.com/jdc0589/JsFormat)
	-	[LESS-build](https://github.com/sirlancelot/LESS-build-sublime)
	-	[LiveReload](https://github.com/dz0ny/LiveReload-sublimetext2)
	-	[Tag](https://github.com/SublimeText/Tag)
	-	[Theme - Centurion](https://github.com/allanhortle/Centurion)

## Updating Packages

Package Control Packages are automatically updated when you enable the plugin. 
Git Packages can be updated using `update-submodules.sh` which will bring each 
repository up-to-date with the master branch of the origin repository.

## Enable Package Control

I've disabled the [Package Control] plugin by default because it slows down 
Sublime. Just open up `Packages/User/Preferences.sublime-settings`, comment 
out the "Package Control" line and save. Sublime will load it automatically.

  [Package Control]: http://wbond.net/sublime_packages/package_control
  [Fetch]: http://net.tutsplus.com/articles/news/introducing-nettuts-fetch/
