
## ✅ **Resumen del Tema 42 – Sistemas de Bases de Datos Distribuidos (SBDD)**

Los **Sistemas de Bases de Datos Distribuidos (SBDD)** permiten almacenar y gestionar información en múltiples ubicaciones físicas, ofreciendo una visión unificada al usuario. Son fundamentales en aplicaciones que requieren **alta disponibilidad**, **tolerancia a fallos**, **baja latencia** y **escalabilidad horizontal**.

### 1. Concepto y funciones

* Los datos se encuentran distribuidos entre nodos coordinados por SGBD.
* Funciones clave: consultas distribuidas, fragmentación, replicación, control de concurrencia, gestión de fallos.

### 2. Características

* Transparencia de acceso, autonomía local, redundancia, escalabilidad, distribución geográfica.
* Mejora frente a sistemas centralizados en resiliencia, rendimiento y latencia.

### 3. Arquitecturas

* **Cliente-Servidor distribuido**: centraliza lógica en servidores.
* **Peer-to-Peer**: nodos iguales, muy escalable (Cassandra).
* **Federada**: integración de nodos autónomos vía middleware.
* **Blockchain/P2P**: nodos descentralizados sin autoridad central.

### 4. Técnicas de distribución

* **Fragmentación**: horizontal (por filas), vertical (por columnas), mixta.
* **Replicación**: síncrona (consistencia fuerte), asíncrona (alta disponibilidad).
* **Protocolo 2PC**: coordina transacciones distribuidas.
* **CAP**: no se puede garantizar simultáneamente consistencia, disponibilidad y tolerancia a particiones.

### 5. Tecnologías actuales (2025)

| Tecnología     | Modelo     | Rasgos clave                      |
| -------------- | ---------- | --------------------------------- |
| PostgreSQL BDR | Relacional | ACID, replicación bidireccional   |
| MongoDB        | NoSQL      | Sharding, JSON, disponibilidad    |
| Cassandra      | NoSQL      | Escalabilidad horizontal, P2P     |
| CockroachDB    | NewSQL     | Consistencia fuerte distribuida   |
| Google Spanner | NewSQL     | Global, reloj atómico, ACID       |
| BigchainDB     | Blockchain | Descentralización e inmutabilidad |
| OrbitDB/IPFS   | P2P        | Sin servidor central, resistente  |

### 6. Aplicaciones reales

* Comercio electrónico (Amazon): réplica geográfica.
* Sanidad y banca: alta fiabilidad con consistencia estricta.
* Educación: sincronización entre centros y certificación vía blockchain.
* Microservicios: almacenamiento distribuido independiente.
* Blockchain educativo: verificación descentralizada de diplomas.

### 7. Aplicación docente y profesional

**En el aula**: prácticas con PostgreSQL/MongoDB, simulaciones con Docker, introducción a blockchain.
**En el trabajo**: arquitecturas resilientes, desarrollo cloud, DevOps distribuido, trazabilidad segura.
