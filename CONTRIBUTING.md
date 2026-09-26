# Contributing to the Sir Whiskerton Universe

*Welcome. We're glad you're here.*

---

## About This Project

The Sir Whiskerton Universe is a collaborative storytelling project set on a small, chaotic, deeply beloved farm. It is a *soft* universe — a place where nothing truly dies, where kindness is the default, and where the absurd is not just tolerated but *celebrated*.

Whether you're here to write a story, add a character, refine a bio, or simply fix a typo — thank you. This world is built by people who love it, and we're glad you're one of them.

---

## The Golden Rules

Before we get into the technical details, here are the principles that guide everything in this repo:

1. **Be gentle.** This is a soft universe. Even the conflicts are gentle. Even the villains are kind at heart. If a story or bio would cause genuine harm — cruelty, real fear, irreparable loss — it doesn't belong here.

2. **Be whimsical.** The farm runs on gentle absurdity. Talking cats, yodeling fish, a dragon who believes he's a cat, a farmer who talks to scarecrows. If it makes you smile, it probably fits.

3. **Be earnest.** Sincerity is the point. We do not do irony for irony's sake. We do not do cruelty for laughs. We mean what we say, and we say what we mean.

4. **Be consistent.** The universe has rules. They are soft rules, but they are rules. Read the canon before you add to it. If you're unsure, ask.

5. **Be kind to the reader.** Every file should be a pleasure to read. Every story should leave the reader feeling a little warmer, a little lighter, a little more at home.

---

## Repo Structure

```
sir-whiskerton-universe/
├── CONTRIBUTING.md               ← you are here
├── README.md                     ← overview of the universe
├── canon/
│   ├── README.md
│   ├── characters/
│   │   ├── README.md
│   │   ├── animals/
│   │   │   ├── README.md
│   │   │   ├── sir_whiskerton.md
│   │   │   ├── longwei_the_dragon.md
│   │   │   └── ...
│   │   └── humans/
│   │       ├── README.md
│   │       ├── the_farmer.md
│   │       ├── martha.md
│   │       └── ...
│   ├── artifacts/
│   │   ├── README.md
│   │   ├── old_mable.md
│   │   └── ...
│   ├── locations/
│   │   └── ...
│   └── guidelines/
│       ├── interaction_guidelines_farmer_martha.md
│       └── ...
├── stories/
│   ├── README.md
│   └── tales_by_firefly/
│       ├── README.md
│       ├── TBF01_the_night_the_moon_wore_jade.md
│       └── ...
└── ...
```

*(Adjust to match the actual structure of the repo. If a folder doesn't exist yet, create it when you need it.)*

---

## How to Contribute

### Adding a New Character

1. **Choose the right folder.** Animals go in `canon/characters/animals/`. Humans go in `canon/characters/humans/`. If your character is neither (an artifact, a spirit, a place), use your best judgment — and feel free to create a new folder if none fits.

2. **Follow the naming convention.** Filenames should be lowercase, with underscores instead of spaces. Drop articles ("the," "a") unless they're part of the character's identity.
   - `sir_whiskerton.md` ✅
   - `longwei_the_dragon.md` ✅
   - `The Farmer.md` ❌
   - `the_farmer.md` ✅

3. **Follow the bio format.** Every character bio should include, at minimum:
   - A title (with Chinese translation if applicable)
   - A one-line essence or core philosophy
   - Appearance
   - Personality
   - Role on the farm (or in the universe)
   - Key relationships
   - Catchphrases & quirks
   - The deeper truth (what they're afraid of, what they long for)
   - Why they belong
   - A signature quote
   - Status

   See the existing bios for examples. Match the tone.

4. **Update the README.** Add your character to the appropriate index in the folder's README. If they don't fit an existing category, create a new one — but keep it descriptive, not restrictive.

5. **Cross-reference.** If your character interacts with existing characters, add a line to their bios too. The universe is a web, not a list.

### Adding a New Story

1. **Choose the right collection.** The main story collection is `Tales by Firefly`, at `stories/tales_by_firefly/`. If you want to start a new collection, create a new folder and a README for it.

2. **Follow the naming convention.** Stories in Tales by Firefly follow the pattern `TBF##_short_title_in_snake_case.md`.
   - `TBF01_the_night_the_moon_wore_jade.md` ✅
   - `TBF02_the_eucalyptus_road.md` ✅

   The number is *chronological by writing order*, not thematic. The next story is always the next number.

3. **Follow the story format.** Every story should include:
   - A title with the story ID (e.g., `# TBF03 — The Something Something`)
   - A subtitle or epigraph
   - The story itself, divided into parts or scenes
   - A "Story Notes" section at the end (characters, setting, themes, canon notes, future seeds)

   See `TBF01` and `TBF02` for examples.

4. **Update the README.** Add your story to the story index in `stories/tales_by_firefly/README.md`.

### Adding a New Artifact or Location

1. **Create the file.** Artifacts go in `canon/artifacts/`. Locations go in `canon/locations/`.

2. **Follow the artifact/location format.** See `old_mable.md` for an example. Artifact bios typically include:
   - Identification (name, type, location, status)
   - Physical description
   - History or lore
   - Inhabitants (if any)
   - The feeling (what it's like to be there)
   - The mystery (what no one knows)
   - The invitation (how characters interact with it)
   - The artifact's place in the universe

3. **Update the README.**

### Editing an Existing File

1. **Read the whole file first.** Understand the tone, the structure, the intent.

2. **Match the voice.** This universe has a specific voice — gentle, whimsical, earnest, a little wry, deeply warm. Your edits should sound like they were written by the same person who wrote the original.

3. **Be conservative.** If you're unsure whether a change is an improvement, don't make it. If you're *sure*, make it. If you're *very* sure, make it and explain why in the commit message.

4. **Update the README if needed.** If you change a character's name, category, or status, update the index.

---

## The Tone

This is the most important section. The Sir Whiskerton Universe has a *very specific tone*, and everything in the repo should match it.

### The Tone Is:

- **Gentle.** Quiet stakes. Soft humor. No cruelty. Even the conflicts are resolved with kindness.
- **Whimsical.** The farm runs on gentle absurdity. Talking cats, yodeling fish, a dragon who believes he's a cat. If it makes you smile, it probably fits.
- **Warm.** Even the sad moments should feel *held*. Even the lonely characters are *loved*.
- **Earnest.** Sincerity is the point. No irony for irony's sake. No cruelty for laughs.
- **Soft.** Nothing dies. Things change form. The universe is a place where even the hardest edges are rounded.

### The Tone Is Not:

- **Cynical.** We do not mock our characters. We love them.
- **Cruel.** We do not laugh at pain. We laugh *with* joy.
- **Dark.** There are no villains here — only characters who have not yet found their way.
- **Ironic.** We mean what we say. We say what we mean.
- **Grim.** Even the mysteries are gentle. Even the losses are held.

### The Test

If you're unsure whether something fits, ask yourself:

> *Would this make the Farmer smile? Would this make Sir Whiskerton purr? Would this make the farm feel a little warmer, a little softer, a little more like home?*

If yes, it fits.

If no, it doesn't.

---

## The Canon Rules

A few hard rules that everything in this repo must respect:

1. **Nothing truly dies.** Creatures change form. They vanish. They transform. They do not *die*. This is a soft universe.

2. **The animals do not reveal their secret lives to the humans.** The Farmer does not know Sir Whiskerton solves mysteries. Martha does not know Catnip is a mafia don. The comedy and warmth come from this ignorance. Do not break it.

3. **The Farmer and Martha's relationship is a slow, gentle burn.** No forced drama. No love triangles. No rushed resolution. The journey is the point.

4. **Longwei believes he is a cat.** This is not a delusion. It is a choice. Do not correct him.

5. **The farm is a safe place.** Even the chaos is safe. Even the adventures are gentle. Nothing here causes real harm.

---

## Commit Messages

Write clear, descriptive commit messages. Examples:

- `Add bio for Artist Agnes`
- `Fix typo in The Farmer's catchphrases`
- `Merge Quiet Heart and Whimsical Biography into unified Farmer doc`
- `Add TBF03 — The Something Something`
- `Update humans README with new character categories`

---

## Questions?

If you're unsure about anything — the tone, the canon, the format — ask. There are no stupid questions. There is only the farm, and the people who love it.

Welcome.

---

*Jingle on.*
