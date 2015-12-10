# KOver [A Customizable KODI skin]

KOver (for KODI Overlay) offers a different approach of KODI skins. Not just purely designed, it also offers to the user the possibility to **customize it and make thousands of configurations**.
Born to be a PVR oriented skin with a half screen approach, the way the layout was coded evolved in time to allow to dynamically **change positions, sizes, colors and much more to your needs**.
However, because spending time into making it to look how you want is not the taste of everyone, **KOver can also build itself** with some presets.

* [Official Development thread](http://forum.kodi.tv/showthread.php?tid=207581)
* [Official Community page](https://plus.google.com/u/0/b/102331461184341553815/communities/101384208271707123426)
* [Support KOver - Donate](http://pledgie.com/campaigns/30029)

## First start and Basic features

When installing KOver and launching it for the first time, it will write some settings as minimum requirements for the skin to display correctly. Straight after the first start, only one viewtype per section will be available. You have then 2 options :

* Use the [autobuild](https://github.com/Jayz2K/skin.KOver#auto-build) feature to populate viewtypes
* Use the Designer to build your own viewtypes

### Auto Build

`SETTINGS > SKIN SETTINGS > AUTOBUILD`

As said, the auto build feature is made for you to not spend time making all your viewtypes. It's also a good way to see what is possible to do with KOver before you start using the Designer. You will be able to modify the built viewtype after applying the auto build.

#### Auto Build : viewtypes

You can populate KOver with 5 different viewtypes sets : 2 for a PVR use and 3 for a fullscreen use.

| Name | Description |
| -------------------------- |  ----------- |
| **PVR : Horizontal** | Provides a set of viewtypes half screen in horizontal mode. |
| **PVR : Vertical** | Provides a set of viewtypes half screen in vertical mode. |
| **Fullscreen : Classic** | Provides a set of viewtypes full screen. Almost all the screen space is used. |
| **Fullscreen : Two-thirds** | Provides a set of viewtypes full screen. 2/3 of the screen is used, gives a more confortable view. |
| **Fullscreen : Hybrid** | Provides a set of viewtypes full screen. Combine some viewtype of the 2 above presets. |

#### Auto Build : colors

You can apply 4 built-in color schemes.

| Name | Description |
| ---------- |  ----------- |
| **Default dark** | Apply a dark/colorful color scheme. A good one for TVs. It's also the one provided at first launch. |
| **Default light** | Apply a light/colorful color scheme. A good one for computer screens. |
| **Default FTV style** | Apply a dark/orange color scheme. Reproduces the FTV UI colors. |
| **Default Flat style** | Apply a dark/blue color scheme. Gives a 'Flat' style to the UI. |

### Customizing Home

`SETTINGS > SKIN SETTINGS > GENERAL SETUP > EDIT HOME MENU ...`

You can customize KOver home menu like many other skins by setting your menu items and icons. But KOver pushes the personal settings further with extending viewtypes to the Home menu. You can build viewtypes for home like you make them for libraries.
When using the AUTOBUILD feature, KOver provides 3 default viewtypes you can choose. At first launch, the first viewtype is set by default showing you only the submenus. You might want to change this by setting showing widgets instead.

#### Customizing Home menu items

| Name | Feature | Description |
| ---------- | ---------- | ----------- |
| **Select widget** | Common | Choose the widget to display for the item. |
| **Select background** | Common | Choose the picture to display as wallpaper. |
| **Select viewtype** | KOver | Choose the viewtype to display for the item. See [Select viewtype](https://github.com/Jayz2K/skin.KOver#select-viewtype) |
| **Select Bloc 4 Picture** | KOver | Choose an additional picture to display in Bloc 4 (see Designer). |
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

As explained above, KOver allows you to build your own viewtypes and attach them to any Home item.

```
At first launch, you won't see any widget until you set a viewtype made for it (the default one only shows submenu).
```

If you haven't made viewtypes changes in the designer or if you applied a preset from autobuild, you will get the 3 following viewtypes available when you `Select viewtype`

| Name | Description |
| ---------- | ----------- |
| **Home Layout** | This is the default viewtype. Only shows submenu for the mainmenu item. |
| **Libraries** | This is a widget viewtype. Shows the item's widget and switches to submenu using navigation. |
| **Live TV** | This is a widget viewtype. Shows the item's widget and switches to submenu using navigation. Optimized for live tv widget. |

## Advanced features

Advanced features are what makes KOver different. 3 powerfull tools will let you make thousands of combinations between layouts and colors.

* KOver Designer : A WYSIWYG editor for viewtypes building
* KOver Color tool : A WYSIWYG editor for color schemes creation
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

You can create / change the viewtypes for the following sections

| Name | Description |
| ---------- | ----------- |
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
* Copy template to view. [See Working with templates]()

You can access more options for an existing viewtype by clicking on ViewX or it's name. You will then be able to :

* Rename the viewtype (the name that will be displayed as selectable)
* Copy view to template. [See Working with templates]()

###### Exception for epg

EPG window (KODI) doesn't manage viewtypes. In order to customize it, use only the first viewtype in the **TV** [section](https://github.com/Jayz2K/skin.KOver#sections).

###### Exception for extended infos

Extended Infos window (SCRIPT) doesn't manage viewtypes. In order to customize it, use only the first viewtype in the **Programs** [section](https://github.com/Jayz2K/skin.KOver#sections).

#### Blocs

Each viewtype is made of wallpaper, furnitures, 5 blocs and their background. Each bloc has its specific content

| Name | Description |
| -------------------------- | - |
| **[Wallpaper](https://github.com/Jayz2K/skin.KOver#wallpaper)** | You can set the wallpaper's style, choose your own picture or just hide it. |
| **[General Setup](https://github.com/Jayz2K/skin.KOver#general-setup)** | Change the layout orientation or sidebar, dialog panel and separators options. |
| **[Blocs background](https://github.com/Jayz2K/skin.KOver#blocs-background)** | Change the position, size and visibility of the blocs barckground. |
| **[Bloc 1 : List]** | Dedicated to the main nav list (ex. movies, songs). Change the position, size, visibility and list type. |
| **[Bloc 2 : Infos]** | Dedicated to the selected item informations (ex. Duration, plot and iten position in the list). Change the position, size and visibility. |
| **[Bloc 3 : Art]** | Dedicated to the selected item art (ex. Fanart, thumb). Change the position, size and visibility. |
| **[Bloc 4 : Video / Home art]** | If you're in home [section](https://github.com/Jayz2K/skin.KOver#select-viewtype), display the homeart set in Edit Home menu ... .If you're not in Home, embed the current playing video. Change the position, size and visibility. |
| **[Bloc 5 : Submenu]** | Dedicated to the item context menu. Change the position, size and visibility. Also toggles visibility of the other blocs. |

#### Settings

Each blocs has a certain amount of settings you can give different values

##### Wallpaper


