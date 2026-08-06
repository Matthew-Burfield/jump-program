# Reactive Profile Assessment (RPA)

A one-session battery that identifies **which quality is actually limiting your
vertical** — reactive/elastic, eccentric/absorption, propulsive/concentric, or
approach conversion. Run it twice: once now (week 20 deload) and once fresh at the
end of the taper.

---

## The central idea

**The diagnosis lives in the ratios, not the absolute numbers.**

You can't diagnose a limiter from a single jump height. A 24" CMJ tells you nothing
about *why* it's 24". But the *relationships between* a squat jump, a countermovement
jump, a drop jump and a continuous hop tell you exactly which link in the chain is
short — and those relationships hold even when every absolute number is depressed.

That matters right now, because you believe your vertical is at its lowest of the
year. It probably is. Five months of Phase 0–4 is a long accumulation block with
almost no expression work in it, and feeling flat at the end of one is the expected
shape rather than a failure signal. But "expected" isn't "guaranteed" — an
accumulation block *creates* potential, the realisation phases *convert* it, and how
much converts depends on whether the quality you've been training is the one actually
holding you back. This battery answers that before you spend the last eight weeks
finding out empirically.

### One honest caveat about testing while fatigued

Fatigue is **not** ratio-neutral. Reactive and elastic qualities degrade faster under
accumulated fatigue than concentric ones do. So a battery run in a fatigued state is
biased toward making you look *more* reactive-deficient than you are — which is
precisely the false positive you're at risk of confirming.

This is why the protocol is two tests, not one, and why the pair is the actual
experiment:

- **Ratios the same fatigued and fresh** → it's a true structural profile. Train it.
- **Reactive ratios recover disproportionately when fresh** → it was fatigue masking,
  and your Phase 4 block was doing its job.

Run the deload test as a baseline you can compare against, not as a verdict.

---

## Equipment

- **My Jump Lab** (240 fps, drop-jump / RSI mode if your version has it)
- **Phone tripod or fixed mount** — handheld will not survive a 10-week comparison
- **Boxes at 30 cm and 45 cm.** Measure them with a tape; do not trust the printed
  height. Box height accuracy *is* the drop-height curve.
- Backboard with a marked reference for the approach jump
- Tape to mark the floor: phone position, jump position, approach start

---

## Pre-conditions (all of them, or the data is noise)

| | Rule |
|---|---|
| Recovery | ≥48 h from any lower-body lifting; 72 h preferred |
| Timing | Same time of day (±1 h) as the retest |
| Bodyweight | Recorded morning, fasted, that same day |
| Shoes | Same pair both tests — write down which |
| Surface | Hard and non-compliant. Not sand, not a soft rubber mat |
| Camera | Same phone, same mount height, same distance, same frame rate. Mark the floor |
| Caffeine | Same or none. Don't caffeinate one test and not the other |
| Warm-up | The scripted one below, timed, identical both times |

**The single biggest source of bad data:** flight-time measurement inflates jump
height if you tuck your legs on landing. Land with legs extended, in the same body
position you took off in, every rep. Review the video if a number looks surprising.

---

## Warm-up (15 min, scripted)

1. Copenhagen planks — 2 × 20 s per side *(non-negotiable, groin history)*
2. 5 min easy bike or skip rope
3. Ankle mobility: wall knee-to-wall × 10/side · calf raises 2 × 12 slow
4. Hip activation: glute bridges × 15 · lateral band walks × 10/side
5. 20 low pogos, submaximal — ankles only
6. 3 submaximal CMJs at ~70%, then 2 at ~85%
7. 2 min quiet rest before Test 1

---

## The battery

Order matters: least fatiguing and most technique-sensitive first; the squat jump
must come before any countermovement jump so it isn't potentiated. Approach jumps go
last because they're the outcome measure, not a diagnostic input.

### Test 1 — Squat Jump (SJ) · 3 reps · 45 s rest

Hands on hips throughout. Descend to ~90° knee angle, **hold completely still for 3
seconds**, then jump maximally with no re-dip.

> Any visible countermovement voids the rep — redo it. This is the hardest test to
> execute honestly and the most important, because it's the denominator for
> everything below. Film it and check.

**Record:** best height (cm)

### Test 2 — CMJ, hands on hips · 3 reps · 45 s rest

Self-selected depth, continuous, maximal.

**Record:** best height. Also countermovement depth and time-to-takeoff if the app
gives them.

### Test 3 — CMJ with arm swing · 3 reps · 45 s rest

**Record:** best height.

> Check which variant your Apex CNS primer reads use and note it. Whichever it is,
> this is the number that compares to your 24" baseline — don't mix the two.

### Test 4 — Drop-and-stick screen, 30 cm · 3 reps

**A safety gate, not a metric.** Step off (don't jump off), land in an athletic
quarter-squat, freeze for 3 seconds.

**Fail conditions:** heel slamming, knee valgus, a second hop to catch balance, ankle
collapse, any sharp patellar or Achilles sensation.

> **If this fails, stop the drop-jump portion entirely.** That failure is itself a
> finding — absorption-limited — and loading higher drops on top of it is the exact
> mechanism that took out Brent's Achilles: rebounding volume introduced when
> under-prepared, on accumulated posterior-chain fatigue. You are 99.5 kg and Phase 5
> hasn't introduced step-off boxes yet, so you have no recent reactive exposure.

### Test 5 — Drop Jumps, 30 cm then 45 cm · 3 reps each · 90 s between reps, 2 min between heights

Step off the box (do not jump off or step *down*). On contact, minimise ground time
and jump for maximum height. Hands on hips.

**Record per height:** jump height · ground contact time (ms) · RSI

**Bail rules — do not proceed to 60 cm if either fires:**
- 45 cm height is more than ~5% below 30 cm height
- Ground contact time exceeds 300 ms at 45 cm

60 cm is optional and only worth doing if 45 cm was clean *and* RSI was still rising.

### Test 6 — Continuous pogo hops (stiffness test) · 2 × 10 reps · 2 min rest

Legs near-straight, ankles only, hands on hips, continuous, minimum contact, maximum
height. This is the "stiffness hop" from the podcast — the one Brent scored 1.87 on.

**Record:** discard the first 2 reps, take the mean RSI of reps 3–10 from the better
set.

### Test 7 — Approach Jump · 3 attempts · 2 min rest

Your standard approach. **Mark and record the run-in distance** and keep it identical
at retest.

**Record:** touch height, then convert → jump height = touch − 251 cm standing reach.

---

**Total:** ~35 valid jumps, ~60 min including warm-up. This *replaces* the week 20
jump session — it does not get added to one.

---

## Deriving the metrics

Pick **one** RSI formula and never switch:

```
RSI = jump height (m) ÷ ground contact time (s)     ← use this one; the bands below assume it
RSI = flight time (s) ÷ ground contact time (s)     ← different scale entirely, ~2× higher
```

| Metric | Formula |
|---|---|
| **PSAP** (pre-stretch augmentation %) | `(CMJ_akimbo − SJ) ÷ SJ × 100` |
| **Arm contribution** | `CMJ_arms − CMJ_akimbo` |
| **DJ:CMJ ratio** | `best DJ height ÷ CMJ_akimbo height` |
| **Drop-height response** | DJ height at 45 cm vs 30 cm — rising / flat / falling |
| **Optimal drop height** | whichever height produced the best RSI |
| **Conversion gap** | `approach jump height − CMJ_arms height` |

### Interpretation bands

| Metric | Reading |
|---|---|
| **PSAP** | `<5%` no usable SSC · `5–10%` typical trained · `>10%` good elastic contribution |
| **DJ:CMJ** | `<0.95` can't tolerate the eccentric load · `0.95–1.05` neutral · `>1.05` genuinely reactive |
| **RSI @ 30 cm** | `<1.5` poor · `1.5–2.0` moderate · `2.0–2.5` good · `>2.5` strong |
| **GCT @ 30 cm** | `>300 ms` not a reactive jump at all — a slow CMJ off a box · `200–300 ms` typical for a big athlete · `<200 ms` genuinely stiff |
| **Conversion gap** | `<3"` conversion deficit · `6–10"+` what a reactive jumper converts |

> **Norms caveat.** These bands are for orientation, not certification. Phone
> flight-time methods read high against force plates, and the 3.7–4.0 RSI figures
> quoted in the podcast were almost certainly a different device and protocol. Do not
> compare your numbers to theirs. Compare them to *your own retest*.
>
> **PSAP trap:** a high PSAP can mean a strong CMJ *or* a weak SJ. Cross-check the SJ
> against your squat before reading a high PSAP as good news.

---

## Decision tree — what each signature means for Phase 5/6

| Signature | Diagnosis | What it implies |
|---|---|---|
| Low PSAP · DJ < CMJ · falling curve · long GCT | **Reactive / elastic deficit** — the one you suspect | Phase 5/6 plyometrics are the right medicine. Also argues for carrying one supramaximal eccentric set per week through Phase 5 rather than dropping Phase 4's work cleanly. |
| PSAP acceptable · curve falls hard · GCT balloons with drop height | **Eccentric / absorption deficit** — Brent's profile | Supramaximal eccentrics and drop-and-stick landings *before* depth jumps. Do not walk straight into Phase 6 volume. Ben's note: this profile responds fast once addressed. |
| SJ low relative to squat · PSAP high · long GCT everywhere · decent heights | **Propulsive / concentric deficit** | The strength emphasis was correct. Phase 5 bar velocity is where it cashes in. |
| Battery broadly fine · conversion gap still `<3"` | **Conversion / skill deficit** | Approach mechanics — penultimate step, plant, arm timing. Coaching, not physiology. The cheapest inches available. |

You may well be more than one of these. Rank them by how far each metric sits outside
its band, and let that ordering drive where Phase 5/6 emphasis goes.

---

## Scheduling

| Test | When | Why |
|---|---|---|
| **RPA-1** | **Week 20 (3–9 Aug) — Phase 4 deload** | Volume is already halved and the jump session is authored as warm-up only. Substitute this battery for it. Last clean window before Phase 5 changes the stimulus. |
| **RPA-2** | **End of Phase 6 / taper, fresh** | The real diagnosis *and* the year's outcome test. |
| RPA-1.5 *(optional)* | Week 24 deload, end of Phase 5 | Only if you want a mid-check. Three batteries in eight weeks starts turning testing into training — two is enough. |

---

## Logging

Apex's `MaxEffortJumpLog` takes an arbitrary `jumpType` string plus `heightCm`,
`attemptNumber` and `notes`, so the heights log natively as ad-hoc jump movements:

```
sj · cmj-akimbo · cmj-arms · dj-30 · dj-45 · pogo · approach
```

**Gap:** there is no structured home for ground contact time or RSI — the schema has
no `contactTimeMs` column. For now put them in `notes` as `GCT=243ms RSI=1.82` and
keep the computed summary in this repo alongside the protocol. If the RPA becomes a
recurring fixture rather than a two-off, that column is worth adding to Apex.

---

## Before you test — one free sanity check

Your CNS primer reads are already in Apex for every gated session this year. Pull that
series and look at the CMJ trend before test day. It costs nothing and it tells you
whether your vertical is genuinely at its lowest — or whether it's flat and you're
reading fatigue as decline. Those two situations point at different conclusions, and
you'd rather know which one you're in before you interpret the battery.
