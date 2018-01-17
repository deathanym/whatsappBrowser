![](https://image.ibb.co/iSLobm/wsb.png)

### Requisitos:

* [Python3.6](https://www.python.org/downloads/release/python-363/)

### Librerias:

* [peewee](http://docs.peewee-orm.com)
* [pygments](http://pygments.org)
* [flask](http://flask.pocoo.org)


### Instalacion

```sh
$ wget https://github.com/deathanym/whatsappBrowser/
$ git clone clone https://github.com/deathanym/peewee.git
$ cd peewee/
$ python3 setup.py install
```

### Como utilizar

```sh
$ python3 sqlite_web.py 'DATABASE.DB'
```


La configuracion por defecto es la siguiente:

* ``-p``, ``--port``: default is 8080
* ``-H``, ``--host``: default is 127.0.0.1
* ``-d``, ``--debug``: default is false
