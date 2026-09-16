# PlayMint — The Room Is The Game

PlayMint is an original, phone-first party game engine. It turns a single phone into the game host and keeps the rules simple enough for kids, families, friends, classrooms and parties.

## What changed
The original prompt generator was replaced with a complete lightweight game loop:

- **Mission** — physical, creative and silly challenges
- **Hot Seat** — conversation prompts
- **This or That** — instant choices
- **Chaos** — group twists and rule changes
- **Story Lab** — collaborative story starters
- Player names and turn rotation
- Points, rounds and streaks
- Skip and score actions
- Custom packs saved locally on the device
- Shareable custom-pack links using the URL hash
- Print / Save as PDF for physical packs
- PWA metadata for phone installation
- No framework, database, login, API or paid service required

## Product loop
**Open → pick the vibe → play → create a pack → share it → sell the pack.**

The core experience remains free. Creators can make themed packs such as birthday missions, family nights, classroom warmups, road trips and party challenges. The MVP supports a price field so a creator can prepare a pack for an external checkout page without adding payment infrastructure to the game itself.

## Design principles
1. **Zero friction:** no account and no setup wall.
2. **The phone is the host:** one device can run the whole room.
3. **Short rounds:** prompts should get people doing something immediately.
4. **All-ages by default:** the default content avoids adult-only material.
5. **Creator-friendly:** a player can become a pack creator without learning software.
6. **Cheap to operate:** static files and browser storage keep infrastructure near zero.

## Run
Open `index.html` in any modern browser. It is dependency-free and works as a static site.

## GitHub Pages
The repository includes a GitHub Actions workflow that publishes the `playmint` directory when the `playmint-mvp` branch changes. GitHub Pages may require the repository Pages source/environment to be enabled once in repository settings.
