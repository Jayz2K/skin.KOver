# KOver [A Customizable KODI skin]

KOver (for KODI Overlay) offers a different approach of KODI skins. Not just purely designed, it also offers to the user the possibility to **customize it and make thousands of configurations**.
Born to be a PVR oriented skin with a half screen approach, the way the layout was coded evolved in time to allow to dynamically **change positions, sizes, colors and much more to your needs**.
However, because spending time into making it to look how you want is not the taste of everyone, **KOver can also build itself** with some presets.

* [Official Development thread](http://forum.kodi.tv/showthread.php?tid=207581)
* [Official Community page](https://plus.google.com/u/0/b/102331461184341553815/communities/101384208271707123426)
* [Support KOver - Donate](http://pledgie.com/campaigns/30029)

## Menu

* [First start and Basic features](https://github.com/Jayz2K/skin.KOver#first-start-and-basic-features)
 * [Auto Build](https://github.com/Jayz2K/skin.KOver#auto-build)
  * [Auto Build : Viewtypes](https://github.com/Jayz2K/skin.KOver#auto-build--viewtypes)
  * [Auto Build : Colors](https://github.com/Jayz2K/skin.KOver#auto-build--colors)
 * [Customizing Home](https://github.com/Jayz2K/skin.KOver#customizing-home)
  * [Customizing Home menu Items](https://github.com/Jayz2K/skin.KOver#customizing-home-menu-items)
  * [Select Viewtype](https://github.com/Jayz2K/skin.KOver#select-viewtype)
* [Advanced Features](https://github.com/Jayz2K/skin.KOver#advanced-features)
 * [KOver Designer](https://github.com/Jayz2K/skin.KOver#kover-designer)
  * [Sections](https://github.com/Jayz2K/skin.KOver#sections)
  * [Viewtypes](https://github.com/Jayz2K/skin.KOver#viewtypes)
   * [Exception for EPG](https://github.com/Jayz2K/skin.KOver#exception-for-epg)
   * [Esception for Extended Infos](https://github.com/Jayz2K/skin.KOver#exception-for-extended-infos)
  * [Blocs](https://github.com/Jayz2K/skin.KOver#blocs)
  * [Settings](https://github.com/Jayz2K/skin.KOver#settings)
   * [Common](https://github.com/Jayz2K/skin.KOver#common)
    * [Sizing / positioning limitations](https://github.com/Jayz2K/skin.KOver#sizing--positioning-limitations)
	* [IdleFade](https://github.com/Jayz2K/skin.KOver#idlefade)
   * [Wallpaper](https://github.com/Jayz2K/skin.KOver#wallpaper)
   * [General Setup](https://github.com/Jayz2K/skin.KOver#general-setup)
   * [Blocs Background](https://github.com/Jayz2K/skin.KOver#blocs-background)
   * [Bloc 1 : List](https://github.com/Jayz2K/skin.KOver#bloc1--list)
   * [Bloc 2 : Infos](https://github.com/Jayz2K/skin.KOver#bloc2--infos)
   * [Bloc 3 : Art](https://github.com/Jayz2K/skin.KOver#bloc3--art)
   * [Bloc 4 : Video / Home art](https://github.com/Jayz2K/skin.KOver#bloc4--video--home-art)
   * [Bloc 5 : Submenu](https://github.com/Jayz2K/skin.KOver#bloc5--submenu)
  * [Working with Templates](https://github.com/Jayz2K/skin.KOver#working-with-templates)
 * [KOver Color Tool](https://github.com/Jayz2K/skin.KOver#kover-color-tool)
 * [Import / Export features](https://github.com/Jayz2K/skin.KOver#import--export-features)
 

## First start and Basic features

When installing KOver and launching it for the first time, it will write some settings as minimum requirements for the skin to display correctly. Straight after the first start, only one viewtype per section will be available. You have then 2 options :

* Use the [autobuild](https://github.com/Jayz2K/skin.KOver#auto-build) feature to populate viewtypes
* Use the [Designer](https://github.com/Jayz2K/skin.KOver#kover-designer) to build your own viewtypes

### Auto Build

`SETTINGS > SKIN SETTINGS > AUTOBUILD`

As said, the auto build feature is made for you to not spend time making all your viewtypes. It's also a good way to see what is possible to do with KOver before you start using the Designer. You will be able to modify the built viewtype after applying the auto build.

#### Auto Build : viewtypes

You can populate KOver with 5 different viewtypes sets : 2 for a PVR use and 3 for a fullscreen use.

| Name | Description |
| :-----------: |  ----------- |
| **PVR : Horizontal** | Provides a set of viewtypes half screen in horizontal mode. |
| **PVR : Vertical** | Provides a set of viewtypes half screen in vertical mode. |
| **Fullscreen : Classic** | Provides a set of viewtypes full screen. Almost all the screen space is used. |
| **Fullscreen : Two-thirds** | Provides a set of viewtypes full screen. 2/3 of the screen is used, gives a more confortable view. |
| **Fullscreen : Hybrid** | Provides a set of viewtypes full screen. Combine some viewtype of the 2 above presets. |

#### Auto Build : colors

You can apply 4 built-in color schemes.

| Name | Description |
| :-----------: |  ----------- |
| **Default dark** | Apply a dark/colorful color scheme. A good one for TVs. It's also the one provided at first launch. |
| **Default light** | Apply a light/colorful color scheme. A good one for computer screens. |
| **Default FTV style** | Apply a dark/orange color scheme. Reproduces the FTV UI colors. |
| **Default Flat style** | Apply a dark/blue color scheme. Gives a 'Flat' style to the UI. |

### Customizing Home

`SETTINGS > SKIN SETTINGS > GENERAL SETUP > EDIT HOME MENU ...`

You can customize KOver home menu like many other skins by setting your menu items and icons. But KOver pushes the personal settings further with extending viewtypes to the Home menu. You can build viewtypes for home like you make them for libraries.
When using the [autobuild](https://github.com/Jayz2K/skin.KOver#autobuild) feature, KOver provides 3 default viewtypes you can choose. At first launch, the first viewtype is set by default showing you only the submenus. You might want to change this by setting showing widgets instead.

#### Customizing Home menu items

| Name | Feature | Description |
| :-----------: | :-----------: | ----------- |
| **Select widget** | Common | Choose the widget to display for the item. |
| **Select background** | Common | Choose the picture to display as wallpaper. |
| **[Select viewtype](https://github.com/Jayz2K/skin.KOver#select-viewtype)** | KOver | Choose the viewtype to display for the item. See [Select viewtype](https://github.com/Jayz2K/skin.KOver#select-viewtype) |
| **Select Bloc 4 Picture** | KOver | Choose an additional picture to display in [Bloc 4](https://github.com/Jayz2K/skin.KOver#bloc4--video--home-art). |
| **Choose shortcut** | Common | Choose the target for the item. |
| **Set label** | Common | Choose the name to display for the item. |
| **Change icon** | Common | Choose the icon to display for the item. |
| **Change action** | Common | Overrides the onclick action. |
| **Customize submenu** | Common | Open the next level settings for the item. |
| **Move left** | Common | Reorder items. |
| **Move right** | Common | Reorder items. |
| **Add** | Common | Add a new item. |
| **Delete** | Common | Delete item. |

#### Select viewtype

As explained above, KOver allows you to build your own [viewtypes](https://github.com/Jayz2K/skin.KOver#viewtypes) and attach them to any Home item.

> At first launch, you won't see any widget until you set a [viewtype](https://github.com/Jayz2K/skin.KOver#viewtypes) made for it (the default one only shows submenu).

If you haven't made viewtypes changes in the designer or if you applied a preset from [autobuild](https://github.com/Jayz2K/skin.KOver#autobuild), you will get the 3 following [viewtypes](https://github.com/Jayz2K/skin.KOver#viewtypes) available when you `Select viewtype`

| Name | Description |
| :-----------: | ----------- |
| **Home Layout** | This is the default [viewtype](https://github.com/Jayz2K/skin.KOver#viewtypes). Only shows submenu for the mainmenu item. |
| **Libraries** | This is a widget [viewtype](https://github.com/Jayz2K/skin.KOver#viewtypes). Shows the item's widget and switches to submenu using navigation. |
| **Live TV** | This is a widget [viewtype](https://github.com/Jayz2K/skin.KOver#viewtypes). Shows the item's widget and switches to submenu using navigation. Optimized for live tv widget. |

## Advanced features

Advanced features are what makes KOver different. 3 powerfull tools will let you make thousands of combinations between layouts and colors.

* [KOver Designer](https://github.com/Jayz2K/skin.KOver#kover-designer) : A WYSIWYG editor for viewtypes building
* [KOver Color tool](https://github.com/Jayz2K/skin.KOver#kover-color-tool) : A WYSIWYG editor for color schemes creation
* Import / Export : A set of import / export feature for sharing or importing community creations made with Designer and Color tool

**Since those are advanced features, they are disabled by default. Enable them in**

`SETTINGS > SKIN SETTINGS > GENERAL SETUP`

### KOver Designer

KOver Designer is the core of KOver. The whole skin is build around this powerful layout manager. The designer has been made to be as simple as possible to use straight forward. It works with a tree logic :

> Section where you want to create the viewtype
    > The viewtype you want to create / editor
	    > The bloc inside the viewtype you want to configure
		    > The setting you want to change
			
#### Sections

You can create / change the [viewtypes](https://github.com/Jayz2K/skin.KOver#viewtypes) for the following sections

| Name | Description |
| :-----------: | ----------- |
| **Home** | Viewtypes 1 to 9 will be selectable in the "Edit Home menu ...". Each available viewtype can be attached to any main menu item. |
| **Videos** | Viewtypes 1 to 9 will be selectable in the library context menu. Apply to videos, movies and tvshows (video content). |
| **Music** | Viewtypes 1 to 9 will be selectable in the library context menu. Apply to artists, albums (music content). |
| **TV** | Viewtypes 1 to 9 will be selectable in the library context menu. Apply to channels, epg (PVR content). See [exception for epg](https://github.com/Jayz2K/skin.KOver#exception-for-epg). |
| **Pictures** | Viewtypes 1 to 9 will be selectable in the library context menu. Apply to pictures. |
| **Programs** | Viewtypes 1 to 9 will be selectable in the library context menu. Apply to addons, programs and some addons content. See [exception for extended infos](https://github.com/Jayz2K/skin.KOver#exception-for-extended-infos). |
| **Weather** | Viewtypes 1 only applies to Weather. Weather window (KODI) doesn't manage viewtypes. |

#### Viewtypes

In almost all cases, you can create / change up to 9 viewtypes per [section](https://github.com/Jayz2K/skin.KOver#sections). 
You can create a new viewtype in an empty slot with :

* Apply Default Horizontal / Vertical
* Copy template to view. [See Working with templates](https://github.com/Jayz2K/skin.KOver#working-with-templates)

You can access more options for an existing viewtype by clicking on ViewX or it's name. You will then be able to :

* Rename the viewtype (the name that will be displayed as selectable)
* Copy view to template. [See Working with templates](https://github.com/Jayz2K/skin.KOver#working-with-templates)

###### Exception for epg

> EPG window (KODI) doesn't manage [viewtypes](https://github.com/Jayz2K/skin.KOver#viewtypes). In order to customize it, use only the first [viewtype](https://github.com/Jayz2K/skin.KOver#viewtypes) in the **TV** [section](https://github.com/Jayz2K/skin.KOver#sections).

###### Exception for extended infos

> Extended Infos window (SCRIPT) doesn't manage viewtypes. In order to customize it, use only the first viewtype in the **Programs** [section](https://github.com/Jayz2K/skin.KOver#sections).

#### Blocs

Each viewtype is made of wallpaper, furnitures, 5 blocs and their background. Each bloc has its specific content

| Name | Description |
| :-----------: | ----------- |
| **[Wallpaper](https://github.com/Jayz2K/skin.KOver#wallpaper)** | You can set the wallpaper's style, choose your own picture or just hide it. |
| **[General Setup](https://github.com/Jayz2K/skin.KOver#general-setup)** | Change the layout orientation or sidebar, dialog panel and separators options. |
| **[Blocs background](https://github.com/Jayz2K/skin.KOver#blocs-background)** | Change the position, size and visibility of the blocs barckground. |
| **[Bloc 1 : List](https://github.com/Jayz2K/skin.KOver#bloc1--list)** | Dedicated to the main nav list (ex. movies, songs). Change the position, size, visibility and list type. |
| **[Bloc 2 : Infos](https://github.com/Jayz2K/skin.KOver#bloc2--infos)** | Dedicated to the selected item informations (ex. Duration, plot and iten position in the list). Change the position, size and visibility. |
| **[Bloc 3 : Art](https://github.com/Jayz2K/skin.KOver#bloc3--art)** | Dedicated to the selected item art (ex. Fanart, thumb). Change the position, size and visibility. |
| **[Bloc 4 : Video / Home art](https://github.com/Jayz2K/skin.KOver#bloc4--video--home-art)** | If you're in home [section](https://github.com/Jayz2K/skin.KOver#select-viewtype), display the homeart set in Edit Home menu ... .If you're not in Home, embed the current playing video. Change the position, size and visibility. |
| **[Bloc 5 : Submenu](https://github.com/Jayz2K/skin.KOver#bloc5--submenu)** | Dedicated to the item context menu. Change the position, size and visibility. Also toggles visibility of the other blocs. |

#### Settings

Each bloc has a certain amount of settings you can give different values. Some are commons to most of the blocs, others are specifics.

> Please note that some settings will lock others depending on the given value. For example like for [Sizing / positioning limitations](https://github.com/Jayz2K/skin.KOver#sizing--positioning-limitations).

##### Common

| Name | Description |
| :-----------: | ----------- |
| **Visibility** | You can choose between `VISIBLE` `HIDDEN` `IDLEFADE` `ONFOCUS`. ONFOCUS is available in bloc 5 only. [See idlefade here](https://github.com/Jayz2K/skin.KOver#idlefade). |
| **Horizontal position (column)** | Set the element's start position on the grid (horizontal). You can choose between `A` `B` `C`. |
| **Vertical position (row)** | Set the element's start position on the grid (vertical). You can choose between `A` `B` `C`. |
| **Width** | Set the element's amount of columns on the grid. You can choose between `1COLUMN` `2COLUMN` `3COLUMN`. |
| **Hight** | Set the element's amount of rows on the grid. You can choose between `1ROW` `2ROW` `3ROW`. |

###### Sizing / positioning limitations

> It's usefull for you to know that you CAN'T set a bloc outside the Blocs Background or bigger than it.
Also, reducing / moving the blocs background will move or reduce the blocs inside it in order to fit the new configuration.

###### Idlefade

> The Idelfade feature makes the element to completely fade after a certain amount of seconds. The time fater idlefade starts can be set in

`SETTINGS > SKIN SETTINGS > GENERAL SETUP`

##### Wallpaper

Specifics :

| Name | Description |
| :-----------: | ----------- |
| **Background style** | You can choose between `FANART` `COLOR` `IMAGE` . |
| **Background image** | You can browse for your own picture / pictures set. |

##### General setup

Specifics :

| Name | Description |
| :-----------: | ----------- |
| **Layout Orientation** | Set the whole layout orientation. You can choose between `HORIZONTAL` `VERTICAL`. Mostly used for sidebar position. |
| **Sidebar Position** | Set the sidebar position (sticks to borders). You can choose between `LEFT` `RIGHT` `TOP` `BOTTOM`. |
| **Sidebar Autohide** | Set the sidebar to autohide. You can choose between `DISABLED` `ENABLED` `IDLEFADE`. When blocs background is not 3X3, ENABLED is not available. [See idlefade here](https://github.com/Jayz2K/skin.KOver#idlefade). |
| **Dialog panel Position** | Set the Dialog panel position. You can choose between `LEFT` `RIGHT` `TOP` `BOTTOM`. |
| **Dialog slide Type** | Set the way the dialog panel opens. You can choose between `PUSH` `OVER`. PUSH slides all blocs when the panel's edge reaches one of them. OVER just slide over everything. |
| **Horizontal Separator** | Add a 12 pixels gap between blocs (vertically). You can choose between `AB` `BC` `NONE`. |
| **Vertical Separator** | Add a 12 pixels gap between blocs (horizontally). You can choose between `AB` `BC` `NONE`. |

> Also it's important to note a particularity for Home [section](https://github.com/Jayz2K/skin.KOver#sections). Since setting different positions for the sidebar makes the navigation in the mainmenu impossible, only the first viewtype has the options `Layout Orientation` and `Sidebar Position`. Setting them here will apply to all other viewtypes in Home [section](https://github.com/Jayz2K/skin.KOver#sections).

##### Blocs background

No specifics

##### Bloc1 : List

Specifics :

| Name | Description |
| :-----------: | ----------- |
| **List Type** | Set the look of the list. You can choose between `FIXEDLIST` `WIDELIST` `POSTER` `BANNER` `FANART` `TILES` `CARD` `CUSTOM1` `CUSTOM2` `CUSTOM3`. |
| **List Orientation** | Set the list's scrolling orientation. You can choose between `HORIZONTAL` `VERTICAL`. |
| **Go Submenu** | Set the position for submenu to open when you reach the end of the list. You can choose between `LEFT` `RIGHT` `UP` `DOWN`. |
| **Scroll Indicator** | Show scroll indicators over the list. You can choose between `VISIBLE` `HIDDEN`. Matches the List Orientation. |

##### Bloc2 : Infos

No specifics

##### Bloc3 : Art

Specifics :

| Name | Description |
| :-----------: | ----------- |
| **Art Type** | Set art to show in the bloc. You can choose between `FANART` `POSTER` `THUMB`. When ExtraFanart is enabled, you can also choose `CLEARART` `CLEARLOGO` `DISCART`. |
| **Scroll Indicator** | Show scroll indicators over the arts. You can choose between `VISIBLE` `HIDDEN`. Matches the Bloc1 : List Orientation. |

##### Bloc4 : Video / Home art

No specifics

##### Bloc5 : Submenu

Specifics :

| Name | Description |
| :-----------: | ----------- |
| **List Type** | Home [section](https://github.com/Jayz2K/skin.KOver#sections) only !. Set the look of the list. You can choose between `FIXEDLIST` `WIDELIST` `POSTER` `BANNER` `FANART` `TILES` `CARD`. |
| **List Orientation** | Home [section](https://github.com/Jayz2K/skin.KOver#sections) only !. Set the list's scrolling orientation. You can choose between `HORIZONTAL` `VERTICAL`. |
| **Bloc1 Visibility on Focus** | Set the [Bloc 1](https://github.com/Jayz2K/skin.KOver#blocs) visibility if Bloc5 has focus. You can choose between `VISIBLE` `HIDDEN`. |
| **Bloc2 Visibility on Focus** | Set the [Bloc 2](https://github.com/Jayz2K/skin.KOver#blocs) visibility if Bloc5 has focus. You can choose between `VISIBLE` `HIDDEN`. |
| **Bloc3 Visibility on Focus** | Set the [Bloc 3](https://github.com/Jayz2K/skin.KOver#blocs) visibility if Bloc5 has focus. You can choose between `VISIBLE` `HIDDEN`. |
| **Bloc4 Visibility on Focus** | Set the [Bloc 4](https://github.com/Jayz2K/skin.KOver#blocs) visibility if Bloc5 has focus. You can choose between `VISIBLE` `HIDDEN`. |
| **Go Back** | Set the position for submenu to open when you reach the end of the list. You can choose between `LEFT` `RIGHT` `UP` `DOWN`. |
| **Scroll Indicator** | Home [section](https://github.com/Jayz2K/skin.KOver#sections) only !. Show scroll indicators over the list. You can choose between `VISIBLE` `HIDDEN`. Matches the List Orientation. |

#### Working with templates

When you have set a [viewtype](https://github.com/Jayz2K/skin.KOver#viewtypes), you might want to copy it and only change a few settings like `List type` or `Visibility`. Templates are made for that.
3 templates slots are available for you to copy existing views into it. You can then recall them to apply on empty [viewtypes](https://github.com/Jayz2K/skin.KOver#viewtypes) or override an existing one.

You can access the templates menu by clicking on the [viewtype](https://github.com/Jayz2K/skin.KOver#viewtypes) name. The following options are available :

| Name | Description |
| :-----------: | ----------- |
| **Copy View to Template** | Copy all the settings of the current viewtype in the chosen template. |
| **Copy Template to View** | Copy all the settings from the chosen template to the viewtype. |
| **Export Template** | Export all the settings of the chosen template in a zip file. |
| **Delete Template** | Delete all the settings in the template. |

> Please note that copying in both ways will override all targets' settings. You won't be prompted for confirmation.

> Exporting a template keeps the template number. That means exporting template 1 will result in filling template 1 at zip import. Also importing a template will override the template's content.

> It's recommended for export to give a relevant name and the template number to ensure restoring the correct one.

### KOver Color tool

Many elements of KOver can be colorized. Use the color picker in the Color tool or type directly your own AARRGGBB code. 
AARRGGBB codes can be obtained easily with an online color picker.

### Import / Export features

In progress ...