# Changelog

## Release 1.3.1

* IMPORTANT FIX: the pan gesture now works fine.
* NEW: ARC is supported conditionaly.

## Release 1.3.0

* NEW: You can now change the slide direction (left -> right or right -> left).

## Release 1.2.0

* NEW: add `NVSlideMenuControllerCallbacks` category on `UIViewController`.
* NEW: default implementation of `NVSlideMenuControllerCallbacks` category has 
been added to View Controller Containers provided by Apple.

## Release 1.1.3

* NEW: add `panGestureEnabled` property.
* DEPRECATED: `panEnabledWhenSlideMenuIsHidden` property is now deprecated.
* FIX: issue [#2](https://github.com/nverinaud/NVSlideMenuController/issues/2) has been fixed.

## Release 1.1.2

* UPDATE: make `-[NVSlideMenuController isMenuOpen]` a public API.

## Release 1.1.1

* FIX: fix a typo in README for `no ARC compiler flag`.

## Release 1.0.2

* NEW: add a nice shadow on the content view controller's view.

## Release 1.0.1

* FIX: The menu state is now preserved when presenting a view controller modally.

## Release 1.0.0

* First release.