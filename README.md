# Can you read a network’s mind?

An interactive quiz: look at the first-layer weights of small game-playing networks and guess which game each one learned.

It’s a single static page (`index.html`) plus images. No build step, no tracking, no cookies.

## Publish on GitHub Pages

1. Create a new public repository on GitHub (for example `network-mind-quiz`).
2. Upload everything in this folder to the repository root: `index.html`, `.nojekyll`, `README.md` and the `images` folder.
   (On github.com: **Add file → Upload files**, then drag the files and folder in. `.nojekyll` is hidden on some computers; if it doesn’t upload, it’s optional.)
3. Go to **Settings → Pages**. Under “Build and deployment”, set **Source** to “Deploy from a branch”, choose the `main` branch and the `/ (root)` folder, and save.
4. After a minute or two the quiz is live at `https://USERNAME.github.io/REPO/`.

## Optional: link previews

So the link shows a preview image on Substack, social media and messaging apps, open `index.html`, find `USERNAME.github.io/REPO` in the `og:image` line near the top, and replace it with your real address.

## Use on Substack

Substack can’t embed custom pages, so link to it: add `images/social-preview.png` (or a screenshot) to your post, then a **Button** block labelled “Take the quiz” pointing at your GitHub Pages address.

## Editing

- Questions, options and explanations are plain HTML in `index.html`.
- The answer key is the `KEY` line in the script near the bottom: one list per section, giving the position (starting at 0) of the correct option for each question.
