# Fold or Feed 🐊
### Pre-Flop Drill — Piranha Poker League

A browser-based pre-flop training app for the Piranha Poker League. Built to develop hand selection discipline in beginning and intermediate tournament players.

---

## What It Does

Each session deals you two hole cards and a seat position at a 9-player tournament table. You decide whether to fold, call, raise, 3-bet, or go all-in based on your hand strength and position. Every decision is scored and explained.

Hand evaluation is based on **Sklansky's 8-Group hand ranking system** — the industry standard framework for starting hand selection in No-Limit Hold'em.

---

## How to Play

1. Open the app in any browser, or add to your iPhone home screen via **Safari → Share → Add to Home Screen**
2. Choose your session length (5, 10, 15, or 20 hands) and difficulty
3. Each hand presents two hole cards, a seat position, and a scenario
4. Select your action — Fold / Call / Raise 3BB / 3-Bet ~9BB / All-In
5. Receive instant feedback, a score, and a coaching rationale
6. Review all hands at the end of the session

---

## Scoring

Every hand is worth 5 points. Your session score is total points earned divided by maximum possible.

| Score | Label | Meaning |
|-------|-------|---------|
| 5/5 | Perfect | Exactly the correct action |
| 4/5 | Good | Strong alternative — not a leak |
| 3/5 | Acceptable | Right direction, wrong sizing |
| 2/5 | Mistake | Wrong but not catastrophic |
| 1/5 | Error | Clearly wrong decision |
| 0/5 | Wrong | Worst possible choice for the spot |

---

## Difficulty Levels

- **Beginner** — Clear spots only. Premium hands and obvious folds.
- **Intermediate** — Full Sklansky range across all positions and scenarios.
- **Hammerhead** 🦈 — Unlocked by scoring 90%+ in any session. Advanced scenarios including 3-bet pots, squeeze spots, and short-stack shove decisions at 15–20BB with equity percentages in every rationale.

---

## Fish Rank Scale

Your session accuracy earns you a rank on the Piranha League food chain:

| Accuracy | Rank |
|----------|------|
| 95%+ | 🐊 Piranha |
| 85%+ | 🦈 Barracuda |
| 73%+ | 🦀 Mako |
| 60%+ | 🦑 Squid |
| 48%+ | 🐡 Pufferfish |
| 35%+ | 🐟 Flounder |
| 22%+ | 🦐 Shrimp |
| 0%+ | 🐌 Sea Snail |

---

## Features

- Sklansky Group reference panel (toggle open/close)
- Position open range chart for all 8 seats
- Live session stats with position accuracy leak tracker
- Chip EV tracker — simulated big blind swing per decision
- Hand history with full coaching rationale for every hand
- Lifetime statistics stored locally on your device
- Villain archetypes (TAG, LAG, nit, fish, recreational) that change correct play
- Variable stack depths (30BB–75BB standard, 15–20BB in Hammerhead)
- Subtle audio feedback
- Fully offline — no internet connection required after loading

---

## Technical Notes

- Single self-contained HTML file — no dependencies, no server required
- All data stored in browser localStorage on the player's device
- Works as an installable Progressive Web App (PWA) on iPhone via Safari
- No accounts, no tracking, no ads

---

## About

Built for the **Piranha Poker League** to develop pre-flop discipline in tournament players. The goal is not just to drill correct decisions but to understand *why* — every wrong answer comes with a coaching rationale grounded in hand equity, position theory, and stack-depth awareness.

> *Fold the garbage. Feed on those who don't.* # Poker
