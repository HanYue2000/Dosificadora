# Simulación de Dosificadora Industrial de Botellas en CADe SIMU y PC SIMU

Este repositorio contiene los archivos y la documentación técnica para la simulación interactiva de una **máquina dosificadora de botellas con faja transportadora**. El control lógico y secuencial se realiza mediante programación Ladder en PLC, integrado dinámicamente con una interfaz física interactiva.

---

## 📂 Contenido del Proyecto

* **[dosificadora-cadesimu.cad](dosificadora-cadesimu.cad):** Esquema de lógica de control Ladder para PLC en CADe SIMU. Configura el arranque/paro del sistema, el movimiento de la cinta transportadora, el llenado controlado, la temporización de ciclo de 7 segundos, los actuadores y las alarmas de standby.
* **[dosificadora-pcsimu.sim]:** Interfaz visual interactiva en PC SIMU que representa el proceso real de la faja transportadora, botellas, dosificadores, sensores ópticos de presencia y nivel, y panel de control.
* **[Documentacion.md](Documentacion.md):** Documentación técnica completa. Incluye la explicación detallada de cada línea (Rung) de lógica Ladder, diagrama de flujo del proceso, la configuración de los objetos de planta y un análisis crítico sobre la alineación de las tablas de E/S.
* **[Previos.md](Previos.md):** Guía de saberes previos recomendados sobre electricidad industrial, neumática, control mediante PLC y técnicas de integración CADe/PC SIMU.

---

## 🛠️ Requisitos de Software

1. **CADe SIMU (v3.0 o superior):** Para simular y monitorear la ejecución del diagrama Ladder en el PLC.
2. **PC SIMU:** Para simular la faja transportadora y los sensores en tiempo real.

---

## 🚀 Guía Rápida para Iniciar la Simulación

1. **Alineación de Variables:** Asegúrate de verificar las tablas de E/S descritas en la sección 5 de [Previos.md](Previos.md) para garantizar que CADe SIMU y PC SIMU compartan las mismas direcciones físicas.
2. **Iniciar Simulación en CADe SIMU:** Abre `dosificadora-cadesimu.cad` (clave `4962`) y presiona el botón de **Play** (Simulación).
3. **Iniciar Simulación en PC SIMU:** Abre `dosificadora-pcsimu.sim` (clave `9966`), presiona el botón del monitor de PC (pantalla verde) y luego presiona **Play**.
4. **Operación:** Presiona el botón de marcha en PC SIMU para arrancar la banda transportadora e iniciar el proceso automático de envasado y llenado.
