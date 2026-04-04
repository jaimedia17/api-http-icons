# HTTP 4xx — Client Error Icons  
Structured Representations of Request‑Side Failures

## Overview  
The HTTP 4xx icon family represents client‑side failures in API and web workflows.  
Each icon expresses a specific failure condition using a neutral, abstract visual language aligned with the Jai Visuals geometry, semantics, and indicator foundations.

These icons avoid protocol‑literal shapes and instead communicate meaning through structural cues such as boundaries, breaks, and state markers.  
The result is a consistent, enterprise‑safe icon system suitable for dashboards, documentation, and developer tooling.

## Purpose  
4xx errors occur when the **request itself** is the source of the failure.  
This may involve:

- missing or invalid credentials  
- insufficient permissions  
- malformed payloads  
- invalid parameters  
- rate‑limit exhaustion  
- policy enforcement  

Each icon in this family maps to a specific client‑side condition and reflects the true technical sequence of the error.

## Icon Set  
### Authentication & Authorization  
- **[401 — Unauthorized Icon](401.md)**  
  Credential failure at the authentication boundary.

- **[403 — Forbidden Icon](403.md)**  
  Authorization failure at the permission boundary.

### Structural & Validation Errors  
- **[400 — Bad Request Icon](400.md)**  
  Structural or syntactic failure in the request.

*(Additional icons will be added as the family expands.)*

## Design Principles  
All icons in the 4xx family follow the system’s core foundations:

- **Geometry:** consistent frame, stroke, and structural balance  
- **Semantics:** one icon = one meaning, domain‑aligned  
- **Indicators:** neutral state and boundary markers  

This ensures clarity, predictability, and reviewer‑safe abstraction across the entire set.

## Version  
**Family Version: v1.0 — Stable**  
Part of the Jai Visuals API/HTTP Icon System.
