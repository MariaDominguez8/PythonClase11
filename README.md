
# Clase 11 - Entorno Virtual en Python

1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window

2. Creamos una carpeta o directorio: 

mkdir python-final

3. Entramos en ella: 

cd python-final

4. Iniciamos el repositorio:

git init

5. Creamos un archivo:

touch finales.py

6. Abrimos VSC:

code .

7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:

python -V

python3 -V

8. Creamos el entorno virtual en Python:

python3 -m venv venv #Creamos el entorno virtual

9. Activamos el entorno virtual:

source venv/bin/activate #Activamos el entorno virtual en Linux

venv/scripts/activate #En windows

10. Hacemos actualización del pip de Python

python3 -m pip install --upgrade pip #Actualizamos el pip

11. Investigar ¿Qué es el pip y porque lo actualizamos?
    
¿Qué es el pip?
pip (Pip Installs Packages) es una herramienta de línea de comandos para instalar y gestionar paquetes de Python. Los paquetes son colecciones de módulos o bibliotecas que podes usar en tus proyectos.

¿Por qué actualizamos pip?
Seguridad: Las actualizaciones corrigen vulnerabilidades.
Compatibilidad: Mejoras en compatibilidad con nuevas versiones de Python y otros paquetes.
Nuevas Funcionalidades: Incluyen nuevas características y mejoras.
Corrección de Errores: Solucionan problemas de versiones anteriores.
Rendimiento: Mejoras en velocidad y eficiencia.

12. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.

13. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba.
