# Chaos Edition Beta 0.3

A Yoshi's Island hack that randomly enables silly gameplay modes (and optionally
randomizes graphics, music and screen exits) as you play. Beta: expect bugs,crashes  and unbalanced settings.

## Opening the menu

Hold **L + R + Start** on the title screen, the world map or in a level.

- **Up/Down** select, **A** edit/enter,  **Left/Right** change
  values
- **B** goes back, **Start** exits
- Numbers are hexadecimal. Changes apply at the next LOAD.

## Menu pages

**/RUN**
- **RUN SEED**: same seed + same settings should be same run. **RESTART SEED** resets it.
- RUN is unfinished and has to be implemented properly (sometime)

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
  - **MIN DELAY / DELAY VARIANCE**: time between shots. **WARNING FRAMES**: cursor time before firing.
  - **SHOT SPEED**: projectile speed (max 0FFF - very high speeds may pass through you).
  - **SIDES MASK**: edges it fires from (1 left, 2 right, 4 top, 8 bottom, add together).
  - **RANDOMIZE**: random projectile, speed and delay for every shot (ignores the settings above).
- **HIGHLAND**: random sprites spawn near you and sprites move chaotically.
  Frequency, variance and speed cap settings.
- **ENVIRONMENT**:
  - **HARMFUL GROUND / AIR**: MIN/MAX stars per second drained while on the ground or in the air.
    A value in the range is picked each time the mode starts.
  - **POISON COINS / FLOWERS**: stars gained or lost per coin or flower.
  - **PAIR WITH DEATH AT 0**: environment modes also kill you at 0 stars.

**/RANDOMIZATIONS**
- **GRAPHICS**: random level headers, backgrounds, colours and sprite graphics (NICE or wild presets).
- Can cause issues as it affects if there's water in a stage or if certain sprites show up at all
- "Nice" preset tries to fit graphically - can still cause issues
- F My Shit Up preset - does just that and it will look awful so have fun
- **OTHERS**: music and instrument sets (instruments shuffle might sound shit)
- Also instrument shuffle might cause instability, especially on console so beware!
- **SCREEN EXIT SHUFFLE** changes where every exit/entrance leads, tries to make it beatable but this is an early test.
- applies at the next map stage

**/CHEATS**
- Full file load, free movement, and Start+Select to always pause/exit.

Settings are not saved between resets.

---

# Dnalsi

Dnalsi is a hack of vanilla levels that go from 6-8 -> 1-1 and plays all levels in reverse.
A lot of World Map graphics are reversed as well as cutscenes.

Beta for now but 98% complete - jus need to edit the text and test 100%
