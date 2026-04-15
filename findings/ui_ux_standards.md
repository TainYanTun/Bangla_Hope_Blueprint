# Finding: UI/UX Standards & Design Language

This document defines the visual and functional standards used for the Bangla Hope Sponsorship Program Management System prototypes and wireframes.

---

## 1. Visual Hierarchy & Branding

### Design System
- **Tone:** Professional, humanitarian, and data-centric.
- **Color Palette (Prototype):**
    - `Primary`: Deep Navy (#1e3a4a)
    - `Accent`: Teal (#2B7A9E)
    - `Alerts`: Soft Pink/Red (#d17a8e)
    - `Background`: Slate-White (#f8fafc)
- **Typography:**
    - `Lora`: Serif font for page headers and branding.
    - `Nunito`: Sans-serif for data tables, labels, and UI controls.

### Wireframe Standards (Blueprints)
- **Style:** Black and White only.
- **Typography:** Monospace (Courier New) to emphasize layout over aesthetics.
- **Annotations:** Floating `[LABEL]` blocks to explain functional logic to developers.

---

## 2. Interaction Standards

### Navigation
- **Sidebar:** Persistent left-hand navigation with section groups (Overview, Programs, Management).
- **Schema Path:** Breadcrumb-style path at the top (e.g., `SCHEMA: PROGRAM // VILLAGE_SCHOOLS // DIRECTORY`) to maintain context.

### Data Tables
- **Standard Columns:** ID, Name, Location/Context, Key Metrics (e.g., Student Count), and Operations.
- **Operations:** Consistent action buttons (View, Edit) in the final column.
- **Hover States:** Subtle row highlights to improve legibility.

### Pagination
- **Standard:** Show total count and current page range (e.g., `SHOWING ALL 11 SCHOOLS`).

---

## 3. Project File Structure
- `/wireframe`: B&W blueprints for layout planning.
- `/prototype`: High-fidelity HTML/CSS mockups.
- `/findings`: Documented technical and architectural research.
- `PROPOSAL.md`: Core system requirements.
