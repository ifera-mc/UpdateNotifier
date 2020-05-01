# UpdateNotifier

| HitCount | License |
|:--:|:--:|
|[![HitCount](http://hits.dwyl.io/JackMD/UpdateNotifier.svg)](http://hits.dwyl.io/JackMD/UpdateNotifier)|[![GitHub license](https://img.shields.io/github/license/JackMD/UpdateNotifier.svg)](https://github.com/JackMD/UpdateNotifier/blob/master/LICENSE)|

### A handy virion for PocketMine-MP plugin developers that checks if a new release for a plugin is available on Poggit. If so then it notifies the user about the new release.

### Features

- Super simple virion to be used in your plugins.
- It checks if a new release for a plugin is available on Poggit. If so then it notifies the user about the new release.

### API

```php
JackMD\UpdateNotifier\UpdateNotifier::checkUpdate($pluginName, $pluginVersion);
```
- **$pluginName** is the name of the plugin whose update you want to check.
- **$pluginVersion** is the current version of the plugin whose update you want to check.

<br />

- For information regarding how to use a virion in a plugin please refer [here](https://poggit.github.io/support/virion.html).

### Disclaimer

This plugin is designed to be used only by PocketMine-MP developers who wish to provide their users with the info of when an update to the plugin is available.

### Credits:

- [Sandertv](https://github.com/Sandertv) for helping me with the code. I know you said that you didn't want any credits but it only seems fair by doing so.
