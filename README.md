**Herramienta de Asignación de Teclas y Personalización de Frases**

**Introducción**

Esta herramienta permite crear combinaciones de teclas (hotkeys) para enviar frases específicas en Habbo. Es especialmente útil para Organizadores de Eventos, DJ´s y Traders.

**Requisitos**

Sistema operativo compatible con (Windows, Linux, macOS).

AutoHotkey instalado para ejecutar los scripts generados. Puedes descargarlo desde: https://www.autohotkey.com/.  (IMPORTANTE)!!!!!

**Características y Uso**

**1.** Asignar Combinaciones de Teclas**

Puedes asignar una tecla a una frase de la siguiente manera:

En la interfaz de usuario, verás varios botones con letras (A, S, D, etc.).

Haz clic en uno de los botones, por ejemplo, "A", para asignar una frase a la combinación Ctrl + A.

Ingresa la frase que deseas que se envíe al presionar esa combinación en el campo de texto.

La herramienta guardará la combinación de teclas y la frase, mostrando un mensaje de confirmación en la interfaz.

Ejemplo:
Si asignas la frase "Hola" a la tecla A, entonces al presionar Ctrl + A, se enviará "Hola".

**2.** Guardar el Mensaje

Asigna las combinaciones de teclas como se explica en el paso anterior.

Ingresa el nombre del archivo en el campo de texto de la interfaz. (Donde dice Nombre del Evento)

Haz clic en el botón Guardar para generar el archivo .ahk en la carpeta de Descargas.

El script generado incluirá todas las combinaciones de teclas y frases asignadas.

Ejecuta el script dando doble click en él para automatizar las combinaciones de teclas.

**3.** Cambiar el Tamaño de la Ventana

La aplicación permite ajustar su tamaño mediante los siguientes botones:

Botón "Pequeño": Reduce la ventana a 330x310 píxeles.

Botón "Predeterminado": Restaura el tamaño original de 660x620 píxeles.

**4.** Alternar entre Pantalla Completa y Ventana

Modo de Pantalla Completa: Si la ventana está en modo ventana, al hacer clic en el botón "Pantalla Completa", la aplicación cambiará a pantalla completa.

Modo Ventana: Si la aplicación ya está en pantalla completa, al hacer clic en el botón, volverá al modo ventana.

**5.** Mensajes y Estado

Un Label de estado en la interfaz mostrará mensajes de confirmación y errores, tales como:

Confirmación de la asignación de teclas.

Estado del guardado del script (exitoso o con errores).

Errores si faltan datos o si hay problemas al guardar el archivo.

**6.** Solución de Problemas

El Label con los mensajes no se muestra:

Verifica que el Label esté correctamente configurado dentro del proyecto en Godot.

Asegúrate de que el Label esté visible antes de actualizar su texto.

El archivo no se guarda:

Verifica que tienes permisos de escritura en la carpeta de Descargas.

Asegúrate de que el campo de nombre de archivo no esté vacío.

Asegúrate de tener AutoHotkey instalado y configurado correctamente.

**Contribución**

*Si deseas mejorar esta herramienta o reportar errores, puedes hacer un fork del repositorio y enviar un pull request. Toda colaboración es bienvenida.*

