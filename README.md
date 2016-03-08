# DOCKER XAMMP
### Reportes Varios

Descargar e instalar Docker ToolBox
```
$ https://www.docker.com/products/docker-toolbox
```

Bajar imagen
```
$ docker pull tomsik68/xampp
```

Running
```
$ docker run -p 41061:22 -p 41062:80 -d -v ~/reporte:/www tomsik68/xampp
-- /$home/reporte ruta local a montar
```

Access ssh
```
$ ssh root@192.168.99.100 -p 22
```

Testing
```
http://192.168.99.100:41062/www/
http://192.168.99.100:41062/xampp
Open (reemplazar "XXX" por 100, 101, 102, ... dependiendod de la VM)
```

Stop
```
$ docker stop [Repository]
```

Otros
```
$ docker images
$ docker ps
```

