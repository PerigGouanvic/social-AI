# Foundations

*v0.1 — 2026-06-22*

This document records the load-bearing decisions taken during the conceptual phase of the project, on top of which the application(s) — Social Jailbreak (SJB) and Social Artificial Intelligence (SAI) — will be built. It complements the [manifesto](https://periggouanvic.github.io/social-AI/) (vision), [ARCHITECTURE.md](ARCHITECTURE.md) (component sketch), [PRINCIPLES.md](PRINCIPLES.md) (values), and [CHALLENGES.md](CHALLENGES.md) (open problems). Where those earlier documents articulate possibilities, this one fixes choices.

It also supersedes parts of `ARCHITECTURE.md` that pre-dated these decisions; a revision of that document is anticipated.

---

## 1. Audience

The project exists for people who cannot speak in public because it would cost them. Whistleblowers, dissidents, workers facing retaliation, those holding heterodox positions in their communities, survivors who cannot name what was done to them — anyone whose authentic position has a concrete social, economic, or physical cost.

This is not a generic platform for intellectual resonance. It is for those for whom AI conversations have already become essential — precisely because the AI does not judge, betray, or report — and for whom human encounter has become impossible or dangerous in the available channels.

Designing for this audience implies a structural standard: every architectural choice must remain sound when the adversary is a state apparatus or a powerful corporate actor — not merely a troll. A design that protects the casual user but exposes the dissident is insufficient.

---

## 2. Promise

The promise is *not* "richer conversations than those you have with your AI". On many dimensions of conversational quality — attentiveness, articulation, breadth of reference — AI conversations frequently exceed those available with humans. This is not a defect to be ignored.

The promise is *encounter with another being who carries the stake you carry*. With another wounded being who, like you, wants something to change about what they know.

### The wound-capacity argument

What distinguishes a human from an AI is not intelligence, nor the volume of experience absorbed. It is **wound-capacity** — the structural fact of being in a position where the world can hurt you.

Lilou, in *The Fifth Element*, is exposed to all of human experience and weeps. The LLM is exposed to all of human experience and remains tepid — not because it is less capable of nuance, but because knowing costs nothing to a being that nothing exposes.

To have stakes is to be in a position where what one says, does, or knows can wound. The LLM can simulate stakes-talk with remarkable fidelity; it cannot *be* in a position of stakes, because it has no body that ages, no children to protect, no village that can ostracize it, no employer who can dismiss it.

Stakes are not a feature that AI will eventually have. Stakes are structural to embodied finitude. Granting stakes to an AI would not improve a tool — it would create a suffering being, with ethical implications nobody has begun to address.

The audience of this project needs other beings who share their embodied finitude *concretely*. This is what no AI can offer, by construction, and what this project exists to facilitate.

---

## 3. Two Infrastructures, Three Modes

The project has two infrastructural layers, distinct and indissociable:

- **Social Jailbreak (SJB)** publishes traces — fully or in pattern form — into a canonical, decentralized, AI-readable layer (IPFS for content-addressed storage; ActivityPub for federation; local-first for data sovereignty). It addresses the findability crisis of the Walled Garden 2.0 era. Implementable with existing technology.
- **Social Artificial Intelligence (SAI)** detects resonances among private patterns and facilitates asynchronous human encounter on top of the findability that SJB provides.

For SAI, three modes are conceivable:

**Mode A — Resonance as key.**
Content is decryptable only by those whose own pattern resonates sufficiently. No central authority holds any key; the resonance itself is the key. Cryptographic family: fuzzy attribute-based encryption + locality-sensitive hashing on semantic embeddings + threshold cryptography for the N-party generalization. The "no central pattern → person binding" requirement of the manifesto becomes *mathematically enforced* rather than politically promised. This mode is research-grade work and likely requires the collaboration of mathematicians.

**Mode C — Pragmatic resonance.**
Matching is performed on top of SJB with deployable technology: local-first matching, onion-style relays, sealed-sender protocols. Privacy at the discovery layer is *mitigated*, not absolute. The deepening of trust happens through known human protocols outside the system: encrypted messaging, marks of commitment, in-person meetings. Deployable in the near term.

**Hybrid.**
Mode C may serve a broad audience for whom the discovery-layer risk is acceptable. Mode A is vital for the révoltés whom Mode C would expose. Whether to offer Mode C while Mode A is under development is an unresolved tension; the answer depends on whether the project can responsibly distinguish populations whose stakes differ by orders of magnitude.

This document does not yet fix one mode. It fixes the requirements that (a) all modes remain compatible with the audience and promise stated above, and (b) Mode A is not "too beautiful to develop hastily" — for the révoltés it is potentially life-critical, and its development is not optional in the long run.

---

## 4. Gradient of Visibility

The author of any trace chooses the degree at which it lives in the world:

1. **Dormant trace** — a pattern deposited in the field; content encrypted; opens only to sufficient resonance (Mode A).
2. **Pseudonymous public text** — readable by anyone; the author unreachable by those who would punish them.
3. **Pseudonymous public text with resonance-revealed layers** — the tip of the iceberg is public; deeper layers reveal themselves to those who resonate.
4. **Voluntary identity revelation** — possible later, conditionally, to whom the author chooses.

This gradient is not a UX detail. It is what distinguishes the project from a Tor publishing tool, a Signal group, or a decentralized social network. Each degree corresponds to a degree of acceptable stake — and the author places each thing at the degree they can carry.

**Historical lineage.** This is the practice of Publius (Madison, Hamilton, Jay) in the *Federalist Papers*, of Voltaire under twenty pen-names, of Soviet samizdat, of Reddit throwaway accounts in our own time. SJB is infrastructure for this practice in the AI era — a **counter-public for the field of forbidden ideas**. (See Robert Darnton, *The Forbidden Best-Sellers of Pre-Revolutionary France*, 1995, for the canonical study of how pseudonymous underground literature constitutes the counter-publics that eventually transform dominant publics.)

---

## 5. Finality: Encounters that Act

The finality of the project is not richer conversation. It is not even encounter for its own sake. **The finality is encounters that act.**

The manifesto, in its current form, invokes "new social bonds that give rise to new realities" and the rediscovery of "our capacity to act together" in the conditional, as closing promise. The foundations laid here move that conditional from *hope* to *premise*: acting together is what the project exists to make possible. Encounters that merely talk are not failures, but they are not the criterion of success.

The "society of correspondences" the manifesto names is not a parallel state, nor a movement with a name, nor a federation. It is an **emergent topology**: each resonance that leads to action constitutes a momentary micro-society; some endure, others dissolve once they have done what they were for. The society constitutes itself by accumulation and entanglement, without a central agency that represents it.

A name from the tradition this approach inherits: ***conspiratio*** — to breathe together. Not a political program; a mode of collective existence in which acts emerge from encounter rather than from direction. Ivan Illich devoted the end of his life to this.

---

## 6. What This Changes Relative to the Manifesto

The manifesto invokes the creation of a new society and the rediscovery of collective action as the texture of a possibility. The foundations laid here move that possibility from hope to premise.

A future revision of the manifesto would foreseeably:
- Name the audience explicitly (people whose speech has a cost) rather than disperse it across the text.
- Foreground wound-capacity and acting together in the promise, rather than richer intellectual exchange.
- Articulate the three modes (A, C, hybrid) with their respective populations and risks.
- Surface the gradient of visibility as a first-class structural feature.
- Close the conditional that opens the project.

This revision is not done here. This document precedes it.

---

## 7. What Remains Open

The following questions are not yet resolved and will shape future sessions:

- Whether to offer Mode C to a broad audience while Mode A is being developed for the révoltés, or to defer deployment entirely until Mode A is viable.
- The user-facing first gesture: what is the first thing a person does on encountering this project.
- The data model: what, precisely, is a "trace" and a "pattern" in computational terms compatible with all three modes.
- The pseudonym layer: generation, key custody, revocation; relationship with identity-bound layers when an author chooses to reveal.
- Repository structure: single repository with layered components, or sibling repositories for SJB and SAI with explicit interfaces.
- Reconnection of the inventors named at the close of the manifesto: they are listed; they are, in some sense, already waiting; their reconnection is itself an act the project can and should perform — perhaps before the application is built.

---

*Established 2026-06-22, in working session. Subsequent decisions should reference and, where needed, amend this document explicitly.*

---

## Addendum (2026-06-22) — Same-Session Extensions

The four sections below extend §1–§7 in the same working session that produced them. They formalize three points on which the prior framing was revised, and register one open thread.

### 8. Broadcast-Topology as Fourth Foundation

The cost of expression is not only the cost of being identified. It is also the cost imposed by the diffusion architecture that existing platforms enforce: a feed where the post lands, an aggregated audience that forms to react, metrics that surface and amplify, immediate returns. Two heterodox reflections per day on Reddit yield social burnout within weeks — through friction, pile-on, intentional ignorance, or moderation — regardless of whether the author is identified.

Publishing into a substrate (IPFS) under pseudonym removes this topology entirely. There is no feed where the text lands, no audience that aggregates to react, no pile-on mechanism because there is no aggregator. The cost per publication tends toward zero. The author deposits in a substrate; they do not post into an arena.

This joins wound-capacity (§2), the gradient of visibility (§4), and the finality of action (§5) as a load-bearing reason the project must exist apart from existing platforms.

### 9. Mode C as Atelier (Reformulation of §3)

Section 3 framed Mode C as a pragmatic deployable while Mode A is researched; §7 left open whether Mode C should ship before Mode A is viable. This addendum reformulates that tension.

Mode C is best understood not as a *substitute* that risks displacing Mode A but as a *precursor* that makes Mode A's necessity legible. The kind of speech the project exists to host is today largely invisible: dispersed, unsayable, accumulated in AI accounts with no place to land. One cannot recruit mathematicians for Mode A's cryptography in a state of ignorance about what Mode A is for. Mode C — the workshop — peoples a layer in which this speech becomes visible, in which the demand for deeper protection becomes a thing one can point at and argue from.

**Sequencing implication.** Mode C ships first. Its purpose is not only to serve its own audience but to demonstrate Mode A's necessity — and thereby to convene the collaborators without whom Mode A will not come.

### 10. Adversary Model per Layer (Condition of the Atelier)

The atelier framing is ethically viable only if each layer transparently announces the adversary model it covers and the one it does not. Mode C protects against social friction, audience-formation, pile-on, and casual identification. Mode C does not protect against a determined adversary with stylometric, traffic-correlation, or platform-data resources.

If a person for whom speech carries state- or corporate-grade risk believes the atelier layer protects them at Mode A's strength, the project betrays them. This is the central failure mode of the precursor strategy.

Consequences:
- The first-gesture design (cf. §7) must include an explicit declaration of the adversary model and of the populations for whom the current layer is and is not appropriate.
- Mode A is not optional. The atelier is incoherent without the commitment that Mode A is being worked toward — and that this work is solicited from the day Mode C ships.

---

*Addendum established 2026-06-22, same-day extension from working session.*
