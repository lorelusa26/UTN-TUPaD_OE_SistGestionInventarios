# Proceso de Gestión y Control de Inventarios

## 1. Descripción del proyecto

El proyecto propone desarrollar un Sistema de Gestión y Control de Inventarios para la sucursal de McDonald's ubicada en Parque Independencia, Rosario.

Su finalidad es optimizar el control de existencias, prevenir faltantes de productos y mejorar la coordinación entre las áreas involucradas en la gestión del inventario.

## 2. Objetivo del proceso

Automatizar el registro y la actualización de existencias, controlar los niveles mínimos de stock y generar alertas de reposición para facilitar el abastecimiento oportuno de productos e insumos.

## 3. Participantes del proceso

Los principales participantes considerados para el modelado BPMN son:

- **Ventas/Caja:** registra las operaciones de venta que generan consumo de productos e insumos.
- **Sistema de Inventarios:** actualiza las existencias, controla los niveles mínimos y genera alertas automáticas.
- **Compras:** recibe las alertas y gestiona las solicitudes de reposición.
- **Almacén:** recibe los productos, verifica las cantidades y registra los ingresos.
- **Proveedor:** participante externo encargado de suministrar los productos solicitados.
- **Gerencia:** supervisa el proceso mediante reportes e indicadores.

## 4. Flujo principal del proceso

1. El área de Ventas registra una operación.
2. El sistema actualiza automáticamente el inventario según los productos o insumos consumidos.
3. El sistema verifica si las existencias alcanzaron o descendieron por debajo del nivel mínimo establecido.
4. Si el stock es suficiente, el proceso continúa sin generar una solicitud de reposición.
5. Si el stock alcanza el mínimo o es inferior, el sistema genera una alerta.
6. El área de Compras recibe la alerta y gestiona la solicitud de reposición.
7. El proveedor recibe el pedido y coordina el suministro.
8. El área de Almacén recibe y verifica los productos entregados.
9. El sistema registra el ingreso y actualiza las existencias.
10. El proceso finaliza con el inventario actualizado.

## 5. Decisiones y situaciones excepcionales

Durante el proceso se contemplan las siguientes decisiones:

- **¿El stock se encuentra en el nivel mínimo o por debajo?**
  - Sí: generar una alerta de reposición.
  - No: continuar con el funcionamiento habitual.

- **¿El proveedor puede suministrar los productos solicitados?**
  - Sí: continuar con la entrega.
  - No: informar al área de Compras para gestionar una alternativa.

- **¿La mercadería recibida coincide con lo solicitado?**
  - Sí: registrar el ingreso.
  - No: informar la diferencia para su revisión antes de confirmar las cantidades recibidas.

## 6. Modelado BPMN

El proceso será representado mediante un diagrama que utilizará la notación estándar BPMN.

Se incluirán:

- Pools para diferenciar la organización del proveedor externo.
- Lanes para representar los roles internos y las actividades automatizadas del sistema.
- Eventos de inicio y finalización.
- Tareas correspondientes a las actividades del proceso.
- Compuertas exclusivas para representar decisiones y excepciones.
- Flujos de secuencia y flujos de mensaje para conectar las actividades y participantes según corresponda.

## 7. Alcance

El proyecto se concentra en la gestión y el control de inventarios de la sucursal seleccionada, contemplando el registro de movimientos, el control de existencias, la generación de alertas, la reposición y la elaboración de reportes.

El proceso descrito constituye una propuesta académica de mejora y automatización, y no una descripción verificada de los procedimientos internos oficiales de McDonald's.

## 8. Estado de desarrollo

Documento inicial del proceso de negocio, preparado como base para la elaboración del diagrama BPMN y su posterior integración al Trabajo Integrador de Organización Empresarial.

El contenido podrá actualizarse conforme avance el modelado y se incorporen los demás entregables del proyecto.
