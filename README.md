# statamic-cachemanager
Cache Manager Widget for Statamic V2.x  
by Rudy Affandi (2016)

![screen shot 2016-04-11 at 2 10 17 pm](https://cloud.githubusercontent.com/assets/1151181/14435616/2ab8a1a4-ffef-11e5-8b38-99094c56b7f3.png)

## What is this?
CacheManager is a Statamic V2.x dashboard widget that allows you to clear your cache/stache directly from the control panel. This is equivalent to the `php please cache:clear` command.

## Installation
Copy `CacheManager` to your `site/addons` folder. Open your control panel, go to the Settings / Control Panel and add the following:
```
- 
  type: CacheManager
  width: 33
```

Save it and visit your Dashboard.

## Road map
- Add static cache, Pagespeed, Opcache, APC Cache clearing method
- Add other features (metrics, time stamp, etc)

## Bugs
Please use the github issue to report bugs.

## I like this, how can I contribute?
Feel free to fork this repo and send me a Pull Request.
