# 🍞 Guía de Usuario - Sistema de Gestión Pan de Dios

**Versión:** 1.4  
**Fecha:** Septiembre 2026  
**Desarrollado por:** MoviSoft SURL · Mypyme Cubana  
**Para:** Panadería Pan de Dios

---

## 📖 Índice

1. [Introducción](#introduccion)
2. [Flujo de Trabajo General](#flujo-de-trabajo-general)
3. [Acceso al Sistema](#acceso-al-sistema)
4. [Dashboard General](#dashboard-general)
5. [Almacén de Materias Primas](#almacen-de-materias-primas)
6. [Recetas](#recetas)
7. [Producción](#produccion)
8. [Productos Terminados](#productos-terminados)
9. [Control de Rendimiento](#control-de-rendimiento)
10. [Puntos de Venta](#puntos-de-venta)
11. [Clientes](#clientes)
12. [Mensajeros](#mensajeros)
13. [Pedidos](#pedidos)
14. [Caja del Día](#caja-del-dia)
15. [Reportes Mensuales](#reportes-mensuales)
16. [Notificaciones](#notificaciones)
17. [Flujo Diario Recomendado](#flujo-diario-recomendado)
18. [Preguntas Frecuentes](#preguntas-frecuentes)
19. [Glosario](#glosario)
20. [Soporte Técnico](#soporte-tecnico)

---

## 🎯 Introducción

¡Bienvenido al Sistema de Gestión de Pan de Dios!

Este sistema fue diseñado específicamente para tu panadería, tomando como base el Excel que usabas diariamente. Ahora todo está **digitalizado, automatizado y conectado** para que:

- ✅ No pierdas tiempo haciendo cálculos manuales
- ✅ Detectes problemas de producción al instante
- ✅ Controle el inventario de materias primas y productos terminados
- ✅ Sepas exactamente cuánto ganas cada día
- ✅ Tienes reportes listos para la ONAT
- ✅ Recibas alertas automáticas cuando algo no va bien

### ¿Qué NO es este sistema?

- ❌ No reemplaza tu criterio como panadero experimentado
- ❌ No toma decisiones por ti (solo te da información)
- ❌ No funciona sin internet (por ahora)

### ¿Qué SÍ es este sistema?

- ✅ Tu asistente digital 24/7
- ✅ La memoria de todo lo que pasa en la panadería
- ✅ Tu herramienta para tomar mejores decisiones

---

## 🔄 Flujo de Trabajo General

Antes de usar el sistema, entiende cómo fluye el trabajo en la panadería:
┌─────────────┐ ┌─────────────┐ ┌──────────────┐ ┌─────────────┐
│ MATERIAS │ ──▶ │ PRODUCCIÓN │ ──▶ │ PRODUCTOS │ ──▶ │ PUNTOS DE │
│ PRIMAS │ │ (Horno) │ │ TERMINADOS │ │ VENTA │
│ (Almacén) │ │ │ │ (Almacén) │ │ │
└─────────────┘ └─────────────┘ └──────────────┘ └──────┬──────┘
│
▼
┌─────────────┐
│ CLIENTE │
│ (Venta + │
│ Caja) │
└─────────────┘
**Cada paso tiene su módulo en el sistema:**

| Paso | Módulo | ¿Quién lo usa? |
|------|--------|----------------|
| 1. Comprar harina, levadura, etc. | 📦 Almacén MP | Administrador |
| 2. Definir cómo se hace cada producto | 📖 Recetas | Administrador / Maestro panadero |
| 3. Planificar qué producir hoy | 👨‍🍳 Producción | Administrador |
| 4. Registrar lo que realmente salió del horno | 📈 Control Rendimiento | Panadero / Administrador |
| 5. Recibir productos terminados en almacén | 🥖 Productos Terminados | Administrador |
| 6. Enviar a los puntos de venta | 🥖 Productos Terminados | Administrador |
| 7. Vender al cliente final | 🏪 Puntos de Venta | Cajeros |
| 8. Cuadrar caja del día | 💰 Caja del Día | Administrador |

---

## 🔐 Acceso al Sistema

### Desde computadora

1. Abre tu navegador (Chrome, Firefox, Edge)
2. Ve a la dirección que te dio MoviSoft (ej: `https://demo.movisoft.cu`)
3. Si tiene contraseña, ingrésala
4. Verás el **Dashboard** con el resumen del día

### Recomendaciones

- ✅ Usa **Chrome** para mejor experiencia
- ✅ Guarda la dirección en **Favoritos**
- ✅ No compartas tu contraseña
- ❌ No uses el sistema desde el celular (aún no está optimizado para móviles)

---

## 📊 Dashboard General

**¿Qué es?** La pantalla de inicio. Te da un "resumen ejecutivo" de todo lo que pasa hoy.

**¿Cuándo usarlo?** Al empezar el día y cuando quieras ver el estado general rápidamente.

### Qué encontrarás

| Sección | Qué muestra |
|---------|-------------|
| **Ventas del día** | Total vendido hoy en CUP y comparación con ayer |
| **Masas producidas** | Cuántas masas se han hecho y harina consumida |
| **PT en almacén** | Productos terminados disponibles para distribuir |
| **Merma** | Porcentaje de pérdidas del día |
| **Gráfico de ventas** | Evolución de ventas por punto (últimos 7 días) |
| **Productos top** | Los 3 productos más vendidos |
| **Alertas de stock** | Materias primas que están por acabarse |
| **Rendimiento hoy** | Eficiencia, sobrecumplimiento y merma |

### Tips

- 💡 Haz clic en **"Ver detalle →"** en cualquier sección para ir al módulo completo
- 💡 Los números en **verde** son buenos, en **rojo** requieren atención

---

## 📦 Almacén de Materias Primas

**¿Qué es?** Control de los 7 insumos que compras: harina, levadura, núcleo, sal, aceite, azúcar, manteca.

**¿Quién lo usa?** El administrador cuando recibe mercadería o necesita saber cuánto queda.

### Funciones principales

#### 1. Ver el inventario actual

La tabla muestra:
- **Código** (001-007)
- **Producto** (nombre del insumo)
- **UM** (unidad de medida: Kg)
- **Stock actual** (cuánto tienes)
- **Stock mínimo** (cuándo debes reabastecer)
- **Precio compra** (último precio pagado)
- **Valor total** (stock × precio)
- **Estado** (OK / Bajo / Crítico)

#### 2. Registrar entrada al almacén

**Cuándo usarlo:** Cuando llega un proveedor con mercadería.

**Pasos:**
1. Clic en **"+ Entrada al almacén"**
2. Selecciona el producto (ej: Harina de trigo)
3. Ingresa la cantidad (ej: 500 Kg)
4. Ingresa el precio unitario (ej: $85/Kg)
5. Opcional: número de factura del proveedor
6. Clic en **"Guardar"**

✅ El sistema actualiza automáticamente el stock y el valor total.

#### 3. Enviar a producción

**Cuándo usarlo:** Cuando vas a empezar a producir y necesitas descontar los insumos.

**Pasos:**
1. Clic en **"Enviar a producción"**
2. Selecciona cuántas masas vas a producir
3. El sistema calcula automáticamente cuánto de cada insumo necesitas (según la receta)
4. Confirma para descontar del almacén

#### 4. Inventario físico

**Cuándo usarlo:** Una vez al mes (o cuando sospeches que el stock no coincide con la realidad).

**Pasos:**
1. Clic en **"Inventario físico"**
2. Cuenta físicamente cada insumo
3. Ingresa las cantidades reales
4. El sistema marca las diferencias

---

## 📖 Recetas

**¿Qué es?** El "libro de recetas" digital. Aquí defines cómo se hace cada producto.

**¿Quién lo usa?** El administrador o maestro panadero.

### ¿Por qué es importante?

Sin recetas, el sistema no puede:
- Calcular cuánto insumo necesitas
- Detectar mermas
- Calcular costos reales

### Funciones principales

#### 1. Ver el catálogo de recetas

La tabla muestra todas las recetas con:
- Nombre del producto
- Categoría (Panes, Pizzas, Galletas, etc.)
- Unidades que salen por masa
- Cantidad de insumos
- Costo estimado
- Fecha de última modificación

#### 2. Crear nueva receta

**Cuándo usarlo:** Cuando empiezas a hacer un producto nuevo (ej: empanadas, dulces).

**Pasos:**
1. Clic en **"+ Nueva receta"**
2. Llena los datos:
   - **Nombre del producto** (ej: "Empanada de queso")
   - **Categoría** (ej: "Otros")
   - **Unidades por masa** (ej: 12 empanadas por masa)
   - **Precio de venta** (ej: $150 CUP)
3. Agrega los **ingredientes**:
   - Selecciona el insumo (ej: Harina de trigo)
   - Ingresa la cantidad por masa (ej: 15 Kg)
   - Repite para cada insumo
4. Clic en **"Guardar receta"**

✅ El sistema calcula automáticamente el costo estimado.

#### 3. Editar receta existente

**Cuándo usarlo:** Cuando cambias la proporción de ingredientes (ej: le pones más azúcar al pan).

**Pasos:**
1. Busca la receta en la tabla
2. Clic en el ícono ✏️ (editar)
3. Modifica lo que necesites
4. Clic en **"Guardar"**

⚠️ **Importante:** Si cambias una receta, los cálculos de producción futuros usarán la nueva versión.

#### 4. Duplicar receta

**Cuándo usarlo:** Cuando tienes un producto muy parecido a otro (ej: "Pan suave caña 150g" basado en "Pan suave caña 130g").

**Pasos:**
1. Clic en el ícono 📋 (duplicar)
2. Se crea una copia con el nombre "X (copia)"
3. Edítala para ajustarla

#### 5. Eliminar receta

**Cuándo usarlo:** Cuando dejas de hacer un producto definitivamente.

⚠️ **Cuidado:** Esta acción no se puede deshacer. Si el producto tiene historial de ventas, considera mejor dejarlo pero marcarlo como "inactivo".

---

## 👨‍🍳 Producción

**¿Qué es?** La planificación de lo que se va a producir hoy.

**¿Quién lo usa?** El administrador al inicio del día.

### Funciones principales

#### 1. Crear orden de producción

**Pasos:**
1. Clic en **"+ Nueva orden"**
2. Selecciona el producto (ej: Pan Suave caña 130g)
3. Indica cuántas masas vas a hacer (ej: 15 masas)
4. El sistema calcula: 15 × 12 = **180 unidades esperadas**
5. Asigna el panadero responsable
6. Guarda la orden

✅ La orden aparece en la lista con estado "Programada".

#### 2. Ver el estado de las órdenes

La tabla muestra:
- **Orden** (código único)
- **Hora** programada
- **Producto**
- **Masas** a producir
- **Unidades esperadas**
- **Estado** (Programada / En proceso / Terminada)
- **Responsable**

#### 3. Marcar orden como terminada

Cuando el panadero termina, se registra en el módulo de **Control de Rendimiento** (ver sección siguiente).

---

## 🥖 Productos Terminados

**¿Qué es?** El almacén de los 22 productos listos para vender. Es el "puente" entre Producción y los Puntos de Venta.

**¿Quién lo usa?** El administrador durante todo el día.

### Flujo de trabajo
Producción (horno) ──▶ Almacén PT ──▶ Puntos de Venta
│
├── Panadería
├── Kiosko Manuelita
├── Punto Venta 2
└── Mensajeros
### Funciones principales

#### 1. Ver el inventario de productos terminados

La tabla muestra los 22 productos con:
- **Stock actual** (unidades disponibles)
- **Stock mínimo** (cuándo reabastecer el punto)
- **Entradas hoy** (lo que llegó del horno)
- **Salidas hoy** (lo que se envió a puntos)
- **Precio** de venta
- **Valor total** (stock × precio)
- **Estado** (OK / Bajo / Crítico / Agotado)

**Estados:**
- 🟢 **OK**: Stock por encima del mínimo
- 🟡 **Bajo**: Stock por debajo del mínimo
- 🔴 **Crítico**: Stock por debajo del 50% del mínimo
- ⚫ **Agotado**: Sin stock

#### 2. Recibir productos de producción

**Cuándo usarlo:** Cuando sale una tanda del horno.

**Pasos:**
1. Clic en **"📥 Recibir de producción"**
2. Selecciona el producto (ej: Pan Suave caña 130g)
3. Ingresa la cantidad (ej: 180 unidades)
4. Opcional: número de orden de producción (ej: OP-2026-0847)
5. Selecciona el responsable (panadero)
6. Clic en **"📥 Registrar entrada"**

✅ El stock se actualiza automáticamente y queda registrado en el historial.

#### 3. Distribuir a puntos de venta

**Cuándo usarlo:** Cuando envías productos a la Panadería, Kiosko, Punto 2 o Mensajeros.

**Pasos:**
1. Clic en **"📤 Distribuir a puntos"**
2. Selecciona el producto
3. Selecciona el destino (ej: Kiosko Manuelita)
4. Ingresa la cantidad (ej: 50 unidades)
5. El sistema te muestra el stock disponible
6. Selecciona el responsable
7. Clic en **"📤 Distribuir"**

✅ El stock del almacén PT disminuye y queda registrado el envío.

⚠️ **Validación:** Si intentas enviar más de lo que tienes, el sistema te avisa.

#### 4. Ajuste de inventario

**Cuándo usarlo:** Para correcciones especiales:
- 🗑️ Merma (producto deteriorado)
- 🎁 Donaciones
- 📋 Ajuste por inventario físico
- ⚠️ Corrección de errores

**Pasos:**
1. Clic en **"⚖️ Ajuste de inventario"**
2. Selecciona el producto
3. Selecciona el tipo de ajuste
4. Ingresa la cantidad (negativa para restar, positiva para sumar)
5. Explica el motivo (obligatorio)
6. Clic en **"⚖️ Aplicar ajuste"**

⚠️ **Importante:** Todos los ajustes quedan registrados con el motivo. Úsalo responsablemente.

#### 5. Ver historial de movimientos

Abajo verás:
- **Últimos movimientos** (resumen rápido)
- **Historial completo** con filtros por tipo y fecha

#### 6. Editar stock mínimo

**Cuándo usarlo:** Cuando cambia la demanda de un producto y necesitas ajustar el umbral de alerta.

**Pasos:**
1. Busca el producto en la tabla
2. Clic en el ícono ⚙️
3. Ingresa el nuevo stock mínimo
4. Acepta

#### 7. Exportar inventario

Clic en **"📥 Exportar CSV"** para descargar el inventario actual en formato Excel.

---

## 📈 Control de Rendimiento

**¿Qué es?** El módulo más importante para detectar problemas. Compara lo que **debía salir** vs lo que **realmente salió** del horno.

**¿Quién lo usa?** El panadero al terminar cada tanda, o el administrador al final del día.

### ¿Por qué es crítico?

Porque aquí detectas:
- 🔍 Harina de mala calidad (rinde menos)
- 🔍 Horno descalibrado (quema productos)
- 🔍 Panaderos con bajo rendimiento
- 🔍 Sobrecumplimientos (ganancia extra)

### Funciones principales

#### 1. Registrar producción real

**Cuándo usarlo:** Cada vez que sale una tanda del horno.

**Pasos:**
1. Clic en **"+ Registrar producción real"**
2. Selecciona el producto
3. El sistema calcula automáticamente las **unidades esperadas** según la receta
4. Ingresa las **unidades reales** que salieron
5. El sistema muestra inmediatamente la **desviación**:
   - ✅ **Verde**: dentro del margen aceptable (±3%)
   - 📈 **Azul**: sobrecumplimiento (más de lo esperado)
   - ⚠️ **Rojo**: merma (menos de lo esperado)
6. Selecciona la **causa** (si hay desviación):
   - Harina de baja calidad
   - Levadura vencida
   - Error de medición
   - Problema con horno (quemado)
   - Masa no fermentó bien
   - etc.
7. Selecciona la **acción tomada** con el excedente/deficiencia:
   - Se vendió a precio regular
   - Se vendió con descuento
   - Se donó
   - Se desechó
   - etc.
8. Agrega notas si es necesario
9. Clic en **"Guardar registro"**

✅ El registro queda en el historial y, si la desviación supera los umbrales configurados, se genera una notificación automática.

#### 2. Ver los KPIs del día

- **Eficiencia global**: % de lo producido vs lo esperado
- **Sobrecumplimiento**: unidades extra (ganancia)
- **Merma total**: unidades perdidas (pérdida)
- **Registros**: cuántas producciones se cerraron

#### 3. Analizar desviaciones por producto

El gráfico de barras muestra qué productos tienen más problemas.

#### 4. Ver top causas de desviación

Identifica patrones: si "harina de baja calidad" aparece muchas veces, hay que cambiar de proveedor.

#### 5. Ranking de panaderos

Muestra quién tiene mejor/peor eficiencia. Útil para:
- Reconocer al mejor panadero
- Detectar necesidad de capacitación
- Identificar posibles robos hormiga

#### 6. Exportar datos

Clic en **"📥 Exportar CSV"** para análisis externo en Excel.

---

## 🏪 Puntos de Venta

**¿Qué es?** Vista consolidada de los 4 puntos: Panadería, Kiosko Manuelita, Punto Venta 2 y Mensajeros.

**¿Quién lo usa?** El administrador para ver el desempeño de cada punto.

### Qué verás

- **Tarjetas** con las ventas del día por punto
- **Tabla detallada** con inventario, ventas, merma y cobros (efectivo vs transferencia)

### Tips

- 💡 Compara el desempeño entre puntos
- 💡 Detecta si un punto tiene mucha merma
- 💡 Revisa la proporción efectivo/transferencia

---

## 👥 Clientes

**¿Qué es?** Directorio de todos tus clientes (mayoristas y regulares).

**¿Quién lo usa?** El administrador y los mensajeros.

### Funciones

- **Ver directorio** con nombre, tipo, teléfono, zona, compras del mes
- **Agregar cliente nuevo**
- **Importar desde Excel** (si ya tienes una lista)
- **Exportar lista**

### Tipos de clientes

- 🟣 **Mayorista**: restaurantes, cafeterías, hoteles
- 🔵 **Regular**: clientes frecuentes
- 🟢 **Nuevo**: clientes recientes

---

## 🛵 Mensajeros

**¿Qué es?** Control del equipo de delivery.

**¿Quién lo usa?** El administrador para asignar pedidos y calcular comisiones.

### Qué verás

- **Estado** de cada mensajero (En ruta / Disponible / Descanso)
- **Zona** asignada
- **Pedidos del día**
- **Ventas generadas**
- **Comisión** calculada automáticamente (8% por defecto)
- **Liquidación** del período

---

## 📋 Pedidos

**¿Qué es?** Gestión de pedidos de clientes (especialmente mayoristas y delivery).

**¿Quién lo usa?** El administrador al recibir pedidos por teléfono o WhatsApp.

### Estados de un pedido

- ⚪ **Pendiente**: recién creado
- 🟡 **Preparando**: en producción
- 🔵 **En camino**: con el mensajero
- 🟢 **Entregado**: completado

---

## 💰 Caja del Día

**¿Qué es?** El arqueo y conciliación de todo lo cobrado hoy.

**¿Quién lo usa?** El administrador al cierre del día.

### Qué verás

- **Efectivo** total
- **Transfermóvil** total
- **EnZona** total
- **Total del día**
- **Movimientos** detallados con hora, punto, método y referencia

### Tip importante

Al final del día, compara el total del sistema con el dinero físico + las transferencias recibidas. Deben coincidir.

---

## 📊 Reportes Mensuales

**¿Qué es?** Análisis consolidado del mes con tendencias y comparativas.

**¿Quién lo usa?** El administrador para tomar decisiones estratégicas y preparar reportes para la ONAT.

### Qué encontrarás

- **KPIs del mes**: producción, eficiencia, merma, ingresos
- **Gráficos de tendencia**: eficiencia diaria, merma vs sobrecumplimiento
- **Análisis comparativo**: mes actual vs mes anterior
- **Top productos, panaderos y causas** del mes
- **Proyecciones** para el mes siguiente

### Exportación

- **📥 Exportar PDF**: reporte ejecutivo para mostrar a socios o contadores
- **📊 Exportar Excel**: datos crudos para análisis profundo

---

## 🔔 Notificaciones

**¿Qué es?** Sistema de alertas automáticas cuando algo requiere tu atención.

**¿Quién lo usa?** El administrador (tú).

### Tipos de notificaciones

- 🚨 **Críticas**: merma muy alta, stock crítico
- ⚠️ **Advertencias**: stock bajo, eficiencia bajando
- ℹ️ **Información**: sobrecumplimiento, logros del equipo

### Dónde verlas

- **Campana** en la esquina superior derecha (con badge rojo si hay no leídas)
- **Centro de notificaciones** (menú lateral) con historial completo

### Configurar umbrales

Clic en **"⚙️ Configurar umbrales"** para definir cuándo te alerta el sistema:

| Umbral | Valor por defecto | Qué significa |
|--------|-------------------|---------------|
| Merma por producción | > 5% | Alerta si una producción pierde más del 5% |
| Merma diaria acumulada | > 50 uds | Alerta si en el día se pierden más de 50 unidades |
| Eficiencia global | < 95% | Alerta si la eficiencia del día baja de 95% |

### Preferencias

- 🔊 **Sonido**: activa/desactiva sonido al recibir notificación
- 📧 **Email**: resumen diario por correo (simulado en demo)
- 🔔 **Push**: notificaciones del navegador

---

## 📅 Flujo Diario Recomendado

Para aprovechar al máximo el sistema, sigue este orden cada día:

### 🌅 Mañana (5:00 AM - 7:00 AM)

1. **Abrir el Dashboard** → ver el resumen de ayer
2. **Revisar notificaciones** → atender alertas pendientes
3. **Almacén MP** → verificar stock de insumos
4. **Producción** → crear las órdenes del día
5. **Productos Terminados** → verificar stock disponible

### 🍳 Durante la producción (7:00 AM - 12:00 PM)

6. **Control de Rendimiento** → registrar cada tanda que sale del horno
7. **Productos Terminados** → recibir lo producido
8. **Productos Terminados** → distribuir a los 4 puntos

### 💼 Tarde (12:00 PM - 5:00 PM)

9. **Pedidos** → gestionar pedidos de mayoristas
10. **Mensajeros** → asignar entregas
11. **Clientes** → atender consultas

### 🌙 Cierre (5:00 PM - 7:00 PM)

12. **Puntos de Venta** → revisar ventas del día
13. **Caja del Día** → cuadre de caja
14. **Dashboard** → ver resumen final
15. **Notificaciones** → atender últimas alertas

### 📊 Una vez por semana

16. **Reportes Mensuales** → analizar tendencias
17. **Recetas** → ajustar si es necesario
18. **Almacén MP** → inventario físico

---

## ❓ Preguntas Frecuentes

### P: ¿Puedo usar el sistema sin internet?
**R:** No por ahora. Necesitas conexión. Estamos trabajando en una versión offline.

### P: ¿Se guardan mis datos si cierro el navegador?
**R:** Sí, todo se guarda automáticamente en el navegador (localStorage). Pero si limpias los datos del navegador, se pierden. Por eso es importante exportar reportes periódicamente.

### P: ¿Puedo tener varios usuarios?
**R:** En esta versión, no. Es un sistema mono-usuario. Para multi-usuario necesitamos la versión con backend (consulta a MoviSoft).

### P: ¿Qué pasa si me equivoco al registrar una entrada?
**R:** Usa el módulo de **Ajuste de inventario** en Productos Terminados, o contacta a MoviSoft para correcciones en otros módulos.

### P: ¿Puedo cambiar los precios?
**R:** Sí, en el módulo de **Recetas** puedes editar el precio de venta de cada producto.

### P: ¿Cómo sé si un proveedor me está dando mala harina?
**R:** Revisa el módulo de **Control de Rendimiento**. Si ves que "Harina de baja calidad" aparece muchas veces como causa de merma, es señal de que debes cambiar de proveedor.

### P: ¿Puedo agregar productos nuevos?
**R:** Sí, en **Recetas** puedes crear nuevas recetas para cualquier producto (empanadas, dulces, pasteles, etc.).

### P: ¿Cómo preparo el reporte para la ONAT?
**R:** Ve a **Reportes Mensuales** y haz clic en **"📥 Exportar PDF"**. El reporte incluye todo lo necesario para el libro de ventas de Mypyme.

### P: ¿Qué hago si el sistema está lento?
**R:** Cierra otras pestañas del navegador, o recarga la página con `Ctrl + F5`.

### P: ¿Puedo usar el sistema desde una tablet?
**R:** Sí, pero la experiencia es mejor en computadora. Estamos preparando una versión móvil optimizada.

---

## 📚 Glosario

| Término | Significado |
|---------|-------------|
| **MP** | Materia Prima (harina, levadura, etc.) |
| **PT** | Producto Terminado (pan listo para vender) |
| **Masa** | Porción de masa cruda que se produce de una vez |
| **Merma** | Producto perdido (quemado, caído, deteriorado) |
| **Sobrecumplimiento** | Producción mayor a la esperada (ganancia extra) |
| **Eficiencia** | % de lo producido vs lo esperado (meta: 95%+) |
| **CUP** | Peso Cubano (moneda nacional) |
| **Transfermóvil** | App de transferencia bancaria cubana |
| **EnZona** | Plataforma de pagos cubana |
| **ONAT** | Oficina Nacional de Administración Tributaria |
| **Mypyme** | Micro, pequeña y mediana empresa (régimen legal cubano) |
| **Kiosko** | Punto de venta pequeño (en tu caso: Kiosko Manuelita) |
| **Arqueo** | Conteo físico del dinero en caja |
| **Cuadre** | Verificar que el dinero físico coincide con el sistema |
| **Ticket promedio** | Valor promedio de cada venta |
| **Stock mínimo** | Cantidad mínima que debe haber en almacén |

---

## 🛠️ Soporte Técnico

### ¿Tienes un problema o sugerencia?

**MoviSoft SURL** está aquí para ayudarte.

### Canales de contacto

- 📧 **Email:** soporte@movisoft.cu
- 📱 **WhatsApp:** +53 5XXX-XXXX
- 🌐 **Web:** www.movisoft.cu
- 📍 **Dirección:** [Tu dirección en Cuba]

### Horario de soporte

- Lunes a Viernes: 8:00 AM - 6:00 PM
- Sábados: 9:00 AM - 1:00 PM
- Domingos: Cerrado (urgencias por WhatsApp)

### Antes de contactar soporte

1. ✅ ¿Revisaste la **Guía de Usuario** (este documento)?
2. ✅ ¿Probaste recargar la página con `Ctrl + F5`?
3. ✅ ¿Verificaste tu conexión a internet?
4. ✅ ¿Probaste desde otro navegador?

Si nada funciona, contáctanos con:
- Descripción del problema
- Captura de pantalla (si es posible)
- Navegador que usas
- Hora en que ocurrió

---

## 🎓 Capacitación

MoviSoft ofrece sesiones de capacitación para tu equipo:

- **Básica** (2 horas): Dashboard, Almacén, Producción
- **Intermedia** (3 horas): Productos Terminados, Rendimiento, Puntos de Venta
- **Avanzada** (4 horas): Reportes, Notificaciones, Análisis de datos

Consulta precios y disponibilidad con tu contacto en MoviSoft.

---

## 📝 Registro de Cambios

| Versión | Fecha | Cambios |
|---------|-------|---------|
| 1.0 | Sep 2026 | Versión inicial con módulos básicos |
| 1.1 | Sep 2026 | Agregado módulo de Recetas editables |
| 1.2 | Sep 2026 | Agregado Control de Rendimiento |
| 1.3 | Sep 2026 | Agregados Reportes Mensuales y Notificaciones |
| 1.4 | Sep 2026 | Agregado módulo de Productos Terminados |

---

## 🙏 Agradecimientos

Gracias por confiar en **MoviSoft** para digitalizar tu panadería.

Este sistema fue diseñado con cariño pensando en las necesidades reales de las Mypymes cubanas.

**¡Que el pan nunca falte en tu mesa ni en la de tus clientes!** 🍞

---

**© 2026 MoviSoft SURL · Todos los derechos reservados**  
**Hecho en Cuba 🇨🇺 con ❤️ para Pan de Dios**
