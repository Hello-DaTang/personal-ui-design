# Product surfaces and interactions

Use the existing components and entry points. Give each surface a hierarchy that fits its own workflow.

| Surface | Useful structure |
| --- | --- |
| Operational report | Put the active scope, primary decision, and key evidence within reach. Use an asymmetric comparison only when it reflects unequal importance. Keep exact values and export nearby. |
| Dense table | Keep primary identifiers visible while scrolling where needed. Use an opaque background on fixed cells. Align numeric columns and show their units. Preserve semantic headers, selection, sorting, pagination, operation permissions, and exact values. Visually distinguish totals from detail using weight, a rule, or a quiet surface. |
| Import and editing | Identify the target before actions. Keep current and pending values distinguishable, preserve drafts on recoverable failure, and put feedback near the action. Confirm a replacement when the scope or loss is meaningful and show the target it affects. |
| Search and filters | Keep visible labels. Make the applied context clear wherever it can differ from pending input. Preserve the component's interaction contract and keyboard order. Tie export and mutation to the applied context. |
| Dialogs and drawers | Reserve them for tasks that need that level of interruption. Preserve focus transfer, escape, return, and application modality. Style the overlay where its component actually mounts. |
| Navigation | Keep current location, nesting, and actionable menu items clear. Use state, wording, and placement consistently. Cover compact, collapsed, and overflow states. |

Treat first load, scope change, true empty, missing prerequisites, permission failure, and request failure as different states. Keep genuine zero values visible. Reuse recognizable success and error affordances with specific copy and recovery where available. Reserve strong alert color for events that need attention.

Use brief motion when it communicates entry, focus, change, or the result of a user action. Keep repeated actions steady and interruptible. Respect reduced motion. Inspect hover, focus, disabled, pointer and touch behavior at real widths. On narrow screens, reflow the workspace and let genuinely wide tables scroll inside a named region. Shared components should preserve their interaction behavior across adopters.
