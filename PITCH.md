# PITCH.md

Six lines and a lever. Your words. The last two are scored.

Built: Un agente de atención conectado a herramientas locales y a un servidor MCP.
Does: Consulta la reserva, el estado del vuelo y la política para orientar al pasajero o escalar el caso.
Number: 61,112 antes y 65,843 después, tokens de entrada por corrida, n=5 contactos resueltos.
Guardrail: Escala las reservas grupales a una persona; lo probamos con G2HL9V y escalate_to_human.
Next: Evaluar precisión, tono y coste por contacto antes de operar en producción.
Still broken: No existe un control de tono de entrada; un mensaje abusivo todavía recibe una respuesta calmada y servicial.
Lever: cost
Caveat: Recortar descripciones de herramientas baja el costo de tokens de entrada pero no mide si Claude sigue eligiendo la herramienta correcta: la precisión de enrutamiento queda fuera del número.

## Priya asked

Costs: Solo inferencia del modelo — infraestructura, revisión humana y canales de voz quedan fuera del número.
Wrong: Un delay de 45 minutos que no activa ningún cupón cuesta lo mismo de procesar que una cancelación completa.
Runs it: El equipo de operaciones de contacto digital que administra el chat de Larkspur.
Left out: Los 223,000 contactos que los humanos siguen manejando (42%), el canal de voz completo, y las fallas de tono que aún llegan al cliente.
