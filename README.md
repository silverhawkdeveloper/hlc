# Instalación de Django

1.- Entorno virtual. Lo primero que deberíamos hacer es instalar una herramienta que nos va a servir de entorno virtual. De esta manera, vamos a tener aislada la aplicación Django sin entorpecer el resto del sistema. Podríamos incluso tener un entorno virtual con diferentes versiones de Django para cada ejercicio.

Para ello, hacemos lo siguiente:

    apt install python3.8-venv
    python3 -m venv mi_entorno (esto crea la carpeta myenv en el directorio donde se ejecute)

    Activar el entorno virtual. Una vez hecho lo anterior, podemos activarlo con el siguiente comando (deberemos hacerlo cada vez que comencemos nuevamente a desarrollar la aplicación):

    source mi_entorno/bin/activate

2.- Instalación de Django. Seguimos estos pasos.

    Nos aseguramos que tenemos actualizado pip

    python -m pip install --upgrade pip

    Vamos a realizar una instalación mediante el fichero requirements.txt

    Django~=4.1

    Ahora ejecuta la siguiente orden para instalar Django:

    pip install -r requirements.txt

