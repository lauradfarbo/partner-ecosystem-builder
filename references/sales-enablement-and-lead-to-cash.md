# Partner Sales Enablement and Lead-to-Cash Design

## Sales enablement assets

Partner-facing sales assets fail for one of two reasons: they're too generic to actually help a partner rep sell (a copy-paste of the client's own internal deck with "partner" stamped on it), or they're too detailed to actually get used (a 40-page document a partner rep never opens before a call). Build for the second failure mode by default; it's the more common one.

### Partner-facing sales brief

One to two pages, built to be read in under five minutes before a call. Structure:

- What the product does, in the language the partner's buyer uses, not the client's internal language.
- The specific problem this solves for the partner's typical customer, stated as a problem, not a feature list.
- Three or four common objections and a short, direct response to each.
- Pricing and packaging basics the partner needs to set expectations, without necessarily needing full pricing authority.
- A single next step: how to register a deal, who to contact for support, where to find more.

### Battle card

Built when the partner is likely to hear the client's product compared to a specific competitor. Structure:

- One line on when the client's product wins and one line on when it doesn't. Honesty here builds more partner trust than a card that claims to win every comparison.
- Three or four specific differentiators, each with a concrete reason it matters to the buyer, not just a feature name.
- Two or three questions the partner can ask the buyer that surface the client's strengths naturally, rather than leading with a direct competitive attack.

### Solution brief

Used when the partner's audience needs a slightly deeper technical or use-case explanation than the one-pager sales brief covers, often relevant for technology/integration partners or for a specific vertical use case a reseller sells into. Structure:

- The use case, described from the buyer's side (what they were trying to do, what wasn't working).
- How the client's product, alone or combined with the partner's product, solves it.
- A short proof point if one exists (a metric, a named or anonymized customer result).

### Keeping assets current

Enablement assets go stale fast, especially around pricing and positioning. Set an explicit review cadence (quarterly is reasonable for most early-stage clients) and assign it to a specific owner. An audit that finds enablement assets referencing an old price point or a retired feature is one of the most common findings in a stalled-program diagnostic; see `audit-and-blueprint-framework.md`.

## Deal registration and attribution

Deal registration exists to answer two questions cleanly: who gets credit for a deal, and how much. Without it, "partner pipeline" is a set of anecdotes.

### Two categories, tracked separately

**Partner-sourced.** The partner brought the opportunity; the first real conversation happened because of the partner's introduction. This earns the full commission or credit rate.

**Partner-influenced.** The client's own team found the opportunity, but the partner materially helped move it (joined a call, gave a reference, provided technical validation). This earns a reduced rate, commonly around half the sourced rate, though the exact split should reflect the client's own economics rather than a borrowed number.

Report these two categories separately, always. Blending them into a single "partner revenue" number hides which motion is actually doing the work.

### Registration rules that hold up

- First-in registration wins, within a defined protection window (90 days is a common default for referral and co-sell motions; reseller motions often run longer windows tied to the sales cycle, see `reseller-and-hardware-motion.md`).
- Registration has to reflect active involvement, not just familiarity ("I know someone there" is not a registered deal).
- Tag attribution in the CRM at the point of origin, not retroactively reconstructed once a deal is about to close. Retroactive tagging is where attribution trust breaks down between partner and client teams.
- Build a conflict resolution rule before the first conflict happens: when both direct sales and a partner are independently working the same account, decide in advance (based on registration timestamp, relationship depth, or an agreed split) rather than negotiating it deal by deal under time pressure.

### The lead-to-cash process, end to end

Map this explicitly for any client past the earliest informal-referral stage, because gaps here are where partner-sourced pipeline quietly disappears:

1. **Lead capture.** How does a partner actually submit a lead or register a deal (a form, a CRM object, an email to a shared inbox). The simpler this step, the more it actually gets used.
2. **Routing.** Who receives it, and how fast. A lead that sits unrouted for a week damages the partner relationship as much as a lost deal does.
3. **Qualification.** Does the client's own qualification process treat a partner-sourced lead any differently than an inbound lead, and should it (partner-sourced leads often arrive with more context and can sometimes skip early qualification steps).
4. **Progression and visibility.** Can the partner see where their registered deal stands, even at a basic level (registered, in progress, closed). A partner with no visibility into deal status stops trusting the registration process within a quarter or two.
5. **Close and payout.** How commission or credit gets calculated, confirmed, and paid, and how fast. Slow or unclear payout is one of the fastest ways to lose an otherwise productive partner.
6. **Post-close attribution reporting.** Does the sourced/influenced split actually make it into whatever reporting leadership looks at, or does it get lost between the CRM and the dashboard.

A client with no CRM sophistication yet can still run a version of this with a shared spreadsheet and a defined weekly check, as long as every one of these six steps has an actual owner and an actual mechanism. The tooling matters less than whether each step has both.
