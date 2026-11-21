# Istoria: Georgian History Quiz

A single-page quiz for studying the history of Georgia, from the Dmanisi hominins to the EU Association Agreement. The questions are in Georgian.

საქართველოს ისტორიის ტესტი: 200 კითხვა, შემთხვევითი თანმიმდევრობით, მყისიერი შეფასებით.

## Features

- 200 multiple-choice questions on Georgian history
- Choose 10, 20, 50 or all questions per round; questions are shuffled every time
- Instant feedback on each answer, with the correct answer highlighted
- Final score at the end
- No build step or dependencies: one HTML file with plain CSS and JavaScript

## Run it

Open `index.html` in any browser, or serve the folder:

```bash
python3 -m http.server
```

## Adding questions

Questions live in the `allQuestions` array in `index.html`:

```js
{
  "q": "საქართველოს ტერიტორიაზე სად აღმოაჩინეს ჰომო გეორგიკუსი?",
  "choices": ["შულავერში", "დმანისში", "თრიალეთში", "ბოლნისში"],
  "answer": 1   // index of the correct choice, starting at 0
}
```
