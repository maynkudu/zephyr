---
name: zephyr
description: Adapt a reference or existing component into an original product design shaped by the user's preferences. Use for "make it our own", removing generic AI UI, redesigning copied components, vague visual feedback, or translating a Cat's Paw package into a distinct design. Accept plain language, examples and corrections without requiring design vocabulary. Exact reproduction belongs to Cat's Paw.
---

# Zephyr

Make the component belong to its product. Preserve the behavior that helps people and deliberately redesign what communicates identity. Changing colors or renaming classes is not a complete adaptation.

## 1. Understand what the component must do

Read the whole component, styles, state owners and important call sites before editing. Inspect the running product and reference. Accept a Cat's Paw package when available; use its verified behavior and provenance without treating hypotheses as facts. If there is no package, capture enough of the source to explain the behavior you intend to preserve.

Establish audience, task, content, destination system, fixed constraints and permitted changes. Read [preference discovery](references/preference-discovery.md) before interpreting informal or ambiguous feedback, and use its preference profile for substantial adaptation. Accept fragments, spelling mistakes, mixed languages, contradictory examples and "I don't know". The user supplies intent, not a technical specification.

If the user asked a question, answer it without editing. If exact fidelity was requested, use Cat's Paw; switch only when adaptation is authorized. Follow host planning and approval requirements. Completion: a brief names the product need, preserved behavior, confirmed preferences, tentative interpretations and open design choices.

## 2. Diagnose the actual design

Use [the adaptation review](references/adaptation-review.md). Name concrete problems in the actual component and link each to a user task or observed failure. Separate defects from optional preferences. Inspect hierarchy, composition, content density, type, assets, controls, feedback, responsiveness, motion and accessibility.

Study relevant original works and the incumbent design system. Select references for specific mechanisms or relationships, record what each changes, and read reusable component source. Prefer one developed direction. Assess it against this user's profile; a generic minimal style is not the default definition of good design. Completion: every proposed change has a reason, a scope and a way to assess it.

## 3. Design the transformation

Write a transformation table using [the brief template](templates/adaptation-brief.md). For each area, say what remains, what changes and why. Rework composition, information hierarchy, typography, assets, material treatment or motion only where the product calls for it. Originality is judged from the resulting work, not a fixed count of changed properties.

Use the project's tokens and component conventions. Preserve explicit user constraints. Under maynkudu's rules, use spacing and typography instead of unrequested visible borders; keep keyboard focus visible, use useful labels, omit decorative numbering and redundant explanatory copy, and avoid northeast arrows. Elsewhere follow that host's requirements rather than imposing personal preferences universally. Keep the existing icon system for narrow changes.

Use installed writing, design and motion skills when relevant, including `unslop`, `aryan-voice`, `frontend-design` and `animation-fundamentals`. If unavailable, apply the substantive checks in this package; name any missing capability needed for the task. Do not invent tool calls or depend on a private library.

Develop the hardest representative state with actual content and assets in an isolated preview before expanding. State the interpretation in ordinary words and let the rendered example carry the decision. Offer at most two targeted alternatives when a consequential preference remains unresolved. For open creative decisions, present that preview through the host's review workflow. Completion: the proposed component demonstrates its primary task, demanding state and user-specific direction.

## 4. Implement within the approved scope

Build composed components with explicit state and one owner per animated property. Preserve useful interactions, data contracts and keyboard semantics. Replace copied branding and content with material appropriate to the product. Preserve attribution and asset/font license requirements; redesign does not remove provenance or grant reuse rights.

Handle loading, empty, error, disabled and success states where applicable. Use real content lengths, actionable errors and honest progress. Choose reflow from content requirements and measured space. Give motion an explicit input, driver, origin, direction and interruption policy. Provide an operable reduced-motion path. Completion: all changed states function in the host and remain within the agreed transformation table.

## 5. Verify and deliver

Follow [verification](references/verification.md). Compare the original, proposed direction and actual result at matched states and sizes. Test preserved behavior, changed behavior, keyboard/focus, interruption, reduced motion, overflow and console errors. Check final words in context. Inspect the result against the brief and fix demonstrated defects within scope.

When feedback arrives, use the correction loop in preference discovery. Keep accepted choices and change the specific rejected relationship; investigate when "still wrong" signals a mistaken interpretation. Deliver the adapted source, a concise transformation record, preference profile, provenance, runtime evidence and remaining gaps. Keep the Cat's Paw source baseline intact. Automated checks establish their measured properties; human review establishes acceptance of the design.
