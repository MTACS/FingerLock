# FingerLock - A convenient way to unlock your device

![FingerLock](http://mtac.app/assets/images/fingerlockbanner.png)

## Current Features

* Default fingerprint image for a clean look 
* Custom tint colors
* Custom positioning
* Custom images
* Different haptic feedback options 
* Hide lockscreen page dots
* Hide 'Swipe up to unlock/Press home to unlock' text

## Theming

FingerLock versions 2.3+ use a different system for custom images than before. Each theme is now stored as a ```.bundle``` located inside FingerLock's theme directory at ```/Library/Application Support/FingerLock```. To add your own custom theme, copy the ```FingerLock.bundle```, and rename it to your choosing. Place your custom image inside your ```.bundle``` and rename it to ```button.png```. If your image has custom colors within it, make sure to disable 'Use Template Image' under FingerLock > Other. This option is off by default, as the included theme is one single color. If you'd like to use color selected from FingerLock, enable template images.

This new way of loading themes allows designers to package their custom theme into one that can be downloaded with a package manager. The layout of the folder structure is below. 

```layout -> Library -> Application Support -> FingerLock -> CustomTheme.bundle -> button.png```
                
Add this folder structure and build your deb. If you'd like it to appear in a section inside your package manager, add ```Section: Themes (FingerLock)``` to your control file.

## Feature Requests

[Create new request](https://github.com/MTACS/FingerLock/issues/new?assignees=MTACS&labels=&template=feature_request.md&title=)

## Bug Reports

[Create new report](https://github.com/MTACS/FingerLock/issues/new?assignees=MTACS&labels=bug&template=bug-report.md&title=)

