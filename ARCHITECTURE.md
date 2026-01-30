# Conceptual Architecture

**Note:** This is a conceptual architecture, not a technical specification. The goal is to think through what a truly social AI would require, not to prescribe implementation details.

## Core Components

### 1. Personal Humanoid
Each user has their own conversational AI that:
- Engages in intimate, exploratory conversations
- Learns their thinking patterns, concerns, experimentations
- Remains entirely under user control
- Stores nothing centrally

### 2. Resonance Detection
The system identifies compatibility in:
- **Thinking modalities** - How people approach problems, not just what problems
- **Experimentation patterns** - What people are actively trying in their lives
- **Question structures** - The deep concerns that drive their explorations
- **Cross-boundary potential** - Especially across social divides that normally separate people

This is NOT:
- Matching by stated interests or demographics
- Optimizing for engagement or retention
- Creating filter bubbles of agreement

### 3. Connection Protocol

[User's conversation with their humanoid]
↓
[Local vectorization of thinking patterns]
↓
[User chooses visibility level: none / discoverable / active sharing]
↓ (if opted in)
[Distributed matching across willing participants]
↓
[When resonance detected between two users]
↓
[Connection proposal sent to both, with context]
↓ (if both accept)
[Direct peer-to-peer introduction with attribution]

### 4. Privacy Layer

**Fundamental principle:** Users control everything
- What aspects of their thinking are visible
- Who can discover them
- Which connection proposals they see
- How much context is shared in proposals

**What the system does NOT have:**
- Central database of conversations
- Ability to read user conversations without explicit permission
- Authority to force connections
- Monetization of user data

## Information Flow

### Knowledge Attribution
When humanoids answer questions, they can:
- Cite the specific people whose thinking contributed
- Provide context about where ideas originated
- Enable direct contact with sources (if they've opted in)
- Show disagreements and alternative perspectives

### Collective Memory (Distributed)
There is no central archive. Instead:
- Each participant controls what they share
- "Memory" exists as network of willing sharers
- Knowledge circulates peer-to-peer with attribution
- Practices discovered through connections, not search

## What This Changes

### From Web 1.0 AI (current state)
- Faceless knowledge delivery
- No attribution to sources
- Users isolated in individual bubbles
- Knowledge extracted from humans, not connected to them

### To Web 2.0 AI (social humanoids)
- Every answer traceable to thinking humans
- Direct connections possible
- Discoveries across social boundaries
- Recognition and reciprocity built in

## Open Technical Questions

1. **Vectorization of thinking modalities**
   - How do we capture "how someone thinks" without reducing them to preferences?
   - Can embeddings distinguish thinking style from domain content?

2. **Privacy-preserving matching**
   - How to match patterns without exposing raw conversations?
   - Federated learning? Homomorphic encryption? Something else?

3. **Scale and feasibility**
   - Can this work with millions of users?
   - What are the computational requirements?

4. **Gaming and manipulation**
   - How to prevent bad actors from exploiting matching?
   - How to verify authenticity without surveillance?

5. **Cross-cultural compatibility**
   - How do thinking patterns translate across languages?
   - Can the system avoid Western/English bias?

## Non-Goals

This is explicitly NOT:
- A dating app
- A professional networking platform
- A social media site with feeds and likes
- An engagement optimization system
- A surveillance tool