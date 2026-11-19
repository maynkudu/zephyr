# Preference discovery

An incomplete prompt is normal input. Translate it into testable design choices and expose consequential assumptions in a concrete preview. Do not require users to specify fonts, breakpoints, animation engines or design terminology.

## Build a small preference profile

Read the current request, supplied examples, existing product and explicit preferences already in the conversation. For each decision record the user's actual words or reference, your interpretation, scope and confidence. Use four statuses:

- Fixed. An explicit requirement or prohibition applies within its stated scope.
- Confirmed. The user accepted a specific decision or result.
- Tentative. A reasonable interpretation that can be changed cheaply.
- Unknown. A choice that lacks useful evidence.

Useful dimensions include audience, tone, density, hierarchy, composition, type, palette, material, imagery, icons, motion, accessibility needs, device context and implementation constraints. Record only dimensions relevant to the work. Preferences are independent; someone can want dense content, playful illustrations and restrained motion together.

Prioritize explicit current corrections, current confirmed choices, applicable saved preferences, then the incumbent product. Use inspected references and craft defaults for remaining gaps. Higher-priority host requirements and explicit user constraints still apply. Ask a focused question when two explicit requirements conflict materially. Treat examples as evidence about particular traits unless the user requests an exact copy.

Use `templates/preference-profile.md` locally in the task artifacts. Remember preferences for the current task by default. Ask before creating durable user memory or editing standing rules. A prior project's palette is not a universal preference. Do not store inferred personal traits.

## Translate ordinary language

These are hypotheses to test, not a dictionary of fixed meanings:

| User says | Useful first interpretation | Check in the preview |
| --- | --- | --- |
| "Less corporate" | Replace generic stock imagery and formal copy; explore more specific composition | Which exact trait was rejected? Keep useful structure |
| "Premium" or "expensive" | Improve typography, spacing, assets and control consistency | Avoid assuming black/gold, serif type or sparse content |
| "Too much going on" | Clarify competing actions and grouping | Preserve information needed for the task |
| "More fun" or "make it pop" | Strengthen one relevant emphasis, illustration or feedback behavior | Avoid adding motion, saturation and decorations everywhere |
| "Same vibe, but mine" | Identify the liked relationships and redesign product-specific expression | Record what is preserved and what changes |
| "I like this, hate that" | Compare the examples for the specific liked and rejected traits | Do not average every trait into a generic compromise |
| "I don't know, you decide" | Choose a coherent direction from the product and known preferences | Show the demanding representative component with stated assumptions |
| "Smaller", "cleaner", "faster" | Inspect the referent and infer the likely local issue | Clarify size versus density, clutter versus missing content, or latency versus animation duration when it changes implementation |

Infer obvious spelling errors from context. Respond in language the user understands. Preserve their intended names and wording unless editing copy is part of the task. Avoid correcting their terminology unless the distinction affects the result.

## Keep clarification useful

Continue work that does not depend on missing answers. Ask at most one or two concrete questions in a round when the answer changes function, scope, irreversible work or the core visual direction. Prefer recognition over recall: show a relevant contrast or describe an outcome in plain words. Do not hand the user a design questionnaire.

Use a reversible default when the cost of guessing is small. Record the assumption and build the smallest meaningful preview. When the user delegates judgment, make the decision; do not repeatedly return it as a question. Host approval requirements remain in force.

If no examples are supplied, find suitable references yourself. If references conflict, separate what each contributes and propose one resolved direction. A prompt saying "anything" still calls for a product-specific decision and evidence.

## Correct without restarting

1. Locate the element and relationship the feedback addresses. Inspect the current result and existing decisions.
2. Convert the correction into a specific change. "Too floaty" might mean excess vertical space or an underdamped spring; use the relevant evidence before choosing.
3. Keep accepted layout, behavior and content outside that scope. Explain a dependency when changing the rejected detail necessarily changes another part.
4. Update the task preference profile with the correction's actual scope. Show the revised representative state and run affected checks.
5. If feedback repeats, test a different interpretation of the cause. Offer two focused contrasts only when that will resolve the ambiguity.

Keep making useful progress while experiments improve the result. Report missing sources, tools, untestable behavior or unresolved contradictions plainly. The skill promises a concrete, revisable result and honest verification, not mind reading or guaranteed first-pass approval.
