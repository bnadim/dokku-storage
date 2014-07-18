## [Dokku](https://github.com/progrium/dokku) plugin add a persistent storage to an app

Commands
--------
```
$ dokku help
     storage <app>                                  check if a persistent storage is attached
     storage:add <app>                              Add a persistent storage
     storage:del <app>                              remove persistent storage
```

Installation
------------
```
cd /var/lib/dokku/plugins
git clone https://github.com/bnadim/dokku-storage storage
dokku plugins-install
```
