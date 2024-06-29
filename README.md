# utn-1er-semestre-python-clase-11

> Hoy vamos a hacer actividad en Python en un día como programadores:

1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window

2. Creamos una carpeta o directorio: 

```sh
mkdir python-final
```

3. Entramos en ella: 
```sh
cd python-final
```
4. Iniciamos el repositorio:
```sh
git init
```
5. Creamos un archivo:
```sh
touch finales.py
```
6. Abrimos VSC:
```sh
code .
```
7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:
```sh
python -V

python3 -V
```
8. Creamos el entorno virtual en Python:
```sh
python3 -m venv venv #Creamos el entorno virtual
```
9. Activamos el entorno virtual:
```sh
source venv/bin/activate #Activamos el entorno virtual en Linux

venv/scripts/activate #En windows
```
10. Hacemos actualización del pip de Python
```sh
python3 -m pip install --upgrade pip #Actualizamos el pip
```
11. Investigar ¿Qué es el pip y porque lo actualizamos?
<sub>
El término "pip" se refiere a "Python Package Index" y es un sistema utilizado para instalar y administrar paquetes de software escritos en Python. Este índice actúa como un repositorio centralizado que contiene una vasta colección de paquetes desarrollados por la comunidad de Python. Cada paquete puede proporcionar funcionalidades adicionales, bibliotecas, herramientas o frameworks que facilitan el desarrollo de software en Python.
</sub>
<sub>
Actualizar el "pip" se refiere a actualizar el propio gestor de paquetes de Python, no los paquetes individuales que se instalan con él. Es importante mantener el "pip" actualizado por varias razones:
</sub>
<sub>
Compatibilidad y funcionalidad: Las versiones más recientes de "pip" pueden ofrecer mejoras significativas en términos de estabilidad, rendimiento y nuevas características. Esto garantiza que puedas aprovechar las últimas capacidades de gestión de paquetes y resolver problemas conocidos de versiones anteriores.
</sub>
<sub>
Seguridad: Las actualizaciones periódicas de "pip" a menudo incluyen correcciones de seguridad importantes. Mantenerlo actualizado ayuda a proteger tu entorno de desarrollo contra vulnerabilidades conocidas que podrían ser explotadas si se utiliza una versión desactualizada.
</sub>
<sub>
Compatibilidad con nuevos paquetes: Algunos paquetes nuevos pueden requerir una versión mínima de "pip" para funcionar correctamente. Mantener "pip" actualizado asegura que puedas instalar y usar estos nuevos paquetes sin problemas.
</sub>
<sub>
Actualizar "pip" es un proceso sencillo y se puede hacer utilizando el propio "pip" instalado en tu sistema con el comando pip install --upgrade pip. Este comando descarga e instala la versión más reciente de "pip" disponible en el índice oficial de Python Package Index.
</sub>
<sub>
En resumen, actualizar "pip" es crucial para aprovechar las últimas mejoras de rendimiento y seguridad, así como para garantizar la compatibilidad con las versiones más recientes de los paquetes de Python que utilices en tus proyectos de desarrollo.
</sub>