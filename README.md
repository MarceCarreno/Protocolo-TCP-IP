# Conceptos Básicos del Protocolo TCP/IP

---

## 1. 🌐 ¿Qué es el protocolo TCP/IP y por qué es importante?

### Breve historia y propósito

TCP/IP (Transmission Control Protocol/Internet Protocol) es una suite de protocolos de comunicación que fue desarrollada en los años 70 por el Departamento de Defensa de Estados Unidos. Su propósito original era crear una red robusta y descentralizada que pudiera funcionar incluso si algunas partes fallaban.

El protocolo TCP/IP es como el "idioma universal" que permite que diferentes dispositivos en la red se comuniquen entre sí, sin importar su marca, sistema operativo o ubicación geográfica.

### Su rol en el funcionamiento de Internet

TCP/IP es la base sobre la que funciona Internet. Cada vez que envías un mensaje de WhatsApp, navegas por una página web, o transmites un video en YouTube, estás utilizando TCP/IP. Es el sistema que permite que los datos viajen desde tu dispositivo hasta su destino, atravesando múltiples redes y servidores en el camino.

---

## 2. 🏗️ Modelo TCP/IP vs Modelo OSI

### Comparación de capas

El modelo OSI (Open Systems Interconnection) es un modelo teórico de 7 capas que describe cómo deberían funcionar las comunicaciones de red. TCP/IP, por otro lado, es un modelo práctico de 4 capas que realmente se usa en Internet.

| **Modelo OSI (7 capas)** | **Modelo TCP/IP (4 capas)** | **Función Principal** |
|--------------------------|-----------------------------|-----------------------|
| **7. Aplicación** | | Interfaz con el usuario final |
| **6. Presentación** | **4. Aplicación** | Formato y encriptación de datos |
| **5. Sesión** | | Gestión de conexiones y sesiones |
| **4. Transporte** | **3. Transporte** | Control de flujo y confiabilidad |
| **3. Red** | **2. Internet** | Enrutamiento y direccionamiento |
| **2. Enlace de datos** | | Control de errores y acceso al medio |
| **1. Física** | **1. Acceso a red** | Transmisión de bits y señales |

### ¿Por qué usamos TCP/IP en la web?

TCP/IP se adoptó porque es más simple y práctico que el modelo OSI. Mientras OSI era muy detallado teóricamente, TCP/IP ya estaba funcionando en redes reales. Además, TCP/IP es más flexible y se adapta mejor a las necesidades cambiantes de Internet.

---
# 🌐 Modelo TCP/IP y Direccionamiento IP

## 3. 🧱 Las 4 capas del modelo TCP/IP (explicado fácil)

El modelo TCP/IP describe cómo viajan los datos por internet, dividido en 4 capas. Cada una cumple un rol clave en la comunicación de red.

### 1. Capa de Aplicación
- Interactúa directamente con el usuario o las aplicaciones.
- Protocolos comunes:
  - **HTTP/HTTPS** → navegación web
  - **DNS** → convierte nombres en direcciones IP
- 📌 *Ejemplo:* cuando visitas un sitio web.

### 2. Capa de Transporte
- Divide los datos en partes (paquetes) y se asegura de que lleguen bien.
- Protocolos:
  - **TCP** (confiable, lento)
  - **UDP** (rápido, sin garantía)
- 📌 *Ejemplo:* ver un video en streaming usa UDP.

### 3. Capa de Internet
- Encargada de enrutar los paquetes a su destino.
- Usa direcciones IP y protocolos como:
  - **IP (Internet Protocol)**
  - **Routing** → caminos por donde viajan los datos.

### 4. Capa de Acceso a Red
- Conecta físicamente los dispositivos a la red.
- Tecnologías comunes:
  - **Ethernet**
  - **Wi-Fi**
- 📌 *Ejemplo:* conexión del notebook al router por Wi-Fi.

---

## 4. 🌐 Direccionamiento IP: IPv4 vs IPv6

### ¿Qué es una dirección IP?
Una IP es como el número de casa de un dispositivo: permite identificarlo y que se comunique con otros en la red.

### Estructura básica de una IP

- **IPv4:** 4 bloques numéricos (0–255), separados por puntos.  
  Ej: `192.168.1.1`

- **IPv6:** más largo, con números y letras, separados por dos puntos.  
  Ej: `2001:0db8:85a3:0000:0000:8a2e:0370:7334`

### Comparación: IPv4 vs IPv6

| Característica         | IPv4             | IPv6                          |
|------------------------|------------------|-------------------------------|
| Longitud               | 32 bits          | 128 bits                      |
| Formato                | `192.168.0.1`    | `2001:0db8::7334`             |
| Capacidad              | ~4 mil millones  | Casi infinita 🌍				|
| Estado actual          | Saturado         | Alternativa moderna           |

### IP pública vs privada

- **IP pública:** visible desde internet. Identifica tu red en el exterior.
- **IP privada:** solo visible dentro de tu red local (como en casa).

📌 *Ejemplo de IP privada:* `192.168.0.100` (Wi-Fi del hogar)

---
