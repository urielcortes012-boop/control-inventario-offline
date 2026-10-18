# 📦 D' Artagnan POS - Control de Inventario y Punto de Venta

<div align="center">
  <img src="logo.jpg" alt="D' Artagnan Logo" width="130" style="border-radius: 50%;">
  <h3>Sistema de Punto de Venta y Gestión de Stock Offline</h3>
  <p>Software de escritorio rápido, seguro y sin necesidad de conexión a internet para la administración completa de inventario, ventas y usuarios.</p>

  <p>
    <a href="https://github.com/urielcortes012-boop/control-inventario-offline/releases/latest">
      <img src="https://img.shields.io/badge/Versi%C3%B3n-1.0.0-6366f1?style=for-the-badge" alt="Versión">
    </a>
    <img src="https://img.shields.io/badge/Plataformas-macOS%20%7C%20Windows-22c55e?style=for-the-badge" alt="Plataformas">
    <img src="https://img.shields.io/badge/Modo-100%25%20Offline-f59e0b?style=for-the-badge" alt="Offline">
  </p>
</div>

---

## 📥 Descargas Rápidas (Instaladores Oficiales)

Descarga la versión lista para instalar en tu computadora:

| Sistema Operativo | Instalador | Formato | Enlace Directo |
| :--- | :--- | :--- | :--- |
| **🍎 macOS** | Versión 1.0.0 | `.dmg` | [**Descargar para Mac**](https://github.com/urielcortes012-boop/control-inventario-offline/releases/download/v1.0.0/D.Artagnan.POS-1.0.0.dmg) *(~100 MB)* |
| **🪟 Windows** | Versión 1.0.0 | `.exe` | [**Descargar para Windows**](https://github.com/urielcortes012-boop/control-inventario-offline/releases/download/v1.0.0/D.Artagnan.POS.Setup.1.0.0.exe) *(~82 MB)* |

> 📌 También puedes ver todas las versiones y notas de actualización en la [sección de Releases](https://github.com/urielcortes012-boop/control-inventario-offline/releases).

---

## 🚀 Guía de Instalación

### 🍎 En macOS
1. Descarga el archivo [`D.Artagnan.POS-1.0.0.dmg`](https://github.com/urielcortes012-boop/control-inventario-offline/releases/download/v1.0.0/D.Artagnan.POS-1.0.0.dmg).
2. Abre el archivo `.dmg` con doble clic.
3. Arrastra el icono de **D' Artagnan POS** hacia tu carpeta de **Aplicaciones**.
4. *(Primera ejecución)*: Si macOS te muestra una advertencia de desarrollador no verificado, haz **clic derecho** sobre la aplicación en Aplicaciones y selecciona **"Abrir"**.

### 🪟 En Windows
1. Descarga el archivo [`D.Artagnan.POS.Setup.1.0.0.exe`](https://github.com/urielcortes012-boop/control-inventario-offline/releases/download/v1.0.0/D.Artagnan.POS.Setup.1.0.0.exe).
2. Haz doble clic en el instalador y sigue las instrucciones en pantalla.
3. *(Aviso SmartScreen)*: Si aparece la pantalla azul *"Windows protegió su PC"*, pulsa en **"Más información"** y luego en **"Ejecutar de todas formas"**.
4. Se creará automáticamente un acceso directo en tu Escritorio y Menú Inicio.

---

## ✨ Características Principales

- 🛒 **Punto de Venta Rápido (POS):** Escaneo con código de barras o búsqueda rápida, cobro en efectivo y cálculo instantáneo de cambio.
- 📦 **Control de Inventario:**
  - Agregar nuevos artículos con código, nombre, categoría, stock, precio de compra y precio de venta.
  - Edición en línea de productos existentes.
  - Alertas automáticas de stock bajo.
  - Importación y exportación de inventario con hojas de cálculo **Excel (.xlsx / .csv)**.
- 📊 **Reportes y Finanzas:** Historial detallado de tickets, cálculo de ganancia neta estimada y exportación de reportes a Excel.
- 👥 **Gestión de Usuarios:** Roles de Cajero y Administrador con contraseñas seguras y avatares personalizados.
- 🔌 **100% Offline:** Toda la información se guarda localmente en el equipo sin necesidad de internet ni servidores externos.

---

## 🛠️ Instalación para Desarrolladores

Si deseas clonar el proyecto para modificar o auditar el código:

```bash
# 1. Clonar el repositorio
git clone https://github.com/urielcortes012-boop/control-inventario-offline.git
cd control-inventario-offline

# 2. Instalar dependencias
npm install

# 3. Iniciar en modo desarrollo
npm start

# 4. Compilar instaladores
npm run build:mac   # Genera instalador .dmg para macOS
npm run build:win   # Genera instalador .exe para Windows
```

---

<div align="center">
  <sub>Desarrollado por <b>Uriel Cortés</b> • D' Artagnan POS</sub>
</div>
