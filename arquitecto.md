# Checklist de cumplimiento — Arquitecto de Infraestructura

> Niveles incluidos: **TRAINEE** y **JUNIOR**  
> Formato: Área → Tema → Ítems evaluables

---

# TRAINEE

## Perfil / definición del rol
- [ ] Se evidencia rol de **líder técnico** con conocimientos sólidos de **arquitectura, infraestructura y cloud**.
- [ ] Conoce diversas tecnologías y **métodos de integración**.
- [ ] Conoce el **proceso de diseño** y muestra interés/apasionamiento por aprender.

---

## Infraestructura — Fundamentos de Infraestructura
- [ ] Implementa acciones básicas sobre servicios de infraestructura (web, directorio, ficheros, bases de datos, etc.) en servidores físicos o virtuales.
- [ ] Distingue diferencias y relaciones entre servicios en distintos ambientes y ubicaciones del cliente.
- [ ] Identifica qué **sistemas operativos (SO)** maneja y su nivel.
- [ ] Describe experiencia realizando **parchado**.
- [ ] Resuelve el escenario: remediar vulnerabilidad RDP en **100 servidores** (enfoque, plan, ejecución, control).
- [ ] Explica si tiene conocimiento de **virtualización** y da ejemplos.
- [ ] Explica qué es un **bastion host** y para qué sirve.

---

## DevOps — Fundamentos DevOps
- [ ] Implementa automatización mediante scripting (PowerShell, Bash, Python u otro).
- [ ] Sabe aprovisionar arquitecturas mediante **IaC**.
- [ ] Describe la arquitectura más compleja que ha desplegado y con qué lenguaje/herramienta.
- [ ] Explica qué es un repositorio de versionamiento.
- [ ] Da ejemplos de comandos de versionamiento (básicos).

---

## Networking — Fundamentos de Redes
- [ ] Entiende conceptos de **VPN**, **VLAN**, **subneteo/CIDR**, segmentos de red y enrutamiento.
- [ ] Aplica conceptos en escenarios prácticos y hace troubleshooting básico.
- [ ] Propone un buen diseño de redes en nube (criterios y componentes).

---

## Seguridad — Fundamentos de Seguridad
- [ ] Aplica conceptos de seguridad para acceso a recursos (autenticación/autorización) y seguridad en sistemas operativos.
- [ ] Entiende y aplica el principio de **mínimo privilegio** y buenas prácticas de aseguramiento.
- [ ] Explica para qué sirve **IAM**.
- [ ] Explica el concepto de **mínimo privilegio** con claridad.
- [ ] Explica qué es **hardening**.
- [ ] Explica qué es un ataque **DDoS**.
- [ ] Menciona otros tipos de ataques que conoce (y breve descripción).

---

## Almacenamiento y Cómputo — Base Infraestructura TI
- [ ] Administra y diseña almacenamiento de **objetos, archivos y bloques** (on-prem o cloud).
- [ ] Distingue entre almacenamiento **permanente** y **temporal**.
- [ ] Explica tipos de almacenamiento (p. ej., EFS/EBS/Blob) y casos de uso de cada uno.
- [ ] Resuelve el escenario: dónde almacenar un **video 4K de 4 horas** (decisión y justificación).

---

## Bases de datos — Fundamentos SQL
- [ ] Está familiarizado con SQL y realiza consultas en algún motor de BD.
- [ ] Entiende funcionamiento y casos de uso de motores **relacionales**.
- [ ] Distingue bases de datos **distribuidas** vs **centralizadas**.
- [ ] Distingue entre bases de datos **relacionales** y **no relacionales**.
- [ ] Explica qué es **SQL**, **DDL** y **DML**.
- [ ] Explica qué es una BD relacional.
- [ ] Resuelve el escenario: con tablas *cliente* y *productos*, obtener qué productos compró un cliente y cantidades ordenadas descendentemente.

---

## Cloud Computing — Fundamentos Cloud
- [ ] Identifica diferencias entre **IaaS, PaaS, SaaS, FaaS** y da ejemplos claros.
- [ ] Gestiona de forma consistente servicios desde interfaces gráficas (con criterio operativo).
- [ ] Define IaaS/PaaS/SaaS con ejemplos.
- [ ] Indica qué servicios usaría para entender el estado de un servicio en nube.

---

## Observabilidad — Fundamentos de Monitoreo y Observabilidad
- [ ] Reconoce la importancia de entender el estado de soluciones desplegadas.
- [ ] Configura monitoreo usando alguna herramienta (mínimo básico).
- [ ] Enumera pilares de monitoreo que conoce.

---

## Estilos y conceptos de Arquitecturas — Fundamentos de Arquitectura
- [ ] Identifica atributos de calidad relevantes según contexto de negocio.
- [ ] Conoce el **Well-Architected Framework**.
- [ ] Explica qué es una arquitectura orientada a eventos.
- [ ] Explica qué es SOA.

---

# JUNIOR

## Perfil / enfoque de nivel
- [ ] Muestra autonomía para dirigir problemas similares.
- [ ] Demuestra comprensión contextual.
- [ ] Toma decisiones adecuadas para situaciones estándar.

---

## Infraestructura — Manejo de infraestructura
- [ ] Implementa acciones de mejora, troubleshooting y automatización sobre arquitecturas **cloud native**, tradicionales y **serverless**.
- [ ] Entiende conceptos de HPC como **placement groups** y optimización de recursos.
- [ ] Explica dos métodos de actualizaciones: **Canary**, **Rolling**, **Blue/Green**.
- [ ] Explica el concepto de “las **Rs**” y da ejemplos.
- [ ] Resuelve escenario: migrar **SQL Server 50GB** a cloud sin interrupción y sin perder licenciamiento (enfoque y plan).
- [ ] Explica qué significa “**as a service**”.
- [ ] Explica qué hacen los comandos indicados (x, x, x, x) cuando aplique.

---

## Networking — Manejo de redes
- [ ] Define e implementa una solución de networking básica para despliegue en nube.
- [ ] Define **CIDRs** con capacidad de crecimiento.
- [ ] Diseña red altamente disponible (capa transporte, seguridad) incluyendo servicios como **VPN**.
- [ ] Entiende capas modelo **OSI**, modelo **TCP/IP**, sockets, puertos y conceptos relacionados.
- [ ] Calcula cuántas IPs cubre el segmento **10.0.0.0/24**.
- [ ] Explica la función de un **NAT Gateway**.
- [ ] Resuelve escenario: EKS debe comunicarse con S3 sin salir a Internet (solución y componentes).

---

## Seguridad — Conocimiento de seguridad
- [ ] Diseña soluciones de seguridad en nube para mitigar vulnerabilidades.
- [ ] Reduce superficie de ataque a nivel de red.
- [ ] Ejecuta/define escaneo y evaluación de vulnerabilidades.
- [ ] Indica servicios para monitorear y cerrar brechas de seguridad.
- [ ] Explica cómo identificar un ataque y cómo repelerlo (respuesta/mitigación).

---

## Almacenamiento y Cómputo — Manejo de infraestructura TI
- [ ] Diseña, administra y optimiza distintos tipos de almacenamiento según casos de uso.
- [ ] Dimensiona cómputo de forma escalable y costo-eficiente según demanda.
- [ ] Explica diferencia entre almacenamiento de **bloque** y **objeto**.
- [ ] Explica qué entiende por **FaaS**.
- [ ] Enumera consideraciones para seleccionar cómputo y almacenamiento (rendimiento, costo, IOPS, latencia, durabilidad, escalabilidad, etc.).

---

## Bases de datos — Definiciones de bases de datos
- [ ] Aplica el teorema **CAP** en selección de soluciones (según necesidad del cliente).
- [ ] Realiza actividades de administración de BD.
- [ ] Desarrolla scripts básicos de administración y automatización.
- [ ] Explica de qué trata CAP.
- [ ] Explica qué es **NoSQL** y menciona motores que conoce.
- [ ] Diferencia **OLAP** vs **OLTP**.
- [ ] Explica salida de joins: **inner, left, right, full outer** (con ejemplo de tablas).

---

## Observabilidad — Manejo de monitoreo y observabilidad
- [ ] Implementa monitoreo de baja y media complejidad con alertamiento proactivo.
- [ ] Explica objetivo y ventajas de observabilidad vs monitoreo.
- [ ] Entiende y contextualiza los **3 pilares** de observabilidad.
- [ ] Resuelve escenario: degradación en ciertos momentos del día sin visibilidad/alertas (plan de instrumentación + alertas + trazas/logs/métricas).
- [ ] Explica qué es **CloudWatch Agent**.
- [ ] Indica prerrequisito para definir **métricas personalizadas**.
- [ ] Explica cómo monitorear métricas de sistema operativo (OS metrics).
- [ ] Explica qué permite **CloudWatch Logs**.
- [ ] Resuelve escenario compliance: retener logs de llamadas de API en AWS por **2 años**.

---

## DevOps — Bases de cultura DevSecOps
- [ ] Explica diferencias entre **CI** y **CD** con ejemplos prácticos.
- [ ] Produce templates IaC modulares (o stacks anidados) reutilizables en uno o varios lenguajes.
- [ ] Produce scripts en Python/Bash/PowerShell u otro.
- [ ] Describe el concepto de **Infraestructura como Código (IaC)**.
- [ ] Enumera herramientas usadas para IaC.
- [ ] Describe qué recursos ha creado con IaC.
- [ ] Indica sección mandatoria en un template de **CloudFormation**.
- [ ] Explica diferencia entre **terraform plan** y **terraform apply**.

---

## Marcos de referencia de la nube — Buenas prácticas Cloud
- [ ] Aplica principios del **Well-Architected Framework**.
- [ ] Aplica cada pilar en diseño e implementación de arquitecturas.
- [ ] Es capaz de llevar a cabo un **WAR** (Well-Architected Review).
- [ ] Explica cada pilar y cómo lo apalanca con servicios en una arquitectura.

---

## Continuidad de negocio — Fundamentos de resiliencia
- [ ] Aplica conceptos: **RTO, RPO, HA, DRP, Backup/Restore** en servicios cloud.
- [ ] Explica cómo los **SLAs** determinan la estrategia de continuidad.
- [ ] Explica buenas prácticas para gestión de plataformas en nube.
- [ ] Describe: excelencia operacional, seguridad, confiabilidad, performance, optimización de costos.
- [ ] Da un ejemplo de qué tener en cuenta según Well-Architected Framework.
- [ ] Explica la ventaja de aplicar un **WAR**.

---

## Estilos y conceptos de Arquitecturas — Manejo de arquitecturas
- [ ] Explica con ejemplos: microservicios, event-driven, monolíticas.
- [ ] Explica qué es una arquitectura orientada a eventos.
- [ ] Explica qué es SOA.
