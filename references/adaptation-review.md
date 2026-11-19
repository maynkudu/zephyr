# Adaptation review

Inspect the actual component before choosing a treatment. Tie criticism to observable content, behavior or product requirements.

| Area | Inspect | Useful adaptation |
| --- | --- | --- |
| Purpose | Can people identify the task and next action? | Reorder content around the actual decision |
| Hierarchy | Competing actions, repeated headings, uniform emphasis | Make emphasis reflect importance and frequency |
| Composition | Width allocation, grouping, whitespace, content density | Fit proportions to content and reading order |
| Typography | Actual font, weights, axes, line length, wrapping | Choose a coherent hierarchy with real font files and fallback metrics |
| Content | Generic promises, decorative labels, fake counts, repeated explanations | Use concrete product content, concise instructions and honest status |
| Controls | Affordance, names, selection, errors, destructive actions | Clarify behavior while preserving appropriate semantics |
| Assets | Branding, stock motifs, mismatched icons, provenance | Use appropriate owned/licensed assets and a consistent drawing system |
| Motion | Input, clock, feedback, interruption, reduced motion | Preserve causal relationships and fit expression to the task |
| Reflow | Long words, narrow containers, zoom, touch, localization | Measure minimum useful sizes and move to an appropriate composition |
| Accessibility | Names, roles, contrast, focus, reading order, keyboard | Use native elements and the relevant APG interaction pattern |

"AI UI" is not a reliable diagnosis. Name the actual defect, such as repeated helper copy, unnecessary badges, indistinguishable actions, arbitrary gradients, poor focus behavior or a hover effect that implies nonexistent interactivity. Any of those treatments can be appropriate when they communicate a real product need.

Adaptation preserves useful mechanisms deliberately. A gallery may retain continuous drag and interruption while changing layout, assets, type and selection presentation. A modal's visual shell may change while its focus containment, Escape handling, accessible title and focus restoration remain.

Originality cannot be certified by a similarity score. Preserve source provenance and attribution as required. A changed palette cannot convert somebody else's font, footage or artwork into an owned asset.

Read the relevant WAI-ARIA APG pattern rather than applying one keyboard model to every control. Modal dialogs, menus, tabs, comboboxes and disclosures have different responsibilities. Automated accessibility checks complement pointer, keyboard and assistive-technology testing; they do not replace those tests.
