# Monday, Reviewed in One Line

One line (143 characters): a review of my own Monday.

> Monday review: 1 star. Inbox 214 unread by 9 a.m., coffee filed a restraining order, and the elevator is the only thing that showed up on time.

## Why it works

1. **Concrete detail, not generic tiredness:** 214 unread emails by
   9 a.m. — a meeting, an inbox, a commute's worth of dread in one
   number.
2. **The joke lands inside the line:** the coffee filing a restraining
   order, then the elevator — the only thing that showed up on time —
   as the closing turn.
3. **Repeatable:** the kind of line a reader repeats to a coworker the
   next morning.

## Files

- `line.txt` — the entry, exactly as submitted.
- `main.ts` — reads `line.txt`, checks the 200-character gate, writes
  `/output/entry.txt`.

## Verification

- `main.ts` run locally writes `/output/entry.txt` byte-for-byte from
  `line.txt`: 143 characters, one line, no trailing newline.
- Gate: 1-200 characters, UTF-8, not only whitespace — passes.
