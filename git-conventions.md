# Git conventions for TopDown Project

## 1. Branch naming
feature/topdown-<short-description>   # новая механика
bugfix/topdown-<short-description>    # исправление бага
docs/topdown-<short-description>      # только документация

Пример: feature/topdown-aim-rotation

## 2. Commit format
- Language: English
- Header: <type>(<scope>): <imperative, max 50 chars>
  Types: feat, fix, refactor, docs, style, test, chore
  Scope: camera, input, enemy, ui, inventory, stats, docs
- Body (if needed): blank line, then bullet list:
  - change 1
  - change 2

Пример:
feat(combat): add melee attack with cooldown

- add AttackComponent with timer
- bind to left mouse button
- play slash VFX on hit

## 3. Atomic commits
One commit = one logical change.
If you can say "and also" — split.

## 4. Project focus: TopDown
