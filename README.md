# EarthCare

Sistema inteligente de monitoreo de plantas desarrollado en Kotlin para Android.

EarthCare permite monitorear variables ambientales en tiempo real mediante sensores IoT conectados a Firebase, proporcionando alertas inteligentes, visualización histórica de datos y asistencia conversacional mediante PlantGPT.

---

## Tecnologías utilizadas

- Kotlin
- Android Studio
- Firebase Authentication
- Firebase Realtime Database
- ESP32
- MPAndroidChart
- PlantGPT
- IoT

---

## Características principales

### Monitoreo en tiempo real

- Temperatura
- Humedad exterior
- Humedad del suelo
- Luz

### Gestión de plantas

- Registro de plantas
- Configuración personalizada
- Parámetros ideales por especie

### Alertas inteligentes

- Exceso de luz
- Falta de luz
- Temperatura alta
- Temperatura baja
- Humedad fuera de rango

### Visualización histórica

- Gráficas de temperatura
- Gráficas de humedad
- Gráficas de luz

### PlantGPT

Asistente conversacional para responder preguntas relacionadas con el cuidado de plantas.

---

## Arquitectura

ESP32
↓
Sensores IoT
↓
Firebase Realtime Database
↓
Aplicación Android
↓
Visualización y alertas

---

## Capturas

### Inicio de sesión

![Login](screenshots/login.png)

### Dashboard principal

![Dashboard](screenshots/dashboard-principal.png)

### Alertas inteligentes

![Alertas](screenshots/alertas.png)

### PlantGPT

![PlantGPT](screenshots/plantgpt.png)

### Gráfica de luz

![Luz](screenshots/grafica-luz.png)

### Gráfica de temperatura

![Temperatura](screenshots/grafica-temperatura.png)

### Gráfica de humedad

![Humedad](screenshots/grafica-humedad.png)

---

## Firebase

### Authentication

![Authentication](docs/firebase-authentication.png)

### Realtime Database

![Database](docs/firebase-realtime-database.png)
![Database](docs/firebase-realtime-database1.png)
![Database](docs/firebase-realtime-database2.png)
![Database](docs/firebase-realtime-database3.png)
![Database](docs/firebase-realtime-database4.png)
![Database](docs/firebase-realtime-database5.png)

---

## Hardware

### Prototipo físico

![Hardware](hardware/prototipo-fisico.jpg)

---

## Autor

Francisco Javier Cordoba Tufiño

Ingeniería en Software
Universidad Autónoma de Querétaro
