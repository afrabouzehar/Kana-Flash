# 🃏 Kana Flash
### `02_kana_flashcards.html`

A flip-card flashcard app for drilling the complete hiragana and katakana syllabary, including voiced (dakuten) and semi-voiced (handakuten) characters.

---

## What's Inside

- **~150 cards** covering the full kana set (hiragana + katakana, basic + dakuten + handakuten)
- Three deck modes: Hiragana only, Katakana only, or Mixed
- Self-graded: mark each card *Got it*, *Missed*, or *Skip*
- Missed-card retry mode to focus on weak spots
- Live stats bar (correct · missed · remaining)
- Progress dot timeline at the bottom of the screen

---

## How to Use

### Filtering the Deck
Click one of the three buttons in the top-right to choose your deck:

| Button | Cards shown |
|--------|-------------|
| **Hiragana** | あ–ん + dakuten/handakuten |
| **Katakana** | ア–ン + dakuten/handakuten |
| **Mixed** | All ~150 cards shuffled together |

### Studying

1. A kana character appears on the front of the card.
2. **Tap the card** (or press `Space` / `↑`) to flip and reveal the romaji.
3. Grade yourself with the buttons below:

| Button | Keyboard | Meaning |
|--------|----------|---------|
| ✕ Missed | `←` or `J` | You didn't know it |
| → Skip | `↓` or `K` | Skip for now |
| ✓ Got it | `→` or `L` | You knew it |

### When the Deck Ends
A results screen shows your correct / missed count and percentage.  
- **Retry Missed Cards** — rebuilds the deck using only the cards you missed.  
- **Restart All** — reshuffles the full deck from scratch.

---

## Characters Covered

### Hiragana
| Row | Characters |
|-----|-----------|
| Vowels | あいうえお |
| K | かきくけこ |
| S | さしすせそ |
| T | たちつてと |
| N | なにぬねの |
| H | はひふへほ |
| M | まみむめも |
| Y | やゆよ |
| R | らりるれろ |
| W | わをん |
| Dakuten G/Z/D/B | が/ざ/だ/ば rows |
| Handakuten P | ぱ row |

### Katakana
Same rows as above in katakana form: ア, カ, サ … パ row.

---

## Technical Notes

- Pure HTML + CSS + Vanilla JS — zero dependencies.
- 3D card flip using CSS `transform-style: preserve-3d`.
- Fonts: Bebas Neue, Space Grotesk, Noto Serif JP (Google Fonts).
- Fully offline-capable after initial font load.

---

*Part of the Kana Learning Suite · see also `01_big_kana_test.html` and `03_words_reading_test.html`*