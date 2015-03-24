## Installed Packages

-	**via Package Control**

	I'm using [Package Control][] to add packages that don't have a Git 
	Repository or those I that don't have any contributions to.

	-	[Alignment][]
	-	[Jade][]
	-	[JSHint][]
	-	[Modific][]
	-	[MSBuild][]
	-	[Nettuts+ Fetch][]
	-	[PHP-Twig][]
	-	[Puppet][]
	-	[Razor][]
	-	[Sass][]
	-	[SublimeCodeIntel][]
	-	[VBScript][]
	-	[Wrap Plus][]

-	**via Git Submodules**

	Git is much less exciting and only updates when I tell it to, but I can 
	also try out my own changes on submodules without worrying about them 
	being lost on an update.

	-	[ApacheConf](https://github.com/colinta/ApacheConf.tmLanguage)
	-	[AutoFileName](https://github.com/BoundInCode/AutoFileName)
	-	[Emmet](https://github.com/sergeche/emmet-sublime)
	-	[Git](https://github.com/kemayo/sublime-text-2-git)
	-	[JsFormat](https://github.com/jdc0589/JsFormat)
	-	[LESS-sublime](https://github.com/danro/LESS-sublime)
	-	[Theme - Spacegray](https://github.com/kkga/spacegray)
	-	[ZenTabs](https://github.com/travmik/ZenTabs)

## Updating Packages

Package Control Packages are automatically updated when you enable the plugin. 
Git Packages can be updated using `update-submodules.sh` which will bring each 
repository up-to-date with the master branch of the origin repository.

## Enable Package Control

I've disabled the [Package Control] plugin by default because it slows down 
Sublime. Just open up `Packages/User/Preferences.sublime-settings`, comment 
out the "Package Control" line and save. Sublime will load it automatically.

  [Alignment]: https://wbond.net/sublime_packages/alignment
  [Jade]: https://packagecontrol.io/packages/Jade
  [JSHint]: https://packagecontrol.io/packages/JSHint
  [Modific]: https://sublime.wbond.net/packages/Modific
  [MSBuild]: https://sublime.wbond.net/packages/MSBuild
  [Nettuts+ Fetch]: http://net.tutsplus.com/articles/news/introducing-nettuts-fetch/
  [Package Control]: https://wbond.net/sublime_packages/package_control
  [PHP-Twig]: https://sublime.wbond.net/packages/PHP-Twig
  [Puppet]: https://sublime.wbond.net/packages/Puppet
  [Razor]: https://sublime.wbond.net/packages/Razor
  [Sass]: https://sublime.wbond.net/packages/Sass
  [SublimeCodeIntel]: https://packagecontrol.io/packages/SublimeCodeIntel
  [VBScript]: https://sublime.wbond.net/packages/VBScript
  [Wrap Plus]: https://sublime.wbond.net/packages/Wrap%20Plus
