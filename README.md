# 💌 A Crossword for the Guy Who Makes Me Cross My Words

### It's an adult promposal!

An interactive, personalized crossword that turns shared memories and inside jokes into a surprise invitation.

[Explore the code](https://github.com/snayhuh/crossword-puzzle/blob/main/index.html) · [Make your own version](#make-it-your-own)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![No dependencies](https://img.shields.io/badge/dependencies-none-ff75a8?style=flat-square)

</div>

---

## ✨ The idea

Some questions are more fun when you have to work for the answer.

This project began as a way to turn favorite memories, running jokes, and little moments into a crossword puzzle to ask my partner a question. Each clue is personal. A few special squares contain letters that come together to reveal a secret message—and solving the puzzle unlocks the final surprise.

It's part crossword, part digital love note, and entirely built from scratch.

## 🧩 What it does

- **Personalized clues:** Across and Down prompts inspired by shared memories and inside jokes.
- **Interactive 13 × 12 grid:** Type answers directly into the crossword, with arrow-key navigation and automatic movement between cells.
- **Instant puzzle checking:** The **Check puzzle** button identifies empty squares and incorrect letters, with visual feedback.
- **Hidden message:** Marked pink squares contribute letters to a message that fills in as you play.
- **A final reveal:** Completing the puzzle unlocks a special invitation. No spoilers here. 💗
- **Helpful controls:** Clear the grid and show or hide the reveal markers.
- **Responsive layout:** The crossword and clues stack on smaller screens, with horizontal scrolling for the grid when necessary.
- **Zero dependencies:** Everything lives in one HTML file—no build tools, frameworks, or installation required.

## 🚀 Run it locally

1. Clone the repository:

   ```bash
   git clone https://github.com/snayhuh/crossword-puzzle.git
   ```

2. Open the project folder:

   ```bash
   cd crossword-puzzle
   ```

3. Open `index.html` in your browser.

That's it! You can also download the repository as a ZIP and open `index.html` directly. No server setup needed.

## 🎮 How to play

1. Read the **Across** and **Down** clues.
2. Click a square and type your answers, one letter per cell. For multi-word answers, leave out the spaces.
3. Watch the marked squares fill in the secret-message blanks.
4. Use **Check puzzle** to see which squares need another look.
5. Solve the puzzle to discover the surprise. 💌

**Tip:** Use your keyboard's arrow keys to move between squares. You can toggle the reveal numbers if you want more of a challenge.

## 🛠️ Built with

| Technology | Purpose |
| --- | --- |
| **HTML5** | Page structure, clues, and puzzle interface |
| **CSS3** | Pink-and-rose styling, grid layout, and responsive design |
| **Vanilla JavaScript** | Dynamic grid generation, keyboard controls, answer validation, and the secret-message reveal |

The project is intentionally lightweight: **one `index.html` file, no external libraries, and no build step.**

## 💡 Make it your own

Want to create a surprise crossword for someone special? The puzzle data and messages are defined directly in `index.html`.

| Customize | Where to look |
| --- | --- |
| Crossword dimensions | `ROWS` and `COLS` |
| Correct letters and their positions | `solution` object |
| Starting-square numbers | `numbers` object |
| Secret-message squares | `revealCells` and `revealLabels` |
| Secret-message text | `targetMessage`, `displayTarget`, and the final reveal section |
| Across / Down clues | The two ordered lists in the HTML |
| Colors and styling | CSS variables in `:root` |

**Note:** The grid, clues, numbered cells, and reveal-letter mapping are manually configured. Changing the crossword's answers or layout requires updating those values together; this is not an automatic crossword generator.

## 🗂️ Project structure

```text
crossword-puzzle/
└── index.html       # Markup, styling, crossword data, and gameplay
```

## 💖 Why I made this

My partner loves puzzles and I wanted to ask him to be my plus one to a wedding in a fun way! It's an adult proposal!

---

<div align="center">

Made with ❤️, JavaScript, and an unreasonable amount of wordplay.

**[Back to top ↑](#-a-crossword-for-the-guy-who-makes-me-cross-my-words)**

</div>
