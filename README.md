# The Spellbook

A dyslexia spelling programme for a 10-year-old Harry Potter fan, built on encoding, morphology, and Latin roots.

## What is this?

Eight interactive lessons + offline workbooks. Each lesson is about 20 minutes, requires nothing to print, and can't be failed.

**The core idea:** Sofia reads brilliantly via sight words, but spelling is a separate skill. Instead of sounding out (which doesn't work for English), we build words from meaning-carrying bricks — Latin roots, spelling patterns, morphology — and anchor everything to names and places she already knows from Harry Potter.

### The lessons

1. **What Spells Actually Mean** — Voldemort, Lumos, Reducto. Spells are built from Latin bricks.
2. **The Silent Letters** — gh, kn, wr, mb, gn. Five letters nobody says out loud, hidden in famous names.
3. **Nobody's Name Is An Accident** — Remus Lupin, Draco Malfoy, Bellatrix. Every character name is a clue.
4. **One Sound, Five Spellings** — The /er/ sound: Hermione, Firebolt, Durmstrang, Earwax, Wormtail.
5–8. Coming soon: ou patterns, transfiguration (suffix rules), the /shun/ ending, creatures & review.

## How to use

### For Sofia
Open `index.html` in any browser. Tap a lesson to start. That's it.

### For a tutor/ALNCo
- **Spelling-Programme-Sofia.docx** — Full scope & sequence, teaching notes, tracking table.
- **The-Spellbook-Sofia.docx** — Child-facing workbook (23 pages, pitched to her level).
- **Spellbook-Activities-Sofia.docx** — Offline activities (44 pages, 1 per page, ready to print).

Sessions are 25 minutes, 3× per week. Each lesson online lesson + offline workbook unit = one session.

## Hosting

This is a static site. You can host it anywhere:

- **GitHub Pages** (free) — see below
- **Netlify** (free tier, drag-and-drop)
- **Any web server** — just upload the folder

### To host on GitHub Pages

1. **Create a new GitHub repo** called `spellbook` (or whatever you want)

2. **Initialize git in this folder and push**:
   ```bash
   cd spellbook-site
   git init
   git add .
   git commit -m "Initial commit: The Spellbook"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/spellbook.git
   git push -u origin main
   ```

3. **Enable Pages** in GitHub:
   - Go to Settings → Pages
   - Set source to "Deploy from a branch"
   - Select `main` branch
   - Save
   - GitHub will give you a URL like `https://YOUR-USERNAME.github.io/spellbook`

4. Done. The site is live.

## Structure

```
spellbook-site/
├── index.html                           # Homepage (all 8 lessons, 4 playable)
├── lesson-1.html                        # What Spells Actually Mean
├── lesson-2.html                        # The Silent Letters
├── lesson-3.html                        # Nobody's Name Is An Accident
├── lesson-4.html                        # One Sound, Five Spellings
├── Spelling-Programme-Sofia.docx        # Teacher/ALNCo guide
├── The-Spellbook-Sofia.docx             # Sofia's workbook
├── Spellbook-Activities-Sofia.docx      # Offline activities
└── README.md                            # This file
```

## Pedagogy

### Why this works

- **Encoding, not decoding.** Sofia reads well. Spelling is a separate task; she's not failing at reading, she's learning a new skill.
- **Meaning over sound.** English doesn't work phonetically. These lessons teach the patterns that *do* work: morphology (how words are built), orthography (how they're spelled), and etymology (why).
- **Self-checking is structural.** Every activity has Sofia check her own work before correction. That's not a kindness — it's how orthographic mapping works.
- **No invented lessons.** All examples are real English words that will appear in her school writing (science, history, essays).
- **One pattern at a time.** Each lesson is one spelling pattern or root set, with multiple examples in multiple contexts (names, spells, places, student names).

### The Welsh context

- Programme uses ALNCo terminology (not SENCO)
- Written for a child in the Welsh national curriculum
- Teaches toward KS3 writing, not KS1 phonics

## Contact

Built for Sofia by Gethin, September 2026.

---

**The Spellbook** · dyslexia spelling programme built on Harry Potter
