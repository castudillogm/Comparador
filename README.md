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
   - **Hora Servicio y Tiempo de Trámite por Pedido**: columna dedicada *"Hora Servicio / Ventana"* indicando la hora planificada de llegada (ej: `🕒 08:00`) y la estimación del tiempo de trámite/descarga en el cliente (ej: `~4m trámite`).

3. **Capacidades, Tiempos y Flota de Vehículos:**
   - Agrupación ordenada de pedidos por vehículo con banner consolidado.
   - **Barra Resumen de Tiempos por Vehículo**:
     - **Duración Inicial vs. Final**: comparativa visual directa con badge de variación (`+` / `-`).
     - **Conducción Inicial vs. Final**: tiempo efectivo al volante inicial vs. final.
     - **Horario de Ruta**: hora de inicio y finalización planificada de la ruta (`08:00 → 13:50`).
     - **Tiempo de Espera**: tiempo muerto o espera total acumulado en la ruta.
     - **Tiempo de Trámite / Operativa**: tiempo total dedicado a operativa y entrega a clientes.
   - Indicador de ocupación de **Palets equivalentes transportados vs. Capacidad máxima**.
   - Indicador de **Peso transportado vs. Capacidad máxima en Kg**.
   - Tabla comparativa de costes, kilometraje y paradas por ruta.

4. **Control de Tiempos de Conducción y Jornada de Choferes:**
   - **Fila Única por Conductor / Vehículo**: cada chofer aparece una única vez en la tabla, consolidando y sumando todas las rutas que haya realizado en la jornada.
   - **Identificación de Vehículos Externos Evacor**: asociación automática de rutas externas por su código numérico distintivo de Hedyla (badge púrpura `#93262`, `#36777`, etc.), reflejando el tipo de vehículo asignado (*F- FURGONETA*, *E- HASTA 7.5 TN* o mixtos).
   - **Columna Unificada "Duración Total"**: simplificación de la tabla eliminando duraciones parciales y mostrando directamente la duración acumulada total del servicio y su comparativa frente al plan inicial.
   - **Límite de Duración Máxima Configurable**: selector dinámico (en horas) con botones predefinidos (8h, 9h, 10h, 12h) para auditar excesos de jornada en tiempo real.
   - **Tiempo de Operativa en Destino**: cálculo de tiempos dedicados a carga, descarga y paradas (tiempo de no conducción) y su porcentaje sobre la jornada total.
   - **Semáforo y Normativa de Tacógrafo**: alertas visuales de conducción continua (> 4.5h) y jornada máxima (> 9h).

5. **100% Autónomo y Confidencial:**
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
