# KOver [A Customizable KODI skin]

KOver (for KODI Overlay) offers a different approach of KODI skins. Not just purely designed, it also offers to the user the possibility to **customize it and make thousands of configurations**.
Born to be a PVR oriented skin with a half screen approach, the way the layout was coded evolved in time to allow to dynamically **change positions, sizes, colors and much more to your needs**.
However, because spending time into making it to look how you want is not the taste of everyone, **KOver can also build itself** with some presets.

* [Official Development thread](http://forum.kodi.tv/showthread.php?tid=207581)
* [Official Community page](https://plus.google.com/u/0/b/102331461184341553815/communities/101384208271707123426)
* [Support KOver - Donate](http://pledgie.com/campaigns/30029)

## First start

When installing KOver and launching it for the first time, it will write some settings as minimum requirements for the skin to display correctly. Straight after the first start, only one viewtype per section will be available. You have then 2 options :

* Use the [autobuild](https://github.com/Jayz2K/skin.KOver#auto-build) feature to populate viewtypes
* Use the Designer to build your own viewtypes

## Auto Build

`SETTINGS > SKIN SETTINGS > AUTOBUILD`

As said, the auto build feature is made for you to not spend time making all your viewtypes. It's also a good way to see what is possible to do with KOver before you start using the Designer. You will be able to modify the built viewtype after applying the auto build.

### Auto Build : viewtypes

You can populate KOver with 5 different viewtypes sets : 2 for a PVR use and 3 for a fullscreen use.

| Name | Description |
| ---------- |  ----------- |
| **PVR : Horizontal** | Provides a set of viewtypes half screen in horizontal mode. |
| **PVR : Vertical** | Provides a set of viewtypes half screen in vertical mode. |
| **Fullscreen : Classic** | Provides a set of viewtypes full screen. Almost all the screen space is used. |
| **Fullscreen : Two-thirds** | Provides a set of viewtypes full screen. 2/3 of the screen is used, gives a more confortable view. |
| **Fullscreen : Hybrid** | Provides a set of viewtypes full screen. Combine some viewtype of the 2 above presets. |

### Auto Build : colors

You can apply 4 built-in color schemes.

| Name | Description |
| ---------- |  ----------- |
| **Default dark** | Apply a dark/colorful color scheme. A good one for TVs. It's also the one provided at first launch. |
| **Default light** | Apply a light/colorful color scheme. A good one for computer screens. |
| **Default FTV style** | Apply a dark/orange color scheme. Reproduces the FTV UI colors. |
| **Default Flat style** | Apply a dark/blue color scheme. Gives a 'Flat' style to the UI. |

## Customizing Home

`SETTINGS > SKIN SETTINGS > GENERAL SETUP > EDIT HOME MENU ...`

You can customize KOver home menu like many other skins by setting your menu items and icons. But KOver pushes the personal settings further with extending viewtypes to the Home menu. You can build viewtypes for home like you make them for libraries.
When using the AUTOBUILD feature, KOver provides 3 default viewtypes you can choose. At first launch, the first viewtype is set by default showing you only the submenus. You might want to change this by setting showing widgets instead.

### Customizing Home menu items

| Name | Feature | Description |
| ---------- | ---------- | ----------- |
| **Select widget** | Common | Choose the widget to display for the item. |
| **Select background** | Common | Choose the picture to display as wallpaper. |
| **Select viewtype** | KOver | Choose the viewtype to display for the item. See [Select viewtype]() |
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

### Select viewtype

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