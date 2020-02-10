# Laravel-Backpack-ArcaneDev-LogViewer

Integrate [ArcaneDev/LogViewer](https://github.com/ARCANEDEV/LogViewer) in your [Laravel-Backpack](https://github.com/Laravel-Backpack/CRUD) project

![log-viewer](https://user-images.githubusercontent.com/4065733/33958155-4463c27c-e009-11e7-860c-aae56b2b368f.png)

# Requirements

- [Laravel Backpack](https://github.com/Laravel-Backpack/CRUD)

- Daily logs enabled in your .env file `LOG_CHANNEL=daily`

## Installation

```BASH
composer require medianet-dev/backpack-log-viewer

php artisan vendor:publish --provider="MedianetDev\BackpackLogViewer\BackpackLogViewerServiceProvider"

```

after running those commands add this line bellow to the sidebar_content.blade.php file.

```BASH
<li class='nav-item'><a class='nav-link' href='{{ backpack_url('log-viewer')}}'><i class='nav-icon fa fa-history'></i> <span>Logs</span></a></li>
```

## More options 

More options available in /config/log-viewer.php

Documentation:

[https://github.com/ARCANEDEV/LogViewer](https://github.com/ARCANEDEV/LogViewer)
