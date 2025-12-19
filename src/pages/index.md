---
layout: ../layouts/Layout.astro
title: Hello World Redes
---

## Redes, de cero a crack

Playlist:
<!-- markdownlint-disable MD033 -->
<div style="position: relative; width: 100%; height: 0; padding-bottom: 56.25%;">
  <iframe src="https://www.youtube.com/embed/k2e6eWyn0fE?list=PLg9145ptuAijivEI4t0cb31FA41zqclwO"
    style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
    frameborder="0" allowfullscreen>
  </iframe>
</div>
<!-- markdownlint-enable MD033 -->
### 0. Bases mínimas (antes de redes)

No es redes todavía, pero sin esto todo lo demás se vuelve magia.

- Bits y bytes
- **Números binarios**
- Base 2
- Por qué 8 bits = 1 byte

<!-- [\[Método Fácil\] Convertir de Binario a Decimal y viceversa. - YouTube](https://www.youtube.com/watch?v=c-hyLLdDt7I) -->

<!-- markdownlint-disable MD033 -->
<div style="position: relative; width: 100%; height: 0; padding-bottom: 56.25%;">
  <iframe src="https://www.youtube.com/embed/c-hyLLdDt7I"
    style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
    frameborder="0" allowfullscreen>
  </iframe>
</div>
<!-- markdownlint-enable MD033 -->

Objetivo: entender que **todo lo que viaja en una red son bits**.

---

### 1. Qué es una red (conceptual)

- Comunicación por una red
- Emisor y receptor
- Mensaje
- Canal
- Ruido
- Latencia
- Ancho de banda

Analogías útiles:

- Correo
- Llamadas telefónicas
- Carreteras a nivel nacional y continental.
<!-- [¿Cómo funciona Internet? - YouTube](https://www.youtube.com/watch?v=rw41W8crZ_Y) -->
<!-- markdownlint-disable MD033 -->
<div style="position: relative; width: 100%; height: 0; padding-bottom: 56.25%;">
  <iframe src="https://www.youtube.com/embed/rw41W8crZ_Y"
    style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
    frameborder="0" allowfullscreen>
  </iframe>
</div>
<!-- markdownlint-enable MD033 -->
Objetivo: entender **el problema que las redes resuelven**.

---

### 2. Internet como sistema

No la web, la infraestructura.

- Qué es un ISP
- Routers de gran escala
- Rutas
- DNS
- Navegador
(Video en la playlist)
Objetivo: entender que Internet **es una red de redes**, no un servicio mágico.

---

### 3. Redes locales (LAN)

El mundo chico y controlable. Tu casa o una oficina.

- Qué es una red local
- Switch (qué hace y qué no)
- Router (idea básica)
- Qué pasa cuando dos dispositivos se comunican

Conceptos:

- Broadcast y Unicast
- Quién pregunta
- Quién responde

(Video en la playlist)
Objetivo: entender **qué pasa en tu casa u oficina**.

---

### 4. Capas y abstracción

Primero la idea, después los nombres.

- Por qué dividir el problema en capas
- Qué problema resuelve cada capa

Luego:

- Modelo OSI (visión conceptual)
- Modelo TCP/IP (visión práctica)

(Video en la playlist)
Objetivo: entender **dónde vive cada problema**.

---

### 5. Direcciones e identificación

Empieza lo que ya es red.

- Qué es una dirección
- Por qué los dispositivos necesitan identificarse
- MAC address (idea general)
- IP address (idea general)

Introducción fuerte al binario:

- Conversión binario ↔ decimal
- Por qué una IP es un número

Ejemplo:

192.168.1.1
↓
11000000.10101000.00000001.00000001

<!-- markdownlint-disable MD033 -->
<div style="position: relative; width: 100%; height: 0; padding-bottom: 56.25%;">
  <iframe src="https://www.youtube.com/embed/801xu7tGEfA"
    style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
    frameborder="0" allowfullscreen>
  </iframe>
</div>
<!-- markdownlint-enable MD033 -->

Objetivo: que una IP deje de parecer un string mágico.

---

### 6. Protocolos fundamentales

Ahora sí, nombres concretos.

- IP: direccionamiento
- TCP vs UDP: confiabilidad
- DNS: nombres a números
- HTTP: intercambio de documentos

Sin detalles internos todavía.

Objetivo: reconocer **quién hace qué**.

---

### 7. Subredes (el binario importa de verdad)

Primer punto donde mucha gente se pierde.

- Qué es una subred
- Máscara de red
- CIDR (`/24`, `/16`)
- Por qué dividir redes

Conceptos binarios clave:

- AND binario
- Rangos
- Conteo de hosts

<!-- markdownlint-disable MD033 -->
<div style="position: relative; width: 100%; height: 0; padding-bottom: 56.25%;">
  <iframe src="https://www.youtube.com/embed/kceWXMaJsew?list=PLINy58Bvq5_L2WfuQeZ4t77EEhj-sG675"
    style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
    frameborder="0" allowfullscreen>
  </iframe>
</div>
<!-- markdownlint-enable MD033 -->
Objetivo: entender **por qué el binario no es opcional**.

---

### 8. Seguridad básica de redes

Sin hacking de película.

- Qué significa confiar
- Qué es cifrar
- HTTPS
- Firewalls (concepto)
- NAT

Objetivo: entender **qué se protege y por qué**.

---

### 9. Observación y diagnóstico

Donde todo se vuelve real.

- ping
- traceroute
- IP local y pública
- Lectura básica de headers HTTP

Objetivo: dejar de adivinar y empezar a observar.

---
