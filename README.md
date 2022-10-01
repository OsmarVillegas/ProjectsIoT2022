# ProjectsIoT2022

# Integrantes
 - Osmar Israel Villegas Martínez
 - Alan Manuel Mendoza Arredondo
 - Cristian Uriel Camacho Pérez
 - José Manuel Martínez García
 
# Objetivo general

El objetivo es crear una caja fuerte inteligente, que ofresca seguridad y confianza, que de al usuario la seguridad de poder resguardar sus
objetos valiosos.
 
# Objetivos específicos

 - Proteger los objetos que contenga con un servomotor el cual solo se habrira si se ingresa la contraseña correcta.
 - Proteger la caja el fuego pues contara con un sensor de temperatura que avisará cuando se eleve demasiado.
 - Avisar al usuario si hay alguna fuga o incendio cerca de la caja.
 - Tomar fotos a las personas que fallen al ingresar una contraseña incorrecta, esto para que el usuario esté informado sobre quienes intentan
   abrir la caja,

# Tabla de Software utilizado

| Id   | Software | Versión    | Tipo      |
| ---  | ---      | ---        | ---       |
| 1    | Visual Studio Code         |  17.2      |   IDE     |
| 2    | Arduino         |  2.0.0     |   IDE     |

# Tabla de Hardware utilizado

 | Id       | Componente      | Descripción   | Imagen    | Cantidad | Costo Total |
 | ---      | ---             | ---           | ---       | ---      |  ---      |
 | 1        | Pantalla lcd    | Es un dispositivo empleado para la visualización de contenidos o información de una forma gráfica, mediante caracteres, símbolos o pequeños dibujos, los cuales pueden variar todo esto en función del modelo.              |![Pantalla lcd](https://user-images.githubusercontent.com/105257367/193393699-1f1dae43-522b-431f-bee4-061be5f2c627.png](https://http2.mlstatic.com/D_NQ_NP_912813-MLM42803541664_072020-O.webp)  |     1    |    $116    |
 | 2        | Sensor de temperatura | Un sensor de temperatura es un dispositivo que transforma los cambios de temperatura en señales eléctricas que luego pueden ser procesadas por equipos eléctricos o eléctronicos              |           |     1    |           |
 | 3        | Sensor de gas   | Los sensores de gases MQ son una familia de dispositivos diseñados para detectar la presencia de distintos componentes químicos en el aire. Podemos conectar estos dispositivos a un autómata o procesador como Arduino.              |           |     1    |   $129     |
 | 4        | Cámara          | ESP32-CAM, es un dispositivo que puede llamarse un todo en uno. Aparte de la conectividad Wifi y Bluetooth que viene de fábrica, pines GPIO, se le han añadido dos opciones más. Lleva integrado una pequeña cámara de video y una conexión para una tarjeta MicroSD, donde podremos almacenar fotos o videos.               |           |     1    |           |
 | 5        | Servomotor      | Servo es un tipo de motor DC con reductora que sólo puede girar 180 grados. Se controla mediante el envío de impulsos eléctricos de Arduino.               |           |     1    |           |
 | 7        | Leds            | Un LED (acrónimo del concepto inglés light-emitting diode) es un diodo emisor de luz.              |           |     2    |           |
 | 8        | Bocina(buzzer)  | Un 'zumbador es un transductor electroacústico que produce un sonido o zumbido continuo o intermitente de un mismo tono.              |           |     1    |           | 
 | 9        | Adaptador wifi  | El módulo WiFi ESP8266 es un autocontenedor SOC, con pila integrada protocolo TCP/IP que puede dar acceso a cualquier microcontrolador a su red WiFi.              |           |     1    |           |
 | 10       | Botones         | El pulsador tiene cuatro patillas que están conectadas a pares como se ve en el siguiente esquema.              |           |     10   |           |
 | 12       | ESP32           | ESP32 es la denominación de una familia de chips SoC de bajo costo y consumo de energía, con tecnología Wi-Fi y Bluetooth de modo dual integrada.              |           |     1    |    $150   |
 
# Épicas del proyecto (Mínimo debe haber unaa épica por integrante equipo)

 - Detectar incendios cercanos a la caja fuerte
 - Detectar si la presencia de humo en el ambiente
 - Tomar fotos de la persona que fracase al intentar abrir la caja
 - Abrir la caja cuando se ingrese la contraseña correcta
 - Emitir un sonido de alerta cuando alguien falle al intentar abrir la caja y también al abrirse 
 - Se encenderá un foco de color verde si se ingresó la contraseña correcta y uno rojo si se ingresó una contraseña incorrecta
 - Se conectara a una aplicación la cual podra abrir la caja de forma remota si cuenta con usuario y contraseña correcta

# Tabla de historias de usuario

 | Id  | Historia de usuario             |  Prioridad   | Estimación    | Como probarlo | Responsable      |
 | --- | ---                             | ---          | ---           | ---           |  ---             |
 | 1   | Funcionalidad del proyecto      |    Alta      | 3 - 4 semanas | Hacer pruebas de funcionalidad              |  Todo el equipo  |
 | 2   | Funcionalidad del servomotor    |    Alta      |   3 semanas   | Tratar de abrirlo con contraseñas incorrectas y con fuerza |  Todo el equipo  |
 | 3   | Funcionalidad de los sensores   |    Alta      | 2 - 3 semanas | Acer pruebas con calor y gases cerca de estos              |  Todo el equipo  |
 | 4   | Funcionalidad de audio          |    Media     |   2 semanas   | Tratar de abrirla de forma errónea y activar los sensores    |  Todo el equipo  |
 | 5   | Cámara                          |    Media     | 3 - 4 semanas | Guardar las el contenido que se logre recavar con esta en una meemoria extraible y verificar su estado |  Todo el equipo  |
 | 6   | Funcionalidad de los botones    | Media - Alta | 1 - 2 semanas | Hacer pruebas ingresando diferentes combinaciones de números      |  Todo el equipo  |
 | 6   | Funcionalidad de los leds       |    Baja      | 1 - 2 semanas | Tratar de hacer que estos se actien conforme fueron programados     |  Todo el equipo  |

# Prototipo en dibujo
 
 ![imagen](https://user-images.githubusercontent.com/105257367/193393699-1f1dae43-522b-431f-bee4-061be5f2c627.png)

