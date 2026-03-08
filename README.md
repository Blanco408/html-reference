# HTML Kitchen Sink

The goal of this project was to demonstrate every current HTML element and a selection of deprecated ones across eight focused pages. The site covers document metadata, text semantics, media embedding, tables, forms, document structure, deprecated elements, and experiments. All pages are styled with a single CSS file and validated against the W3C HTML validator. The content is themed around cybersecurity and CompTIA Security+ exam topics.

## Custom Experiments

**Experiment 1: contenteditable Attribute**
Hypothesis: Setting contenteditable="true" on a div would make it editable in the browser with no JavaScript.
Finding: It worked exactly as expected. Clicking inside the div allowed direct text editing in the browser. The changes are not saved anywhere refreshing the page resets the content.

**Experiment 2: hidden Attribute**
Hypothesis: The hidden attribute would hide an element from the page but keep it in the DOM.
Finding: The element was invisible on the page but visible in DevTools under the Elements panel. It still exists in the HTML source it is just not rendered.

**Experiment 3: spellcheck Attribute on textarea**
Hypothesis: Setting spellcheck="true" vs spellcheck="false" on two textareas would show a visible difference when typing misspelled words.
Finding: The browser underlined misspelled words in red in the spellcheck="true" textarea and showed no underlining in the spellcheck="false" one. Behavior may vary by browser.

## LLM Use
LLMs are useful but they do tend to write bad code. I would say its more helpful for things like correcting grammer for me READMe. It was also helpful with fixing indentations as I feel that is important when writing cclean code.