# Software DeLaCruz - Sistema de Gestión y Trazabilidad de Pecheras

**Software DeLaCruz** es una aplicación web integral ("Full Stack") diseñada para la gestión, control de inventario y trazabilidad del ciclo de vida de pecheras industriales. Permite administrar desde el registro y asignación a plantas, hasta el control de lavados y baja de unidades.

> **Nota:** Actualmente, el proyecto se encuentra en **Modo Demo/Simulación**. La conexión a la base de datos física y la lectura de hardware (Puerto Serial/RFID) están simuladas mediante datos de prueba (Mock Data) para facilitar el despliegue y la visualización de la interfaz.

## 🚀 Características Principales

* **Dashboard Interactivo:** Visualización gráfica de estadísticas de inventario, lavados y distribución por planta.
* **Gestión de Inventario:**
    * Registro de nuevas pecheras (con soporte para lectura de UIDs).
    * Asignación y distribución a diferentes centros de trabajo (Plantas).
    * Baja y eliminación de unidades defectuosas.
* **Ciclo de Lavado:** Módulo para registrar y monitorear los lavados realizados, controlando el desgaste y la vida útil.
* **Administración:** Gestión de usuarios y perfiles de empresas.
* **Reportes:** Generación de informes exportables en Excel y PDF.

## 🛠 Tecnologías Utilizadas

### Frontend (Cliente)
* **React 18+** (con Vite para un desarrollo rápido).
* **Bootstrap 5:** Para el diseño responsivo y componentes de interfaz.
* **React Router:** Gestión de navegación y rutas protegidas.
* **Axios:** Comunicación HTTP con el servidor.
* **Librerías Adicionales:** `react-chartjs-2` (Gráficos), `jspdf` (PDFs), `xlsx` (Excel), `sweetalert2` (Alertas).

### Backend (Servidor API)
* **Node.js & Express:** Servidor REST API robusto.
* **Simulación de Hardware:** Lógica preparada para integración con **SerialPort** (lectores RFID/Códigos), actualmente simulada para demos web.
* **Base de Datos:** Arquitectura preparada para **MySQL** (actualmente usando datos Mock en memoria).

---

## 📦 Instalación y Ejecución Local

Para correr este proyecto en tu computadora, necesitas tener instalado [Node.js](https://nodejs.org/).

### 1. Clonar el repositorio
```bash
git clone [https://github.com/TU_USUARIO/Software-DeLaCruz-main.git](https://github.com/TU_USUARIO/Software-DeLaCruz-main.git)
cd Software-DeLaCruz-main
