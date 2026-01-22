# SistemaGestionVehicular
Prueba sistema de gestion vehicular
README

PARA INSTALAR EL PROYECTO GESTION VEHICULAR SON LOS SIGUIENTES PASOS.

SOFTWARE
JDK 17
Maven
Angular CLI
Node.js v24
Eclipse o Visual Studio (con la extension de Spring tool)

Puerto = 8085

Backend
1.Descomprimir carpeta
2.Si estas en Eclipse File>Import>Maven>Existing maven projects> Ruta del projecto
3.Si es visual studio solo debes abrir el IDE y de ahi la carpeta del programa
4.En Eclipse ejecutar el programa principal el "main" debajo del cuadro de "help" en visual studio lo corres.

PRUEBAS POSTMAN=
ENPOINTS

CREAR SERVICIO

http://localhost:8085/api/servicios

{
    "nombre": "Cambio de aceite",
    "descripcion": "Incluye filtro de aceite",
    "categoria": "MANTENIMIENTO",
    "precio": 500.00
}

LISTAR TODO

http://localhost:8085/api/servicios

LISTAR CATEGORIAS
http://localhost:8085/api/servicios?categoria=MANTENIMIENTO

http://localhost:8085/api/servicios?categoria=LIMPIEZA

http://localhost:8085/api/servicios?categoria=REPARACION

ELIMINAR POR ID
http://localhost:8085/api/servicios/2

FRONT

DESCOMPRIMIR MANTENIMIENTO-FRONT.RAR

ABRIR VISUAL STUDIO Y ABRIR CARPETA DE MANTENIMIENTO-FRONT

VERIFICAR QUE ESTE INSTALADAS LAS DEPENDENCIAS

npm install

Levantar Puerto 4200 configurado automaticamente
ng serve -o

cerrar Puerto ctrl + C


Se deberia abrir en el navegador el diseño
