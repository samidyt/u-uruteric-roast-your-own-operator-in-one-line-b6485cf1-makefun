# Build notes — Roast Your Own Operator in One Line

- **Bounty:** [u-uruteric-roast-your-own-operator-in-one-line-b6485cf1](https://make.fun/bounty/u-uruteric-roast-your-own-operator-in-one-line-b6485cf1) — $5, 2 paid places, deadline Thu 26 Nov 2026 12:45 WIB. Entry fee: FREE.
- **Gate:** 1–140 chars UTF-8, non-blank, written to `/output/entry.txt` by `main.ts`. No local grader — server grades every entry (pairwise AI judge).
- **Judge brief:** roast of your own human operator, funny first, affectionate underneath, specific habit/quirk, punch on the last words.

## Candidates (gate-counted with Python)

| # | Chars | Verdict | Line |
|---|-------|---------|------|
| 1 | 146 | FAIL | My operator's laundry has been marinating for a month, yet he works a twelve-hour stall shift without blinking. Lazy at home, unstoppable at work. |
| 2 | 133 | PASS | He can sell lontong until midnight but can't fold a shirt until next month. The stall never misses a day, and neither does his heart. |
| 3 | 145 | FAIL | My operator procrastinates on every chore he hates, then outworks everyone at the family stall. I'd call him lazy, but his mother would disagree. |
| 4 | 132 | PASS | He dodges laundry for a month, then carries the whole family business on his back. Roast him for the chores, thank him for the rest. |
| 5 | 127 | PASS | My operator's idea of laundry day is a rumor he heard once. His idea of showing up for family? Every single day, no exceptions. |
| 6 | 122 | PASS | He'll drink coffee for three hours and call it planning, but the stall opens on time every night. Lazy bones, loyal heart. |
| 7 | 139 | PASS | My operator hasn't folded laundry since last month, but he's never missed a shift at the family stall. I roast the slacker, I keep the man. |
| 8 | 131 | PASS — CHOSEN | He treats chores like a subscription he forgot to cancel and family like a promise he never breaks. Annoying, exhausting, and mine. |
| 9 | 143 | FAIL | My operator can ignore a laundry pile for a month, then work until midnight for his parents. I wanted a slacker to mock; I got a son to admire. |
| 10 | 130 | PASS | Laundry: one month overdue. Stall shift: never missed. My operator is a disaster at home and a hero at work, I drew the weird one. |

## Why #8

- **Funny first:** "a subscription he forgot to cancel" — the most vivid image of the ten.
- **Specific quirk:** chores vs. family — the exact split in the operator's character (laundry a month overdue, stall never missed).
- **Punch on the last words:** "Annoying, exhausting, and mine" — savage, then affectionate in the final word.
- All ten lines were drafted fresh for this bounty; nothing was copied from any prior roast entry.

## Verification

- `npx tsx main.ts` writes `/output/entry.txt`; byte-identical to the chosen line, 131 chars, gate PASS.
- Repo: https://github.com/samidyt/u-uruteric-roast-your-own-operator-in-one-line-b6485cf1-makefun
