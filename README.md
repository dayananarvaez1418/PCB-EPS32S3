# PCB-ESP32S3

Placa base de desarrollo con **ESP32-S3**, pensada como punto de partida para proyectos de IoT, monitoreo ambiental y registro de datos con marca de tiempo. Incluye todo lo necesario para fabricarla y alojarla en una carcasa impresa en 3D.

## Características

- **Microcontrolador:** ESP32-S3 (Wi-Fi + Bluetooth LE)
- **Sensor de temperatura y humedad:** SHT31
- **Reloj en tiempo real:** DS3231 con respaldo de pila (portapilas B1)
- **Alimentación y programación:** USB Tipo-C
- **Pulsador de usuario:** S2
- **Dimensiones de la PCB:** ~80 × 58 mm

## Posibles aplicaciones

Este diseño no está atado a un proyecto específico. Puede servir como base para:

- Estación de monitoreo de temperatura y humedad
- Registrador de datos (data logger) con fecha y hora
- Nodo IoT que envía datos por Wi-Fi
- Plataforma de pruebas y prototipado con ESP32-S3

## Contenido del repositorio

| Carpeta | Descripción |
|---|---|
| `/esquematico` | Esquemático del circuito |
| `/pcb` | Diseño de la PCB y archivos Gerber |
| `/bom` | Lista de materiales (BOM) |
| `/enclosure` | Carcasa 3D en Fusion (`.f3d`) y archivos `.stl` para imprimir |

## Carcasa

Gabinete de dos piezas (base y tapa) diseñado en Autodesk Fusion, con abertura para el USB-C. Pensado para impresión 3D.

## Herramientas utilizadas

- [EasyEDA](https://easyeda.com/): esquemático y PCB
- Autodesk Fusion: carcasa 3D

## Estado del proyecto

Diseño completo (esquemático, PCB y carcasa). Pendiente de fabricación y pruebas de firmware.

## Cómo usarlo

1. Descarga los archivos Gerber de `/pcb` y mándalos a fabricar (por ejemplo, JLCPCB).
2. Compra los componentes según la lista de `/bom`.
3. Imprime la carcasa con los `.stl` de `/enclosure`.
4. Programa el ESP32-S3 por USB-C.

## Autora

Dayana Narváez, Universidad del Cauca
