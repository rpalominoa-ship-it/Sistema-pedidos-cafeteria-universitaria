
# Sistema de Pedidos para Cafetería Universitaria
 ## Descripción del Caso
El Sistema de Pedidos para Cafetería Universitaria es una aplicación diseñada para facilitar y agilizar el proceso de compra de alimentos y bebidas en la cafetería del campus. Permite a estudiantes, docentes y personal administrativo consultar el menú disponible, realizar pedidos y gestionar el proceso de manera eficiente.
## Problemática Identificada
1. Ausencia de seguimiento de pedidos: Los estudiantes no pueden rastrear el estado de su pedido.

2. Comunicación ineficiente: No existe sistema automatizado para informar sobre el estado de los pedidos

3. Falta de visibilidad: Incertidumbre sobre tiempos de espera y estado de preparación

# Objetivos
## Objetivo General
Desarrollar un sistema sencillo de gestión de pedidos que permita seleccionar, procesar y gestionar pedidos del menú de manera eficiente, reduciendo errores manuales y mejorando la experiencia del usuario.

## Objetivos Específicos
- Automatizar el proceso de registro y cálculo de pedidos

- Reducir tiempos de espera y aglomeraciones

- Mejorar la comunicación entre clientes y personal

- Optimizar la gestión del inventario y ventas
  
# Requerimientos del Sistema
### Requerimientos Funcionales
|ID|	Requerimiento	|Descripción|
|--|--------------------|-----------|
|RF-1|	Registro de pedidos|	Permitir registrar nuevos pedidos con al menos un producto del menú|
|RF-2|	Gestión del menú|	Agregar, editar y eliminar productos con nombre, descripción y precio|
|RF-3|	Cálculo automático	|Calcular automáticamente el total del pedido basado en productos seleccionados|
|RF-4	|Consulta de pedidos	|Permitir consultar pedidos registrados filtrados por fecha|
|RF-5	|Validación de datos|	Validar cantidades como números positivos y existencia de productos|

### Requerimientos No Funcionales
|ID|	Requerimiento|	Descripción|
|--|-----------------|-------------|
|RNF-1|	Rendimiento|	Responder a solicitudes en menos de 2 segundos|
|RNF-2|	Usabilidad	|Interfaz intuitiva que permita completar pedido en máximo 3 pasos|
|RNF-3	|Disponibilidad	|Estar disponible 95% del tiempo durante horario universitario (7:00-19:00)|

# Tabla de Pruebas
### Pruebas Unitarias
|ID Prueba|	Requerimiento	|Datos Entrada|	Resultado Esperado|
|---------|-----------------|-------------|-------------------|
|PU-1	|RF-3: Cálculo automático	|Producto: Café ($2.00), Cantidad: 3	|Total: $6.|00
|PU-2|	RF-5: Validación de datos|	Cantidad: -1, Producto Id: 999	|Error: "La cantidad debe ser mayor a 0"|
|PU-3	|RF-1: Registro de pedidos	|Productos: Sándwich, refresco Cantidades: 1,2	|Pedido registrado con ID único|

### Pruebas de Validación
|ID Prueba|	Requerimiento	|Datos Entrada	|Resultado Esperado|
|---------|-----------------|---------------|------------------|
|V-1	|RNF-2: Usabilidad|	Usuario nuevo realiza primer pedido	|Completa en ≤3 minutos sin ayuda|
|V-2|	RF-4: Consulta de pedidos	|Fecha: 2025/07/19|	Lista de 10 pedidos de esa fecha|

# Tipo de Mantenimiento Propuesto

### Mantenimiento Perfectivo:
Este mantenimiento es el más relevante, ya que la mayoría de los cambios propuestos buscan mejorar y ampliar las funcionalidades existentes.
|Componente	|Descripción|	Impacto|
|-----------|-----------|----------|
|Seguimiento en Tiempo Real	|Barra de progreso visual con estados definidos|	Elimina incertidumbre del usuario  |
|Sistema de Notificaciones|	Notificaciones PUSH, SMS e in-app	|Reduce congestión en cafetería|
|Métodos de Pago| Expandidos	Tarjetas, billeteras digitales, saldo estudiantil	|Incrementa conveniencia|
|Modo Nocturno	|Temas visuales dinámicos	|Mejora accesibilidad y UX|

### Mantenimiento Correctivo
Este mantenimiento se enfoca en solucionar defectos en la lógica de negocio del sistema.

Objetivo: Corregir defectos en la lógica de negocio.

Problema Crítico:
Cancelaciones no registradas: Error en gestión de estados de pedidos

Impacto: Pérdida de integridad de datos y flujos incorrectos

# Reflexión sobre Control de Versiones
#### Importancia en el Desarrollo
El control de versiones es fundamental para el mantenimiento eficiente del software. En este proyecto, permite:

#### Beneficios Implementados
- Trazabilidad completa de todos los cambios realizados

- Rollback seguro en caso de implementaciones problemáticas

- Documentación automática del historial de desarrollo

## Lecciones Aprendidas

1. Mensajes descriptivos son esenciales para el mantenimiento a largo plazo

2. Code reviews sistemáticos mejoran la calidad del código

3. Tags semánticos agilizan el proceso de release

4. Git hooks automatizan la verificación de calidad

### Impacto en el Mantenimiento
El uso adecuado de control de versiones reduce significativamente los costos de mantenimiento al:

- Facilitar la identificación de cambios problemáticos

- Permitir desarrollo paralelo de múltiples mejoras

- Automatizar procesos de integración y despliegue

- Mantener documentación siempre actualizada

