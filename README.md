# Alicia’s Stakeholder Concept Studio

A static website with four interviewer tabs, 22 concept lessons, and 23 practice questions. Megan, Carter, and Jacob use a statement, three things to look into, and the main tradeoffs. Steph’s six mini-cases use an executive headline plus four parts: start with the economics, look at three drivers, investigate, and close with a conditional recommendation. Steph’s questions and reveal wording follow the supplied practice material.

## Publish on GitHub Pages

1. Create a **public** GitHub repository, such as `stakeholder-concept-studio`.
2. Extract the ZIP. Upload **the files inside it**, including `index.html`, directly to the repository’s top level. Do not upload the ZIP itself or nest the files inside another folder. Commit the upload to `main`.
3. In the repository, open **Settings → Pages**. Choose **Deploy from a branch**, then **main** and **/(root)**. Click **Save**.
4. Wait for deployment. Return to **Settings → Pages** for the published website link.

[Official GitHub Pages setup instructions](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

## Files

- `index.html`: website entry page.
- `style.css`: layout and colors.
- `data.js`: study content and structured practice answers.
- `app.js`: tabs, answer reveals, quizzes, and progress controls.
- `openai.svg` and `mashimaro-leaf.png`: the original images.
- `.nojekyll`: serves the static files without Jekyll processing.

No installation or build command is required. To preview locally, open `index.html` in a browser with the other files alongside it. Progress is saved in each visitor’s browser; it is not shared between visitors.

To update content, edit `data.js` and commit the changes. GitHub Pages republishes changes to the configured branch.

Personal interview preparation. Not an official OpenAI resource.
