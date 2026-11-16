# Pump Roulette

A workout fundraiser. Spin the slot machine: one reel picks an exercise, the other picks your reps. One slot on the reps reel is **To Failure**. The page is a single vertical screen, built to screen-record on a phone.

## How to play

1. Open the page and press **SPIN**.
2. Do the exercise for the number of reps shown. If it lands on **To Failure**, keep going until you cannot do another clean rep.
3. Spin again.

## Setup tab

- **Exercises:** tap the exercises you want, 4 to 6. Tap again to remove one. Type a name under the list to add your own.
- **Reps:** set the lowest and highest rep count (1 to 100, default 10 to 25) and turn the To Failure slot on or off.
- **Reset to defaults:** puts everything back to the starting exercises and rep range.

Setup saves in each browser, so it only affects the device you change it on. Record from the Play tab.

## Changing the defaults

Open `index.html` and edit the `CONFIG` block at the top of the script:

- `exercises`: the exercises selected at the start.
- `morePool`: other exercises shown as options in Setup.
- `minReps` and `maxReps`: the starting rep range.
- `failure`: `true` adds the To Failure slot.
- `credit`: an optional line shown under the machine, such as a handle or campaign name.

## Variations and weighted reps

Low rep counts are easy, so make them harder. Pick a rule before you start and stick to it. For example, treat the bottom third of your range (10 to 14 on the default range) as a bonus round:

- **Add weight:** hold a dumbbell or kettlebell, wear a weighted vest or backpack, or use a heavier load than usual.
- **Slow the tempo:** 3 seconds down, 1 second pause, then up.
- **Use a harder variation:**
  - Push-ups: feet elevated, or add a clap.
  - Squats: goblet squats or jump squats.
  - Lunges: walking lunges while holding weights.
  - Burpees: add a tuck jump or a push-up.
  - Kettlebell swings: use a heavier bell, or swing one-handed.

You can also add a bonus to a low spin, such as a second set or a 30-second plank, and double the reps on a high spin if you're feeling strong. Pick the rules in advance and tell your viewers, so the challenge stays fair.
