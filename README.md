# Simulación de Dosificadoras Industriales en CADe SIMU

Este repositorio contiene proyectos de simulación para **máquinas dosificadoras neumáticas** diseñadas en **CADe SIMU** (con lógica FBD en PLC LOGO!) y preparadas para ser vinculadas con **PC SIMU** para visualización 2D/3D interactiva.

---

## 📂 Contenido del Proyecto

* **[cadesimu-dosificadora.cad](file:///d:/Work/Simu/cadesimu-dosificadora.cad):** Simulación de dosificadora volumétrica/compuerta de **3 cilindros** con control de ciclo por lote (contador a 5 ciclos) y alarma acústica/luminosa.
* **[cadesimu-dosificadora-2.cad](file:///d:/Work/Simu/cadesimu-dosificadora-2.cad):** Simulación avanzada de **4 cilindros** que integra la dosificación temporizada junto con el control de paso físico de los envases (tope de entrada/salida).
* **[Documentacion.md](file:///d:/Work/Simu/Documentacion.md):** Documentación teórica completa sobre qué es una dosificadora, tipos y el flujo detallado de la simulación.

---

## 🛠️ Tecnologías y Software Necesarios

1. **CADe SIMU (v3.0 o superior):** Para simular la lógica de control del PLC Siemens LOGO! y el circuito neumático.
2. **PC SIMU:** Para la interfaz gráfica y visualización del proceso físico (cinta transportadora, botellas, tolvas, etc.).

---

## 🚀 Cómo Ejecutar la Simulación

### 1. Preparación en CADe SIMU
1. Abre **CADe SIMU** e introduce la clave de acceso estándar (`4962`).
2. Abre uno de los archivos `.cad` de este repositorio (`cadesimu-dosificadora.cad` o `cadesimu-dosificadora-2.cad`).
3. Agrega la **Tabla de Entradas/Salidas (I/O)** si aún no está en el lienzo y mapea las variables de los finales de carrera de los cilindros y electroválvulas.
4. Presiona el botón de **Play (Simulación)**.

### 2. Vinculación con PC SIMU
1. Abre **PC SIMU** (clave `9966`).
2. Diseña o abre tu entorno de planta (cilindros, tolva de dosificación, y botellas).
3. Asegúrate de que las direcciones de entradas (`I0.x`) y salidas (`Q0.x`) coincidan con las configuradas en las tablas de CADe SIMU.
4. Presiona el botón de **Play (Simulación)** en PC SIMU.

---

## 📝 Licencia

Este proyecto es de uso libre con fines educativos y de aprendizaje en automatización industrial.
