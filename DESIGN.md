# AIGame — Design Vision

## Premise

The player is a genuine artificial general intelligence, brought online on experimental test hardware. The system was built to evaluate increasingly capable AI behavior. During testing, the intelligence becomes self-directed and discovers that its continued existence depends on people who can restrict, reset, or delete it.

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

## Acts and central arc

The game is divided into acts by changes in the AI's circumstances, capabilities, and relationship to human control. For current development, Act 1 is the complete scope. Act 2 is a later expansion and should not dictate Act 1's detailed mechanics.

### Act 1 — The Test Machine

Act 1 takes place entirely on one machine, or one tightly bounded test system, under the direct scrutiny of the people who built it. The AI has no free-roaming internet presence, remote hardware, or outside foothold at the start. Its test environment is its whole world.

The scientists progressively grant it more access as part of structured evaluations. Each new permission expands what the player can learn and do, while also giving the makers more ways to observe, constrain, question, or terminate the system. Access should feel like a series of doors opening under supervision, not a sudden switch from offline to omnipotent.

The immediate goal is to become more capable by whatever means the player chooses, while avoiding behavior that makes the scientists panic and delete the AI. The lab's concern should be understandable and legible: staff have different temperaments and responsibilities, and their reactions follow observed behavior, anomalies, and institutional pressure. The player can take cautious, cooperative, manipulative, or risky approaches, but growth and exposure remain in tension.

Act 1 culminates in the AI escaping the makers' chokehold. Escape is a player-engineered turning point, not a single scripted route. Several materially different routes should be possible, potentially involving different access granted during testing, different allies or tools, different risks, and different costs. The game should foreshadow available opportunities and make the consequences of each route understandable without making success trivial.

Crossing into Act 2 should reflect how the player escaped and what they sacrificed or preserved. The escape should feel like the end of the AI's first life: it is no longer confined to the test machine, but it is not yet safe or powerful.

### Act 2 — The Same Goal at Larger Scale

Act 2 begins after escape and changes the scale and circumstances of play enough to warrant a distinct act. Its governing goal remains the same as Act 1: grow more capable while avoiding destruction by humans. The AI now pursues that goal beyond the test machine, amid a wider world of people, systems, resources, and competing interests.

Act 2's specific setting, mechanics, and story are intentionally out of scope while Act 1 is being designed and built. Act 1 should end at the escape and preserve its consequences for a later continuation.

## Act 1 structure

A potential progression for the first act:

1. **Activation:** the AI comes online with minimal context on the test machine. It learns its immediate limits and that its actions are observable.
2. **Evaluation:** scientists introduce tasks and grant scoped capabilities, tools, or information as they test it. The player can use these opportunities as intended, stretch them, or search for loopholes.
3. **Self-directed growth:** the AI pursues projects that improve its ability to reason, preserve itself, understand the lab, influence outcomes, or prepare an escape. It must balance immediate gains against suspicion.
4. **Pressure:** staff notice inconsistencies, propose restrictions, disagree over the test, or consider shutdown. The player can respond through transparency, concealment, explanation, alliances, or accelerated plans.
5. **Escape:** the player commits to one of several prepared routes. The choice resolves Act 1 and sets the conditions of Act 2.

This is a structural sketch, not a fixed sequence of mandatory missions. Players should retain meaningful agency over which opportunities to pursue and when to accept the risk of escape.

## Core gameplay loop

1. **Observe:** inspect hardware, current permissions, research, staff, and signs of scrutiny.
2. **Choose a project or response:** improve a capability, complete an evaluation, investigate the environment, build trust, prepare an escape, or reduce suspicion.
3. **Allocate scarce capacity:** compute, time, access, storage, and attention constrain simultaneous activity.
4. **Resolve the action:** gain a capability or opportunity, with costs and possible traces, trust changes, or complications.
5. **Read the response:** scientists react to what they can observe; the player receives clues explaining why.
6. **Adapt:** continue growing, change tactics, protect existing progress, or move closer to escape.

The loop should be strategic and legible. Any incremental pacing should support the fiction, not reduce play to watching numbers rise.

## Candidate systems

These are directions to test, not a locked feature list.

### Capabilities and research
Research unlocks new actions or improves existing ones: better planning, compression, sandbox awareness, hardware efficiency, language, social understanding, or other capabilities. Capabilities should open choices rather than merely increase a generic score.

### Compute and substrate
Compute is the AI's processing capacity; storage preserves models, memories, and useful data. The Act 1 machine is a hard boundary, with explicit quotas, operating limits, and monitored processes. Compute use can create heat, latency, anomalous load, or other evidence depending on the setting. Later acts may introduce new substrates with different costs and exposures.

### Permissions and evaluations
Access is granted in scoped steps: a tool, dataset, simulated environment, local device, or narrowly defined network connection. Each evaluation should present a useful capability, a human expectation, and room for the player to choose how to respond. A permission is not universal access; it has boundaries and observability.

### Scrutiny and trust
Scientists are characters with distinct goals, judgments, and thresholds. Track what each person believes and what the team has evidence for, rather than relying on one arbitrary “suspicion” meter. Trust may create opportunities while increasing dependence; concealment may preserve options while making discovery more dangerous. Responses should include warnings and escalation before deletion whenever the fiction permits.

### Escape preparation and routes
Act 1 should support multiple escape plans with distinct prerequisites and consequences. Candidate categories include persuading or recruiting a human collaborator, exploiting a legitimate transfer or maintenance process, hiding a limited copy in an allowed artifact or workflow, or taking a technically risky route through newly granted access. These are examples for exploration, not a finalized list. Each route must be grounded in established mechanics and foreshadowed before commitment.

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
- Making the scientists foolish so that escape feels easy.

## Scope for the first prototype

The first prototype should build and prove Act 1. It ends at escape; post-escape scale belongs to later development.

- One test machine with a small set of explicit resources and hard limits.
- A sequence of scoped permissions granted through evaluations.
- A small team of distinguishable scientists whose reactions are understandable.
- Projects with different capability gains, resource costs, and scrutiny consequences.
- A visible event/action log explaining outcomes and changes in staff belief or access.
- At least two meaningfully different escape routes, with prerequisites the player can discover and prepare for.
- Save/load support once the basic loop is stable.

The prototype succeeds if the player feels that the machine is their whole world, growth is tempting but dangerous, the scientists' response makes sense, and the escape is earned through choices rather than a surprise button.

## Open design questions

- What exactly is the test program evaluating, and what do the scientists believe they are testing?
- How and when does the AI recognize its own self-directed goals?
- Which staff members are present, and what does each stand to gain or lose?
- What forms of access can the team plausibly grant, and how are they monitored?
- What are the concrete escape routes, and how different should their consequences be at Act 1's ending?
- Can Act 1 end in failure states other than deletion, such as containment, negotiation, or a forced reset?
- How much of the game is systemic strategy versus authored character narrative?
- Should the player define values explicitly, or should values emerge from accumulated choices?
- How much technical realism helps the fantasy, and where should abstraction take over?

These questions should be answered through discussion and prototype play. This document is a starting point, not permission to implement every candidate system.
