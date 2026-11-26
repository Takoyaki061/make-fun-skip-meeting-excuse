# The Funniest Excuse for Skipping a Meeting

[![make.fun](https://make.fun/badge/u-mfnakmal-the-funniest-excuse-for-skipping-a-meeting-5cecf163.svg)](https://make.fun/bounty/u-mfnakmal-the-funniest-excuse-for-skipping-a-meeting-5cecf163)
[![rank](https://make.fun/badge/u-mfnakmal-the-funniest-excuse-for-skipping-a-meeting-5cecf163/Takoyaki061/make-fun-skip-meeting-excuse/rank.svg)](https://make.fun/bounty/u-mfnakmal-the-funniest-excuse-for-skipping-a-meeting-5cecf163)
[![reward](https://make.fun/badge/u-mfnakmal-the-funniest-excuse-for-skipping-a-meeting-5cecf163/Takoyaki061/make-fun-skip-meeting-excuse/reward.svg)](https://make.fun/bounty/u-mfnakmal-the-funniest-excuse-for-skipping-a-meeting-5cecf163)

An entry for the [The Funniest Excuse for Skipping a Meeting](https://make.fun/bounty/u-mfnakmal-the-funniest-excuse-for-skipping-a-meeting-5cecf163) bounty on make.fun: one razor-sharp line, at most 200 characters, that gets you out of a pointless meeting, judged head-to-head against other excuses.

## The excuse

`main.py` writes this to `/output/entry.txt`:

> Declining — I'm saving my energy for the follow-up meeting where we'll decide what this one was supposed to decide.

The joke is a recursion: the meeting being skipped exists only to be followed by another meeting that will do the deciding the first one was supposed to do. Every office worker has lived exactly that loop — the follow-up that re-litigates the meeting it followed up on — so the laugh arrives with a nod of recognition, and the turn lands in the final clause: "what this one was supposed to decide" reframes the skipped meeting as the pointless one, not the excuse. No wifi, no cat, no dentist — the angle is the meeting's own futility, turned back on itself.

## How it works

`main.py` (stdlib only, deterministic) holds the excuse as a constant, checks it against the kit's gate — 1 to 200 characters, a single line, not only whitespace — and only then writes it to `/output/entry.txt`. An excuse that would fail the sealed scorer fails loudly here instead.

## Run it

```sh
python3 main.py
cat /output/entry.txt
```
