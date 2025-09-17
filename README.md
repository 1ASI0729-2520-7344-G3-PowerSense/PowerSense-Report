# PowerSense-Report

# Capítulo IV: Product Design

## 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines.

### 4.1.2. Web Style Guidelines.

## 4.2. Information Architecture.

### 4.2.1. Organization Systems.

### 4.2.2. Labeling Systems.

### 4.2.3. SEO Tags and Meta Tags

### 4.2.4. Searching Systems.

### 4.2.5. Navigation Systems.

## 4.3. Landing Page UI Design.
### 4.3.1. Landing Page Wireframe.

### 4.3.2. Landing Page Mock-up.
A continuación los Mock ups, estos son los modelos de diseño que se utilizarán en la elaboración del landing page y servirá de modelo y base para la elaboración del landing page. 

<img src="img/mulp1.png">
<img src="img/mulp2.png">
<img src="img/mulp2.png">
<img src="img/mulp3.png">
<img src="img/mulp4.png">
<img src="img/mulp5.png">
<img src="img/mulp6.png">
<img src="img/mulp7.png">
<img src="img/mulp8.png">
<img src="img/mulp9.png">
<img src="img/mulp10.png">
<img src="img/mulp11.png">
<img src="img/mulp12.png">
<img src="img/mulp13.png">


## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.

### 4.4.2. Web Applications Wireflow Diagrams.

### 4.4.2. Web Applications Mock-ups.

### 4.4.3. Web Applications User Flow Diagrams.

## 4.5. Web Applications Prototyping.

## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Software Architecture Context Diagram.

<img src="img/context.png">

### 4.6.2. Software Architecture Container Diagrams.

<img src="img/container.png">

### 4.6.3. Software Architecture Components Diagrams.

<img src="img/component.png">

## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.

<img src="img/class diagram.png">

### 4.7.2. Class Dictionary.

### a. User (Entity, Aggregate Root)

Descripción: Representa a un usuario de la plataforma (hogar o PYME). Es la raíz de agregado, pues controla los dispositivos y recomendaciones asociadas.

### Atributos:

- `userId: Long` → Identificador único del usuario.

- `name: String` → Nombre del usuario.

- `email: String` → Correo electrónico del usuario.

- `password: String` → Contraseña encriptada.

- `role: String` → Rol del usuario (ej. admin, cliente).

### Métodos:
No definidos directamente; se gestionan mediante AuthService.

### b. AuthService (Service)

Descripción: Servicio que gestiona la autenticación y autorización de los usuarios.

### Métodos:

- `login(email: String, password: String): User` → Permite que un usuario inicie sesión.

- `register(user: User): User` → Registra un nuevo usuario en el sistema.

- `logout(userId: Long): void` → Cierra sesión de un usuario.

### c. Device (Entity)

Descripción: Representa un dispositivo IoT conectado a la plataforma.

### Atributos:

- `deviceId: Long` → Identificador único del dispositivo.

- `name: String` → Nombre del dispositivo (ej. lámpara, refrigerador).

- `type: String` → Tipo de dispositivo (sensor, actuador).

- `status: String` → Estado actual (encendido/apagado).

- `location: String` → Ubicación física del dispositivo.

### d. DeviceService (Service)

Descripción: Servicio encargado de la gestión de dispositivos.

### Métodos:

- `addDevice(userId: Long, device: Device): Device` → Registra un nuevo dispositivo para un usuario.

- `removeDevice(deviceId: Long): void` → Elimina un dispositivo existente.

- `updateDevice(deviceId: Long, device: Device): Device` → Actualiza información de un dispositivo.

- `listDevices(userId: Long): List<Device>` → Obtiene la lista de dispositivos de un usuario.

### e. ConsumptionRecord (Entity, Value Object inside Aggregate Device)

Descripción: Registro histórico de consumo energético de un dispositivo.

### Atributos:

- `recordId: Long` → Identificador del registro.

- `deviceId: Long` → Identificador del dispositivo asociado.

- `timestamp: Date` → Momento en que se tomó la medida.

- `energyUsed: Double` → Cantidad de energía consumida (kWh).

### f. ConsumptionService (Service)

Descripción: Servicio encargado de obtener y analizar datos de consumo energético.

### Métodos:

- `getConsumption(userId: Long): List<ConsumptionRecord>` → Obtiene el historial de consumo de un usuario.

- `getRealTimeData(deviceId: Long): ConsumptionRecord` → Devuelve el consumo energético en tiempo real de un dispositivo.

### g. Schedule (Entity, Value Object inside Aggregate Device)

Descripción: Representa una programación de encendido/apagado para un dispositivo.

### Atributos:

- `scheduleId: Long` → Identificador único de la programación.

- `deviceId: Long` → Dispositivo asociado.

- `startTime: Date` → Hora de inicio de la acción.

- `endTime: Date` → Hora de fin de la acción.

- `action: String` → Acción a ejecutar (ej. encender, apagar).

### h. ScheduleService (Service)

Descripción: Servicio que gestiona las programaciones de dispositivos.

### Métodos:

- `createSchedule(schedule: Schedule): Schedule` → Crea una nueva programación.

- `deleteSchedule(scheduleId: Long): void` → Elimina una programación existente.

- `listSchedules(userId: Long): List<Schedule>` → Obtiene las programaciones asociadas a un usuario.

### i. Recommendation (Entity, Value Object inside Aggregate User)

Descripción: Representa una sugerencia de optimización energética generada para un usuario.

### Atributos:

- `recommendationId: Long` → Identificador de la recomendación.

- `userId: Long` → Usuario al que está dirigida.

- `message: String` → Mensaje con la recomendación.

- `timestamp: Date`→ Momento en que fue generada.

### j. RecommendationEngine (Service)

Descripción: Motor de IA que analiza patrones de consumo y genera recomendaciones.

### Métodos:

- `generateRecommendations(userId: Long): List<Recommendation>` → Genera una lista de recomendaciones personalizadas para un usuario.

### k. Database (Infrastructure Service)

Descripción: Capa de persistencia que gestiona la comunicación con la base de datos.

### Métodos:

- `save(entity: Object): void` → Guarda una entidad.

- `findById(id: Long): Object` → Busca una entidad por ID.

- `findAll(entity: String): List<Object>` → Recupera todas las instancias de un tipo de entidad.

- `delete(id: Long): void` → Elimina una entidad por ID.

## 4.8. Database Design.
### 4.8.1. Database Diagram.
