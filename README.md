# Flow2 Ejercicio con nodo Function
Este repositorio contiene el segundo flow con NodeRed

## Descripción
El segundo ejercicio que se realizara en Node-Red consiste en darle un formato legible para humanos al timestamp utilizando un nodo function para mostrar la fecha en la sección debug. Partiremos del resultado del ejercicio Marca de tiempo con nodos inject y Debug. Si no lo tienes lo puedes descargar de nuestro GitHub: https://github.com/codigo-iot/flow1-NodeRed

El punto de partida sera el siguiente flow

![](nodeRed_Flow2/primerflow.png)



## Pasos a seguir
1. Entrar a [localhost:1880](http://localhost:1880)
2. Exportar el flow 1 haciendo clic en Menu > Exportar > Current Flow > JSON > formatted > download. Opcional, tomarlo del repositorio de clase anterior.
3. Importar el flow 1 haciendo clic en Menu > Importar > Seleccionar un archivo para importar > Importar > Importar una copia
4. Configurar el nodo function haciendo doble clic sobre el
5. Agregar el codigo del [ejemplo ](https://edu.codigoiot.com/mod/lesson/view.php?id=3896&pageid=3824) a la pestaña On Message
6. Activar el nodo Debug y asegurarse de que el nodo inject este lanzando mensajes cada 5 segundos
7. Hacer clic en Deploy.



