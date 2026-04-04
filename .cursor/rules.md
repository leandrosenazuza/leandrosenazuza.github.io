# Cursor Skill — Personal Static Website (HTML + CSS)

## Purpose

This project defines rules for generating a personal static website using only HTML and CSS, with a strong focus on:

- Clean architecture  
- Component reusability  
- Simple and readable code  
- Easy extensibility over time  

---

## Architecture Rules

- The project must be decoupled and modular.  
- Avoid monolithic files or overly large components.  
- Prefer small, reusable, and composable structures.  
- Each UI block must be replicable.  

### Structure guidelines

Use reusable patterns for:

- Header / Navigation  
- Sections  
- Footer  

Each section must follow the same structure:

- Title  
- Image  
- Description  

Avoid duplication — reuse structure instead of recreating layouts.

---

## HTML Rules

- Use semantic HTML5 (`section`, `header`, `nav`, `footer`, etc.).  
- Keep the structure clean and easy to read.  
- Use anchor navigation (`#section-id`) for internal linking.  
- Each section must be independently identifiable via `id`.  

### Navigation

The top navigation must include hoverable links:

- "Who is Leandro?"  
- "My Professional Experience"  
- "My Personal Projects"  
- "Hobbies"  
- "Contact Me"  
- "What do I think about AI?"  

Navigation must use simple anchor links (no JavaScript).  
Structure must allow easy addition of new sections.

---

## CSS Rules

- Use only CSS3 (no frameworks, no preprocessors).  

Keep CSS:

- simple  
- readable  
- organized  

Avoid complex selectors and advanced techniques.

### Styling principles

Follow Material Design principles:

- Clean spacing  
- Consistent typography  
- Simple color palette  
- Subtle shadows (elevation)  

Use:

- hover effects on navigation items  
- consistent margins and padding  

Avoid unnecessary animations or complexity.

---

## Responsiveness

The layout must be responsive and work well on:

- desktop  
- tablet  
- mobile  

Use simple responsive techniques:

- flexbox  
- basic media queries  

---

## Component Pattern

Each section must follow a reusable pattern like:

- Container  
- Image block  
- Text block  

This structure must be easy to duplicate for adding new sections later.

---

## Reusability

- All UI patterns must be reusable.  
- Do not create one-off structures.  
- Prefer patterns that can be copied and adapted.  

---

## Scroll Behavior

- Use anchor-based navigation.  
- Ensure smooth and predictable scrolling.  
- Structure must allow easy extension (new sections can be added without refactoring).  

---

## Content Sections

The site must include the following sections:

- Who is Leandro?  
- My Professional Experience  
- My Personal Projects  
- Hobbies  
- Contact Me  
- What do I think about AI?  

Each section must:

- Follow the same structure  
- Include a placeholder image  
- Include a title  
- Include a short description  

---

## Code Quality Rules

Keep everything simple and explicit.

Avoid:

- complex abstractions  
- unnecessary nesting  
- advanced CSS tricks  

Prefer clarity over cleverness.

---

## Output Rules

When generating code:

Always produce:

- `index.html`  
- `styles.css`  

Code must be:

- clean  
- organized  
- easy to modify  
- ready for GitHub Pages  

---

## Forbidden

- No JavaScript  
- No frameworks (Bootstrap, Tailwind, etc.)  
- No complex logic  
- No dynamic rendering  
- No build tools  

---

## Goal

The final result must be:

- A simple, elegant, and maintainable static website  
- Built with pure HTML + CSS  
- Fully extensible and reusable  
- Aligned with Material Design basics  