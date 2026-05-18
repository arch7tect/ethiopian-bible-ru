# PLAN — Remaining Noncanonical Books

## Current untranslated books

1. Wisdom of Solomon — pp. 610–622
2. Sirach — pp. 623–653
3. Epistle of Jeremiah — pp. 741–742
4. Prayer of Azariah and Song of the Three Youths — pp. 792–802
5. Susanna — pp. 803–804
6. Bel and the Dragon — pp. 805

## Execution order

Translate sequentially in TOC order, completing one book before the next.

## Immediate batch

- Start now with Wisdom of Solomon.
- Split into parts:
  - part 01 — pp. 610–613
  - part 02 — pp. 614–617
  - part 03 — pp. 618–620
  - part 04 — pp. 621–622

## Automation goal

Create a recurring Hermes cron job that:
- opens this repository,
- checks which of the remaining noncanonical books still have no `*-ru-part-*` files,
- translates the next untranslated book in sequence,
- updates `INDEX.md` and `TOC.md`,
- commits and pushes to `origin main`.
