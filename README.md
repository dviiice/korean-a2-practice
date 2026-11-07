# Korean A2 Exam Practice & TOPIK I Training

A browser-based Korean study website with two separate practice pages:

-   **A2 semester exam practice** --- the main page for semester
    vocabulary, grammar, and mixed mock-exam practice.
-   **TOPIK I training** --- a separate beginner TOPIK I page for
    vocabulary, grammar, and mixed practice.

The site is made with standalone HTML, CSS, and JavaScript. It does not
require a package manager, server-side code, or a build step.

## Files

For the GitHub Pages repository root, use these filenames:

  File                      Purpose
  ------------------------- -------------------------------------------
  `index.html`              Korean A2 semester exam practice homepage
  `topik_i_training.html`   Standalone TOPIK I training page

Use the latest supplied TOPIK file,
`topik_i_training_standalone_start.html`, and rename it to
`topik_i_training.html` when adding it to the repository.

Keep both HTML files in the **same repository folder**. The A2 page
links to the TOPIK I page, and the TOPIK I page includes a link back to
A2 practice.

## Publish with GitHub Pages

1.  Open your GitHub repository.
2.  Upload `index.html`.
3.  Upload `topik_i_training_standalone_start.html`, renamed to
    `topik_i_training.html`.
4.  Make sure both files are in the repository root (not inside
    different folders).
5.  Commit the changes to the branch configured for GitHub Pages,
    usually `main`.
6.  In the repository, open **Settings → Pages** and confirm that GitHub
    Pages is configured to deploy from the correct branch and folder.
7.  Open the published site. The A2 page should load at the site root.
    Use its TOPIK I link to open the separate TOPIK page.

After replacing either HTML file, commit the new version. It may take a
short time for GitHub Pages to publish the changes. If an older version
remains visible, refresh the page or clear the browser cache.

## Practice features

### A2 semester exam page

-   Vocabulary, grammar, and mixed mock-exam practice.
-   Easy A2 and advanced practice options where provided by the page.
-   Configurable question timer options.
-   Light and dark display themes.
-   Korean questions and instructions, with English support in
    explanations.
-   Answer feedback and review of incorrect answers.

### TOPIK I training page

-   Separate vocabulary, grammar, and mixed mock-exam practice.
-   Easy mode uses the semester A2 vocabulary and grammar; hard mode
    uses TOPIK I vocabulary and more advanced grammar questions.
-   A built-in TOPIK I vocabulary bank with all 1,671 entries from the
    linked vocabulary reference, searchable on the training page.

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
├── topik_i_training.html
└── README.md
```
