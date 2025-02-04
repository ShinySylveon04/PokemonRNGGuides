---
title: 'Egg RNG Guide without Masuda and/or Shiny Charm'
description: 'RNG for eggs without using Masuda Method and without the Shiny Charm'
slug: 'retail-sm-egg-no-mmsc'
subCategory: 'Custom Firmware'
---

## How is this different than using the Masuda Method and/or Shiny Charm?

When using the Masuda Method and/or Shiny Charm, the ESVs of every egg are already set in a predetermined order that will not change. The only way to reach the frames you want is to accept and/or reject however many eggs it takes to reach those frames. However, without using the Masuda Method and without having the Shiny Charm, the ESVs are not generated until the moment you accept the egg. This means ANY egg frame can be ANY ESV you want it to be.

```Note: ESV is short for Egg Shiny Value. This is what determines if an egg will hatch shiny or not.
If an ESV matches a TSV (Trainer Shiny Value) then the egg will hatch shiny.
```

## Tools

## Tools

- A 3DS with PCalc ([PCalc Install Guide](https://www.pokemonrng.com/misc-3ds-installing-pcalc))
- [3DSRNGTool](https://github.com/wwwwwwzx/3DSRNGTool/releases)

## Step 1: Set Up 3DSRNGTool

### In the upper right of 3DSRNGTool:

1. Input your game version and your TSV.

   - With PCalc, you can find your TSV by pressing `Start + Up` to bring up the Game View window. Your TSV is listed by where it says `YOUR TSV`.

2. Input the initial seed. You can find this by pressing `Start + Up` to bring up the Game View window. The initial seed is found where it says `Init Seed:`.
3. The "Shiny Charm" box must be unchecked. If you have the Shiny Charm you cannot use this method.

```
If you are wanting to RNG the egg to have a specific ESV that is not yours, click on "Edit TSV List" and input the TSV(s).

Do not input the TSV in the upper right. YOUR TSV must be used in the upper right or else the RNG will be incorrect.
```

### For parents information:

- Fill it out according to the parents you are using.
  - Make sure the "Masuda Method" box is not checked. If the parents are of different languages you cannot use this method.
  - Double check that the parents are of the same language. Checking this now will save you from wasting time later.

```
Note: The region of the Pokemon does not affect anything, it is only the language of the Pokemon that matters for Masuda Method.
```

If using a Ditto and genderless Pokemon, the Ditto will be the female.
Otherwise, the Ditto will be the opposite gender of the other parent.

Note about breeding for Rockruff:

- If its ability is Own Tempo, then the ability can either be 1, 2, or H, it won’t make a difference.
- If its ability is not Own Tempo then its abilities are [1] Keen Eye, [2] Vital Spirit, or [H] Steadfast.

### For current status

1. For the "Current Status" section in 3DSRNGTool input the current egg seeds of your game.

   - Using PCalc, press `Start + Down` in-game to bring up the egg seed window and input them into 3DSRNGTool.

2. Do not check the "Main RNG Egg (PID)" box. We will be doing this later.

3. For "Filters", input the info for the egg you are wanting.

4. Do not check the "Shiny Only" box even if you are wanting a shiny egg. The ESV of the egg will be RNG'd separately.

5. Input "0" as the starting frame.

6. Click "Calculate".

## Step 2: Finding a Target Frame

You can choose any of the given frames, but lower frames are generally better due to less egg accepts/rejects.

1. Right click on the row for the one you want and click "Set as Target Frame".

2. Click on "Shortest Path" and "Calculate".

   - This will automatically calculate the shortest path for the least number of accepts and rejects for your target egg.

3. Accept and/or reject the eggs in the order given from top to bottom. Doing the accepts and/or rejects out of order will result in the wrong egg seeds.

   - The very last egg you are going to accept will be your target egg. Do NOT accept this egg!

4. Once you are to your target egg seeds, continue with the rest of the guide.

```
With PCalc you can check which egg frame you are on by looking at your egg seeds in-game (Start + Down to bring up the menu).
```

## Step 3: RNGing the ESV of the Egg

1. Once you have the egg you want to be shiny ready to pick up from the daycare helper, save the game in case you mess up and need to start over for the next part.

2. Stand directly in front of the daycare helper and start the dialogue to accept the egg.

   - Standing off to the side may cause NPCs to fluctuate when making a timeline.

3. When you get to the choice of “Yes” or “No”, press `Start + Up` to bring up the Game View window in-game, and then pause the game (`Start + Select`).

   - If the Game View window is already open, close and open it again when at the "Yes" or "No" selection to reset NPC counter.

4. Follow the steps below to create a timeline to obtain the ESV you want.

   - Check the "Main RNG Egg (PID)" box in 3DSRNGTool under "Current Status".
   - Afterward, reset "Filters" by clicking on the gear icon.
   - Then follow the [timeline guide](https://www.pokemonrng.com/retail-usum-timeline) to create a timeline.
   - Creating a timeline is necessary to know what frames you can actually land on due to NPC influence on frames.

5. After making a timeline you can now search for a target frame that you are able to land on.

   - If you are wanting to RNG the egg to have a specific ESV that is not yours, click on "Edit TSV List", input TSV(s), and check the "Other TSVs Shiny" box.
   - Check the "Shiny Only" box.
   - Then "Calculate" to find frames that will give the ESV(s) you want.
   - Choose any of the blue highlighted frames (lower frames are better because of less waiting time).

6. Advance to that frame and when you land on it, Press `A` to accept egg.

Congrats! You should now have the egg you wanted with the TSV you RNG’d for. If not, you can reset the game if you saved before picking up the egg and try again.

```
Tip: You can use PCalc to check the egg's info. Press Start + Left to bring up Party View and then Select + Right to cycle through the different slots.
```
