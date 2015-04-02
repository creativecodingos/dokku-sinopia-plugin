Sinopia plugin for Dokku
----------------------

WIP....
----------------------

Project: https://github.com/progrium/dokku

Installation
------------
```
cd /var/lib/dokku/plugins
git clone https://github.com/creativecodingos/dokku-sinopia-plugin.git sinopia
dokku plugins-install
```


Commands
--------
```
$ dokku help
      sinopia                        Get infos about the private sinopia registry
      sinopia:expose                 Binds the sinopia container to a higher port on host (restarts sinopia)
      sinopia:hide                   Unbinds the sinopia container from a port on host (restarts sinopia)
      sinopia:backup                 Backups the sinopia storage folder
      sinopia:reconfig               Updates the sinopia config (restarts sinopia)
      sinopia:remove                 Deletes the sinopia containers and the sinopia folder on dokku host
```

Simple usage
------------

Get infos about sinopia
```
$ dokku sinopia
```
