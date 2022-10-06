Repositorio de la clase de git + github  
Comisión 22573 - Codo a Codo - Desarrollo Web FullStack

**Instrucciones para clonar repositorio**  
*(solo se realiza un vez)*  
1. Abrir la terminal del sistema operativo o de vs code  
2. navegamos hasta la carpeta donde queremos descargar el repositorio usando los [comandos de navegación en terminal](http://www.falconmasters.com/offtopic/como-utilizar-consola-de-windows/)  
3. Por último, clonamos el repositorio:  
`git clone https://github.com/jorgeEF/Clase_git.git`

**Flujo de trabajo**  
*(se repite cuantas veces necesitemos)*:  
1. Actualizar ramas remotas:  
`git fetch`  
2. Actualizar la rama principal del proyecto, en este caso es main:  
`git pull`
3. Crear nueva rama local para tarea:  
`git checkout -b nombre_rama`  
4. Hacer las modificaciones deseadas a un archivo.  
5. Agregar el archivo modificado al seguimiento de git:  
`git add nombre_archivo`  
6. Hacer commit y comentario:  
`git commit -m "explicación modificación"`  
7. Modificar otro archivo  
8. Agregar el otro archivo modificado al seguimiento de git:  
`git add .`  
9. Hacer commit y comentario:  
`git commit -m "terminé mi rama"`  
10. Publicar rama:  
`git push origin nombre_rama`  

**El repositorio incluye la guía en PDF usada en clase.**
