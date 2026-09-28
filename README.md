# GrupaMar • Comparador de Planificaciones (Hedyla vs. Especialista)

Herramienta analítica de auditoría y evaluación del rendimiento de algoritmos de optimización de rutas frente a la intervención humana del especialista de tráfico.

![GrupaMar](grupamar-logo.jpg)

---

## 🚀 Características Principales

1. **Auditoría de Planificaciones:**
   - Comparación instantánea entre el **Plan Inicial (Hedyla)** y el **Plan Final (Especialista)**.
   - Cálculo automático del **Índice de Fidelidad / Eficiencia (%)** del algoritmo.
   - Detección precisa de pedidos mantenidos, reasignados a otros vehículos y rescatados de la lista de no asignados.

2. **Trazabilidad 100% de Pedidos:**
   - Separación estricta entre **Albarán** (`T...`) y **Expedición** (`E...`).
   - Identificación del **Cliente y Destino** real de cada entrega.
   - Desglose logístico real entre **Palets** (paletizado completo) y **Bultos** (paquetería suelta / mixta).

3. **Capacidades y Flota de Vehículos:**
   - Agrupación ordenada de pedidos por vehículo con banner consolidado.
   - Indicador de ocupación de **Palets equivalentes transportados vs. Capacidad máxima**.
   - Indicador de **Peso transportado vs. Capacidad máxima en Kg**.
   - Tabla comparativa de costes, kilometraje y paradas por ruta.

4. **100% Autónomo y Confidencial:**
   - Se ejecuta íntegramente en el navegador web local en JavaScript nativo.
   - **Sin necesidad de APIs externas ni servidores**.
   - Máxima privacidad: ningún dato de clientes, rutas o costes sale de la red local.

---

## 🌐 Cómo usar la aplicación

1. Abre el archivo `index.html` en cualquier navegador web moderno (Chrome, Edge, Firefox, Safari).
2. Sube o arrastra el archivo HTML del **Plan Inicial (Hedyla)**.
3. Sube o arrastra el archivo HTML del **Plan Final (Especialista)**.
4. Pulsa en **"Ejecutar Comparación"**.
5. Obtendrás el informe completo de auditoría, resumen ejecutivo para dirección, métricas clave (KPIs), tabla de utilización de flota y trazabilidad completa de pedidos.

---

## ⚙️ Publicación en GitHub Pages

Para ver este proyecto online en cualquier dispositivo:
1. Ve a la pestaña **Settings** de este repositorio en GitHub.
2. En el menú lateral izquierdo, haz clic en **Pages**.
3. En **Build and deployment > Branch**, selecciona la rama `main` y la carpeta `/(root)`.
4. Pulsa **Save**.
5. En unos segundos estará disponible públicamente en:
   `https://castudillogm.github.io/Comparador/`

---

*Desarrollado según el Manual de Identidad Visual y Libro de Estilo de GrupaMar (Transporte y Logística).*
