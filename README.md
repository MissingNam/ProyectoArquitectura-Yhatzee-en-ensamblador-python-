# ProyectoArquitectura-Yhatzee-en-ensamblador-python-

Notas:
Este repositorio junta varias cosas asi que se trabajara por separado

1. Pyhton 32 Bytes:
   Este proyecto funcionen python 32 bytes, esto por la arquitectura de MASMx86
   es imposible correrlo en Visual Studio Community, por lo tanto la parte hecha
   en pyhon tendra que ser realizada en Visual Studio Code

2. C/Assembly:
   Pese a que se encuentra aqui, es necesario trabajarlo en visual studio community
   esto debido a que es necesaria la estructura de libreria dimanica que ofrece

3. Configuracion de Visual Studio Communty:
   Ir a propiedades del proyecto en VSC y cambiar la estructura del proyecto de x64 a
   Win32, es recomendable trabajar lado a lado con un proyecto regular de C/C++, junto
   A otro proyecto en libreria dinamica, para poder hacer debug

4. Comunicacion Pyhton-Assembly:
  Es necesario la libreria ctypes, incluire descripciones en comentarios dentro del
  archivo en pyhton de como utilizar (almenos hasta donde se) la libreria

5. Actualizacion de libreria:
   Cuando se realiza un cambio en la libreria en C/Ensamblador, es necesario recrear
   la libreria (esto precionando Ctrl+Shift+B, en VSC), luego en la carpeta del proyecto
   existe una subcarpeta llamada debug (o relase dependiendo de tu configuracion pero no
   afecta), alli estaran varios archivos, copiar OrigenIntento2.dll y pegarlo en la
   carpeta donde esta el codigo de pyhton para que lo pueda leer, NOTA: Asegurarse de
   reemplazar la carpeta original

6. Dudas posteriores:
   Cualquier duda que no quede clara, colocala aqui para que pueda crear un punto adicional
   contestandola, Si alguien externo esta leyendo esto, esto es un proyecto escolar
   tengan paciencia si esta terriblemente mal:

   

