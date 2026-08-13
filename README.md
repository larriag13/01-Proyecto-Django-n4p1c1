# 01-Proyecto-Django-n4p1c1

**Autor:** Luis Arriagada

---

## 1. Configuración Global de Git

* `git config --global --list`  
  Muestra la lista de todas las variables de configuración globales guardadas en Git.

* `git config --global user.name larriag13`  
  Establece el nombre de usuario global para identificar la autoría de los cambios.

* `git config --global user.email luis.arriagada13@inacapmail.cl`  
  Establece el correo institucional vinculado a las contribuciones en el repositorio.

---

## 2. Flujo de Trabajo y Control de Versiones

* `git add .`  
  Agrega todos los archivos nuevos, modificados o eliminados del directorio actual al área de preparación (*staging*).

* `git commit -m "comentario de lo realizado"`  
  Guarda un registro de los cambios preparados en el repositorio local junto con un mensaje descriptivo.

* `git push origin main`  
  Envía los commits confirmados en la rama local hacia la rama principal (`main`) en el servidor remoto (`origin`).