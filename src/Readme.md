# Tarea 3

**Descarga la imagen 'httpd' y comprueba que está en tu equipo.**
    
    sudo docker pull httpd:2.4
 
![descarga httpd](img/Screenshot_20241018_113624.png)1.png)

````
 sudo docker images
 ````

![img](img/Screenshot_20241018_113827.png)

**Crea un contenedor con el nombre 'dam_web1'.**

````
sudo docker run --name dam_wet1 -p 8000:80 -d httpd:2.4 httpd -DFOREGROUND -c "ServerName localhost"
````

![Screenshot_20241018_114753.png](img/Screenshot_20241018_114753.png)

