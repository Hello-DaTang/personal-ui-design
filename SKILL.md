---
name: personal-ui-design
description: Design, implement, or visually review distinctive product UI and data visualizations. Use for page layout, UI/UX redesign, design systems, and chart work when the visual experience matters. Skip changes limited to backend behavior, data plumbing, or infrastructure.
---

# Personal UI Design

Default to a light visual system. Design an additional dark theme when the brief or a product requirement calls for one. The user's current direction takes precedence. Preserve the product's supported appearance settings. Aim for a distinctive first impression through typesetting, composition, proportion, and purposeful color, with the legibility and density needed for repeated work.

1. **Read the product in use.** Inspect the existing design notes, routes and roles, rendered screens, component primitives, and data contracts. Identify the frequent tasks, decisions, and failure states. Use the actual stack and data shape as evidence.
2. **Establish a visual point of view.** Choose a recurring visual decision grounded in the work, such as a shared alignment between filters, chart dates, and table columns. Make the first important fact or action visible early. Give frequently compared content a consistent position. Use the same principles across the product while adapting palette, typography, and structure to this project.
3. **Build with existing mechanisms.** Reuse mature components and the live APIs. Align shared tokens and primitives before applying targeted layout changes. Preserve data definitions, entry points, permissions, and action semantics. Extract patterns supported by multiple real uses.
4. **Judge the rendered result.** Compare representative real states in a browser, including interaction and narrow layouts. Revise concrete problems from the rendered evidence. For a project redesign, reconcile `DESIGN.md` with the inspected implementation and document any material gap.

Read only the references needed for the assignment.

- [Visual direction and design system](references/design-system.md) for audits, style exploration, tokens, and `DESIGN.md`.
- [Product surfaces and interactions](references/app-surfaces.md) for operational layouts, tables, forms, overlays, states, and motion.
- [Data visualization](references/data-visualization.md) for selecting, styling, and checking charts against the data.
- [Rendered review and rollout](references/render-review.md) for visual iteration, migration, and functional verification.

Use available specialist skills when they fill a gap. Impeccable can support interface critique, Taste Skill can support composition exploration for suitable surfaces, Tufte Data Viz can review encoding, and Data to Viz can help choose a chart. Keep the project brief authoritative and satisfy applicable licenses before incorporating third-party material. These are optional capabilities.
