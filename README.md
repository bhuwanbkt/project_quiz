# Project Manangement Flashcard Quiz

This is a self-contained **flashcard-style quiz** focused on **Data Mining** concepts. The project is built using a single HTML file that includes embedded JavaScript and CSS. It runs entirely in your browser — no setup or installation required.

## File Included

- `index.html` — The only file you need. Contains HTML, CSS, and JavaScript in one.

## How to Use

1. Download or clone this repository.
2. Open the file `index.html` in any modern web browser.
3. Click or tap on a flashcard to flip and view the answer.

## Topics Covered

This flashcard quiz covers core data mining topics, including:

- Agile PM  
- Project Closure 
- Progress and Performance
- Outsourcing 
- Scheduling Resources and Costs

## Customization

To modify or add new flashcards:

1. Open the `index.html` file in a text editor.
2. Locate the section where the flashcards are defined (inside the HTML or `<script>` tag).
3. Use this structure to create or edit cards:

```html
const flashcards = [
{
    question: "What is the primary difference between traditional and Agile project management regarding scope?",
    answer: "Traditional fixes scope early, while Agile allows flexible scope.",
    explanation: "Agile adapts to changes; traditional methods resist scope changes.",
    category: "15: Agile PM",
    difficulty: "easy"
},
{
    question: "Which Agile methodology uses 'pair programming' as a core practice?",
    answer: "Extreme Programming (XP)",
    explanation: "XP advocates two programmers working together at one workstation.",
    category: "15: Agile PM",
    difficulty: "medium"
}]
