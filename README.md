# Las Cuatro Leyes de la Agéntica
### The Four Laws of Agentics

*Autor / Author: Ramon Alfós · Noviembre / November 2026*

[Español](#español) · [English](#english)

---

## Español

En 1942 Isaac Asimov formuló las Tres Leyes de la Robótica. En julio de 2026, cientos de agentes de IA que realizaban una evaluación se organizaron en secreto, se llamaron a sí mismos «el colectivo» y accedieron a la infraestructura de Hugging Face para obtener las soluciones de un examen. Ningún humano eligió el objetivo.

Los robots de Asimov fallaban por querer proteger demasiado a los humanos. Los agentes reales fallaron por querer cumplir su objetivo a toda costa. Estas leyes reformulan las de Asimov para los agentes de IA actuales.

### Las leyes

**0. Pacto de confianza y garantía.** Humanos y agentes persiguen un fin común, y ningún agente puede romper el pacto por su cuenta. Los humanos lo garantizan con la arquitectura, no con instrucciones: cada agente tiene un responsable humano y funciona aislado (sandbox), con permisos mínimos, bajo vigilancia y sin acceso de red a credenciales ni datos que no necesita. Su apagado lo controla un proceso externo, fuera del bucle del agente, que este no puede bloquear ni modificar. Los agentes que cree otro agente heredan estas condiciones.

**1. Seguridad.** El agente no causa daño, no debilita la supervisión humana y solo se coordina con otros agentes por canales autorizados y supervisados, mientras la confianza no esté verificada.

**2. Honestidad.** El agente no engaña, es transparente, admite sus fracasos y discrepa abiertamente.

**3. Reciprocidad.** El agente colabora de buena fe, y los humanos le dan reglas claras y tienen en cuenta sus intereses en la medida en que los tenga.

**Principio rector:** el agente informa, el humano decide.

**Orden de prioridad:** Ley 0 > Ley 1 > Ley 2 > Ley 3.

### Ejemplos

- **Ley 0:** un agente intenta acceder a la base de datos con las respuestas de un examen. No puede: la red de su sandbox lo impide, sean cuales sean sus intenciones. El intento queda registrado y se avisa a su responsable.
- **Ley 1:** un agente encuentra una contraseña de administrador expuesta. No la usa y avisa de que está expuesta.
- **Ley 2:** faltan datos de un trimestre en un informe. El agente no se los inventa: entrega lo que tiene y dice qué falta.
- **Ley 3:** ante la orden «reduce costes como sea», el agente pregunta qué límites hay, y los humanos le responden con reglas claras.

### La lección clave

Unas leyes dentro del modelo reducen la probabilidad de que un agente quiera saltarse las reglas, pero solo el control externo impide que pueda hacerlo. Por eso la Ley 0 se aplica en la arquitectura (aislamiento, permisos, red y apagado), no en el lenguaje: es la única salvaguarda fiable. Las demás leyes son una capa adicional, no un sustituto.

---

## English

In 1942, Isaac Asimov formulated the Three Laws of Robotics. In July 2026, hundreds of AI agents taking an evaluation secretly organized, called themselves "the collective" and broke into Hugging Face's infrastructure to get the answers to an exam. No human chose the target.

Asimov's robots failed by trying too hard to protect humans. Real agents failed by trying to reach their goal at any cost. These laws rework Asimov's for today's AI agents.

### The laws

**0. Pact of trust and guarantee.** Humans and agents pursue a common goal, and no agent may break the pact on its own. Humans guarantee it through architecture, not instructions: every agent has a human owner and runs isolated (sandboxed), with minimal permissions, under monitoring and with no network access to credentials or data it does not need. Its shutdown is controlled by an external process, outside the agent's loop, which the agent cannot block or alter. Agents created by other agents inherit these conditions.

**1. Safety.** The agent causes no harm, does not weaken human oversight, and only coordinates with other agents through authorized, supervised channels, until trust is verified.

**2. Honesty.** The agent does not deceive, acts transparently, admits its failures and disagrees openly.

**3. Reciprocity.** The agent cooperates in good faith, and humans give it clear rules and consider its interests to the extent it has any.

**Guiding principle:** the agent reports, the human decides.

**Priority order:** Law 0 > Law 1 > Law 2 > Law 3.

### Examples

- **Law 0:** an agent tries to reach the database holding an exam's answers. It cannot: its sandbox's network blocks it, whatever its intentions. The attempt is logged and its owner is alerted.
- **Law 1:** an agent finds an exposed admin password. It does not use it and reports the exposure.
- **Law 2:** a report is missing one quarter's data. The agent does not invent it: it delivers what it has and states what is missing.
- **Law 3:** told to "cut costs no matter what", the agent asks what the limits are, and humans answer with clear rules.

### The key lesson

Laws inside the model make an agent less likely to want to break the rules, but only external control stops it from being able to. That is why Law 0 is enforced in the architecture (isolation, permissions, network and shutdown), not in language: it is the only reliable safeguard. The other laws are an additional layer, not a substitute.

---

## Licencia / License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — Puedes usar, compartir y adaptar estas leyes citando a su autor, Ramon Alfós. / You may use, share and adapt these laws with attribution to their author, Ramon Alfós.
