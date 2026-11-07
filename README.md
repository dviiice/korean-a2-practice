# Korean A2 Exam Practice & TOPIK I Training

A browser-based Korean study site with a study guide and two separate practice pages:

-   **A2 study guide** --- the homepage with Vocabulary and Grammar tabs,
    semester vocabulary with English or European Portuguese meanings,
    grammar explanations and examples in both languages, and a searchable
    study resources panel.
-   **A2 practice tests** --- vocabulary, grammar, and mixed mock exams
    with easy A2 and harder TOPIK I Level 2-style question pools.
-   **TOPIK I training** --- a separate beginner TOPIK I page for
    vocabulary, grammar, and mixed practice.

The site uses HTML, CSS, and JavaScript, with shared local scripts for
the A2 vocabulary, harder question banks, and European Portuguese
translations. It requires no package
manager, server-side code, or build step. The resource panel searches a
curated list of Korean dictionaries, courses, vocabulary references, and
TOPIK information. It does not generate answers to questions.

## Files

For the GitHub Pages repository root, use these filenames:

  File                      Purpose
  ------------------------- -------------------------------------------
  `index.html`              A2 study guide and site homepage
  `a2_test.html`            A2 semester vocabulary and grammar tests
  `topik_i_training.html`   TOPIK I vocabulary and grammar tests
  `a2_content.js`            Shared A2 semester vocabulary list
  `practice_questions.js`    Shared harder contextual questions
  `pt_pt.js`                 Shared PT-PT vocabulary and interface translations

Keep all six files in the repository root. The A2 guide links to the
A2 tests, and both test pages link to each other.

## Publish with GitHub Pages

1.  Open your GitHub repository.
2.  Upload `index.html`.
3.  Upload `a2_test.html`, `topik_i_training.html`,
    `a2_content.js`, `practice_questions.js`, and `pt_pt.js`.
4.  Make sure all six files are in the repository root (not inside
    different folders).
5.  Commit and push the changes to the branch configured for GitHub Pages,
    usually `main`.
6.  In the repository, open **Settings → Pages** and confirm that GitHub
    Pages is configured to deploy from the correct branch and folder.
7.  Open the published site. Because `index.html` remains in the
    repository root, it continues to load as the homepage. The guide’s
    relative links open the A2 or TOPIK I practice pages.

After replacing either HTML file, commit the new version. It may take a
short time for GitHub Pages to publish the changes. If an older version
remains visible, refresh the page or clear the browser cache.

## Practice features

### A2 study guide

-   Vocabulary and Grammar are separate tabs; only the selected section
    is shown.
-   Searchable semester vocabulary with English or European Portuguese
    meanings. The language selector changes the vocabulary meanings as
    well as the grammar explanations and example translations.
-   Grammar notes with four or five translated examples for each point.
-   A searchable resource panel with links to the National Institute of
    Korean Language learner dictionary, King Sejong beginner courses and
    apps, TOPIK references, and official TOPIK information. It can filter
    resources by topic and shows the full list when no match is found.
-   Random vocabulary or grammar multiple-choice pop-ups every 20–40 seconds while studying.
    Correct answers show “잘 했어요 :)”. Learners can dismiss a question or
    stop pop-ups for the current page; the choice resets on navigation/reload.

### A2 practice tests

-   Vocabulary, grammar, and mixed mock-exam practice.
-   Easy A2 questions and harder questions using TOPIK I vocabulary and
    grammar, with longer contexts and reading comprehension.
-   Configurable question timer, light/dark themes, English answer
    explanations, and review of incorrect answers.
-   English or Portuguese (Portugal) interface and vocabulary meanings.

### TOPIK I training page

-   Separate vocabulary, grammar, and mixed mock-exam practice.
-   Easy mode uses the semester A2 vocabulary and grammar; hard mode
    uses TOPIK I vocabulary and more advanced grammar questions.
-   A built-in TOPIK I vocabulary bank with all 1,671 entries from the
    linked vocabulary reference, searchable on the training page.
-   English or Portuguese (Portugal) interface and translated vocabulary
    meanings where a PT-PT gloss is available. Unmapped TOPIK glosses retain
    their English source text.

The TOPIK I vocabulary bank reproduces the 1,671 headwords and English
glosses in the linked vocabulary reference PDF. Use the PDF linked on the
TOPIK page as the source reference.

### Confirming an answer

On the updated TOPIK I page, selecting an option highlights it first.
The learner must then press the confirmation button before the answer is
submitted and feedback is shown. The learner can change the selected
option before confirming.

## Study references

The TOPIK I page links to the reference materials supplied for this
project:

-   [TOPIK I vocabulary reference
    PDF](https://learning-korean.com/DL/TOPIK-I-1671.pdf)
-   [TOPIK I grammar reference
    PDF](https://learning-korean.com/DL/TOPIK-I-Grammar.pdf)

The practice site is a study aid. For complete coverage and
authoritative reference, consult the linked source PDFs.

## Saving progress and browser data

Some progress information, such as practice attempts or best scores, is
stored in the browser using `localStorage` where implemented. This
means:

-   Progress is generally tied to the browser and device being used.
-   It does not automatically synchronize between devices.
-   Clearing the browser's site data may erase saved progress.
-   Opening the site in a private/incognito window may not retain
    progress after that session.

## Troubleshooting

-   **TOPIK link does not open:** confirm that `topik_i_training.html`
    is in the same folder as `index.html` and that the filename is
    spelled exactly as shown.
-   **A page looks unchanged after an update:** wait for GitHub Pages to
    finish publishing, then hard-refresh the browser.
-   **A page is missing styling or scripts:** upload the complete HTML
    file without editing or truncating its contents.
-   **Progress has disappeared:** check whether browser site data was
    cleared or whether the page is being opened in a different
    browser/device.

## Project structure

``` text
repository/
├── index.html
├── a2_test.html
├── topik_i_training.html
├── a2_content.js
├── practice_questions.js
├── pt_pt.js
└── README.md
```
