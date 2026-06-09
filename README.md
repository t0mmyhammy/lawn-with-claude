# Lawn With Claude

I fired my lawn care company. Then I hired myself.

This is the repo behind that. It turns a year of homeowner education into one
document, written for your specific yard: a season-long calendar, a shopping
list split by store, the right products by active ingredient, and a watering and
mowing plan. The thinking is on the AI. The doing stays on you. Nobody here drags
the bag or sprays the edges.

I am not an agronomist. I am a homeowner with two young kids who wanted control
over what goes on the grass and got tired of a bill that never quite added up. A
$25 soil test, some photos, and a couple of hours with Claude and ChatGPT
replaced a service I had paid for years.

## Two ways to use it

**1. Just run it (no setup).**
Open [`prompt.md`](prompt.md), copy it into Claude or ChatGPT, and answer the
questions. You will get a plan built for your zone, grass type, and stores in one
sitting. That is the whole thing.

**2. Fork it (gets smarter every year).**
Clone this repo. Fill in [`inputs/profile.template.md`](inputs/profile.template.md)
once, and keep a short [`inputs/history.template.md`](inputs/history.template.md)
log of what you applied and what happened. Next season, feed the history back in
and the plan sharpens. Year two is where this compounds.

## How it works

1. **Test.** Start with a $25 mail-in or home soil test so the fertilizer plan is
   based on data, not guesses. (Bonus: in some states, including Michigan, you
   legally cannot apply phosphorus without a soil test showing you need it.)
2. **Context.** Feed in your photos, your zone and grass type, your prior
   applications, and where the sun and wet spots are. The plan is only as good as
   what it knows about your yard.
3. **Plan.** The AI returns a seasonal calendar, a shopping list grouped by store,
   products named by active ingredient, and the right sequence for pre-emergent,
   fertilizer, overseeding, and water.
4. **Do.** You kneel in the dirt, drag the bag, spray the edges, and fix the
   sprinkler head. The leverage is in the judgment, not the labor.

## What's in here

| File | What it is |
|------|------------|
| [`SKILL.md`](SKILL.md) | A Claude skill. Drop it in your skills folder and it runs the interview for you. |
| [`prompt.md`](prompt.md) | The same logic as a plain copy-paste prompt, for anyone not using Claude skills. |
| [`inputs/`](inputs/) | Blank intake and history templates to fork and keep. |
| [`examples/`](examples/) | A fully worked plan (zone 6a, Kentucky bluegrass) so you can see what good looks like. |

## A word of caution

This is a starting point, not professional turf advice. Read every product label,
follow the rates and re-entry intervals, mind pets and pollinators, and check
your local rules on fertilizer and herbicide. Your lawn, your call.

## License

MIT. Use it, fork it, no warranty on your grass. See [`LICENSE`](LICENSE).

---

*Built by Tom Hamilton. If this is useful, the next thing worth asking is: what
else in your life could you fire and replace with AI plus yourself?*
