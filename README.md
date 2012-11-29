# Sublime Text 2 Configuration

The Obligatory.

## Installed Packages

-	**via Package Control**

	I'm using [Package Control][] to add packages that don't have a Git Repository.

	-	[Nettuts+ Fetch](http://net.tutsplus.com/articles/news/introducing-nettuts-fetch/)

-	**via Git Submodules**

	Git is much less exciting and only updates when I tell it to, but I can also try out my own changes on submodules without worrying about them being lost on an update.

	-	[ApacheConf](https://github.com/colinta/ApacheConf.tmLanguage)
	-	[AutoFileName](https://github.com/BoundInCode/AutoFileName)
	-	[Color Scheme - Daylerees](https://github.com/daylerees/colour-schemes)
	-	[Git](https://github.com/kemayo/sublime-text-2-git)
	-	[JsFormat](https://github.com/jdc0589/JsFormat)
	-	[LESS-build](https://github.com/sirlancelot/LESS-build-sublime)
	-	[Tag](https://github.com/SublimeText/Tag)
	-	[Theme - Soda](https://github.com/buymeasoda/soda-theme)

## Updating Packages

Package Control Packages are automatically updated. Git Packages can be updated using `update-submodules.sh` which will bring each repository up-to-date with the master branch of the origin repository.

  [Package Control]: http://wbond.net/sublime_packages/package_control
