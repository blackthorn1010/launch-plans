# TRADEBOOK — ULTIMATE LAUNCH PLAN
Locked 8–9 September 2026 from blackthorn1010/launch-plans (plans 1–6).
Owner: TJ Standridge · Cleveland / Birmingham, AL
Product facts stay in docs/TRADEBOOK.md. This file is GTM only.
Revised 9 Sep 2026 per tradebook `docs/CHANGES-2026-09-09.md` — targeting,
sequencing, scoreboard and kill gates now follow `docs/ULTIMATE-v2-TARGETING.md`;
credentialing follows `docs/CREDENTIALING.md`; build backlog in `docs/RETENTION-SPEC.md`
and `docs/YEAR-END-AND-FORMS.md`. MONEY, BRAND SPLIT, HARD GATES, the sit-down
script, CHANNELS, WHAT WE THREW AWAY and YEAR 1 MONEY are unchanged.


THE ONE RULE
One city where 3 homes can post and 4 vendors can fill beats 30 accounts
across the corridor with nothing that pairs.
Capability first. Density second. Ads third. App Store last.
TradeBook is the overflow book for the night the usual guy does not answer.
It is not Uber for funerals, not a Red Book clone, not a Standridge lead desk.

POSITION
Corridor overflow layer for first-call work.
Removals are the liquidity pitch (the 2 a.m. pain).
Equipment is the sit-down wedge (you are already in the room).
Trade embalming is second.
All categories live at launch — removal/transport, trade embalming,
cemetery services (open/close, vault setting, monument setting, grounds),
vault supply and delivery, crematory, equipment. A cemetery both posts
work and fills it: one account is two-sided density in one signature,
and its work is daylight and plannable, so the board is not dead at noon.
No category is held back on the roster.

SUCCESS IS
- Week 3: at least one REAL (non-demo) job posted by someone who is not you
- Week 4: 4–6 sit-downs done · 1–3 real corridor awards (fee-waived)
- Week 8: still running ONLY if ≥ 8 real awards total
- Week 12: 8–12 homes have posted · 6–8 vendors have bid · 5–10 awards
  happening without you in the room
- Year 1: 80–150 corridor accounts · 40–80 paying seats · $1.5–3k MRR
  Death Care Repair still pays the bills
- 1,000 users is a 24–36 month chapter, not a 2026 promise

SUCCESS IS NOT
App Store rank. TikTok. A national list. 100 empty accounts.
Mixing brands so vendors think this is Standridge’s lead desk.

---

## MONEY (LOCKED — DO NOT REWRITE)

Seats
- Home $29/mo or $290/yr
- Vendor $29/mo or $290/yr
- First-10 sit-down homes: 90-day comp. Do not invoice day 15 into an empty book.
- Vendors: bid free until first win or 90 days, then founding $149 yr 1
  (first 25, hard cap, corridor first) or $290
- Priority +$29: hidden until a city has 3 vendors in one specialty
- After corridor is green: seats turn on for everyone not already comped/founding

Job fee
- Awards 1–10 in the corridor: $0 book fee (launch subsidy). Still record the award on the book.
- Award 11+: 10% of the BID, ON TOP. Min $15. Max $150.
  $400 bid → home pays $440, vendor keeps $400, book keeps $40
- Handshake “we’ll settle direct” only AFTER a first Pay-on-TradeBook charge.
  Does not refund the book fee. Do not sell it as the free way.
- Contacts stay hidden until Pay-on-TradeBook succeeds or both parties
  explicitly handshake after that first paid job.

Why this mix
Dual seats are the P&L. Job fees are proof the book is alive.
Taxing job #1 is why a director calls Joe instead.
Homes-free-forever deletes the P&L. Handshake-from-day-1 punches a hole
in contacts-hidden-until-pay. Neither survives.

---

## BRAND SPLIT (NON-NEGOTIABLE)

Public board / PWA / homepage     TradeBook
Tagline                           The live book for funeral trade work
Footer / support                  hello@tradebook.co · support@tradebook.co
Repair company                    Standridge / Death Care Repair
                                  Separate site, ads, phone, X
Gumroad kits                      Service Ops. Not on tradebook.co
In-app forms                      TradeBook's — unbranded, job-attached,
                                  no Service Ops mark, no Standridge mark,
                                  no Gumroad link, no cross-sell.
TJ on the book                    Equipment-tech vendor. Homepage silent.

Never put Standridge, Death Care Repair, mechanic45, or
office@deathcarerepair.com on a TradeBook surface.
Never use (205) 681-9122 as the TradeBook number.
Service Ops keeps selling the standalone kits on Gumroad to people who are
not on the book. The kits are not moving into TradeBook; what you know about
these forms builds TradeBook's own document layer. Different product,
different buyer.

Voice: director on the phone. Trade work, first call, award, bid.
Never “AI-powered,” “revolutionize,” or “mortuary marketplace” as the H1.

Recuse-or-publish: resolved — PUBLISH. Phase 1 is an equipment award
(home posts a down Portiboy, you bid it, week one), so recusal would
delete Phase 1. Write the founder-vendor disclosure, put it on vendor
signup and in the terms, and pair it with sealed bids enforced
server-side and a named third party — not you — who decides any
dispute on a job you bid. Disclosed up front it is normal; discovered
later by the founding 25 it is unrecoverable.

---

## HARD GATES
No live card. No AFDA. No ads. No App Store. No TradeBook GBP.
Until these are done.

Payment / legal
[ ] C1–C4 + H1 closed (double checkout, stale Checkout after award,
    auto-release vs no-show, charge.refunded reverses Connect)
[ ] D14 live Stripe keys + price IDs
[ ] D16 public business name TradeBook (not Standridge)
[ ] D18 webhooks: checkout.session.completed, payment_intent.succeeded,
    charge.refunded, account.updated
[ ] DEMO_ACCOUNTS_ENABLED=false. Demo rows off the public board.
    Sit-downs use a sandbox / staff demo, not a live-looking fake job.
[ ] Delete-account visible in Settings. Privacy + terms on the same
    origin the PWA loads.
[ ] Terms match the shipped book: fee $0 on awards 1–10 then fee-on-top,
    handshake after first paid job, no escrow of remains, no workmanship
    guarantee, not a funeral director, not a carrier.
[ ] Grok chat stays off the public site until a locked prompt cannot
    invent fee / handshake policy.

This week — human
[ ] Quo (OpenPhone) 205 or 256. Name on the line: TradeBook.
    If KYC lags, temp SMS labeled TradeBook. Sit-downs still run.
    Never forward to 681-9122.
[ ] Confirm hello@ and support@ land in an inbox you check.
[ ] Waitlist down the morning sit-downs start. CTA → app.tradebook.co
[ ] Add to Home Screen works on a real iPhone and a real Android.
    Winner sees the words “Awarded to you.”
[ ] TJ vendor account complete in TEST. Redo Connect on live keys.
[ ] Comp First-10 homes 90 days.
[ ] Hide Priority +$29. Hide or flag empty-city posts.
[ ] Confirm Stateline still runs removals. Name #10 from a person
    you have stood next to, or drop the line. Do not invent.
[ ] Google Search Console on tradebook.co and app.tradebook.co.
[ ] Do NOT create a TradeBook Google Business Profile yet.

Published hours (only after Quo is live)
Voice 7 a.m.–7 p.m. CT weekdays, Saturday 8–12.
SMS intake 24/7, human reply in published hours.
If you cannot cover 7–7, publish 9–5 and answer late anyway.

Live answer
“TradeBook, this is TJ. Are you posting work or bidding?”
Then stop talking.
If they want a repair truck:
“That’s a repair call. The shop line is 205-681-9122. This line is the book.”

---

## FIRST 10 — REPLACED BY CAPABILITY SCORING (9 Sep)
There are no confirmed homes and no confirmed vendors. The v1 roster was
a candidate list read as a commitment. No name enters a script until a
human verifies it. Do not invent. Elmwood (Dignity) and Jefferson Memorial
are off the sit-down list; they sit on the notify-when-live list below.
SCI / Dignity / Ridout locations are repair customers, not book customers.

Sourcing pass first (~3 hours, free): Alabama Board licensee lists by
county; 90-day obituary counts per home as the case-volume proxy; corporate
filter; removal operators by county, cross-checked with who the homes name
in sit-downs and every operator you have seen in a prep room on a DCR call.

Home scoring — score 25, contact the top 12. 0–2 each:
  Case volume (90-day obits)   2 = 25–60 (≈100–250/yr)   0 = under 10, or 100+
  Ownership                    2 = independent, 1–2 sites 0 = SCI / Dignity / group
  Staffing depth               2 = no FT embalmer or night driver   0 = full crew + fleet
  Cremation mix                2 = cremation-heavy       0 = traditional w/ staff embalmer
  Access                       2 = you have been in the building on a repair call
  Geography                    2 = Birmingham metro      0 = outside tier 1
Sweet spot: high volume, thin staff. ~40 cases has no overflow habit;
400+ has its own vans. Both extremes score zero on purpose.

Vendor scoring — score 20, contact the top 12. Removal/transport first,
trade embalmers in parallel. 0–2 each, coverage scored first:
  Coverage        2 = 24/7 dispatch, answers at 2 a.m.   0 = business hours
  Capacity        2 = 2+ vehicles or 2-man crew          0 = one person, one van
  Credentials     2 = insurance in force, licensing attested   0 = can't produce
  Existing trade  2 = already runs removals for other homes   0 = never worked trade
  Range           2 = Jefferson + one adjacent county    0 = single city
  Response        2 = returns a call inside 2 hours      0 = doesn't call back
A vendor who cannot answer at 2 a.m. cannot serve the overflow pitch.

Geography tiers — work strictly top-down:
  1  Birmingham / Jefferson (~6,500–7,500 deaths/yr) — everything starts here.
  2  Huntsville / Madison (~3,818) — opens only on 3 real Birmingham awards,
     2+ bids per job, and 3 vendors who have bid and lost. Not a date.
  3  Montgomery — later.
  —  Jasper / Cullman / Walker — deprioritized; dropoffs on a Birmingham
     job, do not recruit there.

SIT-DOWN — 10 minutes — say the job is fake out loud
1. They open app.tradebook.co. They are the facility. You are the vendor.
2. They post: removal / transport · pickup Birmingham · dropoff Jasper
   · needed tonight · note “call 15 minutes out.”
3. You bid price + ETA + on-site as ONE offer. Not price alone.
4. They click Award this bid. The app must not pick cheapest.
5. You refresh. Winner must see “Awarded to you.”
6. Stop. No card. No App Store speech.
   Ask: “Would you post a real first call the same way?”
7. If yes: comp 90 days. Put the icon on their home screen.

Vendor sit-down (#9): reverse the chairs. Then ask them to tell two homes
“post it so I see it. I am done missing your voicemail.”

PASS: fake job posted, one bid with price+ETA+method, human award,
winner sees Awarded to you.
FAIL: they think cheapest won; winner only sees generic Awarded;
you took a live payment; you pitched six job types.

Concierge close after a PASS
“Next first call, post it. If nobody bids in four hours I find you
one myself, and we still record the award on the book.”

---

## TWO SIDES AT ONCE — THE PAIRING RULE (replaces TWO LISTS)

Density is counted in matched pairs — a home that can post and a vendor
who can fill it, same city, same week — not in accounts.

Never let one side get more than 2 net ahead in a city.
  4 homes, 2 vendors → stop sit-downs, spend the week on vendor calls.
  4 vendors, 2 homes → stop recruiting, book sit-downs.

Weekly cadence, Birmingham only, weeks 1–8:
  2 home sit-downs (in person, on repair days)
  6 vendor calls (phone, from the truck), aiming at 2 that go somewhere
  Every home sit-down ends: “When you farm one out now, who do you call?”
  Every vendor call ends: “Which homes do you already run for?”
  That is how the list builds itself.

Liquidity roster (founding 25): corridor removals and embalmers first,
cemetery and vault seats open from day one. Slot 1 = Standridge Death
Care Repair, equipment tech, disclosed (see BRAND SPLIT). Stateline is a
candidate, not an anchor — CONFIRM before any script says their name.

Bootstrap, unchanged: until a city has 3 removal vendors, you are the
fallback vendor on equipment. Concierge promise: bid in 4 hours during
published hours; overnight posts get a bid by 8 a.m. or a phone call.

B. Notify-when-live (warm DCR relationships — do NOT burn a founding slot)
Doric of Tennessee (Cowan, TN)
Nichols Burial Service (Fayette, AL)
Cantrell’s Sales LLC (Birmingham, AL) — brand-clean pitch only when equipment goes live
Champion Rogers Vault (Pine Mountain, GA)
Lindley Vaults (Douglasville, GA)
Heritage Cremations (Elizabethton, TN)
Gravitas Transport (Grovetown, GA)
Elmwood Cemetery (Birmingham, AL) — Dignity; script only
Jefferson Memorial Gardens (Birmingham, AL) — shares Currie with #2

Email each: “Your category is not live in your city yet. When it is,
you get a founding slot and I call you first.” Then actually do that.

---

## 12-WEEK SHAPE (revised 9 Sep)

Phase 0 — this week
Payment gates (C1–C4, H1, D14, D16, D18, demo off). Quo line. Founder-
vendor disclosure published; third-party dispute decider named. Sourcing
pass done: 25 homes and 20 vendors scored, top 12 of each with a name, a
person, and a number — all verified, none invented. Call the Alabama
Board on the removal-license question. Settle the Connect account type
with the CPA before any live charge. No live card. No ads.

Phase 1 — weeks 1–4 — Birmingham pairs
Run the weekly cadence. Goal is not accounts; it is 2 matched pairs:
2 homes onboarded who could each post a job that 3+ recruited vendors
could fill. Fee-waived awards. Icon on home screens. The book is still
useful with ONE vendor: TJ on a down machine.
Gate to Phase 2: first real post by someone who is not you.

Phase 2 — weeks 5–8 — first awards without you in the room
Deepen Birmingham to 5–6 homes and 5–6 vendors. Trade embalmers added
once removals are awarding. Three-line forward the day of every real
award. Monday scoreboard. Around week 8 ask ONE home who has actually
used the book to convert early at the annual rate — one yes or one
reasoned no is worth more than ten more comps.

Phase 3 — weeks 9–12 — living book, then Huntsville
Living book = weekly Birmingham awards, 2+ bids per job. Huntsville
opens only on its trigger, the same way: scored list, both sides at
once, pairing rule enforced. Exact-match Google only after 3+ awards in
a week. No second city beyond that, no App Store, no GBP.

TIME SPLIT (waking hours you can give this)
~40% sit-downs and texts
~25% supply (removal / embalmer recruiting)
~15% ops (scoreboard, disputes, Quo)
~20% Death Care Repair (the living)

---

## SCOREBOARD — MONDAY 7:00 A.M. CT (revised 9 Sep)

Pairing health (predicts survival)
Metric                                 Green         Yellow       Red
Matched pairs in tier-1 city           3+            1–2          0
Home:vendor balance                    within 2      3 apart      4+ apart
Vendors who answered at 2 a.m. (tested) 3+           1–2          0
Attested vendors                       all onboarded most         any unattested taking jobs

Award health (unchanged)
Metric                         Green        Yellow       Red
Awards / week in city          5+           2–4          0–1
Bids per open job              3+           1–2          0
Open jobs with 0 bids > 4 h    0 (you fill) 1–2          3+ unfilled
Time to first bid              < 4 h        same day     next day
30-day repeat (homes)          40%+         20–39%       <20%
Fill rate (posted → awarded)   80%+         50–79%       <50%

Leakage (computed, never self-reported)
Repeat-pair share · same-vendor re-post rate · handshake vs Pay-on-TradeBook
share · requested-vendor fallback rate · head-start conversion.
Standing rule: handshake over 40% after award #10 → add record value.
Do not raise the fee.

Counts (do not confuse with health)
Founding slots left (corridor) ≤10          11–20        25 still open
Paid or comped seats corridor  25+          10–24        <10 after week 8
First paid seat (dated)        by week 8    week 9–12    none before the week-12 call
Support first-response         <2 hours     same day     overnight how-to
Demo rows on public board      0            1            any

KILL (revised 9 Sep)
WEEK 2 — supply gate. Fewer than 3 reachable, willing removal vendors in
Birmingham → stop home sit-downs entirely, spend the week on the phone.
A home burned on an unfillable job will not sit down twice.

WEEK 4 — post gate. Zero real posts by anyone but you AND fewer than 10
known outsourcing opportunities across onboarded homes. Get the
denominator: every home texts you when they next farm one out, even if
they don't use the book. Opportunities happened and nobody posted →
product or recall; try SMS-to-post before quitting. Opportunities never
happened → wrong homes; go back to scoring.

WEEK 8 — award gate (unchanged). Fewer than 8 real awards total, OR
never 3 in one week. Stop recruiting. Stop talking about 1,000 users.
Sit with two more directors and watch them post without you in the
room. No ads. No AFDA. No second city.

---

## CHANNELS (RANKED)

1. Prep-room sit-down on a repair call
2. Anchor removal company saying “post it so I see it”
3. Text from a director who just used it
4. Founding-vendor personal ask (corridor only, weeks 1–6)
5. District meeting with that anchor standing next to you
6. AFDA / TFDA / GFDA newsletter AFTER 3 sit-downs + a real screenshot
7. Private Facebook groups — peer tone, no ads-looking posts
8. Exact-match Google AFTER weekly awards
9. Trade press after screenshots with permission
10. Native store listing — icon, not acquisition

FOUNDING VENDOR SMS
Opening TradeBook in the Birmingham–Huntsville corridor. Homes post a
removal, a trade embalming, or a down machine. You bid price + when you
can be there + on-site or mail-in. Home picks. Cheapest does not win by
itself. Your bid is what you keep. First 25 vendors $149 for year one —
bid free until you win. I have corridor slots left. app.tradebook.co

HOME TEXT
When you need a removal and you don’t want to burn three voicemails,
post it on TradeBook. Vendors bid price, arrival, and how they’ll do it.
You award. Nobody auto-picks the cheap one. First homes we sit with
are comped 90 days. app.tradebook.co

ANCHOR REMOVAL ASK (Stateline, if confirmed)
I want homes to post the first call on TradeBook so you see it instead
of missing the voicemail. You bid price + arrival + on-site. They award.
I’ll sit with them. You tell the ones who already use you: post it so
I see it. First year on the vendor side is $149. Bid free until you win.

THREE-LINE FORWARD AFTER A REAL AWARD
Used TradeBook on a [removal / trade embalming / down machine] in [city].
Posted it, saw bids with arrival times, picked who I wanted.
If you want on the book: app.tradebook.co

CANTRELL’S / COMPETING TECH — BRAND-CLEAN ONLY
TradeBook is a live book, not my shop’s lead desk. Homes post work.
Any vendor can bid. I bid equipment as one vendor on the list.
You would too. app.tradebook.co

COLD SCRIPTS — NO ANCHOR, NO REFERRAL (added 9 Sep)
Never promise volume you do not have. A vendor who was oversold does
not answer the second call.

Vendor, cold call
This is TJ Standridge — I work on prep room equipment around Birmingham.
I'm opening a book where homes post removals and trade work and vendors
bid price, arrival time, and how they'll do it. Home picks. Cheapest
doesn't win by itself, and what you bid is what you keep. Bidding is
free until you win. Are you taking trade removals right now, and can
you cover a 2 a.m. two-man call?

Home, cold, in the building on a repair call
While I've got you — when you farm a first call out at night, who do
you call, and how often does it go to voicemail? I built a book for
exactly that. Ten minutes, no card, and I'll show you on your phone.

Vendor, once you have two homes
I've got homes in Birmingham posting overflow. No promises on volume —
it's new. Bidding's free until you win, and the first twenty-five
vendors are $149 for year one. Do you want to see the board?

WHY NOT JUST USE DEATHCALL / MY GUY
Use your guy. Seriously. TradeBook is for the night your guy doesn’t
pick up. DeathCall is a transport company with software — their drivers
are their drivers, they take the margin and pick who goes. We are the
book. You see the price and the ETA before you say yes, and you can
still use the removal service you already like.

WHY NOT RED BOOK
Red Book is a directory. It tells you who exists. It does not tell you
who can be at Cullman by nine tonight and for how much.

---

## WHAT WE THREW AWAY AND WHY

Plan 1 MortisList
Wrong brand, no-code rebuild, Texas/Florida, classifieds and hearses
on day one, 0% fees for life. App already exists. Kept only the
concierge habit and “seed by doing it yourself.”

Plan 5 homes-free-forever + urgent first-accept lane
Homes-free-forever deletes seat revenue. Dual $29 is locked.
Urgent lane is the right product diagnosis for 2 a.m. work and it
is not built. Waiting on an accept-button before sit-downs is how
this dies. Sit-downs run on the live bid + award flow. Urgent lane
is a post-green chapter.

Plan 4 handshake-from-day-1 and grounds-at-launch
Handshake as the free default punches contacts-hidden-until-pay.
Fee $0 on awards 1–10, recorded on the book, is the cleaner subsidy.
Grounds / landscaping waits until a cemetery actually posts it.

Plan 6 50 providers / 100 listings / 100 transactions by December
Correct marketplace textbook. Impossible throughput for one person
between 2 a.m. repair calls. Classifieds stay Phase 2 (~25 paying seats).

Also off the table
Capacitor (Expo already exists). App Store. TradeBook GBP. Ads before
weekly awards. AFDA before 3 sit-downs. Nashville / Atlanta recruiting.
Out-of-corridor founding slots. 1,000 users as a 2026 date.
Standridge on the homepage. Chat-with-Grok on the public site.
A public fake Birmingham → Jasper job sitting on a live board.

---

## YEAR 1 MONEY — HONEST

Stage                 Paying seats         Seat MRR        What it funds
Weeks 1–12            0–15 (most comped)   $0–$400         Quo, domain, Stripe
Year 1 corridor live  40–80                $1,500–$3,000   Closer days + 2027 booth IF green
~400 paying / later   400                  $12–18k         Not a 2026 number

A $400 removal after award #10 = $40 to the book (home paid $440).
Awards 1–10 = $0 book fee on purpose.
Do not spend cash on ads. Spend it on gas to sit-downs.
Death Care Repair remains the living.
