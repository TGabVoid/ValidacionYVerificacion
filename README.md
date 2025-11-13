# 📘 Historias de Usuario

Documentación preparada para repositorio Git — clara, estructurada y lista para desarrollo.

---

## 🚖 1. Aplicación de Movilidad Urbana

**Rol:** Pasajero habitual

### **Historia de Usuario**

**Como pasajero**,
quiero ver el costo estimado del viaje antes de solicitar el vehículo,
para decidir si el precio está dentro de mi presupuesto.

### **Criterios de Aceptación**

* La app debe calcular el costo estimado usando distancia y tráfico en tiempo real.
* La estimación debe mostrarse antes de confirmar el viaje.
* Si existen tarifas dinámicas, deben ser indicadas claramente al usuario.
* La variación entre el costo estimado y el costo final no debe superar el porcentaje permitido por la plataforma.

---

## 📦 2. Sistema de Control Logístico para Almacenes

**Rol:** Operador de inventario

### **Historia de Usuario**

**Como operador de inventario**,
quiero escanear códigos QR de productos usando una pistola lectora,
para registrar entradas y salidas en tiempo real sin errores manuales.

### **Criterios de Aceptación**

* El sistema debe registrar automáticamente la entrada o salida al escanear un producto.
* Los movimientos deben actualizar el stock en menos de 2 segundos.
* La interfaz debe mostrar un mensaje de confirmación o error tras cada escaneo.
* Si un ítem llega a stock cero, debe generarse una alerta automática de reposición.
* Debe existir un historial consultable filtrado por fecha, responsable y SKU.
* Debe existir un mecanismo para corregir escaneos erróneos con trazabilidad del cambio.

---

## 📊 3. Sistema de Reportes para Ventas

**Rol:** Gerente de ventas

### **Historia de Usuario**

**Como gerente de ventas**,
quiero generar reportes mensuales automáticos,
para monitorear el rendimiento del equipo sin procesar datos manualmente.

### **Criterios de Aceptación**

* El sistema debe permitir programar la generación del reporte en una fecha específica.
* El reporte debe incluir ventas totales, metas alcanzadas y variación porcentual respecto al mes anterior.


