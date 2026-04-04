# Semantics Foundations  
Meaning Rules for the Icon System

## Purpose  
Semantics define *what* an icon communicates and *why* it exists.  
Every icon in the Jai Visuals API/HTTP Icon System is built on a strict semantic model to prevent ambiguity and ensure reviewer‑safe clarity.

## Core Principles  
### 1. One Icon = One Meaning  
Each icon expresses a single, unambiguous concept.  
No icon may represent multiple states or overlapping ideas.

### 2. Domain‑Aligned Semantics  
Icons map directly to API and HTTP concepts such as:  
- validation failures  
- authentication and authorization  
- resource state  
- rate‑limit enforcement  
- payload integrity  
- workflow transitions  

### 3. No Visual Metaphors  
Icons must express meaning through structural cues, not metaphor.  
Examples:  
- Slash = invalid  
- Block = denied  
- Break = malformed  
- Arrow = flow  
- Bar = limit  

### 4. Semantic Boundaries  
Each icon belongs to a semantic family with strict boundaries:  
- **400–499:** client‑side failures  
- **Workflow:** process and transitions  
- **Rate‑Limit:** thresholds and enforcement  

No icon may cross semantic families.

### 5. Reviewer‑Safe Neutrality  
Icons avoid:  
- emotional expression  
- anthropomorphism  
- metaphorical imagery  
- ambiguous shapes  

Semantics must remain technical, neutral, and enterprise‑safe.

## Semantic Hierarchy  
1. **Family Meaning** — broad domain (e.g., Client Errors)  
2. **Category Meaning** — sub‑domain (e.g., Validation Failures)  
3. **Icon Meaning** — specific concept (e.g., Malformed Payload)

## Outcome  
Semantics ensure that every icon communicates a precise, predictable meaning that developers can trust and reviewers cannot misinterpret.

