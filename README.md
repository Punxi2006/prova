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
| Tarea                                | Duración (días) | Inicio      | Fin         |
|--------------------------------------|-----------------|-------------|-------------|
| Definición de objetivos              | 1.181           | 09/01/25    | 10/01/25    |
| Análisis de requisitos               | 2.972           | 10/01/25    | 13/01/25    |
| Elaboración del cronograma           | 2.819           | 10/01/25    | 13/01/25    |
| Asignación de roles                  | 4.306           | 14/01/25    | 20/01/25    |
| Identificación de recursos           | 2.819           | 10/01/25    | 13/01/25    |
| Evaluación de riesgos                | 4.306           | 14/01/25    | 20/01/25    |
| Revisión y aprobación del plan       | 4.028           | 20/01/25    | 23/01/25    |

### 1.4 Cronograma  
| #  | Tarea                                | Duración (días) | Inicio      |
|----|--------------------------------------|-----------------|-------------|
| 1  | Primer Sprint                       | 13.361          | 09/01/25    |
| 2  | Definición de objetivos             | 1.181           | 09/01/25    |
| 3  | Análisis de requisitos              | 2.972           | 10/01/25    |
| 4  | Elaboración del cronograma          | 2.819           | 10/01/25    |
| 5  | Asignación de roles                 | 4.306           | 14/01/25    |
| 6  | Identificación de recursos          | 2.819           | 10/01/25    |
| 7  | Evaluación de riesgos               | 4.306           | 14/01/25    |
| 8  | Revisión y aprobación               | 4.028           | 20/01/25    |

### 1.5 Equipo  
- **Jonman Jimenez Mendoza**: Líder del Proyecto.  
- **Jaime Climent Cardona**: Administrador de Infraestructura TI.  
- **Frances Simó Olmo**: Gestor de Riesgos.  

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
| Elemento                  | Cantidad | Coste/Unidad | Total    |
|---------------------------|----------|--------------|----------|
| Servidor de aplicaciones  | 1        | €3,776       | €3,776   |
| Servidor de bases de datos| 1        | €4,777       | €4,777   |
| NAS                       | 1        | €1,500       | €1,500   |

#### Software (Total: €3,027)  
| Elemento                  | Licencias | Coste/Unidad | Total    |
|---------------------------|-----------|--------------|----------|
| Soporte MySQL             | 1         | €2,000       | €2,000   |
| Software de backup        | 1         | €700         | €700     |

#### Infraestructura de Red (Total: €7,500)  
| Elemento                  | Cantidad | Coste/Unidad | Total    |
|---------------------------|----------|--------------|----------|
| Conexión principal        | 1        | €2,500       | €2,500   |
| Estructura de cableado    | 1        | €3,000       | €3,000   |

---

## 5. Evaluación de Riesgos y Contingencias  
### 5.1 Identificación de Riesgos  
- **Tecnológicos**: Fallo de hardware, ciberataques.  
- **Ambientales**: Cortes eléctricos, incendios.  
- **Humanos**: Errores operativos, sabotaje.  

### 5.2 Plan de Contingencia  
- **Medidas preventivas**: Monitoreo, backups, formación.  
- **Respuesta a incidentes**:  
  | Incidente          | Acciones                        |
  |--------------------|---------------------------------|
  | Fallo de hardware  | Activación de servidores de respaldo. |
  | Ciberataque        | Aislamiento y restauración de backups. |

- **Recuperación**: Sitio de respaldo con replicación en tiempo real.  
