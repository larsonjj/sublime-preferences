Jake's Sublime Text 2 Preferences
===================

A collection of my Sublime Text 2 Preferences

## Setup
1. Install Sublime Text Editor ([Link](http://www.sublimetext.com/))
2. Place theme (/themes) in the packages folder (~Library/Applications/Sublime/Packages/User)
3. Place preference file (/preferences) in the packages folder (~Library/Applications/Sublime/Packages/User)
4. Install Package Manager
```python
import urllib2,os; pf='Package Control.sublime-package'; ipp = sublime.installed_packages_path(); os.makedirs( ipp ) if not os.path.exists(ipp) else None; urllib2.install_opener( urllib2.build_opener( urllib2.ProxyHandler( ))); open( os.path.join( ipp, pf), 'wb' ).write( urllib2.urlopen( 'http://sublime.wbond.net/' +pf.replace( ' ','%20' )).read()); print( 'Please restart Sublime Text to finish installation')
```
5. Install Centurion Theme via Package Manager
	Cmd+Shift+P
6. Enjoy!

## Included Themes

Included are the following themes:
1. Espresso Custom (Customised 'Light' Theme based off of Espresso) - Install Soda-Light theme instead of Centurion.
2. Tomorrow Night Eighties ([Link](https://github.com/chriskempson/tomorrow-theme))

## Additional Resources

Other Resources needed for my sublime setup:
1. Centurion Theme ([Link](https://github.com/allanhortle/Centurion))