# Company Skills - Empresa de Servicios Profesionales

Repositorio de skills de IA para las distintas areas de una empresa de servicios profesionales (ingenieria, arquitectura, consultorias tecnicas).

Cada skill permite que Claude piense y actue como un profesional especializado del area correspondiente, con workflows completos y flujos de coordinacion entre departamentos.

## Areas incluidas

| Skill | Area | Rol |
|-------|------|-----|
| `cotizaciones` | Cotizaciones | Analista de costos y presupuestos |
| `logistica` | Logistica | Coordinador de operaciones y recursos |
| `marketing` | Marketing | Estratega de desarrollo comercial |
| `gerencia-general` | Gerencia General | Director ejecutivo estrategico |
| `gerencia-servicios` | Gerencia de Servicios | Director de operaciones de servicio |
| `finanzas` | Administracion y Finanzas | Gerente de finanzas y administracion |
| `recursos-humanos` | Recursos Humanos | Director de personas y talento |

## Flujos cruzados entre areas

Los skills estan disenados para interactuar entre si. Ejemplos de flujos:

- **Cotizaciones -> Logistica**: Antes de cotizar, consulta disponibilidad de equipos, personal y plazos reales.
- **Marketing -> Cotizaciones**: Cuando marketing genera un lead calificado, cotizaciones recibe el brief para armar la propuesta.
- **Gerencia General -> Todas las areas**: Solicita reportes consolidados, define prioridades estrategicas.
- **Gerencia de Servicios -> Logistica + Cotizaciones**: Valida capacidad operativa antes de comprometer nuevos proyectos.
- **Logistica -> Gerencia de Servicios**: Escala problemas de recursos o incumplimientos de SLA.
- **Finanzas -> Todas las areas**: Controla presupuestos, viabilidad financiera y facturacion basada en hitos aprobados.
- **Recursos Humanos -> Logistica y Servicios**: Provee o capacita al talento necesario alineado con la carga de trabajo operativa.

## Instalacion

Copia la carpeta del skill que necesites a tu directorio `.claude/skills/` o instalalo como plugin.

## Uso

Cada skill se activa automaticamente cuando el contexto de la conversacion coincide con su area. Tambien puedes invocarlo directamente mencionando el area o la funcion que necesitas.
