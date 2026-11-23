# Chaos Edition Beta 0.5

A Yoshi's Island hack that randomly enables silly gameplay modes (and optionally
randomizes graphics, music and screen exits) as you play.
 Beta: expect bugs,crashes  and unbalanced settings.

## Opening the menu

Hold **L + R + Start** on the title screen, the world map or in a level.

- **Up/Down** select, **A** edit/enter,  **Left/Right** change
  values
- **B** goes back, **Start** exits
- Numbers are hexadecimal. Changes apply at the next LOAD.

## Menu pages

**/PRESETS**
- Unfinished but has a default preset and allows you to save your current settings (saves through resets hopefully)
- More to come?

**/CHALLENGE RUN**
-  Starts a new file with your chosen settings and see how far you can get on
- A run always shuffles modes per stage set by seed
- **RNG SEED**: same seed + same settings should be same every run.
- **Rerolls** allows you to shuffle modes on pause menu
- **Shuffle Stages** reorders what stage order you play - 6-8 last always

**/GENERAL**
- **MODES TOGGLE**: on/off for enabling modes.
- **MODES RANDOM / CHOSEN**: pick randomely from the allowed modes, or use all the modes you chosen.
- **MODES SHUFFLE**: 
Set when modes change: every **AREA**, each map **STAGE**, or on a **TIMER** (frames).
- **MODES MIN/MAX**: how many modes are randomized to be active.
- **DISPLAY MODES**: Shows what modes have just activated - **LIVE** for displaying without pause, **PAUSE** for freezing game and waiting for input (You can always check modes in pause menu)

**/MODES LIST**
- Choose which modes may be used. **ALL MODES** sets every mode on or off. L/R changes page.
- If you chose **CHOSEN** - all the modes you picked will be active, beware...

**/MODE SETTINGS**
- **CROSSFIRE**: an aiming cursor appears then a projectile is shot at you.
  - **PROJECTILE**: what is shot (**EGG** = random egg each shot).
  - **DELAY MIN/MAX**: time between shots. 
  - **WARNING**: cursor/alarm time before firing.
  - **SPEED MIN/MAX**: min/max projectile speed (max FFF - very high speeds may pass through you).
  - **SIDES MASK**: edges it fires from (1 left, 2 right, 4 top, 8 bottom, add together).
  - **RANDOMIZE PROJECTILE**: randomize projectile type (ignores set projectile)
- **HIGHLAND**: random sprites spawn near you and sprites move chaotically. Frequency, variance and speed cap settings.
- **ENVIRONMENT**:
  - **HARMFUL GROUND / AIR**: MIN/MAX stars per second drained while on the ground or in the air.
    A value in the range is picked each time the mode starts.
  - **POISON COINS / FLOWERS**: stars gained or lost per coin or flower.
  - **PAIR WITH DEATH AT 0**: environment modes also kill you at 0 stars.

**/RANDOMIZATIONS**
- **GRAPHICS**: random level headers, backgrounds, colours and sprite graphics. Four different presets. **EPILEPSY WARNING** (some combinations can be glitchy or flash a lot)
- "Safe" preset tries to fit kinda safe/vanilla combinations
- "Remix" - a wider range of combinations, might contain som ugly ones
- "Experimental" - Does an even wider range of combinations
- F My Shit Up preset - does just that and it will look awful so have fun
- **OTHERS**: music and instrument sets (instruments shuffle might sound shit)
- Also instrument shuffle might cause instability, especially on console so beware!
- **SCREEN EXIT SHUFFLE** changes where every exit/entrance leads, tries to make it beatable but this is an early test.
- applies at the next map stage

**/CHEATS**
- Full file load, free movement, and Start+Select to always pause/exit.

**/EVENTS**
- Shigeru comes at random times and gives you a "gift"
- **Delay MIN/MAX** - Set random timer range for when he appears
- Niceness is just a setting for positive vs negative chance (0/25/50/75/100)


---

# Dnalsi

Dnalsi is a hack of vanilla levels that go from 6-8 -> 1-1 and plays all levels in reverse.
A lot of World Map graphics are reversed as well as cutscenes.

Beta for now but 98% complete - jus need to edit the text and test 100%
