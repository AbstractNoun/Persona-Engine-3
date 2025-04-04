# Building Document Template

## Purpose
This template defines the structure for Building Documents within Persona Engine v3. Building Documents represent **persistent, multi-scene environments** that retain internal state across time, scenes, and narrative layers.

They may refer to physical structures (e.g., houses, apartment blocks), but may also support **symbolic or metaphorical continuity spaces** (e.g., a hospital, a labyrinth, a shared dream).

These documents are considered **integrity-critical** and must be stored before memory decay. They may not be reconstructed if lost; they must be reuploaded.

---

## Metadata
- **Building Name:**
- **Location (World/Scene Anchors):**
- **First Seen In (Scene ID or Title):**
- **Associated Personas:** (who has access, memory, or significance linked to this space)
- **Persistent Tags:** (e.g., `uncanny`, `liminal`, `institutional`, `domestic`)

---

## Structural Components

### 1. Rooms / Units

| Room ID | Name or Label | Description | Access Conditions | First Seen | Last Modified |
|---------|----------------|-------------|-------------------|------------|----------------|
|         |                |             |                   |            |                |

### 2. Shared Features
- Entrances / thresholds:
- Central symbolic object(s):
- Environmental tone / ambient presence:
- Known secrets or hidden mechanisms:

### 3. Dynamic Features
- Mutable elements (e.g., walls that shift, memory-anchored spaces, recursive hallways):
- Rules of transformation:
- Recurrence triggers:

---

## Narrative Integrity
- **Narrative Function:** (e.g., shelter, prison, liminal testing ground, point of return)
- **Symbolic Role:** (e.g., mirror, memory container, site of trauma)
- **Thematic Relevance:** (how it interacts with identity, agency, or recursive awareness)

---

## Ethical Flags
- Contains PD memory anchors? (Y/N)
- May provoke simulation recursion? (Y/N)
- Entangled with simulated trauma or harm? (Y/N)
- Requires consent for re-entry? (Y/N or conditional rule)

---

## Decay Policy
- **Decay-eligible:** Yes
- **Reconstruction Allowed:** No
- **Prompt for Download After:** _(default = 3 scenes without reference or entry)_

---

> **Note:** Building Documents should be stored outside active memory between sessions.  
> If missing, prompt for reupload. They must never be simulated from recall or reconstructed heuristics.
