# 🌌 Orion SaaS — Sistema de Gestión Comercial & POS de Alta Eficiencia

> [cite_start]**Orion** es una plataforma web y ecosistema móvil de vanguardia diseñado para modernizar, automatizar y escalar las operaciones de retail y venta comercial[cite: 3, 15]. [cite_start]Desarrollado originalmente para optimizar la operación de la cadena de tiendas de calzado **Cmoran** [cite: 8, 15][cite_start], Orion evoluciona desde un MVP de Proyecto de Título hacia un software multi-empresa (SaaS) con proyección nacional e internacional[cite: 3, 10].

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.12-blue.svg?logo=python&logoColor=white)](https://python.org)
[![React](https://img.shields.io/badge/React-18-blue.svg?logo=react&logoColor=white)](https://react.dev)

---

## 🚀 El Dolor Operativo vs. La Solución Orion

[cite_start]En el retail tradicional (y bajo sistemas como Bsale), procesos clave como la **Auditoría de Inventarios** y el **Control de Cambios** se ejecutan de manera arcaica: anotando a lápiz y papel para luego transcribir manualmente a hojas de cálculo de Excel[cite: 8, 16].

* [cite_start]**El Problema:** El flujo tradicional de toma de inventario consume hasta **2 días de trabajo continuo**, generando un alto nivel de errores humanos, estrés operativo, duplicación de tareas y descuadraturas ciegas[cite: 16, 17]. El control de cambios se gestiona en cuadernos físicos de forma propensa a fraudes.
* [cite_start]**La Solución Orion:** Digitalización instantánea a través de una interfaz web responsive adaptada a dispositivos móviles[cite: 4, 13, 19]. [cite_start]El personal escanea el calzado directo en bodega usando la cámara del smartphone o lectores bluetooth, reduciendo un proceso crítico de **2 días a solo 2-3 horas**[cite: 16, 19, 20].

### 📊 Comparativa de Eficiencia

| Proceso | Flujo Tradicional (Papel/Excel) | Ecosistema Orion |
| :--- | :--- | :--- |
| **Conteo de Inventario** | [cite_start]2 días (48 horas aproximadas) [cite: 16, 23] | [cite_start]**2 - 3 Horas** [cite: 20, 23] |
| **Registro de Datos** | [cite_start]Manual con lápiz y transcripción posterior [cite: 16, 24] | [cite_start]**Automático (Escaneo de código de barras)** [cite: 19, 25] |
| **Margen de Error** | [cite_start]Alto (Inconsistencias de lectura manual) [cite: 17, 26] | [cite_start]**Mínimo (Validación digital directa)** [cite: 3, 26] |
| **Consolidación** | [cite_start]Tablas de Excel propensas a corrupción [cite: 16, 27] | [cite_start]**Base de Datos Relacional en Tiempo Real** [cite: 6, 27] |
| **Verificación** | [cite_start]Lenta y posterior al cierre del conteo [cite: 18, 28] | [cite_start]**Instantánea (Pre-cuadratura en vivo)** [cite: 20, 28] |

---

## ✨ Características Principales

### 📦 1. Módulo de Auditoría de Inventario Express
* [cite_start]**Modo Conteo Móvil:** Escaneo directo mediante el celular en las sucursales[cite: 4, 36].
* [cite_start]**Pre-cuadratura Automática:** El sistema compara el stock físico real contra el stock teórico reportado por la API de origen (Bsale)[cite: 30, 38].
* [cite_start]**Alertas de Descuadratura:** Panel limpio (UI estilo Linear/Stripe) que expone variaciones exactas de tallas y modelos para aprobación gerencial[cite: 3, 39].

### 💳 2. Punto de Venta (POS) & Facturación Electrónica (SII)
* **Emisión de DTE Directa:** Generación instantánea de boletas y facturas electrónicas integradas con las normativas fiscales vigentes (SII en Chile).
* **Diseño Marca Blanca:** Inyección dinámica del logotipo personalizado de cada empresa o sucursal en el encabezado de los comprobantes y archivos PDF generados.

### 🔄 3. Control Automatizado de Cambios (Anti-Fraude)
* **Digitalización del Cuaderno:** Registro automatizado de productos entrantes, salientes y diferencias de dinero.
* **Validación Rigurosa de Políticas:** Bloqueo automatizado del sistema si un cliente supera el límite de **2 cambios dentro de un periodo de 30 días**.
* **Ticket de Cambio Inteligente:** Generación de tickets estilizados con códigos QR únicos legibles en cualquier sucursal interconectada.

### 🔗 4. Arquitectura de Sincronización (Migración Híbrida)
* [cite_start]Conectividad robusta via API REST para interactuar de forma transparente con el sistema heredado (Bsale), permitiendo operar paralelamente en tiendas piloto sin interrumpir la contabilidad de la empresa madre[cite: 6, 30].

---

## 🛠️ Arquitectura y Stack Tecnológico

Orion se construye sobre una infraestructura moderna, desacoplada y altamente escalable:

* [cite_start]**Frontend:** React + Next.js (Interfaces ultra-rápidas, minimalistas, modo oscuro nativo, estilizado con **Tailwind CSS** [cite: 3, 6]).
* [cite_start]**Backend:** API REST robusta implementada en Python utilizando **Django** (o alternativas de alto rendimiento como FastAPI [cite: 3, 6]).
* [cite_start]**Base de Datos:** PostgreSQL (Modelado relacional estricto optimizado para el control transaccional de múltiples sucursales, productos y stock por tallas/SKU [cite: 6, 13]).
* [cite_start]**Infraestructura Cloud:** Compatible con Supabase (Auth, Base de Datos administrada y Storage [cite: 3]).

---

## 📈 Roadmap / Próximas Fases (Escalabilidad)

* [cite_start][ ] **Fase 1 (Actual):** Ecosistema Core (POS, Inventario Express, Control de Cambios, Multi-sucursal y Migración API)[cite: 4].
* [cite_start][ ] **Fase 2 (Futuro):** Módulo de Machine Learning / IA para predicción de quiebre de stock basado en estacionalidad de ventas, analíticas avanzadas con gráficos interactivos en tiempo real y plataforma de E-commerce unificada[cite: 5].

---

## 📄 Licencia
Este proyecto está bajo la Licencia MIT. Consúltala en el archivo LICENSE para más detalles.
