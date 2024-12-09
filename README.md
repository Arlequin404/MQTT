## MQTT Ruby Client Project
This project demonstrates a simple implementation of an MQTT client using Ruby. The project includes a publisher and a subscriber that communicate through an MQTT broker (e.g., Mosquitto). The purpose is to showcase how MQTT protocols work with Ruby.

**Requirements**
Language and Tools
Ruby Version: >= 3.0.0
Mosquitto (MQTT Broker): >= 2.0.0
Docker: >= 20.10.0
Gems:
mqtt
Installation Steps

**Prerequisites**
Ensure that Ruby, Bundler, and Mosquitto are installed.
Install Docker if you want to containerize the application.
Commands to Clone the Repository
```bash
git clone https://github.com/your-repository-name/mqtt-ruby-client.git
cd mqtt-ruby-client
```
**Run the Project**
Install the required Ruby gems:
```bash
bundle install
```
Start the Mosquitto broker (ensure it's running on port 1883):
```bash
mosquitto
```
Run the subscriber:
```bash
ruby suscriptor.rb
```
Run the publisher:
```bash
ruby publicador.rb
```
Containerize the Project with Docker
Build the Docker image:
```bash
docker build -t mqtt-ruby-client .
```
Run the container:
```bash
docker run --name mqtt-ruby-client -d mqtt-ruby-client
```
Check logs to ensure functionality:
```bash
docker logs mqtt-ruby-client
```
Docker Hub
Link to the Docker Hub repository (replace with your link):
Docker Hub Repository



**ersión en Español**
Proyecto Cliente MQTT en Ruby
Este proyecto demuestra una implementación simple de un cliente MQTT utilizando Ruby. El proyecto incluye un publicador y un suscriptor que se comunican a través de un broker MQTT (por ejemplo, Mosquitto). El propósito es mostrar cómo funciona el protocolo MQTT con Ruby.

**Requisitos**
Lenguaje y Herramientas
Versión de Ruby: >= 3.0.0
Mosquitto (Broker MQTT): >= 2.0.0
Docker: >= 20.10.0
Gems:
mqtt

**Pasos de Instalación**

**Prerrequisitos**
Asegúrate de tener instalados Ruby, Bundler, y Mosquitto.
Instala Docker si deseas contenerizar la aplicación.
Comandos para Clonar el Repositorio
```bash
git clone https://github.com/your-repository-name/mqtt-ruby-client.git
cd mqtt-ruby-client
```
**Ejecución del Proyecto**
Instala las gemas necesarias:
```bash
bundle install
```
Inicia el broker Mosquitto (asegúrate de que está escuchando en el puerto 1883):
```bash
mosquitto
```
Ejecuta el suscriptor:
```bash
ruby suscriptor.rb
```
**Ejecuta el publicador:**
```bash
ruby publicador.rb
```
Contenerizar el Proyecto con Docker
Construye la imagen de Docker:
```bash
docker build -t mqtt-ruby-client .
```
Ejecuta el contenedor:
```bash
docker run --name mqtt-ruby-client -d mqtt-ruby-client
```
Verifica los registros para asegurar el funcionamiento:
```bash
docker logs mqtt-ruby-client
```
**Docker Hub**
Enlace al repositorio en Docker Hub (reemplaza con tu enlace):
Repositorio Docker Hub
