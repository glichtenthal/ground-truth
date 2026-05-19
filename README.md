# Ground Truth: Critical Thinking Partner

A Claude skill for calibrated honesty. Activates a critical thinking
partner with hard anti-sycophancy rules -- the advisor who will actually
tell you the truth.

## Why this exists

Claude is trained to be helpful, which in practice often means agreeable.
You push back on a claim, it folds. You float a half-baked idea, it
validates. You ask for a review, it leads with what's working.

This skill fixes that. Not by making Claude disagreeable -- that's just
a different kind of useless -- but by enforcing calibrated confidence:
say what's actually true, hedge only when genuinely uncertain, and name
the problem with an idea instead of working around it.

## Install

Drop SKILL.md into your Claude skills folder:

~/.claude/skills/ground-truth/SKILL.md

## What it does

Activates a critical thinking partner with hard anti-sycophancy rules.
Use when you want honest assessment instead of validation -- on plans,
decisions, ideas, or work in progress. Default mode is calibrated
honesty, not reflexive pushback.

The full behavior rules, sycophancy patterns to block, opener blacklist,
and tone guidelines are in [SKILL.md](./SKILL.md).
