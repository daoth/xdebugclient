# XDebugClient #

xdebugclient is a simple Microsoft Windows frontend for the PHP debugger, [Xdebug](http://www.xdebug.org), by Derick Rethans, offering a way to debug your PHP scripts without having to switch to a complete new IDE / editor just for debugging.

## News ##

**24/04/2009** - **XdebugClient 1.0-beta5** is available. Changes in Beta 5 are:

  * Listening port is configurable
  * Breakpoints can be toggled using the F9 key
  * Properties are displayed in tooltip
  * Optionally debugging can be started automatically on script load
  * Bugfixes

[Download XDebugClient 1.0-beta5](http://code.google.com/p/xdebugclient/downloads/list)


**22/04/2009** - **XdebugClient 1.0-beta4** is available. Changes in Beta 4 are:

  * Long strings can be displayed in a new window
  * Only breaks on notices when configured to do so
  * Identifier doesn't need to be selected to be inspected
  * Automatically restart debugging after script finished
  * Log is top-down instead of bottom-up
  * Bugfixes

[Download XDebugClient 1.0-beta4](http://code.google.com/p/xdebugclient/downloads/list)

**30/04/2007** - **XdebugClient 1.0-beta3** is available. Changes in Beta 3 are:

  * Restore ability to open files when using the filename rewriting functionality
  * Further improve filename rewriting functionality in regards to opening files manually
  * Properly redraw remaining breakpoints after terminating debugging session
  * Status form is now readonly

**29/04/2007** - **XdebugClient 1.0-beta2** has been released.
XDebug 1.0-beta2 is available. Check out the [downloads](http://code.google.com/p/xdebugclient/downloads/list). Changes in Beta 2 are :

  * Improved directory rewriting, enabling XDC to open files through the Window XP Network Location service and supporting UNC paths.
  * Ability to open files through XDebug's 'Source' command
  * Binary built with non-debug TreeAdvView component (removes annoying FPS message)
  * Binary built with DockSuite 2.0
  * Enhanced file closing behaviour



**14/04/2007** - **Xdebug 1.0-beta1** has been released.
XDebug 1.0-beta1 is available. Check out the [downloads](http://code.google.com/p/xdebugclient/downloads/list). [Bugreports](http://code.google.com/p/xdebugclient/issues/list) and [suggestions](http://groups.google.com/group/xdebugclient-discuss) are very much appreciated.

## Features ##

  * Small / lightweight - no install required
  * Line-based breakpoints
  * Property inspector
  * Call stack overview at breakpoints
  * Should would fairly well with remote scripts when combined with, say, Samba.
  * Run, Step In, Step Out, Step Over

## Requirements ##

  * Microsoft Windows
  * .NET 2.0 framework ([download](http://www.microsoft.com/downloads/details.aspx?familyid=0856EACB-4362-4B0D-8EDD-AAB15C5E04F5&displaylang=en))

## Screenshot ##
![http://xdebugclient-discuss.googlegroups.com/web/xdc-1.0-beta1.png](http://xdebugclient-discuss.googlegroups.com/web/xdc-1.0-beta1.png)


Stepping through & inspecting variables of phpMyAdmin

## Cross-platform ##
Sorry, at this time xdebugclient only works on Microsoft Windows. It may be possible to port XdebugClient to [Mono](http://www.mono-project.com/Main_Page) fairly easily. Especially since the [MonoDevelop](http://www.monodevelop.com/Main_Page) project has a port of the Sharpdevelop text editor component used by [XDebug](http://www.xdebug) but presently  no work in this direction has been done.

## Authors ##

Mathieu Kooiman < xdc@scriptorama.nl >

## XDebugClient makes fond use of: ##

1. The text editor component by the SharpDevelop team
http://www.icsharpcode.net/

2. The Dockpanel Suite by Weifen Luo
http://sourceforge.net/projects/dockpanelsuite/

3. The Advanced Treeview component by Andrey Gliznetsov
http://www.codeproject.com/cs/miscctrl/treeviewadv.asp

Thanks !