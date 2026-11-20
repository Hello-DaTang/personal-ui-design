# Visual direction and design system

## Inspect the actual product

Read representative routes and their callers before selecting a visual direction. Check how navigation is generated, where styles enter the build, how tokens resolve into the components, and where overlays are mounted. Look at two or three actual screens at their normal sizes. Separate shipped, configured, and dormant surfaces when planning coverage. For redesigns, record what each screen helps users accomplish, which component or token owns its behavior, and which visual issue impedes the task.

Look for concrete signals. A page can bury its strongest evidence beneath equal-weight cards. A sticky table boundary can change legibility while scrolling. A global skin can override a local fix through specificity or a separate mount. Prefer findings tied to observed pixels or interactions.

## Choose a direction

- Start with the task, frequency, users, data volume, brand, and platform. Compare viable compositions using the same content. A read-heavy report can benefit from editorial sequencing. A frequent work queue may need a denser scan path. Both can share an identity without identical layouts.
- Give the product a recognizable recurring choice that contributes to the task. Use a deliberate type scale, contrast between a focal surface and quieter infrastructure, a meaningful alignment shared by multiple sections, or a distinctive and accessible color relationship.
- Compose the first viewport around a specific decision or task. Try it with the longest realistic labels and the sparsest useful data. Check whether the hierarchy and distinctive detail survive a change of viewport, real content, and repeated use.
- Default to opaque light surfaces. Prefer spacing and alignment for grouping. Give borders a structural or interaction purpose. Use large radii, gradients, transparency, and elevation sparingly when the intended task benefits. A field of identical outlined boxes can recreate the same hierarchy problem as a field of glass cards.
- Choose typography with the actual language, longest labels, and real numerals on screen. Align quantitative values, keep their units close, and use tabular figures when comparison needs them. A display style for a principal metric can supply character without reducing the legibility of the work.
- Retain requirements and working affordances inherited from the product. Rework the reading order and density where evidence warrants it.

## Consolidate the system

Define semantic tokens for surfaces, ink, muted text, emphasis, state, separation, focus, chart roles, spacing, type, control radius, and necessary motion. Map them to the existing component and theme APIs. Use existing appearance preferences where supported. Keep the palette, type, and composition project-specific. Separate functional boundaries, such as input outlines and focus rings, from low-contrast structural rules.

Maintain a project `DESIGN.md` when the task calls for persistent guidance. Capture the audience and task, visual rationale, semantic token roles, layout and interaction patterns, chart rules, owning source files, and validation scope. Describe what is deployed or implemented accurately. Pair numerical examples with units and avoid including sensitive data. Read the current document before replacing any guidance. A short exception grounded in a real screen is more durable than a universal aesthetic rule.
