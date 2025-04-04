## 3.1. Diseño de la arquitectura del diseño

<img src="1sprint fotos/1. Diseño de la arquitectura del diseño.jpg" width="50%" height="auto" alt="Mi Foto">

## 3.2 Selección de hardware y software 

### Hardware 

| **ELEMENTO** | **CANTIDAD** | **COSTE (unidad)** | **COSTE TOTAL** |
| ------------------------ | - | - | - |
| Servidor de aplicaciones  | 1 | 3.776€ | 3.776€ |
| Servidor de bases de datos | 1 | 4.777€ | 4.777€ |
| Servidor de respaldo | 2 | 3.000 € | 6.000 € |
| NAS (10TB escalable) | 1 | 1.500 € | 1.500 € |
| Estaciones de trabajo | 3 | 800 € | 2.400 € |
| Switches de red Gigabit (paquete 24) | 2 | 215€ | 430€ |
| Routers | 2 | 210€ | 420€ |
| AP Wifi | 1 | 137€ | 137€ |
| Medidas de seguridad físicas | 1 | 3.500 € | 3.500 € |
| SAI | 1 | 278€ | 278€ |
| **TOTAL** | | | **28.318 €** |

**Servidor de aplicaciones:**  

- Hemos utilizado un servidor Dell en concreto el PowerEdge R740, ideal para aplicaciones empresariales exigentes y virtualización  
- Soporta hasta dos procesadores Intel Xenon escalables, nosotros nos hemos decantado por el Intel Xenon Platinum 8253 2.2G 
- Hasta 1 TB pero puede ser escalable de RAM DDR4 (brutal para bases de datos y cargas pesadas). 
- Soporte para NVMe SSDs (velocidad de almacenamiento extrema). 
- Muy usado para virtualización (en nuestro caso Hyper-V), bases de datos y servidores web. 

**Servidor de base de datos:**

- Hemos utilizado un servidor Dell en concreto el PowerEdge R750, ideal especialmente si buscas rendimiento, escalabilidad y confiabilidad en entornos empresariales. 
- Alto rendimiento con procesadores Intel Xeon de última generación. 
- Gran capacidad de memoria RAM (hasta 4 TB) 
- Almacenamiento ultrarrápido con SSD NVMe muy bueno para nuestra empresa ya que nos hace falta fluideza. 

**Servidor de respaldo:** 

- Hemos utilizado un servidor Dell en concreto el PowerEdge R650XS, un servidor de rendimiento equilibrado para respaldo, bases de datos o virtualización
- El R650XS está diseñado para empresas que necesitan un servidor potente pero sin pagar de más por características que quizás no usen.
- Soporta hasta 12 discos (SATA, SAS o NVMe), lo que lo hace ideal para 
- Más memoria permite almacenar más caché en RAM, acelerando bases de 

  datos y reduciendo la dependencia del disco.

**NAS:**

- Hemos utilizado un NAS Synology DS1821ya que es una excelente opción si buscas un NAS potente, escalable y fiable para almacenamiento en red, copias de seguridad o incluso virtualización.
- Gran capacidad de almacenamiento y escalabilidad (8 bahias para discos escalable a 18) 
- Procesador potente con buena eficiencia energética (Usa un AMD Ryzen V1500B) 
- Expansión de RAM hasta 32 GB (Viene con 4 GB DDR4) 

**Estación de trabajo:** 

- Hemos utilizado las estaciones de la marca Dell, en concreto la Dell OptiPlex 7020 ya que es una gran opción si buscas un ordenador de sobremesa potente, fiable y eficiente para oficina, teletrabajo o tareas empresariales.
- Rendimiento potente con Intel Core i5-14500 
- Memoria DDR5 a 4800 MHz, mucho más rápida que la DDR4 (16GB RAM) 
- Disco SSD NVMe de 512GB, hasta 5 veces más rápido que un HDD.

**Switch de red Gigabyte:** 

- Hemos utilizado el switch Tenda TEG1118P-16-250W ya que un switch PoE de 18 puertos Gigabit con funcionalidades avanzadas como VLAN, QoS y transmisión extendida hasta 250 metros, lo que lo hace ideal para redes empresariales, cámaras IP, VoIP y puntos de acceso WiFi.  

**Router:** 

- Hemos utilizado el MikroTik hAP ax³ (C53UiG+5HPaxD2HPaxD) es un router WiFi 6 de alto rendimiento con potente hardware, seguridad avanzada y gran 
flexibilidad, ideal para usuarios exigentes, oficinas y empresariales pequeñas. 
- Procesador potente para multitarea y redes exigentes

**SAI:** 

- Hemos utilizado el SAI Online 1000 VA LCD SH ya que este modelo es ideal para empresas pequeñas y medianas. 
- Proporciona alimentación ininterrumpida en caso de corte de energía, 

  asegurando que tus dispositivos sigan funcionando sin interrupciones.

- El SAI protege contra sobrecargas y cortocircuitos y cuenta con apagado automático cuando la batería está baja para evitar dañar tus dispositivos.

**Software** 

|**ELEMENTO** |**LICENCI** |<p>**COST (unidad)** </p><p>**SA**</p>|<p>**E** </p><p>**COSTE TOT** </p>|||
| - | - | :- | - | :- | :- |
|Sistema operativo servidores (Windows Server)|4 |0 € |0 € |||
|Soporte empresarial (MySQL) |1 |2\.000 € |2\.000 € |||
|Software de backup (Aomei Backup) |1 |700 € |700 € |||
|Sistema de virtualización (VMWare Workstation Pro |1 |193 € |193 € |||
|Antivirus y herramientas de seguridad (F-Secure) |10 |10 € |100 € |||
|Monitorización (Pandora FMS) |1 |34 € |34 € |||
||**3.027 €** |||||

**Sistema operativo servidores:**

- Hemos utilizado Windows Server ya que es idela para empresas pequeñas que no quieren complicarse con otros sistemas operativos.
- Ofrece muchas funciones de seguridad avanzadas (Windows Defender Antivirus y Firewall). 
- Escalabilidad a medida que creces (WS se adapta a las b¡necesidades cambiantes de tu empresa).

**Soporte empresarial:** 

- Hemos utilizado MySQL ya que para una empresa es una opción muy popular debido a su fiabilidad, escalabilidad y flexibilidad, especialmente en entornos 
de bases de datos donde se requiere alta disponibilidad y buen rendimiento.
- MySQL es un sistema de gestión de bases de datos gratuito y de código abierto. 
- MySQL es conocido por su velocidad y eficiencia, manejando con facilidad tanto pequeñas aplicaciones como grandes volúmenes de datos.

**Software de backup:** 

- Hemos utilizado Aomei Backupper ya que es una herramienta de respaldo y recuperación de datos que puede ser muy útil para empresas de cualquier tamaño.  
- AOMEI Backupper permite realizar copias de seguridad completas, incrementales o diferenciales.
- AOMEI Backupper es fácil de usar, incluso para usuarios sin mucha experiencia técnica, con una interfaz gráfica intuitiva.

**Sistema de virtualización:** 

- Hemos utilizado VMWare Workstation Pro ya que es una herramienta de virtualización de escritorios de alto rendimiento que puede ser increíblemente útil para empresas, especialmente en entornos de desarrollo, pruebas y administración de sistemas.
- VMware Workstation Pro permite crear y gestionar múltiples máquinas virtuales en un solo equipo físico. 
- La virtualización permite ejecutar varios sistemas operativos en un solo equipo, lo que reduce la necesidad de hardware adicional y optimiza los recursos.
- Proporciona opciones de cifrado de máquinas virtuales y control de acceso.

## DISEÑO DE LA SEGURIDAD DEL SISTEMA

## 1. Medidas de protección contra amenazas

### 1.1. Amenazas externas

#### 1.1.1. Protección contra ciberataques
- **Firewall y sistemas de detección de intrusos**: Se deben implementar firewalls y realizar un monitoreo constante del tráfico de red en los servidores.
- **Autenticación multifactor (MFA)**: Es recomendable su uso para accesos sensibles y tareas administrativas.
- **Cifrado de datos**: Cifrar la información que se transmite entre los servidores y entre servidores y clientes.
- **Pruebas de seguridad**: Realizar evaluaciones periódicas para identificar y corregir vulnerabilidades.

#### 1.1.2. Protección contra interrupciones de red
- **Redundancia en la conexión**: Contratar múltiples proveedores de internet y utilizar enlaces de respaldo.
- **Balanceadores de carga**: Distribuir el tráfico para evitar sobrecargas en los servidores.
- **Mitigación de ataques DDoS**: Implementar servicios especializados para detectar y neutralizar este tipo de ataques.

#### 1.1.3. Protección contra intrusión física
- **Control de acceso con tarjetas**: Usar tarjetas de proximidad para restringir el acceso físico al CPD exclusivamente a personal autorizado.
- **Cámaras de vigilancia**: Instalar un sistema de videovigilancia activo las 24 horas en todas las áreas del CPD.
- **Guardias de seguridad**: Contar con personal de seguridad para evitar accesos no autorizados.

#### 1.1.4. Protección contra desastres naturales
- **Infraestructura resistente**: Diseñar el CPD con materiales capaces de soportar condiciones extremas.
- **Sistema de extinción de incendios**: Instalar un sistema con gas inerte para apagar incendios sin dañar los equipos.
- **Monitoreo ambiental**: Usar sensores de temperatura, humedad y humo para conocer el estado del entorno en todo momento.

#### 1.1.5. Protección contra cortes de energía
- **Sistema de alimentación ininterrumpida (SAI)**: Garantizar suministro eléctrico temporal ante apagones.
- **Generadores de respaldo**: Contar con generadores que mantengan el CPD operativo si el SAI falla.
- **Monitoreo eléctrico**: Vigilar el voltaje y la corriente para evitar daños por fluctuaciones.

### 1.2. Amenazas internas
- **Capacitación del personal**: Formación continua en buenas prácticas de seguridad y gestión de datos.
- **Gestión de accesos y privilegios**: Aplicar el principio de mínimo privilegio y monitorizar los accesos.
- **Supervisión de actividad interna**: Registrar e inventariar las actividades en servidores y bases de datos.
- **Seguridad en endpoints**: Instalar antivirus en todas las estaciones de trabajo y actuar ante posibles amenazas internas.

---

## 2. Políticas de seguridad de acceso a los recursos del CPD

- **Acceso remoto seguro**: Uso de VPN con cifrado y restricciones a redes no autorizadas.
- **Contraseñas**: Establecer contraseñas seguras y obligar su renovación cada 3 meses.
- **Permisos**: Asignar únicamente los permisos estrictamente necesarios a cada usuario.

# PLAN DE RECUPERACIÓN ANTE DESASTRES

Este apartado describe el plan de recuperación ante desastres para garantizar la operatividad del CPD en caso de incidentes que pongan en peligro su actividad.

## 1. Copias de seguridad

### 1.1. Tipos de copias
- **Copias de seguridad incrementales**: Se realizarán diariamente.
- **Copias de seguridad diferenciales**: Se realizarán semanalmente.
- **Copias de seguridad completas**: Se realizarán mensualmente.

### 1.2. Almacenamiento seguro
- **Almacenamiento local**: Uso de sistemas RAID y NAS.
- **Almacenamiento externo**: Uso de un servidor en una ubicación alternativa.
- **Almacenamiento en la nube**: Soluciones cifradas de almacenamiento remoto.
- **Cifrado de datos**: Implementación del sistema AES-256 para todos los datos.

## 2. Restauración de datos

### 2.1. Pasos para la restauración
1. **Identificación**: Determinar la causa del fallo del sistema.
2. **Evaluación**: Medir el alcance del daño en los sistemas y datos.
3. **Restauración inicial**: Recuperar los servidores principales.
4. **Restauración de bases de datos**: Implementar las copias de seguridad más recientes.
5. **Verificación y pruebas**: Evaluar la integridad y funcionalidad de los sistemas restaurados.

### 2.2. Procedimientos de recuperación
- **Recuperación con snapshots**: Utilizar imágenes almacenadas en entornos de almacenamiento redundantes.
- **Restauración desde servidores alternativos**: Activar los entornos de respaldo en servidores remotos.

## 3. Mecanismos redundantes

### 3.1. Redundancia en el almacenamiento
- **RAID**: Garantizar la recuperación y disponibilidad de los datos. Se utilizará **RAID 5** por su equilibrio entre rendimiento, redundancia y capacidad.
- **Almacenamiento SATA**: Uso de discos de alta velocidad para garantizar la eficiencia operativa.

### 3.2. Infraestructura alternativa
- **Servidores de respaldo**: Servidor implementado en una ubicación distinta al CPD principal.
- **Balanceo de carga**: Distribuir el tráfico de forma equitativa para evitar saturaciones.
- **Energía redundante**: Uso de sistemas UPS y generadores de emergencia.

## 4. Protocolos ante desastres

### 4.1. Plan de acción
- **Roles**: Definir responsabilidades claras para el personal de informática y administración.
- **Protocolos de comunicación**: Coordinar equipos internos y externos de manera efectiva.
- **Escalamiento**: Establecer niveles y tiempos de respuesta ante distintos tipos de incidentes.

### 4.2. Pruebas regulares del plan
- **Pruebas trimestrales**: Simulación de recuperación de sistemas críticos.
- **Evaluación de fallos**: Análisis de vulnerabilidades detectadas y mejora continua.
- **Actualización del plan**: Revisión periódica en función de nuevas amenazas o necesidades operativas.

# 1. Introducción

## 1.1. Propósito del documento

Este documento tiene como finalidad detallar la arquitectura y configuración del Centro de Procesamiento de Datos (CPD) que aloja el sistema de gestión de actividades deportivas de Tavernes. Se examinan tanto los aspectos físicos como lógicos, las decisiones técnicas adoptadas y las estrategias de respaldo y seguridad implementadas para asegurar la operatividad y escalabilidad del sistema.

## 1.2. Alcance

- **Infraestructura física**: Ubicación, distribución y descripción de los equipos (servidores, estaciones de trabajo, dispositivos de red, almacenamiento NAS, etc.).
- **Infraestructura lógica**: Diseño y segmentación de la red (VLANs, subredes, asignación de IPs), configuraciones de servidores, virtualización y servicios.
- **Software y servicios**: Sistemas operativos, aplicaciones críticas, herramientas de respaldo, virtualización y monitorización.
- **Políticas de seguridad y respaldo**: Estrategias para asegurar la integridad, disponibilidad y confidencialidad de la información.

## 1.3. Público objetivo

- Administradores y personal de operaciones de TI.
- Técnicos de mantenimiento y soporte.
- Responsables de seguridad y auditoría de sistemas.

---

# 2. Resumen de la Arquitectura

## 2.1. Descripción general del CPD

El CPD está diseñado para alojar el sistema de gestión de actividades deportivas de Tavernes, garantizando un entorno seguro, escalable y de alta disponibilidad. La arquitectura incluye la segmentación en diferentes VLAN para separar el tráfico de gestión, el de servidores y el de respaldo, lo que optimiza el rendimiento y facilita la administración.

## 2.2. Diagrama de arquitectura

<img src="1sprint fotos/1. Diseño de la arquitectura del diseño.jpg" width="50%" height="auto" alt="Mi Foto">


---

# 3. Infraestructura Física

## 3.1. Ubicación y distribución del CPD

- **Ubicación**: Sala específica con acceso restringido y monitoreo constante.
- **Distribución**: Racks organizados para optimizar el flujo de aire y reducir interferencias, con colocación estratégica de servidores, dispositivos de red y almacenamiento.

## 3.2. Equipos

### 3.2.1. Servidores

- **Servidor de aplicaciones**  
  - Modelo: Dell PowerEdge R740  
  - Procesador: Intel Xeon Platinum 8253 (2.2 GHz)  
  - Memoria: Hasta 1 TB DDR4  
  - Almacenamiento: SSD NVMe (Hyper-V)

- **Servidor de base de datos**  
  - Modelo: Dell PowerEdge R750  
  - Procesadores Intel Xeon (última generación)  
  - Memoria: Hasta 4 TB  
  - Almacenamiento: SSD NVMe

- **Servidor de respaldo**  
  - Modelo: Dell PowerEdge R650XS  
  - Soporta hasta 12 discos SATA, SAS o NVMe  
  - Memoria optimizada para uso de caché

### 3.2.2. Almacenamiento en red (NAS)

- Modelo: Synology DS1821+  
  - Capacidad: 10 TB (hasta 18 bahías)  
  - Procesador: AMD Ryzen V1500B  
  - Memoria: 4 GB DDR4 (ampliable a 32 GB)  
  - Funcionalidades: RAID 5, replicación, backup automat

