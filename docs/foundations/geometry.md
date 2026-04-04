# Geometry Foundations  
Structural Rules for the Icon System

## Purpose  
Geometry defines the structural language of the Jai Visuals API/HTTP Icon System.  
Every icon follows a deterministic geometric framework to ensure consistency, recognizability, and small‑scale clarity across all families.

## Core Principles  
### 1. Frame  
- All icons are built within a consistent square frame.  
- The frame represents a “concept boundary” — request, resource, payload, or state.  
- No element may break the frame unless the concept explicitly requires it (e.g., overflow, rate‑limit).

### 2. Line Weight  
- Uniform stroke weight across the entire system.  
- Ensures clarity at 16px, 20px, and 24px sizes.  
- No decorative variation; all weight changes must express meaning.

### 3. Symmetry & Balance  
- Icons must remain visually balanced even when expressing failure or disruption.  
- Asymmetry is allowed only when semantically required (e.g., slash, break, conflict).

### 4. Shape Language  
- **Square:** structure, payload, request envelope  
- **Circle:** state, status, enforcement  
- **Slash / Break:** invalidity, interruption, rejection  
- **Arrow:** direction, flow, transfer  
- **Bar / Block:** limit, threshold, constraint

### 5. Pixel Discipline  
- All geometry aligns to a strict pixel grid.  
- No fractional coordinates
