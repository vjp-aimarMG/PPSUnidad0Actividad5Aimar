# PPSUnidad0Actividad5Aimar# PPS-Unidad0Actividad5-Aimar
1. Primeramente vamos a crear el repositorio nuevo con los siguientes comandos:
**echo "# PPS-Unidad0Actividad5-Aimar" >> README.md**
**git init**
**git add README.md**
**git commit -m "first commit"**
**git branch -M main**
**git remote add origin git@github.com:vjp-aimarMG/PPSUnidad0Actividad5Aimar.git**
**git push -u origin main**
2. Ahora visualizamos los remotos que tenemos.
![](/imagenes/1.png) 
3. Ahora tendremos que ir añadiendo el contenido del repositorio y hacer un push hasta que finalmente quede así.
![](/imagenes/2.png) 
4. Ahora vamos a crear una rama nueva en el repositorio de un compañero, para ello nos mandaremos invitaciones. Una vez aceptadas clonaremos el repositorio y con el comando **git branch** crearemos una rama nueva con nuestro nombre. Después con **git checkout** cambiaremos a la rama que acabamos de crear. Por último, volveremos a nuestro repositorio y haremos un **cp** a nuestra imagen de avatar y a la carpeta profile. Una vez lo hayamos copiado volveremos al repositorio del compañero y con un **git add -A** y un **commit** subiremos los cambios utilizando **git push** a nuestra rama. Para comprobarlo entramos en el repositorio del compañero y cambiamos de la rama **main** a mi caso la rama **Aimar**.
![](/imagenes/3.png) 
5. Una vez hecho esto haremos lo mismo pero en su rama main.
![](/imagenes/4.png) 
![](/imagenes/5.png) 
6. Vamos a ver los log de mi directorio con **git log**.
![](/imagenes/6.png) 
7. Para mostrar los últimos 3 commit será con **git log -3**.
![](/imagenes/7.png) 
8. Con **pretty** conseguiremos que se vea en una sola línea y más vistoso.
![](/imagenes/8.png) 
9. Para mostrar los último 2 log mostrando las diferencias sería usando **git log -p -2**.
![](/imagenes/9.png) 
10. Para mostrar los log del último días sería con **git log –since=1.day**.
![](/imagenes/10.png) 