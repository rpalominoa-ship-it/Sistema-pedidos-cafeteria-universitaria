# Caso 6: Sistema de Pedidos para una Cafetería Universitaria.

## Descripción breve: 
Aplicación sencilla para registrar pedidos de productos del menú.

### Análisis del Problema
 Ausencia de Seguimiento del Pedido:
El sistema actual no proporciona ningún mecanismo para que los estudiantes puedan rastrear el estado de su pedido una vez realizado, generando una completa falta de visibilidad sobre el estado de preparación
#### Tipo de Mantenimiento: Perfectivo.
Impacto directo en el estudiante:
- Incertidumbre por el tiempo de espera.
- Ansiedad por no saber si su pedido está en proceso, listo o perdido.
- Pérdida de tiempo valioso.
#### Impacto directo en el personal:
- Saturación en el mostrador de entrega.
- Estrés por la presión de los clientes esperando.
- Interrupciones constantes por consultas repetitivas.
#### Consecuencias:
- Ineficiencia en gestión de tiempos de preparación.
- Flujo de trabajo interrumpido constantemente.
- Posibles confusiones en secuencia de pedidos.
## Ausencia de Sistema de Navegación:
No existe ningún mecanismo automático para informar a los estudiantes sobre el estado de sus pedidos, forzando que se comunique de forma presencial.
Tipo de Mantenimiento: Perfectivo.
#### Comunicación ineficiente:
- Los estudiantes deben de permanecer físicamente presentes para recibir actualizaciones.
- Falta de confirmaciones automáticas.
- No hay alertas sobre el estado del pedido.
#### Experiencia del Usuario:
- Frustración por falta de información en tiempo real.
- Incertidumbre constante sobre tiempos estimados.
- Sensación de desorganización del servicio.
#### Consecuencias:
- Personal gasta tiempo valioso repitiendo la misma información
- No hay registro histórico de notificaciones o tiempos.
- imposibilidad de notificar retrasos o cambios de pedidos.
## Tipos de Mantenimiento
Es el proceso de modificar un sistema después de que ha sido entregado y puesto en funcionamiento, con el fin de corregir errores, mejorar su rendimiento, adaptarlo a cambios o prevenir fallos futuros. Su objetivo principal es poder garantizar que el software siga siendo útil, eficiente y vigente a lo largo del tiempo.
- Correctivo: Se realiza para corregir errores o fallas detectadas en el
funcionamiento del software.
- Adaptativo: Se modifica el software para adaptarlo a cambios del entorno,
como nuevas leyes, hardware o sistemas operativos.
- Perfectivo: Se mejora el software para optimizar su rendimiento o agregar
nuevas funciones que los usuarios necesitan.
- Preventivo: Se realizan cambios para prevenir futuros problemas, mejorar la
estructura interna y evitar deterioro.
### Costos del Mantenimiento
El mantenimiento de software generalmente es más costoso que el desarrollo inicial.
Se estima que entre el 60% y 80% del costo total de vida del software se destina al mantenimiento.
Factores que aumentan el costo:
- Código mal estructurado o poco documentado.
- Falta de estándares de programación.
- Cambios frecuentes en los requisitos del usuario.
- Uso de tecnologías antiguas o incompatibles.
#### Factores que reducen el costo:
- Buen diseño desde el inicio.
- Documentación clara.
- Programación modular.
- Uso de herramientas de control de versiones.
#### Etapas del Mantenimiento según Sommerville
- Análisis de solicitudes de cambio.
- Comprensión del software.
- Modificación del software.
- Pruebas del cambio.
- Entrega y documentación.
#### Etapas del Mantenimiento según Pressman
- Identificación del problema o necesidad.
- Análisis del problema.
- Estudio del impacto en el sistema.
- Diseño de la modificación.
- Implementación del cambio.
- Pruebas de regresión (verificar si el cambio daño algo aparte).
- Actualización de documentación.
- Distribución de la nueva versión.
 ### Tipos de Mantenimiento Aplicables
Basado en el análisis de las situaciones problemáticas (SP) y las áreas de mejora (AMS) identificadas en el sistema de pedidos, se determinan los siguientes tipos de mantenimiento de software:
|Tipo de Mantenimiento |Descripción General|
|----------------------|-------------------|
|Mantenimiento Perfectivo|Orientado a mejorar la funcionalidad, usabilidad y rendimiento del sistema, incluyendo la adición de nuevas características.|
|Mantenimiento Correctivo|Orientado a la eliminación de errores o defectos detectados en el funcionamiento del sistema después de su liberación.|


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

##### Problema Crítico:
- Cancelaciones no registradas:  
  - Error en gestión de estados de pedidos

- Impacto: 
  - Pérdida de integridad de datos y flujos incorrectos


