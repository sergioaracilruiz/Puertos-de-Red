# PUERTOS DE RED

## Definición y uso

En el ámbito de las redes informáticas, los puertos de red representan un elemento esencial para la comunicación entre dispositivos y servicios en Internet. A través de ellos, los sistemas pueden identificar de forma precisa qué aplicación debe recibir o enviar información, permitiendo que múltiples procesos se ejecuten simultáneamente sobre una misma conexión.

!!! quote "Definición"
    **Un puerto es un punto virtual en el que comienzan y terminan las conexiones de red.** 

Los puertos están basados en software y los gestiona el sistema operativo de un ordenador. Cada puerto está asociado a un proceso o servicio específico. Los puertos permiten a los ordenadores diferenciar fácilmente los distintos tipos de tráfico: los correos electrónicos van a un puerto distinto de las páginas web, por ejemplo, aunque ambos lleguen a un ordenador a través de la misma conexión a Internet.

Este documento aborda de manera detallada el funcionamiento de los puertos TCP y UDP, explicando su papel dentro del modelo de comunicación en red, especialmente en la capa de transporte. Asimismo, se analizan las diferencias entre ambos protocolos, sus características principales y los contextos en los que se utilizan.

![LAN_ports](./img/lan-ports-vs-ethernet-ports.png)

Además, se presentan los puertos más comunes y sus aplicaciones, junto con la clasificación de los mismos según su rango y función. También se estudian aspectos clave relacionados con la eficiencia, seguridad y gestión de los puertos, destacando la importancia de su correcta configuración para evitar vulnerabilidades y optimizar el rendimiento de la red.

## Contenidos
Esquema de los contenidos de las unidades

### PUERTOS
``` mermaid
graph TD;
    A["PUERTOS DE RED<br>Definición y uso"] --> B["Definición básica<br>Puerto = número lógico"]
    B --> C["¿Cómo funcionan?"]

    C --> D["Socket = IP + Puerto"]

    D --> E[Puertos TCP/UDP]
    E --> F[TCP: fiable, orientado a conexión]
    E --> G[UDP: rápido, sin garantía]
    F --> H
    G --> H[Modelo OSI]
    H --> I[Puertos = capa de transporte]
    
    I --> J[Tipos de puertos]
    J --> K["Bien conocidos (0-1023)"]
    J --> L["Registrados (1024-49151)"]
    J --> M["Efímeros (49152-65535)"]
    L --> N
    M --> N
    K --> N[Eficiencia del uso de puertos]
    K --> O["Puertos más usados<br>HTTP, HTTPS, FTP, SSH, DNS..."]
```

### SEGURIDAD EN LOS PUERTOS
``` mermaid
graph TD;
    A[SEGURIDAD EN LAS CONEXIONES]
    A --> B[Mejoras en los puertos]
    B --> C[Estados de puertos]
    C --> D[Abiertos]
    C --> E[Cerrados]
    C --> F[Filtrados]

    F --> G
    D --> G[Diferencias de rendimiento]
    G --> H[Juegos online]
    G --> I[Descargas P2P]

    I --> J
    H --> J[Riesgos]

    J --> K["Amenazas<br>Malware, escaneo, DDoS"]

    K --> L[Protección]
    L --> M[Firewall, IDS/IPS]
    L --> N[Actualizar servicios]
    L --> O[Abrir solo los necesarios]

    O --> P["Casos especiales<BR>DNS, DHCP, SNMP"]

    P --> Q[Herramientas de comprobación]
    Q --> R[Nmap, test de puertos]

    R --> S[Problemas de red]
    S --> T[CG-NAT]
```

### AMPLIACIÓN SOBRE DNS Y ARP
``` mermaid
graph TD;
    A[DNS]
    A --> B["Caché del DNS<br>DNS flush"]
    B --> C[Limpiar la caché DNS]
    C --> D[Mejora rendimiento del equipo]
    D --> E[Sistemas Operativos]
    D --> F[Navegadores]

    E --> G[Windows]
    E --> H[Linux]
    E --> I[MAC]

    F --> J[Mozilla Firefox]
    F --> K[Google Chrome<br>Opera]

    L[ARP]
    L --> M[Qué es la caché ARP]
    M --> N[Cuando borrar<br>la caché ARP]
    N --> O[Cómo borrar la caché ARP]
    O --> P[Windows]
    O --> Q[Linux]
    O --> R[MAC]
```    