# eva1_2asir_pro001
**Proyecto de primeros pasos con el lenguaje typescript**

Hemos creado el repositoio en local con git init
Hemos creado el proyecto typescripto con tsc --init
Que para compilar usaré: tsc -w


Para volver a subir al repositorio:
git add .
git commit -m "primer commit"
git push -u origin master

Hemos creado el README.md directamente en el repositorio y 
hemos actualilzado el local con git pull
Para ver el estado git status

Hemos exluido la carpeta dist con .gitignore

Para clonar, estando en la carpeta anterior a la del proyecto, 
porque el clone me la crea:
git clone https://github.com/1dampdv/eva1_2asir_pro001.git



Recordar que hemos añadido     "outDir": "./dist",  a tsconfig.json para controlar los archivos transpilados de ts a js

para ejecutar un archivo js: node dist/ejercicio001
