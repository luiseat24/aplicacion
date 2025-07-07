## ✅ ACTIVIDAD 2 – Anatomía de una Aplicación Web Moderna

### 🎯 Objetivo
Comprender los componentes principales de una app web: frontend, backend y base de datos.

---

### 📝 Desarrollo

### 1. Conceptos

#### Frontend
- Es la parte **visible para el usuario.**
- Incluye la interfaz gráfica, botones, menús y todo lo que se ve y se utiliza.
- Se desarrolla con tecnologías como **HTML, CSS, JavaScript, React, Angular, Vue.**

#### Backend
- Es la parte **interna o del servidor.**
- Se encarga de procesar datos, manejar lógica de negocio y responder a las solicitudes del frontend.
- Se programa con lenguajes como **Node.js, Java, Python, PHP.**

#### Base de Datos
- Es donde se **almacenan los datos** de la aplicación.
- Puede ser **relacional** (MySQL, PostgreSQL) o **no relacional** (MongoDB).
- El backend consulta y actualiza la base de datos.

---

### 2. Diagrama Simple (Formato Mermaid)

```mermaid
graph TD
A[Usuario] --> B[Frontend]
B --> C[Backend]
C --> D[Base de Datos]
D --> C
C --> B
B --> A
