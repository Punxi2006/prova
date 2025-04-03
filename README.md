# PROYECTO CPD  
**Frances Simó Olma**  
**Jaime Climent Cardona**  
**Jonman Jimenez Mendoza**  

---

## 1. CPD para el alojamiento del sistema de gestión de las actividades deportivas de Tavernes  
### 1.1 Objetivos  
- Centralizar información en una base de datos estructurada.  
- Minimizar la intervención manual.  
- Generar notificaciones automáticas.  
- Integrar herramientas de planificación.  
- Implementar mecanismos de respaldo y recuperación ante desastres.  
- Disponer de una APP para reservas.  
- Proporcionar soporte técnico.  
- Mantener escalabilidad.  
- Facilitar conexión con sistemas de pago.  
- Monitoreo y mantenimiento proactivo.  

### 1.2 Requisitos  
#### 1.2.1 Requisitos del sistema de Gestión  
- **Iniciar sesión** con usuario y contraseña.  
- **Enviar correo de confirmación** tras reservas.  
- **Agregar al carrito** reservas de pistas/puestos.  
- **Realizar pagos** seguros.  
- **Usabilidad** intuitiva para todos los usuarios.  

#### 1.2.2 Requisitos del CPD  
- **Rendimiento**: Respuesta <2 segundos.  
- **Seguridad**: Cifrado RSA en comunicaciones.  
- **Disponibilidad**: 24/7.  
- **Integridad de datos**.  
- **Recuperabilidad**: Recuperación en 30 minutos.  
- **Capacidad**: 1000 usuarios simultáneos.  
- **Confidencialidad**.  
- **Compatibilidad**: Windows y Linux.  

### 1.3 WBS  
El *Work Breakdown Structure (WBS)* que se presenta a continuación desglosa las tareas. Esto permite organizar el proyecto en tareas manejables. 
<img src="1sprint fotos/Aspose.Words.d33e57a9-2320-4bfb-a090-966139295fa7.005.jpeg" width="50%" height="560" alt="Mi Foto">


### 1.4 Cronograma  
<img src="1sprint fotos/Aspose.Words.d33e57a9-2320-4bfb-a090-966139295fa7.006.png" width="50%" height="150" alt="Mi Foto">


### 1.5 Equipo  
- **Jonman Jimenez Mendoza**: Líder del Proyecto.  
- **Jaime Climent Cardona**: Administrador de Infraestructura TI.  
- **Frances Simó Olmo**: Gestor de Riesgos.  
<img src="1sprint fotos/Aspose.Words.d33e57a9-2320-4bfb-a090-966139295fa7.007.png" width="50%" height="150" alt="Mi Foto">


---

## 2. Documento de Roles y Responsabilidades  
### 2.1 Roles y Responsabilidades  
#### **Líder del Proyecto**  
- Coordinar actividades.  
- Supervisar progreso.  
- Garantizar plazos.  
- Resolver conflictos.  
- Gestión documentación.  

#### **Administrador de Infraestructura TI**  
- Selección de hardware/software.  
- Gestión de redes y seguridad.  
- Mantenimiento y actualizaciones.  

#### **Gestor de Riesgos**  
- Evaluación de riesgos.  
- Desarrollo de estrategias de mitigación.  
- Gestión de incidentes.  

### 2.2 Tareas Asignadas  
#### **Jonman Jiménez Mendoza**  
- Dividir fases del proyecto (WBS).  
- Establecer plan detallado.  
- Designar líder de proyecto.  

#### **Jaime Climent Cardona**  
- Identificar necesidades de hardware/software.  
- Determinar capacidades de procesamiento.  

#### **Frances Simó Olmo**  
- Identificar riesgos.  
- Desarrollar planes de contingencia.  

### 2.3 Tareas en Equipo  
- Establecer objetivos del CPD (09-10/01/25).  
- Determinar requisitos funcionales (09-10/01/25).  
- Revisión final del plan (20/01/25).  
- Aprobación final (20-23/01/25).  

### 2.4 Firmas  
- Jonman Jiménez Mendoza  
- Jaime Climent Cardona  
- Frances Simó Olmo  
<img src="1sprint fotos/Aspose.Words.d33e57a9-2320-4bfb-a090-966139295fa7.008.png" width="70%" height="100" alt="Mi Foto">

---

## 3. Análisis de Requisitos  
### 3.1 Materiales  
#### 3.1.1 Requisitos de Maquinaria  
- **Servidores**:  
  - Aplicaciones: 8 núcleos, 32 GB RAM, 1 TB SSD.  
  - Bases de datos: 16 núcleos, 64 GB RAM, 2 TB SSD.  
  - Respaldos: 4 núcleos, 16 GB RAM, 4 TB HDD.  
- **Estaciones de trabajo**: Intel i5, 8 GB RAM, 512 GB SSD.  
- **Equipos de red**: Switches Gigabit, routers redundantes, firewall.  
- **NAS**: 10 TB, RAID, replicación.  

#### 3.1.2 Requisitos de Software  
- **Sistema de gestión**: Web app, integración con pasarelas de pago.  
- **Bases de datos**: PostgreSQL/MySQL.  
- **Seguridad**: Monitorización, antivirus, SSL.  
- **Virtualización**: VMware/Proxmox.  

#### 3.1.3 Infraestructura de Red  
- **Conectividad**: 1 Gbps principal + redundante.  
- **Diseño**: Segmentación VLAN (gestión, usuarios, servidores).  
- **Seguridad**: Firewall, VPN (WireGuard, OpenVPN), políticas de acceso.  

#### 3.1.4 Escalabilidad y Disponibilidad  
- Balanceo de carga.  
- Clúster de bases de datos.  
- Plan de recuperación ante desastres.  

---

## 4. Recursos Necesarios  
### 4.1 Presupuesto  
#### Hardware (Total: €20,218)  
| ELEMENTO                                   | CANTIDAD | COSTE (unidad) | COSTE TOTAL  |
|--------------------------------------------|----------|---------------|--------------|
| Servidor de aplicaciones                   | 1        | 3.776 €       | 3.776 €      |
| Servidor de bases de datos                 | 1        | 4.777 €       | 4.777 €      |
| Servidor de respaldo                       | 2        | 3.000 €       | 6.000 €      |
| NAS (10TB escalable)                       | 1        | 1.500 €       | 1.500 €      |
| Estaciones de trabajo                      | 3        | 800 €         | 2.400 €      |
| Switches de red Gigabit (paquete 24)       | 2        | 215 €         | 430 €        |
| Routers                                    | 2        | 210 €         | 420 €        |
| AP Wifi                                    | 1        | 137 €         | 137 €        |
| Medidas de seguridad físicas               | 1        | 3.500 €       | 3.500 €      |
| SAI                                        | 1        | 278 €         | 278 €        |
| **TOTAL**                                  |          |               | **23.218 €** |


#### Software (Total: €3,027)  
| ELEMENTO                                     | LICENCIAS | COSTE (unidad) | COSTE TOTAL  |
|----------------------------------------------|-----------|---------------|--------------|
| Sistema operativo servidores (Windows Server) | 4         | 0 €           | 0 €          |
| Soporte empresarial (MySQL)                   | 1         | 2.000 €       | 2.000 €      |
| Software de backup (Aomei Backup)             | 1         | 700 €         | 700 €        |
| Sistema de virtualización (VMWare Workstation Pro) | 1    | 193 €         | 193 €        |
| Antivirus y herramientas de seguridad (F-Secure) | 10     | 10 €          | 100 €        |
| Monitorización (Pandora FMS)                  | 1         | 34 €          | 34 €         |
| **TOTAL**                                     |           |               | **3.027 €**  |


#### Infraestructura de Red (Total: €7,500)  
| ELEMENTO                              | CANTIDAD | COSTE (unidad) | COSTE TOTAL  |
|---------------------------------------|----------|---------------|--------------|
| Conexión principal (1Gbps)           | 1        | 2.500 €       | 2.500 €      |
| Conexión redundante                  | 1        | 2.000 €       | 2.000 €      |
| Estructuración y montaje de cableado  | 1        | 3.000 €       | 3.000 €      |
| **TOTAL**                             |          |               | **7.500 €**  |

### 4.1.4 Servicios Profesionales
| ELEMENTO                               | HORAS ESTIM. | COSTE (hora) | COSTE TOTAL  |
|----------------------------------------|--------------|-------------|--------------|
| Instalación y configuración de hardware | 50          | 50 €        | 2.500 €      |
| Configuración de software y pruebas    | 60          | 50 €        | 3.000 €      |
| Auditoría inicial de seguridad         | 20          | 80 €        | 1.600 €      |
| **TOTAL**                              |              |             | **7.100 €**  |

---

## 5. Evaluación de Riesgos y Contingencias  
### 5.1 Identificación de Riesgos  
- **Tecnológicos**: Fallo de hardware, ciberataques.  
- **Ambientales**: Cortes eléctricos, incendios.  
- **Humanos**: Errores operativos, sabotaje.  

### 5.2 Plan de Contingencia  
- **Medidas preventivas**: Monitoreo, backups, formación.  
- **Respuesta a incidentes**:  
| Incidente         | Acciones Inmediatas                                                       |
|------------------|--------------------------------------------------------------------------|
| Fallo de hardware | Conmutación a servidores de respaldo, aviso a soporte técnico         |
| Ciberataque      | Aislamiento del sistema, análisis de logs, restauración de backup     |
| Pérdida de datos | Restauración de la última copia de seguridad, análisis de causa       |
| Corte eléctrico  | Uso de UPS y generador, notificación a proveedor eléctrico            |
| Incendio/Inundación | Activación de protocolos de evacuación, traslado a sitio alternativo |


- **Recuperación**: Sitio de respaldo con replicación en tiempo real.  
