# Pageneck Chikondowa portfolio

Publish this directory as the root of the public pageneck.github.io repository. In repository Settings > Pages, select Deploy from a branch, main, / (root).

The static interface is hosted by GitHub Pages. It reads only published content from https://pageneck-chikondowa.citrusfawn2.chatgpt.site/api/public/content on every visit. Dashboard, uploads, authentication and storage remain on Sites. Publishing in the existing dashboard updates the data displayed here without a Git commit. Visitors already viewing the page should reload.

Keep Sites public so the public read-only content endpoint works. Never put drafts, private research files, authentication credentials or private source configuration in this repository. Only published attachments are accessible publicly through the Sites download endpoint.

This hybrid setup still depends on Sites availability; it is not an independent backup. There is no GitHub token in the frontend.
