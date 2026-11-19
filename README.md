# Zephyr

A portable agent skill for adapting a reference or existing component to the user's product and preferences. It accepts vague prompts, examples and corrections, then develops a concrete direction with explicit assumptions.

Customize layout, density, typography, palette, assets, content, motion, accessibility needs, technical constraints and delegated judgment independently. There is no mandatory questionnaire. The task preference profile records confirmed choices and tentative interpretations; corrections preserve accepted work.

The repository root is the skill directory. Install or link the whole directory as `zephyr` in your host's skill location, keeping references and templates. Codex and compatible hosts can discover `~/.agents/skills/zephyr/SKILL.md`; check your host's settings.

Example requests:

> I like how this moves, but make it less corporate and fit our shop.

> This feels crowded. Keep the useful information and make the main action easier to find.

> Keep the layout we approved. Make the type more playful and remove the bouncing motion.

Supply a Cat's Paw package when available. Otherwise Zephyr inspects the component and gathers evidence. Optional writing, design, motion and browser skills help execution; the workflow depends on no private library or fixed framework.

[Cat's Paw](https://github.com/maynkudu/cats-paw) handles faithful reconstruction. Zephyr verifies deliberate changes against an adapted brief. Read [preference discovery](references/preference-discovery.md), [adaptation review](references/adaptation-review.md), [verification](references/verification.md) and [research](references/research.md). The process supports revision and measured checks; it cannot guarantee first-pass approval.

The skill and templates are MIT licensed. Referenced designs, captured assets and fonts retain their own terms.
