# Catamaran Estudio — Planificador

Herramienta de planificación de actividades para Catamaran Estudio. Desarrollada para organizar la producción, diseño, fotografía, redes sociales, inventario y entregas del estudio.

## Cómo usar

Abre el archivo `index.html` directamente en cualquier navegador, o accede a la versión publicada en:

**[https://tu-usuario.github.io/catamaran-planner/](https://tu-usuario.github.io/catamaran-planner/)**

> Reemplaza `tu-usuario` con tu nombre de usuario de GitHub.

No requiere instalación ni conexión a internet.

---

## Módulos

### Semana
Vista semanal de lunes a domingo. Permite agregar actividades por día con categoría, responsable, hora, fecha límite y notas. Soporta tareas de varios días que se despliegan visualmente a lo largo del rango seleccionado.

### Mes
Calendario mensual para planear actividades con anticipación, incluyendo bloques de producción y fechas de quema con proveedores externos.

### Checklists
Flujos de producción paso a paso para cada tipo de producto. Incluye barra de progreso y se puede resetear al inicio de cada ciclo.

Productos incluidos:
- Latas cerámicas
- Floreros
- Diseño de nuevo producto
- Moldes en yeso
- Fotografía de catálogo

### Inventario
Registro de materiales e insumos con stock actual, mínimo, unidad de medida y notas de proveedor. Indica automáticamente cuando un material está en stock bajo o agotado.

### Entregas
Registro de pedidos por cliente con fecha de entrega, estado y notas. Los pedidos se ordenan por fecha más próxima y muestran los días restantes con alertas visuales.

---

## Categorías de actividades

| Color | Categoría |
|-------|-----------|
| Morado | Producción in-house |
| Naranja | Tercerizado (Bitácora / Angélica) |
| Verde agua | Diseño de productos |
| Coral | Moldes en yeso |
| Rosa | Fotografía |
| Verde | Redes sociales |
| Azul | Ventas / Admin |
| Gris | Actividades externas |

---

## Responsables

- **Martín** — equipo in-house
- **Yo** — equipo in-house
- **Bitácora** — quema de bizcocho y segunda quema de baja temperatura
- **Angélica** — segunda quema de alta temperatura

---

## Notas técnicas

- El planificador funciona completamente en el navegador sin backend ni base de datos.
- Los datos **no se guardan** al cerrar o recargar la página. Cada sesión empieza desde cero.
- Compatible con Chrome, Firefox, Safari y Edge.
- Incluye modo oscuro automático según la preferencia del sistema.
