# Comparativa ERP-CRM

## 1. Datos
* **Propietario:** SandTrolilol14
* **Empresa:** Caso 21 - Floristería "Flores del Valle"
* **Palabra del día:** COMPAÑERO

## 2. Licencias y modelos
* **Software Libre (FSF):** Se centra en la libertad del usuario (ejecutar, estudiar, modificar y distribuir). Que sea "libre" no significa "gratuito" (free as in freedom, no as in free beer). Un desarrollador puede cobrar por el software o por sus servicios de soporte.
* **Código Abierto (OSI):** Tiene un enfoque más pragmático empresarial. El código fuente debe estar disponible, pero permite combinaciones más flexibles con software comercial bajo sus 10 criterios.
* **Software Propietario:** El código es cerrado, pertenece a una empresa y los usuarios solo compran licencias de uso restrictivas. No se puede modificar ni redistribuir.
* **Edición Community vs Enterprise:** En la práctica, el modelo "Open Core" ofrece una versión *Community* libre (funcionalidad básica, soporte comunitario) y una *Enterprise* de pago (módulos avanzados, soporte oficial del fabricante y alojamiento en la nube).

## 3. Fichas técnicas

### ERP Libre: Odoo Community
* **Licencia:** GNU LGPLv3
* **Versión vigente:** Odoo 19 / 18
* **Lenguaje del servidor:** Python
* **SGBD:** PostgreSQL
* **Modalidad:** Instalación local (On-Premise)
* **Módulos principales:** Ventas, Inventario, Facturación, Fabricación.
* **Fuente:** [Odoo Open Source](https://www.odoo.com/es_ES/page/editions) (Consultado: 24 de septiembre de 2026)

### ERP Propietario: SAP S/4HANA
* **Licencia:** Propietaria (Comercial)
* **Versión vigente:** SAP S/4HANA Cloud 2608
* **Lenguaje del servidor:** ABAP / C++
* **SGBD:** SAP HANA (exclusivo)
* **Modalidad:** Nube o Local
* **Módulos principales:** Finanzas, Cadena de Suministro, RRHH.
* **Fuente:** [SAP S/4HANA](https://www.sap.com/spain/products/erp/s4hana.html) (Consultado: 24 de septiembre de 2026)

### CRM Libre: SuiteCRM
* **Licencia:** AGPLv3
* **Versión vigente:** SuiteCRM 8.x
* **Lenguaje del servidor:** PHP
* **SGBD:** MySQL / MariaDB
* **Modalidad:** Instalación local o nube propia
* **Módulos principales:** Cuentas, Contactos, Campañas, Casos de soporte.
* **Fuente:** [SuiteCRM](https://suitecrm.com/) (Consultado: 24 de septiembre de 2026)

### CRM Propietario: Salesforce
* **Licencia:** Propietaria (SaaS)
* **Versión vigente:** Winter '27
* **Lenguaje del servidor:** Apex
* **SGBD:** Base de datos propietaria (Oracle)
* **Modalidad:** Exclusivamente Nube
* **Módulos principales:** Sales Cloud, Service Cloud, Marketing Cloud.
* **Fuente:** [Salesforce](https://www.salesforce.com/es/) (Consultado: 24 de septiembre de 2026)

## 4. Fe de erratas del tema 2

He localizado los siguientes datos desactualizados en el PDF proporcionado para el Tema 2:

1. **Versión de Odoo:**
   * **Qué dice el tema:** El documento afirma en la página 7 que la versión actual de Odoo es la 14.
   * **Qué es correcto hoy:** Actualmente, la versión vigente de Odoo es la 19.
   * **Fuente:** [Odoo Release Notes](https://www.odoo.com/es_ES/page/release-notes)

2. **Versión de SuiteCRM:**
   * **Qué dice el tema:** El documento afirma en la página 8 que la versión actual de SuiteCRM en GitHub es la 7.14.5.
   * **Qué es correcto hoy:** La versión mayor actual y vigente de SuiteCRM es la rama 8.x.
   * **Fuente:** [SuiteCRM Download Page](https://suitecrm.com/download/)

   ## 5. Matriz de decisión y recomendación

### Justificación de puntuaciones
Para una floristería pequeña (6 empleados) con venta omnicanal y contratos B2B, evaluamos tres opciones: **Odoo Community**, **ERPNext** y **Microsoft Dynamics 365**.
* **Coste total (30%):** Odoo y ERPNext obtienen un 5 al ser gratuitos en licencia, mientras que Dynamics 365 saca un 1 por sus altas cuotas, inasumibles para 6 empleados.
* **Integración Web/TPV (20%):** Odoo destaca (5) porque sus módulos de TPV e eCommerce están nativamente integrados. ERPNext es bueno (4) pero menos intuitivo en tienda, y Dynamics requiere integraciones complejas (3).
* **Inventario (15%) y CRM (10%):** Dynamics 365 es el más potente (5). Odoo y ERPNext cumplen bien (4) para las necesidades de los hoteles y las flores.
* **Soporte/Comunidad (10%):** Odoo tiene la mayor comunidad hispanohablante (5), clave al no pagar soporte oficial.

### Recomendación final
Se recomienda implantar **Odoo Community**. Cubre todos los flujos de la floristería (TPV, Web, inventario y CRM) sin coste de licencias.

**Análisis de riesgos:**
* **Coste total:** Riesgo de subestimar los costes de servidor y configuración.
* **Dependencia del proveedor:** Muy baja (código abierto).
* **Soporte:** Riesgo de depender de foros comunitarios si hay una caída en fechas clave (San Valentín).
* **Migración:** El paso a la versión Enterprise es natural si la empresa crece.