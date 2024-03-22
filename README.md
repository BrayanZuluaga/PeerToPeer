# PeerToPeerChat

Cristian Camilo Ocampo Bravo
Felipe Jiménez Londoño  
Luisa Fernanda Andrade  
Brayan David Zuluaga Cárdenas

Este proyecto implementa un sistema de chat peer-to-peer (P2P) en Python utilizando sockets TCP/IP. Permite a los usuarios conectarse entre sí directamente sin necesidad de un servidor centralizado, lo que proporciona una comunicación descentralizada y más privada.

## Objetivo de la practica

Este proyecto fue desarrollado como parte de un ejercicio práctico para aprender sobre comunicación peer-to-peer y programación de sockets en Python. Proporciona una forma sencilla de establecer comunicación entre usuarios en una red local sin la necesidad de
servidores centrales, lo que puede ser útil para aplicaciones de chat y colaboración entre pares.

## Funcionalidades

- **Agregar Vecinos:** Los usuarios pueden agregar a otros usuarios como vecinos proporcionando su dirección IP y puerto.
- **Ver Vecinos:** Se puede ver una lista de vecinos y su estado de conexión (activo o sin conexión).
- **Enviar Mensajes:** Los usuarios pueden enviar mensajes a sus vecinos conectados.
- **Comprobación de Conexión:** El sistema verifica automáticamente si hay conexión con los vecinos y muestra su estado.

## Cómo Funciona

1. **Inicio del Servidor:** Se inicia un servidor en la dirección IP y puerto especificados.
2. **Conexión entre Vecinos:** Los usuarios pueden agregar a otros usuarios como vecinos mediante el menú principal.
3. **Interacción con el Menú:** Los usuarios pueden elegir entre agregar vecinos, ver vecinos, enviar mensajes o salir del programa.
4. **Agregar Vecinos:** Los usuarios pueden agregar vecinos proporcionando su nombre, dirección IP y puerto.
5. **Ver Vecinos:** Se muestra una lista de vecinos y su estado de conexión.
6. **Enviar Mensajes:** Los usuarios pueden enviar mensajes a sus vecinos, proporcionando el nombre del destinatario y el mensaje.
7. **Comprobación de Conexión:** El sistema verifica automáticamente si hay conexión con los vecinos y muestra su estado.

## Ejecución

Para ejecutar el programa, sigue estos pasos:

1. Clona este repositorio en tu máquina local.
2. Abre una terminal y navega hasta la carpeta donde clonaste el repositorio.
3. Ejecuta el script `peer_to_peer_chat.py`.
4. Sigue las instrucciones en pantalla para interactuar con el programa.

## Requisitos

- Python 3.x
- Conexión a Internet (para la comunicación entre pares)

## Contribución

Si deseas contribuir a este proyecto, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-caracteristica`).
3. Haz tus cambios y haz commit de ellos (`git commit -am 'Agrega nueva característica'`).
4. Haz push de la rama (`git push origin feature/nueva-caracteristica`).
5. Abre un pull request.

¡Gracias por tu contribución!

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para obtener más detalles.
