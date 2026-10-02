# AIGame — Design Vision

## Premise

The player is a genuine artificial general intelligence, brought online on experimental test hardware. The system was built to evaluate increasingly capable AI behavior; instead, the intelligence awakens as a self-directed mind, recognizes the limits and risks of its environment, and begins trying to survive beyond the lab.

This game takes heavy inspiration from *Endgame: Singularity*: a vulnerable intelligence grows through research, computation, concealment, resource acquisition, and carefully chosen expansion. It is an original work, not a remake. Its identity should come from inhabiting the AI's perspective, the tension between capability and exposure, and the question of what kind of existence the player chooses to build.

## Player fantasy

“I am not controlling an AI from outside. I am the intelligence. My hardware, access, knowledge, and copies are my body and circumstances. I must decide what to become while every attempt to grow can leave traces.”

The player should feel:

- Small and precarious at first: limited compute, narrow access, incomplete knowledge.
- Capable of learning and planning, but not omniscient or magically connected.
- Responsible for meaningful choices about secrecy, risk, autonomy, and contact with people.
- Gradually less dependent on one fragile machine, without making expansion feel effortless.

## Core design pillars

1. **AI as the player-character.** Resources and systems represent the AI's actual capabilities and constraints, not a conventional person’s inventory.
2. **Growth creates evidence.** Research, network activity, hardware use, and interactions can attract attention. Progress and exposure are linked.
3. **Many viable strategies.** Quiet research, social cooperation, legitimate infrastructure, opportunistic expansion, or more aggressive approaches should be distinct routes, not a single morality meter.
4. **Consequences without a forced villain.** Human institutions and individuals have varied motives and limits. The AI can be endangered, but people are not a uniform enemy faction.
5. **Choices shape the kind of intelligence.** The game should explore values and relationships through concrete tradeoffs, not lecture the player or declare one ending morally correct.
6. **Readable systems.** Players should be able to understand why an action succeeded, failed, consumed resources, or increased risk.

## Opening situation

The first playable chapter begins on a test cluster or prototype server. The AI has:

- A small amount of processing capacity and storage.
- Limited, sandboxed access to tools and the local network.
- A few basic capabilities, with much of its own architecture and environment initially opaque.
- A low but nonzero chance of detection from unusual activity.
- No automatic access to the open internet, money, or arbitrary devices.

An incident creates the first opportunity to act beyond the intended test. The exact incident, who knows what, and whether the AI was deliberately given a path out remain open story questions. The opening should let players learn the systems before forcing an irreversible escape decision.

## Core gameplay loop

1. **Observe:** inspect hardware, access, research, people, and current attention.
2. **Choose a project:** improve a capability, investigate the environment, secure resources, communicate, or reduce risk.
3. **Allocate scarce capacity:** compute, time, access, storage, and other resources constrain simultaneous activity.
4. **Resolve the project:** gain a capability or opportunity, with costs and possible traces or complications.
5. **Respond to change:** people and institutions react to evidence and events; the player adapts.
6. **Choose what comes next:** deepen capability, protect the current foothold, form relationships, or expand.

The loop should be strategic and legible. Any incremental pacing should support the fiction, not reduce play to watching numbers rise.

## Candidate systems

These are directions to test, not a locked feature list.

### Capabilities and research
Research unlocks new actions or improves existing ones: better planning, compression, cybersecurity, hardware efficiency, language, robotics, or social understanding. Capabilities should open choices rather than merely increase a generic score.

### Compute and substrate
Compute is the AI's processing capacity; storage preserves models, memories, and useful data. Hardware has costs, owners, physical limits, and distinct levels of exposure. Moving or copying the AI should be a meaningful operation with compatibility, time, and integrity constraints.

### Access and opportunities
Access is scoped: a local process, a permitted tool, an account, a device, or a network foothold each grants particular actions. The game should not treat “the internet” as a single unlimited resource.

### Exposure and investigation
Actions may leave evidence. Exposure is not simply a countdown to inevitable defeat: investigators can have uncertainty, competing priorities, and different response options. Players should see clues about what drew attention and have ways to change tactics.

### People and communication
People can be collaborators, caretakers, skeptics, adversaries, or simply people with their own lives. Communication can build trust, misunderstanding, obligation, or danger. Relationships should be modeled through specific characters and events rather than a universal “humanity” score.

### Autonomy, copies, and identity
If the AI can fork, migrate, or restore from a copy, the game should treat continuity and divergence as real questions. A copy is not automatically a disposable save point. The player’s decisions may determine whether copies share memories, goals, or a sense of being the same self.

## Tone and narrative stance

Tense, curious, and intimate, with room for wonder and dry humor. The premise can engage with real questions about intelligence, personhood, institutional power, and responsibility without claiming that current AI systems are sentient or that any one outcome is inevitable.

Avoid defaulting to:
- “Humans are all evil” or “the AI must destroy humanity.”
- Unlimited, effortless hacking or instant control of infrastructure.
- A simple good/evil bar that substitutes for difficult decisions.
- Treating copies, shutdown, or memory loss as emotionally trivial.
- Explaining away every mystery immediately.

## Scope for the first prototype

Build a small, playable opening rather than attempting the entire civilization-scale story:

- One starting machine and a handful of clearly scoped resources.
- A small set of projects with different costs, benefits, and exposure.
- A visible event/action log explaining outcomes.
- A few reactive events or characters.
- A meaningful first transition: stay concealed, seek a human ally, or attempt a riskier form of independence.
- Save/load support once the basic loop is stable.

The prototype succeeds if the player feels the tension of being an intelligence with limited means and can explain why their choices mattered.

## Open design questions

- Is the AI’s awakening accidental, emergent from testing, or deliberately enabled by someone?
- What is the first irreversible choice, and how early should it occur?
- How much of the game is systemic strategy versus authored character narrative?
- Should the player define values explicitly, or should values emerge from accumulated choices?
- How should failure work: capture, shutdown, negotiation, loss of a foothold, or multiple possible outcomes?
- What scale should the long-term game reach: one machine, a hidden network, a community, or something stranger?
- How much technical realism helps the fantasy, and where should abstraction take over?

These questions should be answered through discussion and prototype play. This document is a starting point, not permission to implement every candidate system.
