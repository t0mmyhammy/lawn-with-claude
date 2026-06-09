---
name: lawn-with-claude
description: >
  Build a personalized, season-long lawn care plan you can execute yourself.
  Interviews you about your location, grass type, goals, and preferences, then
  produces a week-by-week calendar, a shopping list split by store, product
  picks by active ingredient, and a watering and mowing plan. Use when someone
  wants to stop paying a lawn service and do it themselves without becoming an
  agronomist first. Trigger phrases: "build my lawn plan", "fire my lawn
  service", "seasonal lawn schedule", "what should I put on my lawn".
---

# Lawn With Claude

This skill turns a year of homeowner education into one document, written for
your specific yard. The thinking is on Claude. The doing stays on you: nobody
here drags the bag, sprays the edges, or fixes the sprinkler head. What you get
is the judgment you used to pay a service for.

## How to run it

Work through four steps in order. Do not skip the interview. A generic plan is
worthless. The whole value is that this plan is built for one lawn.

### Step 1 — Interview

Ask these questions a few at a time, conversationally. If the person does not
know an answer, give them a fast way to find it (most are one search or one
photo away) and a sensible default so the plan can still be built.

**Location and climate**
- What city, or ZIP code, are you in? (Used to infer USDA hardiness zone, first
  and last frost dates, and the soil-temperature windows that drive timing.)
- Irrigation: in-ground sprinklers, hose and sprinkler, or rain only?

**The lawn itself**
- Roughly how many square feet? (A rough pace-off is fine. It sets product
  quantities and cost.)
- What grass type, if you know it? Cool-season (Kentucky bluegrass, fescue,
  ryegrass) versus warm-season (Bermuda, zoysia, St. Augustine) changes
  everything about timing. If unknown, ask for a close-up photo or describe the
  blades and spread habit and make a best guess, stated as a guess.
- Sun versus shade, and any chronically wet or bare patches?
- What does the lawn look like today? (Thin, weedy, mossy, compacted, fine.)

**Goals and constraints**
- What does "better" mean to you? (Thicker and greener, fewer weeds, kid and
  pet safe, low effort, putting-green obsessive, just not embarrassing.)
- How many hours a month are you actually willing to spend?

**Preferences (ask explicitly, do not assume)**
- Organic, synthetic, or a hybrid program? This is a real fork. Organic is
  slower, gentler, and rebuilds soil; synthetic is faster and cheaper per result
  but is a chemical program. Respect the answer and build the whole plan around
  it.
- Any hard nos? (No glyphosate, no synthetic herbicides, pollinator safe,
  pet safe re-entry times that matter to you.)
- Where do you like to buy? (Big box like Home Depot or Lowes, warehouse like
  Costco, a local nursery or co-op, or online.) Plan around their stores.

**History (this is what makes year two smart)**
- What did you do last year and what happened? Anything you applied, when, and
  the result. If this is year one, say so and we start a clean record.

### Step 2 — Soil test (recommend, do not require)

Before prescribing fertilizer, recommend a soil test. It is the single highest
leverage thing a DIY homeowner can do and most skip it.

- Cheapest path: a mail-in test from the local state university extension lab
  (search "[state] extension soil test"). Usually $15 to $25, far better data
  than a hardware-store probe.
- Faster path: a home test kit for pH and rough NPK to get moving now.
- Explain what the results change: pH dictates whether to lime or add sulfur;
  the nutrient and organic-matter readings dictate the fertilizer program.

If they do not want to test, proceed on regional defaults and flag clearly that
the fertilizer plan is an educated guess until tested.

### Step 3 — Build the plan

Produce one clean document with these sections. Use the person's real numbers,
zone, grass type, and store preferences throughout. Never output a generic
calendar.

1. **Season calendar.** A week-by-week or task-by-task schedule across the
   growing season, anchored to soil temperature and local frost dates, not
   guesswork. Cover, in the right sequence for their grass type: pre-emergent
   timing, fertilization rounds, weed control, overseeding or aeration windows,
   grub or pest watch, and mowing.

2. **Product list by active ingredient.** For each application, name the active
   ingredient and what it does, then give specific products that match their
   organic-versus-synthetic choice and their stores. Always lead with the active
   ingredient so they can substitute confidently if a product is out of stock.

3. **Shopping list, split by store.** Group purchases by where they buy, with
   quantities sized to their square footage and a rough total cost. Note what is
   a one-time buy (spreader, rake) versus consumable.

4. **Local sourcing note.** Where a local nursery or extension co-op beats big
   box (bulk seed, regional grass blends, native or organic amendments), say so.

5. **Watering and mowing plan.** Inches per week and a simple way to measure it,
   timing of day, and the correct mowing height and frequency for their grass
   type. Cutting too short causes half the problems people blame on everything
   else.

6. **What this plan will not do.** Be honest about the labor and the limits. The
   plan is the brain. Kneeling in the dirt is still theirs.

### Step 4 — Save the record for next year

Tell the person to keep this plan and jot what actually happened: dates applied,
weather, results, what the weeds did. Next season, feed that record back in at
Step 1 and the plan gets sharper. Year two is where this compounds.

## Principles

- **Match the program to the preference.** Never quietly push synthetics on
  someone who asked for organic, or vice versa.
- **Active ingredient first, brand second.** Brands change and stock runs out;
  the chemistry does not.
- **Timing beats product.** A mediocre pre-emergent applied at the right soil
  temperature beats a premium one applied late. Anchor everything to local
  conditions.
- **State your guesses as guesses.** When grass type or soil is unknown, say so
  and give the cheap way to remove the doubt.
- **Safety is non-negotiable.** Surface re-entry intervals and pet and pollinator
  cautions whenever a product warrants it.

---

> **Want the full version?** This single file is enough to build a real plan. I
> also keep a broader scaffolding behind it: section-by-section templates,
> curated product links by active ingredient, organic and synthetic variants,
> local-sourcing guides, and a prior-year history format that fine-tunes the plan
> season over season. If enough people want it, I will open-source the whole
> thing. Reach out and say so.
