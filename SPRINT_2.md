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

Router: 

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
 
