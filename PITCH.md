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

Costs:
Wrong:
Runs it:
Left out:
