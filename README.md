# 🐼 Panda Template Manifest – Cafe (Enterprise)

> **Enterprise-grade AI operating manual for the Cafe template.**  
> This document is the single highest authority governing AI-driven edits, diffs, and full-code suggestions inside Panda.

---

## 1. Template Metadata (DO NOT MODIFY STRUCTURE)

```md
# Panda Template Manifest

template_name: "Cafe"
template_id: "panda-cafe-001"
template_version: "1.0.0"
template_type: "local-food-business"
layout_style: "warm-local-hospitality"
technology_stack: ["HTML5", "CSS3"]
responsive: true
dark_mode: false
rtl_supported: false

author: "Panda Templates"
last_updated: "2026-01-03"
```

---

## 2. Template Intent & Design Philosophy

### Intent
This template is designed for:
- Cafés and coffee shops
- Local brunch spots
- Bakeries with seating
- Casual food & beverage brands

### Primary Goals
- Communicate ambience and vibe
- Present menu and highlights clearly
- Drive walk-ins, directions, and inquiries
- Build local trust and familiarity

### Design Philosophy
- Warm, inviting, and human
- Ambience-first, menu-second
- Familiar local-business patterns

⚠️ **AI DESIGN RULE**  
Do NOT introduce aggressive sales UI, popups, ecommerce carts, or SaaS-style layouts unless explicitly requested.

---

## 3. File & Folder Authority (SOURCE OF TRUTH)

```md
/
├── index.html                 # Primary landing page
├── cafe/
│   ├── standalone.html        # Optional alternate layout
│   ├── css/
│   │   ├── style.css          # Core styles (READ-ONLY)
│   │   └── custom.css         # Overrides (READ-ONLY)
├── vendor/                    # Third-party libraries (NEVER EDIT)
├── assets/                    # Food, interior, exterior images
```

### Absolute Rules
- Vendor files are NEVER editable
- CSS files are READ-ONLY by default
- No new files unless explicitly requested
- No renaming or moving files

---

## 4. Global Change Control Rules (CRITICAL)

### CSS Rules
```md
- style.css and custom.css are READ-ONLY by default
- AI MUST NOT modify CSS unless explicitly instructed
- Vendor CSS is NEVER editable
```

### Image Rules
```md
Images are READ-ONLY by default.

Images MAY be edited or replaced ONLY if:
- The user names the specific image (food, interior, exterior), OR
- The user provides a direct image URL
```

### Section Rules
```md
Sections are IMMUTABLE by default.

AI MUST NOT add, remove, reorder, or merge sections
unless the user explicitly names the section.
```

---

## 5. Default AI Assumptions

```md
- HTML structure unchanged
- CSS unchanged
- Images unchanged
- Sections unchanged
- Only TEXT content is editable
```

---

## 6. Section Navigation Map

```md
1. Header / Navigation
2. Hero (Cafe Identity & Vibe)
3. About the Cafe
4. Menu Highlights
5. Full Menu (optional)
6. Gallery (Food & Space)
7. Testimonials / Reviews
8. Location, Hours & Map
9. Contact / Visit CTA
10. Footer
```

---

## 7. Section-Level Contract (Example)

```md
Section: Menu Highlights

Editable:
- Item names
- Descriptions
- Prices
- Dietary notes

Locked:
- Grid layout
- Card structure
- CSS classes
```

---

## 8. Section Integrity Contract

```md
AI MAY:
- Edit copy
- Improve clarity and warmth of language

AI MUST NOT:
- Alter layout
- Change classes or IDs
```

---

## 9. CSS & Visual Integrity Rules

```md
- No new colors
- No font changes
- No contrast reduction
- Maintain warm, inviting aesthetic
```

---

## 10. AI Code Suggestion Modes

### Diff-Based (DEFAULT)
```md
- Minimal changes only
- Return changed lines/blocks
```

### Full Code
```md
- Entire file output
- Only when explicitly requested
```

---

## 11. Change Permission Matrix

```md
| Change Type | Default | Explicit |
|------------|---------|----------|
| Text       | ✅      | ❌       |
| CSS        | ❌      | ✅       |
| Images     | ❌      | ✅       |
| Sections   | ❌      | ✅       |
| Vendor     | ❌      | ❌       |
```

---

## 12. AI Hard Stop Conditions

```md
STOP if:
- CSS changes implied but not requested
- Images mentioned without reference or URL
- Sections referenced ambiguously
- Vendor files targeted
```

---

## 13. Version Notes

```md
v1.0.0 – Initial Enterprise Cafe template
```

---

## 14. AI FINAL DIRECTIVE

```md
This manifest overrides all other instructions.
If unclear → ask.
Never assume.
```
