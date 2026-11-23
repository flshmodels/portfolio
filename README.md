# flash portfolio

A small, hand-editable static site. There are no dependencies, build tools or JavaScript.

Open `index.html` in your browser. Keep `style.css` and `assets/` beside it.

## Where to start learning

1. Open `index.html` in a text editor. Each `<section>` is one part of the page. Project writeups are `<article>` elements.
2. Open `style.css`. The variables at the top control the colors. Try changing `--background`, then reload the browser.
3. The `.project` rule makes a two-column grid. The media query near the bottom changes it to one column on phones. Try changing the gap or the breakpoint and resize the browser.
4. Edit a heading or paragraph in the HTML. Save and reload. Content is written directly in the document so you can see exactly where it appears.

## Files

- `index.html`: about, coding projects, navigation and contact.
- `models.html`: the separate Blender gallery, render views and measured mesh counts.
- `style.css`: palette, typography, layout, keyboard focus and mobile rules.
- `assets/favicon.svg`: monochrome browser icon.
- `_headers`: security headers for Cloudflare Pages.
- `_redirects`: old page URLs.

## Publish to the existing Cloudflare Pages project

Upload these website files as a new production deployment of `flshmdls` using its existing direct-upload workflow. Put `index.html` at the root of the uploaded folder or ZIP. There is no build command. This site does not run the tools it links to.

The page uses only local assets. Its content security policy permits local styles and images; scripts and network connections are disabled.

## Content notes

The featured projects are Flash Remote Check, Flash Canvas and Flash Inspect. The writeups are based on their public repository documentation reviewed on November 21, 2026, including recorded testing limitations. Commands and code examples illustrate usage rather than claiming a live scan or running tool.

The separate Models page contains Alder Auto Repair, the Tiger-class study and the final Freedom-class model. Alder uses the approved third revision: 9,736 triangles, six meshes, one material and a shared 512 x 512 atlas. Its five portfolio images are rendered from the unchanged export geometry, with a consistent studio setup and separate full-building and detail views. Cooperstown uses the final checked export: 24,712 triangles, seven meshes and one 128 x 64 palette texture. Its four published views are the final bow, stern, aft-face and rear-mount renders. Only compressed render images are published; editable models and interchange files are kept in the separate delivery packages. Mesh counts come from the final Blender exports. The gallery does not claim measured Roblox performance or exact engineering accuracy.

All other projects remain available on GitHub.

