# Checklist de cumplimiento — Arquitecto de Infraestructura (ADVANCED, SENIOR, MASTER)

> Formato: Nivel → Área → Tema → Ítems evaluables

---

# ADVANCED

## Perfil / enfoque de nivel
- [ ] Puede resolver nuevos problemas.
- [ ] Demuestra comprensión conceptual sólida.
- [ ] Toma decisiones activas con poca o ninguna supervisión.

---

## Infraestructura — Manejo e implementación de Infraestructura
- [ ] Entiende e integra conceptos de **Data Warehousing, Data Lake, Big Data, Visualización, HPC y Clustering** en una arquitectura (implementación o preventa).
- [ ] Realiza mantenimiento a escala con **Manage as Code** (Chef, Puppet, Ansible u OpsWorks Stacks).
- [ ] Define una arquitectura que incorpore **RSocket o gRPC**.
- [ ] Explica estrategia end-to-end para construir una solución de analítica (componentes + estrategia analítica).
- [ ] Define qué arquitectura usaría para desarrollar microservicios en el ejercicio propuesto.
- [ ] Implementa Manage as Code y explica sus ventajas.

---

## Networking — Definiciones de redes
- [ ] Define e implementa networking para estrategia cloud de cualquier tamaño con alta escalabilidad y resiliencia.
- [ ] Usa componentes como **Transit Gateway**, **VPN redundantes**, **Direct Connect**, **NAT Gateway**.
- [ ] Define un esquema de direccionamiento (CIDR) considerando crecimiento orgánico.
- [ ] En AWS, justifica cuándo usar: **VPG**, **Direct Connect**, **VPN**, **VPC Peering**, máscaras de red.
- [ ] Resuelve el escenario multi-cuenta del banco:
  - [ ] Reduce carga operativa del peering con una solución escalable y mantenible.
  - [ ] Mejora rendimiento y disponibilidad frente a caídas de VPN.
  - [ ] Implementa control centralizado de asignación/gestión de IPs por cuenta.
  - [ ] Considera conectividad entre nube, on-prem y entre VPCs.
  - [ ] Propone componentes, flujos y gobierno de red.

---

## DevOps — Cultura DevSecOps
- [ ] Diseña e implementa estrategias de **CI** y **CD** con definición clara de branching y casos de uso.
- [ ] Desarrolla IaC de complejidad media con mejores prácticas y análisis estático de infraestructura.
- [ ] Define criterios para seleccionar estrategia de branching.
- [ ] Diseña estrategia CI/CD (diferencias CI vs CD) y cómo implementarla en un pipeline.

---

## Seguridad y Cumplimiento — Modelo de madurez de seguridad
- [ ] Define e implementa estrategias evolutivas en autenticación y autorización según necesidades de compliance.
- [ ] Diseña gestión multicuenta con enfoque de seguridad.
- [ ] Reduce superficie de ataque y define protección perimetral.
- [ ] Realiza hardening a nivel detallado.
- [ ] Analiza requerimientos de compliance y asegura cumplimiento en nube.
- [ ] Controla el estado de recursos con mecanismos de gobierno/estado (inventario, drift, compliance, etc.).
- [ ] Garantiza cifrado por defecto (p. ej., que un **EBS siempre esté encriptado**).
- [ ] Explica qué son **Conformance Packs (PCI)**.

---

## Base de datos — Definir y aplicar bases de datos
- [ ] Aplica teoremas **ACID, CAP, BASE** según el tipo de base de datos y necesidad.
- [ ] Automatiza tareas administrativas, performance y monitoreo proactivo.
- [ ] Realiza migraciones **homogéneas** y **heterogéneas** de BBDD.
- [ ] Hace troubleshooting sobre BBDD relacionales y no relacionales.
- [ ] Planifica migraciones de datos y selecciona herramientas adecuadas.
- [ ] Enumera tipos de bases de datos que conoce y cómo las optimiza.

---

## Continuidad de negocio — Diseños resilientes
- [ ] Expone ejemplos claros de estrategia de **DRP** y continuidad de negocio.
- [ ] Define e implementa HA, elasticidad, Backup/Restore, replicación y DRP.
- [ ] Negocia SLAs con clientes y los soporta en arquitectura.
- [ ] Ejecuta pruebas de recuperación (ambientes completos o parciales).
- [ ] Conoce e implementa modelos de despliegue: **canary, rolling upgrade, blue/green**.
- [ ] Explica conceptos de HA, elasticidad, backup, replicación, DRP y SLA.

---

## Almacenamiento y Cómputo — Diseños de infraestructura TI
- [ ] Diseña cómputo en IaaS (EC2).
- [ ] Orquesta microservicios con ECS/EKS/Kubernetes.
- [ ] Diseña cómputo serverless (Lambda, Lightsail, Fargate).
- [ ] Dimensiona almacenamiento por componente e identifica configuraciones particulares según caso de uso.
- [ ] Resuelve escenario ASG: mitigación de lentitud por incorporación tardía de instancias.
- [ ] Resuelve escenario Aurora PostgreSQL: evitar degradación cuando analítica consulta la BD (estrategia y medidas).

---

## Observabilidad — Implementación de monitoreo y observabilidad
- [ ] Analiza comportamientos y selecciona datos relevantes (logs, etc.) para optimizar rendimiento.
- [ ] Implementa monitoreo de baja y media complejidad con alertamiento y **autoremediación**.
- [ ] Implementa estrategia de observabilidad **E2E** (retención, compliance, veracidad).
- [ ] Audita acciones y notifica near real-time cuando ocurren en servicios.
- [ ] Define cómo “perpetuar” logs de **CloudTrail** (retención/archivo).

---

## Estilos y conceptos de Arquitecturas — Diseños de arquitecturas
- [ ] Domina más de 3 estilos arquitectónicos y los justifica en servicios cloud.
- [ ] Explica y aplica: **MACH**, **Microfrontend**, **EDA** (y otros si aplica).
- [ ] Explica 2 modelos de arquitectura y sus ventajas.
- [ ] Diferencia **stateless** vs **stateful**.
- [ ] Explica qué entiende por “**bastardizing**” de una arquitectura y cómo evitarlo.

---

## Integración — Integración de arquitecturas
- [ ] Define modelos de integración resilientes y escalables de mediana/alta complejidad.
- [ ] Implementa arquitecturas de integración y conoce su estado en cualquier momento (observabilidad de integración).
- [ ] Explica tipos de colas en **SQS**.
- [ ] Indica en qué caso es mejor cada tipo de cola.
- [ ] Resuelve escenario ecommerce: pérdida de peticiones front-back (arquitectura y acciones correctivas).

---

## Estrategias Cloud — Definición e implementación de estrategias
- [ ] Conoce y aplica estrategias de administración de cuentas.
- [ ] Define estructura de gobierno cloud.
- [ ] Maneja situación de riesgo comercial: cliente quiere cancelar por falta de valor (plan de retención, quick wins, plan de valor).

---

## Marcos de referencia de la nube — Buenas prácticas Cloud
- [ ] Aplica y lidera **WAR** y **CAF** (acompaña talleres de arquitectura).
- [ ] Resuelve escenario de sobreaprovisionamiento/costos altos (diagnóstico + plan de optimización).
- [ ] Explica fases/etapas del **CAF**.

---

# SENIOR

## Perfil / enfoque de nivel
- [ ] Tiene visión de big picture y pensamiento sistémico.
- [ ] Lidera temas importantes.
- [ ] Domina reglas, teorías y alternativas con comprensión profunda.

---

## Infraestructura — Manejo, implementación e innovación de infraestructura
- [ ] Diseña e implementa arquitecturas complejas: Big Data (Kafka, MapReduce, Spark en cloud), HPC o clúster de cómputo.
- [ ] Ha gestionado servidores de aplicación (Tomcat, WebSphere u otros) o explica cómo lo haría.
- [ ] Identifica indicadores/elementos que más impactan la optimización de una implementación recibida.
- [ ] Migra un servidor de aplicaciones a nube (plan técnico).
- [ ] Resuelve escenario WebSphere en nube: desacoplar solución y mitigar cuellos de botella de hardware.

---

## DevOps — Implementación, diseño e innovación (enfoque infraestructura)
- [ ] Diseña pipelines que incluyan despliegue + estrategias de despliegue + vulnerabilidades + validaciones técnicas automatizadas.
- [ ] Implementa arquitecturas modulares altamente escalables y disponibles.
- [ ] Conecta VPCs en regiones distintas minimizando carga operativa (doble vía) y lo justifica.
- [ ] Define consideraciones para implementar **Direct Connect**.
- [ ] Configura acceso privado EC2 → S3 sin Internet (componentes y enfoque).
- [ ] Implementa VPN en AWS y define consideraciones.

---

## Seguridad y Cumplimiento — Cultura DevSecOps
- [ ] Define e implementa políticas de cumplimiento y seguridad a nivel usuario y organización.
- [ ] Prioriza automatización, trazabilidad y recuperación.
- [ ] Conoce estilos de arquitectura de seguridad (p. ej., PACE) y herramientas de seguridad.
- [ ] Define estrategia de networking de alto nivel con seguridad y optimización.
- [ ] Selecciona herramienta para análisis de seguridad de cuenta cloud y requisitos de despliegue.
- [ ] Garantiza parches/versiones y buenas prácticas en cómputo de forma periódica y automática.
- [ ] Implementa línea base de seguridad automatizada.
- [ ] Asesora cliente en consideraciones clave de seguridad cloud y plan de adopción.

---

## Base de datos — Diseño e innovación de bases de datos
- [ ] Diseña arquitecturas altamente transaccionales y selecciona motor/configuración según caso de uso.
- [ ] Evalúa impactos de rediseño sobre la solución.
- [ ] Dimensiona capacidades en modelos IaaS/PaaS y estrategias para desacoplar consultas/mejorar rendimiento.
- [ ] Usa herramientas de automatización y describe acciones realizadas.
- [ ] Usa automatización nativa (p. ej., Runbooks, EventBridge Rules) según escenarios.
- [ ] Desarrolla script bash para copiar, comprimir y registrar ejecución.
- [ ] Maneja errores de Lambda y define flujo alterno si falla (diseño e implementación).

---

## Continuidad de negocio — Diseños altamente resilientes
- [ ] Diseña e implementa HA y DRP considerando impacto por componente (incluye multirregión).
- [ ] Identifica casos de uso y propone arquitectura que los soporte.
- [ ] Lidera equipo cliente y propio para implementar solución adecuada.
- [ ] Aporta escenarios de trabajo bajo DevOps/SRE y aplicaciones prácticas.
- [ ] Explica operaciones Git: clone, merge, pull, push.
- [ ] Compara Jenkins vs CodePipeline/Azure DevOps (casos de uso).
- [ ] Explica cómo implementar Jenkins en cloud.

---

## Almacenamiento y Cómputo — Diseños de infraestructura TI
- [ ] Diseña contenedores/serverless/kubernetes con optimización de costos y automatización de sizing.
- [ ] Selecciona balanceador adecuado según protocolo y necesidades del cliente.
- [ ] Justifica caso de negocio y técnico para serverless vs contenedores (motivaciones y trade-offs).

---

## Observabilidad — Innovación e implementación de monitoreo y observabilidad
- [ ] Diseña e implementa solución de observabilidad con estándares de mercado y como habilitador de DevOps.
- [ ] Conoce pilares de observabilidad y los ha aplicado en clientes.
- [ ] Resuelve escenarios de migración:
  - [ ] Migrar VMWare ESX a cloud.
  - [ ] Migrar RDBMS + Mongo + Oracle a cloud (proceso técnico).
  - [ ] Migrar Wordpress a nube con arquitectura serverless.
  - [ ] Migrar 1500GB a almacenamiento low-cost con limitación de ancho de banda y archivos grandes.

---

## Estilos y conceptos de Arquitecturas — Innovación de arquitecturas
- [ ] Aplica ADD 2.0/3.0, DDD, y evalúa arquitectura con ATAM o SAAM.
- [ ] Identifica problema raíz y propone arquitectura de infraestructura acorde.
- [ ] Optimiza costo-eficiencia en infraestructura.
- [ ] Entiende economía de APIs.
- [ ] Define proceso para implementar IaC reutilizable de infraestructura completa (cómputo, networking, seguridad y BBDD).

---

## Estrategias Cloud — Definición e innovación de estrategias
- [ ] Entiende y enseña Cloud Native.
- [ ] Aplica estrategias de administración de cuentas.
- [ ] Estructura gobierno cloud y usa Control Tower (o similar) adecuadamente.

---

## Documentación — Definición y estructuración
- [ ] Presenta modelos claros por stakeholder usando vistas y puntos de vista.
- [ ] Usa C4 y sketch cuando aplica.

---

# MASTER

## Perfil / enfoque de nivel
- [ ] Tiene intuición y conocimiento tácito.
- [ ] Visión de lo posible e innovación constante.

---

## Innovación — Nuevas tecnologías en cloud
- [ ] Realiza consultoría para cliente preocupado por **costos** y **seguridad** en su infraestructura cloud (diagnóstico + plan).
- [ ] Resuelve escenario Wordpress en ECS privado con EFS + ALB + imágenes desde DockerHub:
  - [ ] Conecta un sitio a SAP on-prem de tercero con restricción de IP/puerto.
- [ ] Diseña solución de onboarding bancario con tecnología on-prem obsoleta, buscando agilidad/escalabilidad y cumpliendo restricción de datos en país (plantea caso para dos países).

---

## Diseño — Diseñar arquitecturas altamente complejas
- [ ] Implementa canary deployment en cloud con tecnologías serverless.
- [ ] Diseña procesamiento stream near-real-time: almacenar HA, descomprimir, procesar, guardar salida y notificar usuario.
- [ ] Diseña solución con MSK (Kafka) auto-administrado:
  - [ ] Sin Lambda, costo eficiente.
  - [ ] Sincroniza archivos procesados a S3 automáticamente.
  - [ ] Reacciona a cambios en bucket para activar procesamiento (sin Lambda).
  - [ ] Flujo: archivos grandes/múltiples formatos → descomprimir → procesar → publicar a tópico.

---

## Troubleshooting avanzado
- [ ] Controla despliegues y garantiza etiquetado obligatorio (tags) mitigando riesgos de seguridad y optimización de costos.
- [ ] Define estrategia DevOps y explica CI/CD con ejemplos reales.
- [ ] Define estrategia de branching adecuada para equipo con mayoría junior/advance.

---

## Estrategias Multi Cloud
- [ ] Optimiza procesamiento batch nocturno en EC2 on-demand con ASG (max 6):
  - [ ] Reduce costo.
  - [ ] Garantiza ejecución y tolerancia a fallos.
  - [ ] Registra eventos fallidos para análisis/reprocesamiento.
  - [ ] Flujo automatizado para tareas.

---

## Observabilidad
- [ ] Diseña observabilidad para clúster EKS con 2 microservicios (100 peticiones/día), con trazabilidad adecuada.

---

## Seguridad
- [ ] Diseña estrategia para cumplir RPO 1h y RTO 24h en solución con:
  - [ ] Cómputo (subredes privadas/públicas), BD key-value, almacenamiento archivos estáticos, motores relacionales, balanceadores.
  - [ ] Plan de implementación paso a paso y justificación.

---

## Documentación (casos operativos)
- [ ] Implementa notificación a equipo cuando ocurran errores 500 tras despliegue en EC2.
- [ ] Detecta consultas costosas en RDS y define cómo identificarlas.
- [ ] Migra catálogo relacional a servicio autoadministrado para fortalecer acceso global (propuesta de arquitectura/servicios).
- [ ] Implementa gestión de usuarios con compliance PCI + DRP + 2FA.
- [ ] Resuelve incidente de “cold start”/latencia en lambdas Java inactivas que invocan servicios (y latencia al escalar).

---

## DevSecOps (gobierno y compliance como código)
- [ ] Implementa landing zone y gestión centralizada de cuentas con controles automáticos (con detalle).
- [ ] Audita automáticamente incidentes de seguridad causados por modificaciones en IaC.
- [ ] Aplica enfoque de governance/compliance como código (según referencia incluida).

---

## Procesamiento de datos
- [ ] Define plan de mejora detallado a partir de SOW del WAR:
  - [ ] Estrategia de observabilidad.
  - [ ] Detección y remediación de vulnerabilidades.
  - [ ] Gestión de cuotas de servicios.
- [ ] Propone solución para gestión de incidentes de seguridad, postura y análisis de seguridad en cuenta.

---

## Entrega de conocimiento — Mentor de mentores
- [ ] Implementa estrategia “mentor de mentores”.
- [ ] Define mecanismo para transferir conocimiento, estandarizar prácticas y escalar capacidades del equipo.
