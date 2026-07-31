---
permalink: /markdown/
title: "Guide"
author_profile: true
redirect_from:
  - /md/
  - /markdown.html
---

This site uses Markdown (kramdown). Keep your content in the following locations:

- Single pages: _pages/
- Collections: _posts/, _talks/, _portfolio/, _publications/

Quick tips
- Headings: #, ##, ### ...
- Paragraphs: blank line between paragraphs
- Links: [text](url)
- Images: ![alt](/images/name.png)
- Code blocks: ```language\ncode\n```
- Inline code: `code`

Math, diagrams and plots
- Math (MathJax) display: use $$ ... $$
- Mermaid diagrams: fenced code block with ```mermaid
- Plotly: fenced code block with ```plotly containing JSON

Preview locally
1. Install Ruby and Bundler
2. bundle install
3. bundle exec jekyll serve
4. Open http://127.0.0.1:4000

If you want this page removed instead, or want a longer personal guide, tell me and I will update or delete it.