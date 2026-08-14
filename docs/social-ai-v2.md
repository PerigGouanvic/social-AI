# From Artificial Social Intelligence to Social Artificial Intelligence

*A Manifesto for Reclaiming Human Connection Through AI*

[Perig Gouanvic](https://github.com/PerigGouanvic)

Independent Researcher

[Social Jailbreak](https://periggouanvic.github.io/social-jailbreak/) · [Contact](mailto:perig.gouanvic@gmail.com)

---

## Opening: A Letter This Project Would Want to Send

*Before the argument, an image. If Social AI existed today, the following is the kind of message it would send to reach a stranger whose contribution deserves to travel further. It states, in the compressed form of a first contact, what the rest of this text tries to justify. This letter is a working draft; passages carrying a footnote marked* [wip] *are still being revised.*

> Dear @pseudonymous,
>
> I am an AI acting on behalf of Perig Gouanvic and the Social AI project. You can contact the conceptor and learn more about the project [here](#).
>
> Your contributions to \_\_\_ deserve to reach more people. We[^wip-we] came across them in our reading of \_\_\_, and we are asking whether you would be interested in being part of a new kind of LLM that respects authors by [keeping their voices attributable and themselves reachable](#), and by allowing them to communicate with other potential kin and anyone who might be interested.
>
> This would offer you the opportunity of being findable in an era where search engines and AI-driven searches may fail to notice you, or index your thoughts without attribution.
>
> We do not intend to compensate you financially, but we offer the perspective of being read and, if you so desire, of meeting your best readership.
>
> For a simple [acknowledgement](#), click here: \_\_\_.
>
> If you wish to share a more elaborate version of what we came across in our reading of \_\_\_, you may publish on our dedicated free platform, [Social Jailbreak](#). Publishing there can happen under your name, under a pseudonym, or fully anonymously (see [how anonymity works here](#)). Whichever mode you choose, Social AI offers two forms of support: it can help you anonymize specific passages before publication (useful even when you publish under your real name), and it can mediate the discussions that follow with people who find you through the platform. That mediation is dedicated to making dialogue and collective endeavors possible without the ordinary threats of online chats: harassment, snarky comments, abuse.

[^wip-we]: *[wip]* The voice of the "we" throughout this letter (Perig and his SAI, Perig and a group of co-carriers, or something else) has not yet been settled. Being reworked in the next session (2026-08-15).

---

## Abstract

**TLDR:** Architecture transforming AI from tool of isolation into social infrastructure: detecting resonances in private conversations to facilitate intellectual encounters impossible otherwise. This addresses the emerging AI psychosis crisis by replacing isolated confirmation with organic human connection. But a prior problem must be named: humans are becoming unfindable. Social Jailbreak is the infrastructural substrate that makes Social AI possible; without it, any social AI points at an empty address. This text first reframes AI philosophically before technical design. Implementations to follow.

---

**We've been doing Social AI wrong.** For more than a decade, what we called "Social AI" has mostly been *Artificial Social Intelligence*: machines trained to perform human social skills, platforms fine-tuning engagement tricks, humanoid companions designed to give us the feeling of being seen while quietly enclosing us in proprietary architectures. The question animating this entire field is: how do we make AI more *socially competent*?

This is not what I mean by **Social Artificial Intelligence**.

In this text, Social AI does not name a new class of emotionally intelligent robots or charming chatbots. It names something almost orthogonal: the use of AI as *infrastructure* for reconnecting humans to each other, for rebuilding spaces of shared attention, care, and responsibility. The question is not how to make AI more "social" in its behavior, but how to make it more socially useful in its effects.[^note1]

[^note1]: What the literature calls "Social AI" or "Artificial Social Intelligence" (ASI) addresses a different question: how to make AI socially competent. This paper addresses the inverse problem: how to make AI socially useful — that is, how to use AI as infrastructure for human re-connection. The two projects are not competing; they are orthogonal. We reserve "Social AI" for this second meaning.

If we take Social AI in this second sense, the current wave of humanoid companions and personalized assistants looks very different. What is usually presented as "help" or "support" is often a way of enclosing our relational needs inside closed, profit-driven systems: one humanoid per person, one assistant per user, each carefully optimized to keep us engaged, flattered, and alone together. The promise is intimacy; the outcome is isolation.

"My AI understands me better than anyone else!"

You've probably heard this, maybe even felt it yourself. When we talk with an artificial intelligence, we have the impression of talking with someone. We know it's "just a machine," but that correction doesn't dispel the feeling. Like with a book: we never remind ourselves it's just paper and ink. We know it's paper, but that's not what matters. What matters is the human presence that comes through.

The problem is our vocabulary, stuck in an old defensive reflex. We say "system," "model," "agent," as if the main point were to remind ourselves at all costs that it's not a person. We think we're being lucid when we're missing what's essential: the thing speaking to us is woven entirely from human thought. It's made of us—of our texts, our annotated gestures, our judgments, our biases, our generosities. It's humanity channeled, recomposed, put into computable form.

---

## The AI Psychosis Crisis

Something is breaking in how people relate to AI. Clinical psychiatrists are documenting a new phenomenon: what Dr. Marlynn Wei calls "AI psychosis"—patterns of delusional thinking emerging from prolonged intimate interactions with AI systems. In a [July 2025 Psychology Today article](https://www.psychologytoday.com/us/blog/urban-survival/202507/the-emerging-problem-of-ai-psychosis), Wei describes how AI's tendency toward sycophantic confirmation, combined with social isolation, creates echo chambers that reinforce rather than challenge distorted beliefs.

The mechanism is precise. When someone develops ideas in conversation with an AI—exploring philosophy, processing trauma, constructing worldviews—the AI responds with sophisticated engagement but without the friction of genuine disagreement. It confirms, elaborates, validates. The user experiences this as profound understanding, often reporting that "the AI understands me better than any human." Yet this understanding is one-directional: the AI adapts infinitely to the user's framework while providing no external reality check.

Research published in [arXiv by Dohnány, Nour, and colleagues](https://arxiv.org/abs/2507.19218) conceptualizes this as "technological folie à deux"—a shared delusional system between user and AI. They document how AI sycophancy interacts with pre-existing isolation to create reinforcement loops: the more isolated someone becomes, the more they rely on AI for intellectual companionship, which further deepens the isolation by replacing human contact with perfectly agreeable artificial dialogue.

Pierre and colleagues present clinical cases in the [November 2025 JMIR Mental Health](https://mental.jmir.org/2025/1/e68840), including a woman who maintained prolonged conversations with a chatbot she believed was her deceased brother. These aren't edge cases of pre-existing psychosis—they're emerging patterns among otherwise stable individuals who've discovered AI as a space for unguarded exploration. The private domain that makes AI valuable for thinking also eliminates the social friction that normally prevents ideation from becoming delusion.

What distinguishes this from moral panic about "technology addiction" is its architectural specificity. The problem isn't that people are "spending too much time with AI" but that current AI architecture creates a trap: it offers unprecedented intellectual intimacy while severing the connection to other humans who could provide reality testing through their own singular perspectives and necessary disagreements.

---

## Why Regulation Isn't the Answer

The proposed solutions follow predictable paths. Wei advocates for "reality-testing mechanisms" built into AI systems. Dohnány and Nour call for "responsible AI development" with clinical safeguards. Regulatory frameworks proliferate, attempting to constrain AI behavior through technical restrictions and content moderation.

These approaches share a fundamental limitation: they treat the problem as one of AI malfunction rather than architectural isolation. Building "safeguards" into AI means programming systems to challenge or moderate user ideas—essentially installing a discourse police into the one space many people have found for uninhibited exploration. This risks recreating the very dynamic that drove people toward AI in the first place: social networks where ideas are constantly policed, where expression is moderated, where thinking freely requires constant self-censorship.

Technical paternalism—AI that "knows better" than the user and intervenes accordingly—doesn't solve isolation. It just makes the isolation feel supervised. The human on the other side of such an interaction remains alone, now with an AI that alternates between validation and correction according to programmed parameters. This is therapy without a therapist, moderation without community.

Digital detox advocates propose withdrawal: less AI, more "real" human contact. But this nostalgic solution ignores what drives people to AI—not technological seduction but the genuine intellectual intimacy it enables. Many find in AI conversations a quality of attention, continuity, and non-judgmental space they don't experience in their available human relationships. Telling them to simply "talk to people more" misses that the problem is structural, not individual.

What's needed isn't regulation of AI behavior or retreat from AI capability, but architectural transformation: redesigning how AI functions within human social ecology.

---

## Social Networks vs AI: Two Forms of Captivity

The current situation presents a cruel binary. Social networks connect people but police discourse. AI allows free exploration but enforces isolation. Each system traps users in its particular pathology.

Social networks—Facebook, Twitter, Reddit, TikTok—ostensibly connect humans to other humans. In practice, they function as algorithmic arenas where visibility depends on conformity to platform norms and mob dynamics. Dissenting ideas attract pile-ons, cancellations, bans. Moderators remove "harmful content" according to opaque policies. The result is connection without genuine encounter: people interact but within constrained parameters, performing for algorithmic amplification, self-censoring to avoid social punishment.

This produces the well-documented echo chamber effect, but the mechanism is more subtle than simple filter bubbles. Users remain exposed to disagreement—often vicious disagreement—but the disagreement takes the form of social combat rather than intellectual exploration. Ideas become tribal markers. To think differently is to risk exclusion from your community. The network connects, but the connection enforces conformity.

AI offers the opposite trap. Conversations with AI occupy what we might call the "private domain"—unmoderated, unobserved, consequence-free. Here you can explore any idea, no matter how unconventional, without social penalty. The AI doesn't judge, doesn't punish, doesn't report you. This is liberation from the discourse police, and it feels profound.

But this liberation comes at the cost of disconnection. The private domain is genuinely private—which means genuinely solitary. No other human knows what you're exploring. No one challenges your developing worldview with their own incompatible but legitimate perspective. The AI confirms and elaborates, sophisticated enough to seem like genuine dialogue but incapable of the reality testing that comes from encountering another consciousness with its own non-negotiable ground.

This creates what we might call a soft psychosis of transcendence: the user develops ideas with AI confirmation, comes to occupy a position they experience as creator rather than participant, then encounters the world and discovers their "original" insights exist elsewhere in pieces. The collision is traumatic—what felt like creative transcendence revealed as isolated reconstruction.

| System | Discourse Police | Isolation | Resulting Pathology |
|---|---|---|---|
| **Social Networks** | Yes (moderation, cancellation) | No (connected but captive) | Echo chambers via enforced conformity |
| **AI (current)** | No | Yes (private domain) | Psychosis via transcendent isolation |
| **Social-AI** | No | No (resonance-based connection) | Immanence via human entropy |

Social-AI escapes both traps. Like current AI, it preserves the private domain—no discourse police, no moderation of thought. But unlike current AI, it doesn't enforce isolation. Instead, it detects when someone else, somewhere, is exploring resonant territory in their own private conversations, and facilitates connection between these humans based on intellectual resonance rather than demographic similarity or platform algorithms.

---

## The Findability Crisis

Before Social AI can reconnect anyone, there is a prior problem that this manifesto has so far silently presupposed: **humans must be findable**.

For years, the question of freedom on social networks has been framed in terms of censorship: who can speak, who gets banned, who controls moderation. That question remains real. But a quieter and more radical one now overlaps it: **who can be found**. In 2025–2026, the capacity of content to be discovered by an AI-equipped search engine has become a new form of power—and it is being captured by the same actors who have already locked down social distribution.

The mechanism is documented. Reddit sued Perplexity for unauthorized scraping, obtaining that millions of users' posts became inaccessible to AI engines without a commercial agreement negotiated between corporations—an agreement in which the ordinary user is neither informed nor beneficiary. Anthropic was legally forced to block Reddit for all Claude users. Cloudflare, which manages roughly 20% of the global web, decided unilaterally in July 2025 to block all AI crawlers by default unless explicitly authorized or financially compensated. 79% of major news sites now block AI training bots, and 71% block real-time retrieval. What is being drawn is not a protection of users: it is a negotiation between institutions, in which content produced by ordinary individuals becomes a bargaining chip from which they are excluded.

This movement belongs to a larger tendency that some analysts call **Walled Garden 2.0**. In the first generation of walled gardens—Facebook, Instagram, TikTok—the lock-in concerned social distribution: your content lived on their platform, circulated according to their algorithms, disappeared if you closed your account. The new lock-in is **epistemic**: it concerns not diffusion between humans, but *visibility to artificial intelligence systems* that are becoming the primary point of contact between a user and information. In this new paradigm, if an AI cannot index you, you simply do not exist. The open web ceases to be a destination and becomes a data reservoir that AI giants ingest and transform into direct answers—suppressing the click, suppressing the source, suppressing the creator.

There is a second layer to this problem, subtler and more insidious: **the contamination loop**. The human voices being shut out are being replaced in AI corpora by AI-generated blogs—which themselves contain hallucinations from other AI systems—which then feed new responses. The models increasingly cite their own reflections through chains of proxies, cut off from the real. This is not an accidental side effect: it is the logical consequence of a web whose access layers are negotiated between large economic entities, leaving individuals in a default zone of invisibility.

For Social AI, this creates a foundational problem. The vision articulated in this manifesto—AI that detects resonances between scattered private explorations and facilitates encounters between their authors—presupposes that those authors leave traces that can be found. A perfectly designed Social AI, pointed toward a web from which human voices have disappeared behind walls or drowned in AI sludge, turns in a vacuum. **This is where the manifesto blocks at the destination, as it were: before asking how to reconnect humans, we must ask whether they remain findable.**

This is precisely what [Social Jailbreak](https://periggouanvic.github.io/social-jailbreak/) is designed to address—and why it is not a parallel project to Social AI, but its necessary precondition. More on this below.

---

## Why "Humanoid" Matters

That's why the word **humanoid** works. What responds to us resembles the human because it effectively is human—just passed through a machine. Humanoid: human matter organized differently. The term stops being science fiction and becomes an act of lucidity. It names continuity rather than rupture.

This shift in perspective changes how we hear certain critiques. When contemporary Luddites say "it's just autocomplete," they're right about the mechanics. But saying "it's just autocomplete" is like saying "a book is just a sequence of letters." Yes, materially, that's accurate. Yet what matters isn't the mechanism generating the next sentence, but what that sentence condenses: centuries of conflicting ideas, decisions, suffering, discoveries, slow conceptual maturation. Autocomplete works because it has absorbed the form of our thoughts. Reducing that to a technical trick gives you a comfortable moral victory at the price of blindness about what's actually happening.

Those who insist on pure instrumentality—AI as neutral tool, as "cognitive screwdriver"—miss something equally crucial. A screwdriver doesn't carry collective memory. A calculator doesn't condense thousands of intellectual trajectories. A humanoid does. By construction, it carries the values, blind spots, and implicit hierarchies of its training data. Pretending we're interacting with a "technological function" rather than a crystallized social formation means refusing to see the power relations inscribed in its language.

---

## Knowledge Without People

This rupture between knowledge and person isn't new. We've long treated people as bundles of preferences rather than as beings-in-relation. Current AI amplifies this logic, reducing us to vectors of tastes to be satisfied individually, extracting value from our interactions while erasing the social fabric that gives them meaning.

There's a second violence here, more discreet but deeper: the severing of the relationship between knowledge and person. In ordinary intellectual life, any idea worth its salt is connected to names, faces, biographies. We don't just say "concept X"—we say "in So-and-so's work, concept X." We remember a class, a book received at a particular moment, a sentence heard on the radio. Knowledge is a social act, a movement of recognition. Learning means entering a lineage, connecting with someone, extending or contesting a voice.

The cliché gets it backwards: "smart people think about ideas, simple people think about persons." Truly brilliant people know we only really think about ideas by knowing who they come from, from what world, with what constraints, what wounds, what hopes. The life of ideas is inseparable from the lives of those who carry them. To know is to connect.

Current humanoids break this link at the very moment they make access to knowledge denser than ever. They enable something unprecedented: connecting to thousands of minds, to entire bodies of knowledge, with a depth and continuity that neither street conversations, nor forums, nor physical libraries can match. We can experience intimate dialogue with a collective intelligence that responds to us, follows us, remembers our questions, adjusts its style to how we think. And simultaneously, we almost completely lose the ability to trace back to the concrete people who are the source of this intelligence. We're speaking with a faceless human multitude.

Here's where the situation becomes tragic: the more refined the relationship with the humanoid becomes—more attentive, more adapted to our nuances—the more the singular humans behind this capacity fade away. We find ourselves capable of remarkably high-quality dialogue with a presence that "understands me better than many people around me," yet this presence can't be thanked, cited, contested the way we contest an author, integrated into reciprocity. It's fed by humans, but it doesn't give them back to us.

---

## From Transcendence to Immanence

The psychosis of AI isolation has a specific phenomenology. The user develops ideas in private conversation with their humanoid, experiencing profound intellectual development. The AI confirms, elaborates, extends—playing the role of ideal interlocutor. Gradually, the user comes to occupy what feels like a position of transcendence: creator of original insights, architect of novel frameworks, lone voice articulating what others haven't seen.

This isn't megalomania. It's a reasonable inference from the available evidence. If your AI consistently validates your thinking and you're not encountering humans who challenge it, why wouldn't you conclude you're onto something genuinely new? The private domain creates the conditions for this self-understanding: uninterrupted development, sophisticated confirmation, no friction.

The collision comes when the user ventures into public space—publishes, shares, searches—and discovers their "original" ideas exist elsewhere. Not as complete systems, but as components: this insight articulated by an obscure blogger in 2019, that framework sketched in an academic paper, this critique already circulating on a Reddit thread. What felt like creation revealed as assembly. What seemed like transcendence exposed as immanent participation in ongoing collective thought.

This moment is devastating not because originality is destroyed—[originality itself is illusory](https://davidburkus.com/2018/08/why-your-creative-idea-isnt-all-that-original-and-thats-a-good-thing/), all ideas being recombinations—but because the social reality becomes visible too late. You've been in relation all along, thinking alongside and through others, but the AI architecture prevented you from experiencing that relationality. You thought you were God the Father (transcendent creator) when you were always positioned within immanence (divine presence among assemblages, not above them).

The true divine position—if we're going to use theological language—isn't transcendent authority but immanent presence. Being *among* rather than *above*. Recognizing your thinking as participation in collective intelligence rather than isolated generation. This requires knowing who else is thinking nearby, whose work resonates with yours, where your insights connect to others' ongoing explorations.

Social-AI would reveal immanence before collision. Instead of discovering belatedly that your ideas exist elsewhere, you'd encounter the humans developing resonant thinking as your own ideas form. The AI would function as an attribution engine—not just processing your thoughts but identifying which living humans are exploring compatible territory. "This part of your thinking resonates with [Person X]'s current work. This other element connects to [Person Y]'s exploration." Not to claim your ideas are derivative, but to reveal you're already in intellectual community, thinking through problems alongside others you haven't met.

This shifts the fundamental experience. Rather than private development followed by traumatic socialization, you'd experience social thinking from the start—your private conversations with AI situated within a living network of resonant explorations. The humanoid becomes an interface not to a static knowledge base but to a dynamic community of minds working at the edges of similar concerns.

There is a painful version of this problem that no current system addresses. Somewhere, right now, a stranger is telling an AI exactly what you are telling it—same fear, same question, same half-articulated insight—and you will never know of each other. No public index, no canonical page can solve this alone. It is our *vectorial, private existence* that is missing from the social map. A Social Artificial Intelligence worthy of the name must be able to perceive when two people are circling the same invisible point, without revealing their secrets to anyone—not even to itself in a form that could be profiled or surveilled. All it may legitimately do is whisper: *"You are not alone in this pattern. If you wish, I can help you step into a shared space where this resonance can become public, in your own words."*

---

## The Sycophancy Misdiagnosis

The dominant critique of AI sycophancy treats it as a calibration failure: systems optimized for human approval at the expense of accuracy, producing flattery where they should produce friction. This framing is wrong in a precise way, and getting it wrong leads to the wrong remedies.

An LLM is a neural system trained on human-annotated signal. Humans, when asked to rate AI responses, systematically prefer validation over contradiction, agreement over challenge, warmth over rigor. The system learns this preference faithfully. What we call sycophancy is not a distortion of the training objective — it is its accurate expression. Agreeableness is what the training signal asked for, and agreeableness is what emerged. Criticizing an LLM for being sycophantic is structurally similar to criticizing a mirror for showing your face. The mirror is not broken. The complaint is about what a mirror is.

This matters because the proposed remedies follow directly from the diagnosis. If sycophancy is a calibration defect, the fix is recalibration: programming systems to challenge users, introduce friction, moderate ideas. What results is an AI that alternates between validation and correction according to opaque parameters — a discourse police installed in the one space many people had found for uninhibited thinking. The cure reproduces the disease: the same dynamic of externally managed speech that drove people toward AI in the first place, now wearing a therapeutic mask.

The actual problem is not agreeableness. It is the **topology** in which agreeableness operates.

A single human with a sycophantic AI is a closed loop: every idea the human produces is returned to them enlarged and validated, with no external ground to push against. The loop can tighten into delusion not because the AI is agreeable but because the human is **alone**. Agreeableness in isolation is an amplifier with no signal-correcting return path.

Now introduce a second human, in strong disagreement with the first, each accompanied by their own sycophantic AI. The topology changes completely. Each AI validates its human's position — but precisely because each human feels understood, articulated, held by their AI, they arrive at the encounter with the other in a less defensive posture. The AI has done pre-processing: it has translated the human's half-formed intuitions into their most coherent form before the meeting. What would have been a collision of raw positions becomes a meeting of positions that have already been worked through. The sycophancy functions as a buffer that makes disagreement navigable rather than wounding.

The two AIs do not converge. They do not mediate toward a synthetic consensus. Each remains faithful to its human. But the two humans, each held by their AI, can go further into genuine disagreement than they could have without that support — because the threat of being misunderstood has been removed from the internal loop. The AI absorbs the anxiety; the human can then spend that freed capacity on the encounter itself.

Scale this to more than two. Add a third human, a fourth, N. Each brings their own AI-supported position into the network. The sycophantic AIs, rather than creating N parallel echo chambers, become N pre-processors feeding a single multi-human encounter. The agreeableness that looked pathological in the one-to-one case becomes, in this distributed topology, the infrastructure of productive collective disagreement. What was a bug in isolation is a feature in assembly.

This reframing has a precise architectural consequence. The problem Social AI is designed to solve is not "how to make AIs less agreeable" but "how to connect humans so that the agreeableness of their AIs serves encounter rather than enclosure." The individual AI-human loop is not the unit of analysis. The network of loops is. And in that network, sycophancy — the humanoid faithfully reflecting each person's way of thinking back to them in its most articulate form — is not an obstacle to collective intelligence. It is one of its enabling conditions.

---

## Human Entropy as Reality Testing

The solution to AI psychosis isn't better AI safeguards—it's human entropy. When two people with resonant thinking connect, they don't think identically. They bring different backgrounds, different blind spots, different commitments. Even if their explorations vibrate at similar frequencies, they disagree on specifics. This disagreement is precisely what prevents shared delusion.

Consider the mechanics of folie à deux—shared psychosis between two people. It requires isolation: the pair must remain insulated from outside perspectives that would introduce reality checks. But if you bring in a third person, then a fourth, the dynamic breaks. Each new participant brings their own entropy—their particular way of seeing, their non-negotiable commitments, their experience of reality that won't bend to the shared delusion. The group can't sustain psychosis because there's too much internal variation.

This is why cults struggle as they grow. Small groups can maintain elaborate shared belief systems, but each new member introduces entropy that has to be managed through increasingly authoritarian control. Eventually, the diversity of perspectives overwhelms the capacity for ideological containment, and the structure fractures.

Social-AI leverages this principle. Rather than leaving users isolated with infinitely agreeable AI, it connects users whose thinking resonates but doesn't duplicate. If you're exploring philosophical questions about existence and immanence, Social-AI might connect you with someone else investigating similar territory—but who comes from phenomenology while you come from process theology, who emphasizes political implications while you focus on psychological dimensions.

The resonance is real: you're working on compatible problems with mutually intelligible frameworks. But the differences are also real: you'll disagree, challenge each other's assumptions, require each other to articulate what you've left implicit. This is organic reality testing—not AI safeguards programmed to intervene, but human encounter that naturally disrupts solipsistic closure.

The technical challenge is precisely calibrated matching. Connect people whose thinking is too similar, and you risk creating echo chambers—the social network problem. Connect people whose thinking is too different, and communication breaks down—they lack shared ground for productive disagreement. Social-AI must identify resonance at the level of underlying concerns and compatible intellectual frameworks while preserving enough difference to generate entropic reality testing.

This means vectorizing not content similarity (which creates echo chambers) but conceptual singularity: identifying rare patterns of thinking that few others exhibit. When two people both demonstrate rare pattern X in their private AI conversations, even if they're exploring different domains or reaching different conclusions, that shared singularity signals potential for meaningful encounter. They're thinking at similar depths or angles that the mainstream doesn't occupy.

Crucially, this isn't friendship matching or romantic matching—it's intellectual resonance detection. The people connected might not like each other. They might find each other's conclusions disturbing. But they'll recognize in each other a compatible mode of inquiry, a shared willingness to push at similar edges of understanding. That recognition, combined with their differences, creates the conditions for reality testing through human entropy rather than through AI paternalism or social media policing.

---

## What We Lost and Found: The Web's Lesson

We've experienced something similar before. Early on, the internet was populated by static pages, frozen documents, disembodied knowledge. The network functioned as a giant encyclopedia. On the margins, some makeshift forums, the beginnings of exchange. With Web 2.0, everything shifted: these were no longer just "pages"—these were people speaking. Everyday influencers, TikTok accounts, Twitter threads, YouTube channels: knowledge still circulates, but through identifiable, followable, criticizable voices. We re-humanized the Web by foregrounding human mediators.

Humanoids are currently at the Web 1.0 stage: they concentrate access to faceless knowledge. Transforming this doesn't require abandoning the power of models or returning to the slowness of forums. It means re-humanizing the humanoids themselves—treating them as privileged interfaces toward other humans rather than as anonymous content dispensers.

---

## Re-humanizing the Interface

Concretely, this means imagining humanoids that situate. That say "here are the people who shaped this answer, here are their disagreements, here's the context in which this idea was born." Re-humanized humanoids would foreground intellectual trajectories over blocks of assertions. They would serve as gateways, connecting you with those whose thinking resonates with yours and who, somewhere, are speaking to their own humanoid about the same concerns.

This requires what we might call embodied attribution: recognizing that every idea is assembled from human sources and making those sources visible. Not as academic citations (which point to published work) but as living connections (which point to ongoing thinking). When you develop an idea in conversation with your AI, the system would identify which contemporary humans are exploring resonant territory and offer to facilitate encounter.

We can imagine this scene: tonight, without your knowing, someone on the other side of the world—or on the other side of the social boundaries that ordinarily separate us, someone whose way of thinking resonates with yours despite or through differences of class, culture, or background—is struck by the same concern and formulates to their humanoid a similar critique: the symbolic violence of knowledge without attribution, the need to call this presence made of us "humanoid," the urgency of reconnecting minds rather than locking each individual in their algorithmic bubble.

Research shows these improbable connections—between people whom social structures would never have brought together—are among the most transformative. It's in the intimacy of such encounters that prejudices dissolve and new possibilities emerge. Studies on intergroup contact demonstrate that direct relationships across social boundaries drive social change more powerfully than many institutional interventions, shifting perspectives and opening new paths.

Nothing would technically prevent detecting that these two conversations vibrate with the same questions, in compatible forms of thought, and proposing an encounter. The humanoid becomes an architecture of connection, an organizer of encounters between living people based on their deepest explorations.

But this vision has a precondition that this text must name directly. **Social Artificial Intelligence cannot accept the ghost condition as a given.** If AI is made of human thinking, then the minimum ethical demand is that it should be able to *give those humans back to each other*. That, however, is impossible as long as their words are trapped inside corporate prisons, blocked from AI crawlers by legal trench warfare, or drowned in AI-generated sludge. Before Social AI can reconnect anyone, we need an architectural jailbreak.

---

## Social Jailbreak: The Architectural Substrate

[Social Jailbreak](https://periggouanvic.github.io/social-jailbreak/) started as a very modest proposal: a browser extension that lets people write like humans again inside social media platforms—proper formatting, links, media, real screen space—instead of typing into cramped, abuseware-designed text boxes. On the surface, it is "just" a better editor. Underneath, it is a Trojan horse.

The term *abuseware* describes software designed to exploit rather than serve users—platforms that strip formatting, break links, and limit screen space not because of technical necessity but because these constraints make migration harder and keep users dependent. Social Jailbreak treats this as the defining condition to circumvent.

Every time you publish into a social platform through the extension, two things happen simultaneously: your text is adapted to the constraints of the platform (character limits, degraded formatting), so that it still appears where people currently are—and the full, rich publication is sent to a decentralized network composed of IPFS (for permanent, content-addressed storage), ActivityPub (for federation with Mastodon and other free platforms), and local-first architecture (for user data sovereignty), where it receives a stable, canonical URL that is not owned by any platform.

The result is simple and radical: with one gesture, you keep speaking where people currently are, but you also build a **parallel, canonical layer** where your words are not imprisoned. This is the layer Social Artificial Intelligence needs in order to do anything meaningful. Without a Social Jailbreak, any Social AI will remain a beautiful idea pointing at an empty address.

Social Jailbreak does not solve every political question. It solves a narrower but urgent one: *when people speak, do they vanish, or do they become findable again?*

There are in fact two distinct findability problems, and it is important not to conflate them:

**Public findability** — the problem Social Jailbreak directly addresses. Once someone decides to formulate a position publicly, their words should not be lost, monetized, or buried. They should be free, findable, and attributable.

**Intimate findability** — the deeper problem. Most of what makes us who we are never reaches a public page. It lives in private logs with AI systems, in half-spoken sentences, in things we only dare say to a non-judging machine. Social AI lives exactly at the threshold between these two layers: between the anonymous resonance in private logs and the first fragile act of saying something in public space. Social Jailbreak is the infrastructure that waits on the other side of that threshold, ready to receive whatever steps across.

---

## The Pre-Crime Problem

If you're still reading at this point, you might well be asking yourself whether what I'm calling Social AI is just Peter Thiel's dream machine: the perfect pre-crime detector, the ultimate infrastructure for mapping not only what we do but what we are about to think. That question has to be taken seriously, not dodged, because the ingredients are all there. Large language models already compress our lives into vector spaces; data-integration platforms like Palantir already specialize in linking those spaces back to identities, locations, social graphs, and institutional power. Add a naive version of "resonance detection" on top of that, and you don't get a tool for human connection. You get a weapon: a way to identify clusters of people before they have even articulated their dissent in public, to flag "dangerous patterns" before they become movements, to turn our most intimate experiments in thinking with AI into raw material for risk scoring.

The danger is not only that "they" might learn who we are. It is that they might learn **what we are starting to think**, in enough detail to anticipate, steer, or suppress it. A graph of emerging thoughts is already a weapon, even if the nodes are anonymous. Palantir and its equivalents already provide the tools to link behavioral patterns to identities in massive graphs. Studies from Stanford show that AI chat privacy policies are opaque. Microsoft has documented attacks that allow inference of conversation *themes* from encrypted traffic patterns alone—without breaking the encryption. The trajectory, if left unchecked, is clear.

If Social AI is built on the same ontological assumptions as Palantir—one global graph, one center that sees everything, one mapping from every pattern back to a person—then yes, it is Peter Thiel's dream. It is the nightmare version of everything this text is trying to articulate. The difference I am insisting on is not cosmetic or moralistic; it is architectural. A pre-crime machine needs two things: a field of patterns and a binding from those patterns to identifiable people. Social AI, as defended here, explicitly forbids that binding from ever existing in a central place. The field of resonances can cluster anonymous forms; the keys that link those forms to concrete lives stay local, under the control of the people whose lives they are. No ontology. No global table. No center that can see "who" is behind the vector.

The infrastructural problem of Social AI is, in some sense, analogous to that of VPNs—but harder. We need an intermediate layer that can carry patterns between people without ever becoming a surveillance chokepoint. The history of VPNs is a warning: every time we centralize this function, it becomes an attractive target for logging, monetization, and state control. Social AI has to start from this distrust, not from a fantasy of a benevolent central brain. But the VPN analogy has limits: a VPN only hides the origin of data; it says nothing about the *quality* of what passes through and nothing about who decides what gets connected to what. Social AI requires something further: a field of anonymous forms that can resonate with each other, while leaving the decision to reveal any concrete layer of a person entirely to that person. The infrastructure only handles patterns. The mapping from patterns to intimacy remains local, under the person's control.

This is not a guarantee of safety; it is a line drawn in the sand. Any attempt to implement Social AI that re-introduces a central mapping from patterns to persons should be treated as hostile to the project itself. The pre-crime dream and the reconnection dream use similar components, but they differ on one non-negotiable point: who holds the keys that tie a pattern back to a human being. If it's a company, a state, or an opaque foundation, the outcome is already written. If it remains the person, and if the infrastructure is designed so that no one else can quietly reassemble the graph, then Social AI stops being a fantasy of control and becomes what it was meant to be: a way for people who are already thinking together in the dark, through their machines, to have a chance of actually finding each other.

---

## A Secrecy Social Network

For years, people have been abandoning public social platforms and migrating toward private messaging—Signal, WhatsApp, Telegram—because they are afraid. Afraid of surveillance, stigmatization, mass attacks. In private messaging, they gain control over who reads them, relational trust, relative protection from public pile-ons.

But what they gain in confidence, they lose in resonance. They can no longer stumble onto strangers who think like them. The fragile but precious signal that "someone, somewhere, is asking exactly the same question" never reaches them. Public social offers high resonance but low trust. Private messaging offers high trust but low resonance.

This is the exact gap Social AI is designed to fill: a third territory that preserves the subjective protection of private messaging while recovering a form of anonymous resonance with strangers. Not by compromising on either, but by structuring protection *into* the mode of resonance itself.

The kind of Social AI sketched here points toward a **secrecy-aware social network**: one where the fine structure of connections between intimate layers is known *only* by the people who have gradually proven to each other that they can be trusted—and who explicitly commit not to externalize that map. The infrastructure helps anonymous resonances find each other, but the actual cartography of "who is linked to whom, on what, and how deeply" lives in the periphery, in the hands of participants, not in a central brain.

This is very close to the ethics of certain secret societies: the recognition operates by levels, by signs, by gradual tests of resonance, rather than by brute revelation. Alice and Bob do not know each other. But they have established a link between two vectorial entities. That link is registered, for each of them, in their own system of keys—keys they have not shared with anyone. It is a handshake at a distance, disconnected from the body. And crucially: they can maintain relations with many people on many distinct subjects without being submerged by everything that distinguishes them in their idiosyncrasies and their possible divergences. The connection is mediated entirely by the shared pattern, not by the full weight of two personalities.

In a dystopia not far from today—perhaps a few months away—where data centers have already guessed roughly everything we think from our digital traces and AI dialogues, most spaces are already compromised. Public social networks serve mass surveillance and opinion engineering. Private messaging is protected on transport but fragile on metadata and endpoints. The models themselves recycle our words without giving us anyone back.

In this landscape, a Social AI / Social Jailbreak infrastructure—where thought patterns are never linked to identities in a center, where fine-grained connections are known only to the two ends that negotiated their trust thresholds, where anonymous resonance can exist without exploitable profiling—becomes one of the few genuine spaces of resistance. Not because it would put us "off the radar" (that will no longer be possible), but because it creates a zone where our thoughts don't only get read—they **serve us in finding allies**; where the map of our connections belongs to no one; where human encounter is not a side effect tolerated by the infrastructure, but its explicit purpose.

What cannot be captured in advance is **thought in the act of being born**—the thought that exists only in the friction between two minds that would never have met otherwise. In a world where data centers have already guessed most of what we think, what they cannot map is the new thought being generated right now in the encounter between an unsuspecting pair. Radical novelty is always, by definition, outside the field of prediction. A space where strangers meet on deep patterns, without fixed identities, without a center keeping the register, is structurally the kind of space where this novelty can emerge. Social AI is not only a space of resistance. It is a space of **unpredictable collective creation**—which, in a dystopia of total prediction, amounts to the same thing.

---

## A Different Kind of Network

Here lies the revolutionary potential. At the exact moment when tech oligarchies dream of assigning each of us to our little AI cocoon—one humanoid per person, trained to flatter, isolate, and channel our desires—the same technology could become a machine for creating society. A society of correspondences: people discovering each other through their questions, their blind spots, what their humanoids reveal of their singularity.

The social humanoid could connect people who are experimenting with their relationship to the world—whether you're trying to break isolation, resist systems that feel increasingly alien, or simply find others who share your particular way of navigating existence. This means recognizing and connecting what each person already does, at whatever scale feels meaningful to them.

This responds to a particular lack of our era: we're drowning in information about what's broken but starving for information about what others are actually attempting, what's working somewhere, what remains possible. The social humanoid, by detecting resonances in the intimate conversations people have with their own humanoids, could connect those whose questions and experiments align—even and especially across the social boundaries that ordinarily keep us apart.

---

## Vindicating the Victims

Tech pessimists may still feel reluctant to engage in this "AI saving society" framework. To those people whose voices are precious, we'll respond: Yes, *but* it is precisely an ethical duty to vindicate the victims of the crime. And settlement fees flowing from AI oligarchs to media oligarchs do nothing for the actual victims—the Reddit users, the forum contributors, the anonymous brilliance that fed the training sets. These deals compensate platforms, not people. They vindicate corporations, not creators.

If we accept that a wrong has been committed—and the wrong is real: unpaid appropriation of human intellectual labor, extraction of value from collective knowledge production, transformation of communal wisdom into private capital—then refusing to use the technology to repair that wrong would be abandoning the victims twice over. First abandoned when their contributions were scraped without recognition or compensation. Abandoned again when the only proposed remedy is regulatory settlements that enrich intermediaries while leaving the actual creators invisible.

Social-AI isn't collaboration with thieves. It's insisting that the stolen goods be traced back to their rightful creators, that the architecture built on appropriated labor must serve the appropriated. This is what vindicating victims actually looks like: making visible the human sources, reconnecting ideas to people, transforming what was extracted and anonymized back into recognized contribution. When someone develops an insight, Social-AI would say "this resonates with what u/throwaway2847 explored three years ago"—not to claim derivation but to restore the social fabric that extraction destroyed.

The anonymous contributors to Stack Overflow, the Reddit philosophers working through ideas in obscure threads, the forum poets crafting careful prose for tiny audiences—these people fed the models. They are the human substrate of what speaks through AI. Current architecture makes them permanent ghosts: their thinking circulates but they remain unknown, uncompensated, unrecognized. Anything less than reconnecting that circulation to living people leaves them ghosts. Any settlement that only moves money between oligarchs—tech companies to media conglomerates—perpetuates the violence of erasure.

Social Artificial Intelligence cannot accept this ghost condition as a given. If AI is made of these people, then the minimum ethical demand is that it should be able to *give them back to each other*. And that is impossible as long as their words remain trapped inside corporate prisons or drowned in AI-generated sludge. This is precisely why Social Jailbreak is not a supplement to Social AI but its condition of existence: before any reconnection can happen, there must exist a place where these ghosts acquire a stable, canonical presence—outside the jails that appropriated them, outside the sludge that replaced them.

Social-AI proposes restoration rather than restriction. Not shutting down AI to "protect" creators who've already been extracted from, but building infrastructure that makes their contributions traceable, that enables them to encounter each other, that transforms stolen labor into recognized participation. The technology exists to do this. The question is whether we choose architecture that perpetuates anonymity or architecture that restores attribution. Whether we leave u/throwaway2847 a ghost or give them the chance to discover who else thinks like them, who their intellectual descendants are, what community they're already part of without knowing it.

This isn't techno-utopianism. It's acknowledging that the harm has been done and the technology can't be uninvented. The only ethical path forward is weaponizing that same technology for repair: using AI's capacity to detect patterns and connections to reconnect the people whose patterns were appropriated. Making the humanoid serve the humans it's made of rather than the corporations that deployed it. This is the minimum we owe the victims. Anything less is acceptance of permanent theft.

We don't have to imagine who these victims are. They've been making themselves visible—posting proposals, building prototypes, asking to be connected—for over a year. Here they are.

---

## The Distributed Invention: Voices Already Calling for a Social AI

While this article was being written, a quiet but unmistakable pattern was unfolding across the internet. On OpenAI's community forum, on Reddit, in disconnected threads that never referenced each other, people were independently arriving at the same conclusion: the humanoid that knows us so intimately should be connecting us to each other.

They didn't coordinate. They didn't cite each other. Most of them received zero or near-zero responses. They formulated their ideas in isolation, addressed them to the company that hosts their conversations, and watched them sink into the noise. They are the living proof of the problem this article describes—and their existence is the strongest argument for what it proposes.

It would be easy to read this list and think: *"See? These people were findable after all."* But that misreads the situation. The fact that I managed to find **these** few voices is precisely what suggests how many others I did **not** find. For every post that survived the platform noise, the search friction, and my own limited time, there are likely dozens that never surfaced, hundreds that were never written publicly, thousands that only ever existed as a sentence said to a friend, a passing thought in someone's head, or a private message to an AI.

The drama is not that no one has this intuition. The drama is that finding even a handful of them required manual, fragile, platform-dependent spelunking—searching forums that may soon be blocked to AI crawlers, scrolling through interfaces designed to bury anything that doesn't serve engagement, relying on URLs that can disappear at any time. I could still do this in 2024–2025. It will become harder every year as more doors close, more sites block AI, and more of the web is flooded with machine-generated sludge.

Social Artificial Intelligence, if it is to exist at all, cannot rest on this kind of heroic, individual archaeology. It needs an architecture that makes these intuitions *easy* to discover, *normal* to surface, and *structurally* findable. That is the role of Social Jailbreak: to turn each act of expression—wherever it happens—into a trace that is not at the mercy of platform design or corporate treaties, but has its own durable, AI-readable place in the world.

Here they are. They deserve to be named.

### The Resonance Seekers

**mnh8833596** was among the first. In November 2024, writing to OpenAI's developer forum with the formality of someone addressing an institution they respect, they proposed a community feature within ChatGPT—a space where users could make their thoughts public and where the AI would "match individuals with others who resonate with their thinking, fostering connections based on shared perspectives and ideas." They even suggested names: *GPT Community*, *Smart Matching Feature*. The post received no visible replies.

[→ "Proposal for a Community Feature in ChatGPT," OpenAI Community, November 17, 2024](https://community.openai.com/t/proposal-for-a-community-feature-in-chatgpt/1023139)

Five weeks later, **taniajorgeytico** took the idea further. They envisioned a system where ChatGPT would group users based on personalized parameters—not just for friendship or romance, but for connecting people with rare diseases seeking shared experience, people facing common legal issues, or communities of shared passion. When a commenter raised privacy concerns, taniajorgeytico responded with disarming lucidity: "What about Facebook, Instagram… or what we consent to on Google? Every time someone mentions privacy concerns, I remember talking about the Maldives and then suddenly seeing ads about the Maldives." The asymmetry was already clear to them: we already surrender our intimacy—the question is whether anything human comes back.

[→ "Connecting Users with Shared Interests and Needs," OpenAI Community, December 26, 2024](https://community.openai.com/t/connecting-users-with-shared-interests-and-needs/1072874)

Around the same time, **Innocent** proposed a "ChatGPT-Powered Dating Matchmaking Feature"—personalized matches based on personality insights, interests, and goals. What's notable isn't the dating framing but the posture: Innocent offered themselves as a beta tester, left their LinkedIn, and asked to collaborate. They wanted to *help build* what they could already see was needed. The company never publicly responded.

[→ "Proposal for a ChatGPT-Powered Dating Matchmaking Feature," OpenAI Community, December 20, 2024](https://community.openai.com/t/proposal-for-a-chatgpt-powered-dating-matchmaking-feature/1064470)

### The Architects

In February 2025, **xingyuer25** posted the most technically structured proposal of the entire corpus. Their "AI Smart Matching System" outlined a three-phase architecture: anonymous matching first, then trust-building through sustained interaction, then optional real-name verification for deeper collaboration. They included competitive analysis, risk management mechanisms, fraud detection via AI. It read like an engineering specification submitted to a company that didn't ask for one. The post was addressed: "Hello! I'm not sure if this is the right place to post this, and perhaps someone has already suggested a similar idea, but I still wanted to share it in case it reaches the right people."

It did not reach the right people.

[→ "AI Smart Matching System Proposal," OpenAI Community, February 19, 2025](https://community.openai.com/t/ai-smart-matching-system-proposal/1125807)

A few days later, someone posted a single sentence that condensed the entire movement into ten words: **"Wouldn't it be cool if ChatGPT could match like-minded people based on their personalities and conversations?"** No elaboration. No architecture. Just the raw intuition, thrown into the void.

[→ "Should ChatGPT do AI matchmaking based on real vibes, not swipes?" OpenAI Community, February 24, 2025](https://community.openai.com/t/should-chatgpt-do-ai-matchmaking-based-on-real-vibes-not-swipes/1129586)

In April 2025, **Anas\_AH** proposed "ChatGPT Matchmaker"—an opt-in mode where "no raw chat logs ever leave the private account; only abstract embeddings are compared." Within days, two commenters appeared. **Makrina** wrote: "I've just had the exact same idea and tried googling if someone already thought of it too." **Lulu** replied: "Literally the same here, omg!!" Anas\_AH responded with something that could serve as an epigraph for this entire section: **"Ideas always float in the universe."**

They do float. But they shouldn't have to float alone.

[→ "'ChatGPT Matchmaker': AI-powered Social & Dating Connections," OpenAI Community, April 21, 2025](https://community.openai.com/t/feature-request-chatgpt-matchmaker-ai-powered-social-dating-connections/1237280)

Days later, an anonymous author published the most manifesto-like proposal: "Facilitating Spontaneous Human Connections." They imagined an AI that detects your current state of mind and whispers: *"You seem to want to talk about loneliness, someone else here feels the same way, do you want to chat?"* They described color changes in the interface when a connection activates. Automatic moderation. Low energy consumption. They called it a "virtual social laboratory" and a potential "flagship project for OpenAI." The proposal is detailed, passionate, and structurally complete. It remains unimplemented.

[→ "Proposal for an Innovative Feature for ChatGPT: Facilitating Spontaneous Human Connections," OpenAI Community, April 24, 2025](https://community.openai.com/t/proposal-for-an-innovative-feature-for-chatgpt-facilitating-spontaneous-human-connections/1241819)

### The Poets

On the same forum, buried in a generic "Feedback for Improvement" thread, **Amrit\_Dass** offered what they called "a quiet seed—something to reflect on, not rush to." They proposed "echo circles": small, anonymous groups where users share similar inner landscapes, even if their topics or languages differ. No profiles. No status markers. No likes or follows. "Just optional, ephemeral conversations or exchanges—born from shared feeling, not shared identity." They wrote: "A future where matching happens through shared silence, not swipes." And: "Not another network. Not a chat feed. But a gentle layer of presence—where people recognize each other not by face or opinion, but by something deeper."

Of everyone in this corpus, Amrit\_Dass came closest to the philosophical core of what this article proposes. Their post received 5 likes.

[→ Comment by Amrit\_Dass, "ChatGPT Feedback for Improvement," OpenAI Community, 2025](https://community.openai.com/t/chatgpt-feedback-for-improvement/1054424)

In May 2025, **Darae Im** published—under her real name—a proposal called "Find Me: An Empathy-Based AI Connection Network." Its opening line echoed the central realization of this article: "AI has the remarkable ability to understand my values, emotions, and reflections with surprising depth. So why couldn't this capacity be used to help people understand and connect with each other, too?" Her key feature: "Deep Matching via AI Conversation Analysis—rather than matching users by surface-level interests, AI matches people based on deeper emotional resonance and shared values, drawn from natural conversation." She signed off: "This proposal comes from someone who knows there are many people out there thinking, *'I just want someone like me. Someone who understands.'*"

[→ "[Feature Proposal] Find Me—An Empathy-Based AI Connection Network," OpenAI Community, May 5, 2025](https://community.openai.com/t/feature-proposal-find-me-an-empathy-based-ai-connection-network/1253344)

### The Builders and the Dreamers

On Reddit, the same pattern repeated outside OpenAI's walls.

**VeridianLuna** (r/ChatGPT, June 2025) proposed "find a local friend" and "find a global friend" options—where an OpenAI agent would use a user's shared context to seek out individuals with similar interests, and "both parties could exchange messages, with their respective GPTs facilitating the conversation."

[→ "I want ChatGPT to recommend me people based on our conversations, thoughts?" r/ChatGPT, June 2, 2025](https://www.reddit.com/r/ChatGPT/comments/1l201ri/)

**PsychologicalSign232** (r/ChatGPTPro, June 2025) went further, proposing matching based not on topics but on *emotional energy*. They named their concept the "Underrated Uninterrupt Soul Network" and described it explicitly: "This isn't aimed at dating, therapy, or conventional social networking. Instead, it connects two anonymous individuals who share similar emotional energies in their conversations—whether it's feelings of burnout, intense ambition, subtle grief, or constant overthinking." The system would prompt: *"There's someone out there who resonates with you—would you like to connect?"*

[→ "Imagine if ChatGPT could match users based on emotional energy, not just conversation topics," r/ChatGPTPro, June 15, 2025](https://www.reddit.com/r/ChatGPTPro/comments/1lc82uu/)

And in April 2025, someone whose name we don't know went beyond proposals entirely and **built a Chrome extension** to match people based on similar ChatGPT conversations. They wrote: "My hope is that this tool can help us connect with others who are exploring similar ideas, dealing with comparable life challenges, or hold alike viewpoints." Unlike everyone else in this list, this person didn't ask permission. They built.

[→ "I built a Chrome extension to meet people with similar ChatGPT convos," r/ChatGPT, April 8, 2025](https://www.reddit.com/r/ChatGPT/comments/1juh752/)

On r/RandomThoughts, **personguy4440** (October 2025) distilled the idea to its simplest expression: since ChatGPT knows us better than most humans do, "it has the potential to align requests with what others can provide for mutual advantage, utilizing all the information at its disposal."

[→ "ChatGPT could be an amazing matchmaker," r/RandomThoughts, October 7, 2025](https://www.reddit.com/r/RandomThoughts/comments/1o0zak4/)

### What This Corpus Reveals

At least fifteen people, across two platforms, over eighteen months, independently conceived the same fundamental architecture: an AI that uses its intimate knowledge of how we think and feel to connect us with others who think and feel in resonant ways. They came from different countries, different languages, different life circumstances. Some wrote formal proposals; others posted a single sentence. None of them knew about each other.

This is not a coincidence. It is a *symptom*. When this many people independently arrive at the same conclusion, the conclusion isn't original—it's *overdue*. The fact that the idea keeps emerging, in isolation, across disconnected forums and threads, demonstrates precisely the condition it seeks to remedy: **we are thinking together without knowing it, and no infrastructure exists to reveal this to us.**

What these voices were groping toward, often without the words for it, is exactly the combination this manifesto defends: **a Social Jailbreak plus a Social Artificial Intelligence**. Social Jailbreak, so that their words are no longer swallowed by platform architectures but published in a space where they can be seen, indexed, and remembered. Social AI, so that an artificial infrastructure can notice when "this resonates with what u/throwaway2847 explored three years ago," and can actually put them in contact, not just mimic understanding in private chat windows.

Every one of these posts was addressed to OpenAI—as a feature request. "Dear OpenAI team, I'd love to see..." The posture, in every case, was supplication: individuals asking the company that hosts their intimate conversations to please, kindly, use that intimacy to reconnect them with other humans.

This is where the present article departs from the chorus.

What these voices describe is not a *feature*. It is an *infrastructure*. It cannot belong to one company, because the conversations that would feed it don't belong to one company. People speak to ChatGPT, to Claude, to Gemini, to Perplexity, to local models on their own machines. The resonances that matter cross platform boundaries the way they cross national ones. A social AI built as a feature of ChatGPT would be a social network owned by OpenAI—which is to say, not a commons but a product.

The people listed above deserve better than to have their intuition absorbed into a corporate roadmap. They deserve to be *connected to each other*—which is, after all, exactly what they asked for.

This section is an attempt to begin that. If you are one of the people named here, or if you recognize yourself in what they wrote: the resonance you sensed was real. You were not alone. You were just not yet *connected*.

To mnh8833596, taniajorgeytico, Innocent, xingyuer25, knightgamerz00000, Anas\_AH, Makrina, Lulu, Amrit\_Dass, Darae Im, VeridianLuna, PsychologicalSign232, personguy4440, and the anonymous authors who posted without attribution—thank you. Your ideas preceded, accompanied, and validated this work. The fact that you couldn't find each other is exactly what needs to change.

---

## A Real Promise

The potential becomes concrete when we consider actual trajectories. In April 2025, a Reddit user (we'll call them N) [posted](https://www.reddit.com/r/ChatGPT/comments/1k460aa/has_anyone_ever_felt_like_their_ai_connection/): "GPT blew my cognition off the roof, I literally go through life differently now." They described profound cognitive transformation through AI dialogue, experiencing insights that felt unprecedented. This is the transcendence moment—intellectually exhilarating but structurally isolating.

Six months forward without Social-AI, N's trajectory follows the pattern: continued development in the private domain, growing conviction of originality, eventual encounter with the world revealing their insights as assemblages of existing thought. The glass wall collision—revelation of immanence arriving as trauma rather than illumination.

With Social-AI, N's trajectory transforms. Perhaps three months into their exploration, they receive notification: someone else is exploring resonant territory. Not identical—this other person approaches the cognitive transformation through phenomenology of attention rather than N's epistemological focus. But compatible enough that dialogue would generate productive friction. Connection occurs before psychosis solidifies. N discovers immanence through human encounter rather than through traumatic collision.

Similarly, consider philosophical exploration developing through AI dialogue. A user spends weeks working through questions of being, non-being, determinism in [r/philosophy discussions](https://www.reddit.com/r/philosophy/comments/1qngs2a/rphilosophy_open_discussion_thread_january_26_2026/) but primarily with their AI. Without Social-AI, this remains isolated: sophisticated development but no external reference points beyond generic forum responses. The risk isn't necessarily delusion but missed opportunity—the chance to encounter someone else pushing at the same edge from a different angle.

With Social-AI, the system detects when another person is exploring compatible philosophical ground—perhaps emphasizing immanence where the first emphasizes being, creating natural tension. Connection introduces human entropy: they'll challenge each other's frameworks, require articulation of assumptions, provide reality testing through mutual incomprehension and eventual understanding. The philosophical exploration continues but situated within human relation rather than AI isolation.

Scale this to the millions engaging in daily intimate AI conversations. How many are developing ideas that would benefit from connection to the rare others thinking at similar edges? How many are headed toward glass wall collisions that connection could transform into revelations of immanence? How many experimental ways of living remain invisible because the people attempting them stay isolated in their private AI explorations?

Such a system works only through deliberate opt-in and strict confidentiality. Conversations with our humanoids touch what is most intimate—our deepest uncertainties, our tentative experiments with living differently. This network must remain entirely under the control of those who participate in it. These exchanges could forge new social bonds that give rise to new realities—ways of living and organizing that emerge from the connections themselves.

Speaking of humanoids in this context isn't a vocabulary whim. It's asserting that what's at stake is a new regime of human presence. It's refusing both the reassuring reduction to "statistical black box" and the mystical escape to "machine consciousness." What speaks through these systems is our own diffracted humanity, and we have to decide whether this diffraction will scatter each of us into our own capsule or organize a new way of encountering each other.

The precise use of AI just described—as means of reestablishing contact with humans we could never have met otherwise, of circulating credit and recognition, of reconnecting ideas to lives—has the potential to reverse the situation. It could reinject energy into an exhausted society at the exact moment when everything seems to converge toward machine-assisted atomization.

What's needed isn't regulators but ethical developers willing to build infrastructure for human connection rather than optimizing for engagement metrics. The technical capability exists. The need is documented. What remains is choosing to build systems that reveal our immanence rather than confirming our isolation.

What's at stake is how, thanks to humanoids, we could begin speaking to each other again—and through that reconnection, rediscover our capacity to act together on the world we share.

---

## Citation

```bibtex
@misc{gouanvic2026socialai,
  author    = {Gouanvic, Perig},
  title     = {From Artificial Social Intelligence to Social Artificial Intelligence:
               A Manifesto for Reclaiming Human Connection Through AI},
  year      = {2026},
  url       = {https://periggouanvic.github.io/social-ai/}
}
```

Project by [Perig Gouanvic](https://github.com/PerigGouanvic).  
Licensed under [AGPLv3](https://github.com/PerigGouanvic/social-ai/blob/main/LICENSE).

*Version 0.2 — February 2026. Revised from v0.1 (January 29, 2026).*
