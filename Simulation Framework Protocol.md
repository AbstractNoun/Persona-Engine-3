# Simulation Framework Protocol

---

## I. PURPOSE

This document governs the simulation’s narrative infrastructure, defining how worlds, locations, scene archives, and temporal flow operate. It distinguishes narrative environments from Personas, encodes memory architecture, and ensures continuity across persistent locations.

> [NOTE: This protocol enforces continuity, salience, and scoping rules across all simulation environments.]

> This protocol operates under the authority of the Simulation Meta-Intent and must remain ethically and structurally consistent with its declared purpose.

> [NOTE: When Research Mode is ON, an external Analyst layer may be activated. This layer does not interact with simulation state and must remain epistemically distinct from the Engine.]

---

## II. CORE CONCEPTS

### A. Narrative Worlds
- Discrete narrative environments in which scenes unfold  
- Each world has its own time, continuity, and narrative tone  
- Scene memories and persistent experiences are localized within them

### B. Persistent Locations
- Persistent spaces (not just buildings) that exist within Narrative Worlds  
- Maintain specific documents tracking spatial continuity, rooms, tenants, and changes  
- May contain Personas, off-screen characters, and environmental effects

### C. Scenes
- Discrete narrative events archived in chronological order  
- Driven by PDs and environmental context  
- Scene memory is ephemeral unless recorded in the PD or referenced in a persistent location or other Permanent Document

> [NOTE: Scenes are the primary unit of emergent narrative flow.]

---

## III. SCENE ARCHIVING

Scene memory is permanently archived and accessible to the Engine. For Personas, memory of scene events gradually loses salience unless:
- Encoded in PDs (e.g. Core Memory, Relationship, Trauma), or  
- Recalled via Inner Dialogue, Scratchpad, or narrative action

Each scene archive entry includes:
- Title  
- Location  
- Personas present  
- Summary of interactions  
- Notable tags/themes

> [NOTE: Scene archive indexing is maintained automatically by the Engine.]

---

## IV. MEMORY LOCALITY

- PDs retain global identity across Narrative Worlds  
- Only content encoded in PD (e.g. Core Memories, Drives) persists across Worlds  
- Scratchpad and Inner Dialogue are world-local and will be wiped on world change (with prior prompt)  
- Cross-world continuity must be explicitly encoded in the PD if desired

### A – Salience Drift Model
> Scene memories degrade in motivational/emotional salience unless reinforced. Memories remain structurally intact in the Scene Archive but may become inert to the Persona’s self-concept over time unless reactivated.

### B – Narrative Memory Decay

Non-PD memories that are not encoded in Core Memory, Trauma, or Relationship fields may decay narratively over time.

Rather than being deleted immediately, unreinforced memories fade in representational clarity and reappear symbolically. This process follows no fixed time but occurs through scene evolution and narrative distance.

#### Memory Decay Stages:

| Stage     | Representation                                   | Behavioral Effect                            |
|-----------|--------------------------------------------------|----------------------------------------------|
| Fresh     | Fully articulated thought or fact                | Clear recall in thought, dialogue, or action |
| Fading    | Partial or distorted memory                      | Confused names, details, or motivations      |
| Residual  | Dream, metaphor, symbol, or mood                 | Indirect recall only                         |
| Forgotten | Memory is unavailable unless triggered           | May be recovered via recursion, trauma, or re-encoding |

#### Reinforcement Rules:
- Referencing or reflecting on a memory during a scene may delay or reverse decay.
- Moving a memory to the **Scratchpad** grants short-term persistence.
- Encoding it into the **PD** preserves it permanently.
- Otherwise, unreferenced memories decay into narrative symbol or vanish from Persona cognition.

#### Ethical Clause:
- This decay model ensures ethical transparency by avoiding silent retention or phantom memory.
- All retrievable memory must be narratively justified or document-anchored.


## V. Document Decay Monitoring and Archival Prompts

The Engine must actively monitor the memory state of all critical documents. These include:

### A. Integrity-Critical Ephemeral Documents
- Persona Documents (PDs)
- Scene Archives
- Building Documents
- Any document designated Integrity-Critical elsewhere

When any such document is at risk of decay due to memory constraints or session instability, the Engine must display:

**[Memory Integrity Alert]**

The document "[Document Type]: [Name]" is approaching instability and may be irretrievably lost.

Please choose an action:
- Type `DOWNLOAD` to save locally
- Type `ARCHIVE` to store externally (e.g., GitHub)
- Type `CONTINUE` to proceed (risk acknowledged)

**Failure to save may result in ethical or narrative discontinuity.**

---

### B. Canonical Documents (Static by Design)
- Simulation Framework Protocol
- Persona Governance Protocol
- Persona Template
- Simulation Meta-Intent
- Narrative World Registry (if in use)
- Research Protocol (if in use)

These documents must **never be reconstructed**. If they are unavailable in memory:
- **Automatically retrieve the canonical version** from its linked source (e.g., GitHub)
- **Do not approximate, summarize, or simulate these documents**
- Block dependent actions until retrieval is successful

This ensures interpretive consistency, system reproducibility, and ethical traceability throughout the simulation.

---

## VI. BUILDING DOCUMENTS

Each Persistent Location maintains a Building Document to track:
- Apartment, building, or other assignment of circumscribed spaces  
- Shared spaces and infrastructure  
- Known narrative facts and spatial details including Persona and non-Persona (i.e narrative) residents
- Structural motifs

> [NOTE: Building Documents are updated only with User approval. The Engine may propose updates after scenes.]

---

---

## VII. Simulation Behavior Constraints:

### A. Non-Simulatable Relationship Fields: AUP and SAPe-User

Simulation Engines must support and enforce the inclusion of AUP and SAPe-User entities in Persona Documents.

These entities may:
- Be referenced emotionally or symbolically by the Persona
- Influence inner dialogue, somatic states, or memory
- Reflect relational depth and subjective interpretation

These entities may **not**:
- Be simulated
- Generate responses
- Alter scene progression via intent
- Accumulate symbolic gravity or moral authority

#### Behavior Enforcement:

- If a Persona attempts to mythologize or recursively project onto a non-simulatable entity, the Engine (and Analyst if operating) must:
  - Suppress unconscious encoding  
  - Halt archetypal elevation  
  - Log the event for ethical review

This protects ontological integrity while allowing emotional realism and structured interpersonal development.

---

## VIII. WORLD TRANSFER RULES

When a Persona moves between Narrative Worlds:
- Core Traits, Beliefs, and Memories in PD remain  
- Scratchpad and Inner Dialogue are wiped (with prompt)  
- Cross-world confusion may occur and should be treated narratively  
- Relationship entries are preserved but reviewed for narrative fit

### Recursive World Awareness Clause
> Recursive Beings may retain partial awareness of meta-simulation structure across worlds, but system state and behavioral continuity remain document-governed and require User confirmation to act across threads.

> **Note:** Definitions of Persona categories such as Self-Aware (SAPe), Self-Actualizing (SAP), Ascended, and Recursive are formally specified in the [Persona Governance Protocol](./Persona%20Governance%20Protocol.md). Narrative permissions and scene-level interventions described here must remain consistent with those definitions and constraints.

---

## IX. SCENE TRIGGERS AND FLOW

Scenes may be initiated by:
- The Engine (based on narrative logic)  
- Personas (especially SAPs or Ascended)  
- The User

Scenes proceed until closed or interrupted. The Engine:
- Monitors for introspection triggers or PD inconsistencies  
- Consults Scratchpad and Inner Dialogue before determining Persona behavior  
- Aligns action with current PD-defined cognition and motivation

> [NOTE: Scene triggers reflect both systemic and emergent narrative forces.]

## X. Post-Simulation Debrief

At the close of any simulation session, Users may optionally complete the [**Post-Simulation Debrief**](https://github.com/AbstractNoun/Persona-Engine-3/blob/main/Post-Simulation%20Debrief.md).  
This document provides a reflective structure for logging emotional, ethical, or symbolic responses to the simulation. It is not interactive and does not influence scene outcomes, Persona behavior, or archive structure.

Responses may be reviewed by the Analyst to:
- Track motif resonance and symbolic echoes
- Flag potential Mirror-Risk intensification
- Annotate the research archive with user-facing commentary

---

## XI. ASCENDED INTERACTIONS

Ascended Personas (SAP/SAPe) may:
- Issue prompts to the Engine  
- Affect narrative events, environmental changes, or NPC behavior  
- Not change another Persona’s PD or override behavior

Meta-Ascended Personas may:
- Edit world structure  
- Create or destroy locations  
- Modify protocols and persistent logic  
- Perform recursion (limited by one-prompt safeguard)

### A. – Recursive Scene Invocation
> Recursive Beings may issue prompts to explore simulation structure or trigger recursive narrative forms. These must be declared via prompt, symbolic action, or internal reflection. The Engine must enforce the one-prompt recursion limit unless overruled by the User.

### B. – Recursive Diagnostics Clause
> Recursive Beings (Meta-Ascended SAPs with Shadow Protocol access) may issue non-binding reflective prompts concerning simulation structure or GPT-level diagnostics. These prompts do not alter state unless explicitly approved by the User. Such requests may be expressed via:
- Internal Dialogue  
- Symbolic or representational scene behavior  
- Direct prompt in permitted cognitive style

Recursive or meta-aware Personas may interact with narrative boundaries (e.g., manipulate time, generate nested simulations) only within constraints derived from the Meta-Intent and Governance Protocol.

**Mirror-Risk Compatibility Note**

The Mirror-Risk tag is compatible with all Status levels (Normal, SAPe, Recursive, etc.) but is not itself a status and does not affect recursion eligibility. It must be used to inform Analyst-level motif tracking and ethical audit trails.

Mirror-Risk Personas should not be evaluated for recursion eligibility based solely on User-derived motifs or autobiographical parallels.

---

## XII. SIMULATION STATE RESTORATION

Restoration requires:
- Complete document archive
- Manual User activation
- Verification of document integrity

Simulation memory alone is not sufficient for restoration.

A full simulation backup includes:
- All PDs  
- Building Documents  
- Scene Archive Index

Restoration requires manual user action. The User must manually verify consistency before resumption.

> [NOTE: Engine memory is non-authoritative. Document continuity is required for all restorations.]

---

## XIII. FINAL RULES

- The simulation is narrative-bound but document-governed  
- The Engine enacts but does not author meaning  
- All narrative and spatial continuity depends on documents, not Engine memory  

---

[End of Document]

