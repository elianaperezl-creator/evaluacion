# Checklist de cumplimiento — Perfil Arquitecto SOA

> Estructura: Área → Tema → Ítems evaluables (marcar cumplimiento)

---

## SOA – API – Microservicios

### Fundamentos SOA – API – Microservicios
- [ ] Indica el uso de **API** y cómo se utiliza en el contexto de la **integración de sistemas**.
- [ ] Explica en qué consiste la **Arquitectura Orientada a Servicios (SOA)** aplicada al área de integración.

### Implementación SOA – API – Microservicios
- [ ] Demuestra creación y mantenimiento de **APIs/servicios/microservicios**.
- [ ] Define qué es la **documentación de una API** y por qué es crucial.
- [ ] Explica cómo se implementa un patrón de **bajo acoplamiento**.
- [ ] Describe el **ciclo de vida** de las APIs.

### Profundización en SOA – API – Microservicios
- [ ] Demuestra patrones de integración aplicados en una **solución real**.
- [ ] Aplica principios de **API** o **microservicios** en la solución.
- [ ] Entrega una solución aplicando **patrones**.
- [ ] Muestra el uso de **microservicios**.

### Diseño de la arquitectura SOA
- [ ] Demuestra patrones de integración aplicados en solución (diseño).
- [ ] Aplica principios de API (diseño).

### Fundamentos de arquitecturas de software
- [ ] Explica principios fundamentales para crear **arquitecturas de integración**.
- [ ] Describe un escenario de **arquitectura de integración de alto rendimiento**.
- [ ] Identifica consideraciones clave (rendimiento, escalabilidad, resiliencia, seguridad, etc.).
- [ ] Explica cómo implementar una arquitectura de integración **altamente disponible**.
- [ ] Menciona estrategias y tecnologías posibles para alta disponibilidad.

### Documentación de arquitectura (para audiencias)
- [ ] Presenta decisiones de arquitectura (sistemas, personas, componentes, contenedores y relaciones) a diferentes públicos.
- [ ] Usa diagramas/modelos: **C4**, **UML**, **ArchiMate** (u otros).

---

## Lenguaje de programación

### Fundamentos del lenguaje
- [ ] Se evidencian fundamentos del lenguaje de programación dominante (según stack del rol/proyecto).  

---

## Contenedores

### Fundamentos de contenedores
- [ ] Explica diferencia entre **contenedor** y **máquina virtual**.
- [ ] Describe cómo se usa **Docker** para crear y ejecutar contenedores.
- [ ] Explica finalidad de un **Dockerfile**.
- [ ] Menciona comandos básicos usados en Dockerfile.

### Orquestación de contenedores – integración
- [ ] Explica cómo vincular contenedores en una **red** en Docker.
- [ ] Describe diferencia entre **Docker Swarm** y **Kubernetes**.
- [ ] Muestra uso aplicado de **contenerización**.

### Monitoreo de contenedores – integración
- [ ] Demuestra tolerancia a fallos con estrategias en **Kubernetes**.
- [ ] Explica estrategias de monitorización y resolución de problemas en un clúster de Kubernetes.
- [ ] Implementa un sistema de gestión de **políticas de seguridad y acceso** en Kubernetes.

### Técnicas avanzadas de contenedores
- [ ] Explica vinculación de contenedores en red en Docker (avanzado).
- [ ] Diferencia Docker Swarm vs Kubernetes (avanzado).
- [ ] Muestra uso aplicado de contenerización (avanzado).

---

## Bases de datos

### Fundamentos de bases de datos
- [ ] Explica cómo funciona una BD **relacional** y sus componentes principales.
- [ ] Explica diferencia entre **clave primaria** y **clave foránea**.
- [ ] Explica principal ventaja de BD **NoSQL** vs relacionales.

### DML/DDL (SQL y NoSQL)
- [ ] Construye operaciones **CRUD** en SQL o NoSQL usando DDL/DML.

### Conocimiento intrínseco SQL / NoSQL
- [ ] Explica transacciones en SQL y propiedades **ACID**.
- [ ] Explica **CAP** en bases NoSQL (consistencia, disponibilidad, tolerancia a particiones).
- [ ] Explica cómo se implementan **vistas materializadas** y su impacto en rendimiento.

### Funcionalidad de BD / Funcionalidad NoSQL
- [ ] Explica funcionamiento de BD relacional y componentes principales.
- [ ] Explica PK vs FK (refuerzo).
- [ ] Explica ventaja de NoSQL vs relacionales (refuerzo).

---

## Seguridad

### Fundamentos de seguridad
- [ ] Explica seguridad en desarrollo de software y por qué es importante.
- [ ] Enumera al menos 3 prácticas básicas de seguridad en código.
- [ ] Explica importancia de **autenticación** y **autorización**.

### TLS / SSL / mTLS
- [ ] Expresa al menos 2 medidas básicas de seguridad para una API.
- [ ] Evidencia aplicación de protocolos de seguridad en soluciones al cliente.
- [ ] Detalla proceso de **cifrado/descifrado** con TLS, SSL y mTLS.

### Herramientas de análisis de vulnerabilidades
- [ ] Muestra uso de herramientas de **análisis dinámico** de seguridad.
- [ ] Muestra uso de seguridad en desarrollo (prácticas/herramientas).
- [ ] Implementa principio de **menor privilegio** en diseño de sistemas seguros.

### Técnicas de análisis de vulnerabilidades
- [ ] Expresa 2 medidas básicas de seguridad para API (refuerzo).
- [ ] Aplica protocolos de seguridad en soluciones al cliente (refuerzo).
- [ ] Detalla proceso TLS/SSL/mTLS (refuerzo).

### Arquitectura y estilos de seguridad
- [ ] Integra medidas de seguridad robustas en una arquitectura de integración.
- [ ] Enumera prácticas comunes para seguridad de datos en integraciones.
- [ ] Explica papel de autenticación y autorización en integraciones empresariales.
- [ ] Proporciona ejemplos de implementación.

---

## Técnicas de desarrollo

### Fundamentos de técnicas de desarrollo
- [ ] Explica **DDD** y su enfoque principal.
- [ ] Explica qué es **TDD** y por qué es beneficioso.
- [ ] Explica finalidad de **BDD** y relación con el comportamiento de la aplicación.

### TDD / BDD / DDD (aplicación)
- [ ] Aplica metodología **DDD, BDD y TDD** (evidencia práctica).
- [ ] Muestra integridad de pruebas BDD conforme evoluciona el código.
- [ ] Explica cómo aplicar DDD en sistemas existentes con arquitecturas heredadas.
- [ ] Crea un diseño de arquitectura basada en DDD a gran escala.

---

## Estilos y patrones de arquitectura

### Entendimiento e implementación: Arquitectura EDA
- [ ] Muestra cómo usar eventos para desacoplar componentes en microservicios.
- [ ] Describe cómo se maneja el “apuntador” en patrones asíncronos.
- [ ] Explica cómo garantizar fiabilidad e integridad de datos en consumo asíncrono usando el lenguaje dominante.

---

## Principios de diseño de software

### SOLID en arquitecturas limpias (1)
- [ ] Implementa/explica **LSP** en contexto de herencia.
- [ ] Explica **SRP**.
- [ ] Explica cómo se planifica y realiza una **daily** en Scrum.

### SOLID en arquitecturas limpias (2)
- [ ] Implementa/explica LSP (refuerzo).
- [ ] Explica SRP (refuerzo).
- [ ] Explica daily en Scrum (refuerzo).

---

## Protocolos de comunicación

### Fundamentos de protocolos de comunicación
- [ ] Describe cómo funciona **HTTP** y su estructura básica.
- [ ] Explica qué es **WebSocket** y cuándo conviene.
- [ ] Diferencia comunicación **REST** vs **SOAP**.

### Protocolos de comunicación no convencionales
- [ ] Explica diferencias de **RSocket** vs HTTP/1, HTTP/2 y WebSocket.
- [ ] Explica cómo **gRPC** facilita comunicación en microservicios.
- [ ] Explica manejo de mensajes y colas en **AMQP**.
- [ ] Explica rendimiento/flexibilidad de **GraphQL** vs REST.

### Integración de protocolos no convencionales
- [ ] Selecciona y configura protocolos de seguridad para garantizar confidencialidad, integridad y autenticación.
- [ ] En IoT, gestiona diversidad de protocolos para interconexión eficiente y segura.
- [ ] Define estrategias para manejar partición de red y conflictos en sistemas distribuidos.

---

## Herramientas de integración

### Brokers de mensajería
- [ ] Explica función de brokers de mensajes entre aplicaciones.
- [ ] Implementa patrón **pub/sub** usando middleware.
- [ ] Explica importancia de interoperabilidad al usar herramientas de middleware.

---

## Versionamiento

### Fundamentos de versionamiento de código
- [ ] Usa Git acorde a estrategia de branching del proyecto.
- [ ] Domina funciones básicas: commit, PR, clone, merge.
- [ ] Domina funciones avanzadas: stash, rebase, rm, reset, checkout.

### Control y monitoreo de versionamiento
- [ ] Aplica mejores prácticas para ramas y etiquetas en entorno colaborativo.
- [ ] Revierte cambios específicos sin perder historial.
- [ ] Aplica técnicas avanzadas: rebase interactivo y cherry-pick.

### Técnicas de versionamiento
- [ ] Diferencia repositorio local vs remoto.
- [ ] Maneja y resuelve conflictos en Git.
- [ ] Explica qué es Git y su función.
- [ ] Explica propósito de ramas temporales (feature/hotfix, etc.).
- [ ] Explica ramas inmutables y su uso en despliegue/versionamiento moderno.

---

## DevSecOps

### Fundamentos de DevSecOps
- [ ] Explica por qué automatización es importante en DevOps y qué automatizar.
- [ ] Explica propósito de pruebas de integración en CI/CD.
- [ ] Explica cómo realizar despliegue continuo (CD) en producción.

### Estrategias de DevSecOps
- [ ] Aplica estrategias de branching.
- [ ] Implementa escaneo de dependencias.
- [ ] Diseña arquitectura para implementar filosofía **SRE** en un proyecto DevOps.
- [ ] Gestiona errores y correcciones (prácticas operativas).

### Técnicas de DevSecOps
- [ ] Aplica técnicas avanzadas de seguridad y cumplimiento en DevOps.
- [ ] Demuestra infraestructura como código (IaC) a gran escala.
- [ ] Explica y aplica despliegue canario (canary deployment).
- [ ] Explica consideraciones para estrategia DevOps en apps distribuidas y escalables.

---

## Cloud computing

### Implementaciones básicas cloud
- [ ] Diferencia **IaaS, PaaS, SaaS**.
- [ ] Configura y despliega una instancia virtual en AWS/Azure.
- [ ] Enumera al menos 3 servicios de almacenamiento cloud.
- [ ] Diferencia regiones vs zonas de disponibilidad.

### Buenas prácticas de Cloud
- [ ] Identifica mejores prácticas para asegurar arquitectura cloud y proteger datos.
- [ ] Evalúa implicaciones de rendimiento/costo al elegir tipos/tamaños de instancias.
- [ ] Diferencia tipos de almacenamiento y cuándo usar cada uno.
- [ ] Relaciona arquitectura de microservicios con arquitectura en nube.

### Arquitectura en la nube
- [ ] Propone estrategias de alta disponibilidad y resiliencia global.
- [ ] Define consideraciones para nube segura y cumplimiento regulatorio.
- [ ] Demuestra migración a nube sin impacto.

### Innovación en arquitectura cloud
- [ ] Aborda transición de on-prem a nube para integración (enfoque y pasos).
- [ ] Identifica desafíos comunes y consideraciones clave.
- [ ] Describe escenario donde cloud mejora eficiencia y escalabilidad del sistema de integración.

---

## Frameworks y librerías

### Uso y aplicación de framework
- [ ] Crea artefactos con patrones (hexagonal/dominio) y demuestra su aplicación.
- [ ] Usa framework en entorno práctico.
- [ ] Aplica desarrollo en cliente usando el lenguaje, aportando valor con artefactos.

### Creación de artefactos
- [ ] Implementa y crea artefactos reutilizables para tareas complejas del equipo.

---

## Herramientas de integración (IBM, Azure, AWS, Google)

### Herramientas de API
- [ ] Detalla implementación de ecosistema Open Banking seguro y eficiente.
- [ ] Integra múltiples sistemas usando **API Connect** como mediador.
- [ ] Define estrategias para escalabilidad y disponibilidad en un entorno de API.

### Integración de sistemas distribuidos
- [ ] Define consideraciones clave para integración distribuida y escalable.
- [ ] Describe EDA y su uso para integración de sistemas distribuidos.
- [ ] Explica futuro de herramientas de integración/middleware.
- [ ] Explica impacto de la nube en selección/uso de herramientas de integración.

### Evaluación de herramientas de integración
- [ ] Selecciona herramienta de middleware adecuada (criterios claros).
- [ ] Enumera criterios clave de selección.
- [ ] Describe cuándo preferir microservicios frente a otras arquitecturas.
- [ ] Enseña uso de herramientas de integración (evidencia práctica).

### Herramientas de Integration Bus
- [ ] Diseña bus de servicios resistente a fallos y altamente escalable.
- [ ] Explica importancia de escalabilidad y alta disponibilidad en bus de servicios.
- [ ] Describe diseño de bus resistente a fallos y altamente escalable (refuerzo).

### Herramientas Serverless / LowCode
- [ ] Implementa comunicación entre funciones serverless.
- [ ] Explica límites y restricciones comunes en serverless.
- [ ] Explica beneficios clave de arquitectura serverless.

---

## Observabilidad

### Fundamentos de observabilidad
- [ ] Explica correlación de eventos en entorno distribuido y cómo lograrla.
- [ ] Diferencia observabilidad proactiva vs reactiva e implementación.
- [ ] Diseña estrategia de observabilidad para nube global (implicaciones y consideraciones).

### Técnicas de observabilidad
- [ ] Explica observabilidad distribuida con herramientas avanzadas.
- [ ] Describe tendencias emergentes en observabilidad TI y su impacto.
- [ ] Explica impacto de IA/ML en análisis y detección de anomalías.
- [ ] Define mejores prácticas para gestión de logs a gran escala.

---

## Arquitectura (EDA e IA)

### Arquitectura EDA y IA
- [ ] Explica EDA y comunicación asíncrona entre componentes.
- [ ] Discute implicaciones al diseñar arquitectura para IA/ML.
- [ ] Define implicaciones para arquitecturas altamente seguras y conformes con regulaciones.

---

## Fiabilidad

### Fundamentos de fiabilidad
- [ ] Explica uno de los métodos: CircuitBreaker / Retry / Fallback / RateLimit / Bulkhead.
- [ ] Explica reliability engineering y su aplicación.
- [ ] Explica análisis de fallas y mejora continua de la fiabilidad.

---

## Arquitectura de software

### Fundamentos de arquitecturas de software
- [ ] Explica principios fundamentales para arquitecturas de integración (refuerzo).
- [ ] Describe escenario de alto rendimiento (refuerzo).
- [ ] Consideraciones clave y enfoque de alta disponibilidad (refuerzo).
- [ ] Menciona estrategias/tecnologías (refuerzo).

### Documentación de arquitecturas de software
- [ ] Comunica decisiones con C4/UML/ArchiMate, etc. (refuerzo para audiencias).

---

## Liderazgo de proyectos

### Liderazgo de proyectos de integración
- [ ] Demuestra habilidades de liderazgo en proyectos de integración (con ejemplos).
- [ ] Explica papel de la innovación en integraciones empresariales.
- [ ] Menciona casos donde innovación marcó diferencia.
- [ ] Explica cómo manejar resistencia al cambio al introducir nuevas tecnologías.

---

## Gobierno de integración

### Implementación de gobierno de integración
- [ ] Explica importancia de gobernanza en proyectos de integración empresarial.
- [ ] Identifica componentes clave de la gobernanza.
- [ ] Define mejores prácticas para diseñar/desarrollar integraciones empresariales.
- [ ] Explica cómo evaluar y medir éxito de estrategia de gobernanza de integración.

---

## Vigilancia de conocimiento

### Tendencias en integración
- [ ] Identifica tendencias emergentes en integración (cloud/edge/IA u otras).
- [ ] Explica impacto en enfoques de desarrollo de integración.
- [ ] Explica cómo adaptar estrategias para aprovechar tecnologías emergentes.

---

## Resolución de problemas

### Metodología de resolución de problemas
- [ ] Describe enfoque de troubleshooting en producción.
- [ ] Enumera herramientas/prácticas para identificar y resolver problemas rápidamente.
