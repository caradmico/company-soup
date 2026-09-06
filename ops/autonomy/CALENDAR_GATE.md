# Evening calendar gate

**Why:** Cara’s time is the scarce resource. When something truly needs her (MFA, money, brand lock, real decision), book **one** evening calendar event in `America/New_York`. Do not replace that with chat ping storms.

## When to gate

Use a calendar event only if one of these is true:

1. **MFA** — login or tool needs 2FA only she can complete  
2. **Money** — spend / refund / invoice / budget above standing HOLD  
3. **Brand** — public copy or visual that locks a door  
4. **Decision** — irreducible go/no-go she alone owns  

Everything else stays in the mill (maker → looker → KEEP/FAIL). Kevin looks once. No empty back-and-forth.

## How

1. Write the ask in one line + artifact URL.  
2. Create a short evening event (about 15 minutes) from `calendar-gate.json` template.  
3. Do **not** commit OAuth secrets or calendar credentials to git. Wire the calendar tool outside the repo.  
4. After she acts, close the gate — don’t re-nag.

Machine-readable: [`calendar-gate.json`](./calendar-gate.json)
