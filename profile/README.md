<h1 align='center'>SecureIoT Home: Intelligent Security for Modern Living</h1>

![OIG3](https://github.com/Smart-Home-Guard/.github/assets/139191192/f088bccc-f982-4d81-b972-2c58f77926e3)

## 🌱 Introduction
* This organization was born due to the Multidisciplinary Project in semester 232.

## 🚀 Tech stack
### CE
* ESP32 + C++
* Raspberry PI + Python
### CS
* An API server built with Rust axum, with a modular philosophy: features can be added easiliy.
  The API server consists of 2 main components:
     * IotTask executor, which listens for incoming messages and send commands from a remote user using MQTT.
     * WebTask executor, which creates API routes and serves them.
  These 2 components have a bidirectional channel theoretically to allow pushing messages.
* MongoDB for being schemaless, new features can be added easily without having to perform migrations.
* A Web server built with Nextjs.
