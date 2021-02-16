# TrueHome
Alexander technique test results

Para ejecutar los codigos de este repositorio siga los siguientes pasos:
* Clone este repositorio en una carpeta local ``` git clone https://github.com/AletzB/TrueHome.git ``` o descargue el archivo zip
* Cree un ambiente de conda ```conda create -n nombredeentorno anaconda```
* Active su nuevo entorno ``` source activate nombredeentorno ```
* Instale las librerias necesarias, para ello en la carpeta base busque el archivo llamado **requirements** e instalelo ```pip install -r requirements.txt```
* Posteriormente dirijase a la carpeta */TrueHome* y ejecute el comando  ```python manage.py runserver```

* Por ultimo dirijase a la direccion que genera por defecto ```http://127.0.0.1:8000/```
* En esa direccion encontrara una pagina sencilla donde se ve reflejada la informacion de la base de datos, si quiere aumentarle el tamaño de la misma digite en el text input que aparece en la parte superior un numero y pulse la tecla enviar, a los pocos segundos en la consola aparecera un OK, luego de ello puede actualiazar la pagina para ver reflejados los datos

