# flash portfolio

A small, hand-editable static site. There are no dependencies, build tools or JavaScript.

Open `index.html` in your browser. Keep `style.css` and `assets/` beside it.

## Where to start learning

1. Open `index.html` in a text editor. Each `<section>` is one part of the page. Project writeups are `<article>` elements, and `<details>` provides the expandable notes without JavaScript.
2. Open `style.css`. The variables at the top control the colors. Try changing `--background`, then reload the browser.
3. The `.project` rule makes a two-column grid. The media query near the bottom changes it to one column on phones. Try changing the gap or the breakpoint and resize the browser.
4. Edit a heading or paragraph in the HTML. Save and reload. Content is written directly in the document so you can see exactly where it appears.

## Files

- `index.html`: all visible writing, navigation, diagrams and video.
- `style.css`: palette, typography, layout, keyboard focus and mobile rules.
- `assets/favicon.svg`: monochrome browser icon.
- `assets/hud-demo.mp4`: existing garage, shop and settings recording.
- `_headers`: security headers for Cloudflare Pages.
- `_redirects`: old page URLs and project anchors.

## Publish to the existing Cloudflare Pages project

Upload these website files as a new production deployment of `flshmdls` using its existing direct-upload workflow. Put `index.html` at the root of the uploaded folder or ZIP. There is no build command. This site does not run the tools it links to.

The page uses only local assets. Its content security policy permits local styles, images and video; scripts and network connections are disabled.

## Content notes

The three writeups are based on the public repository documentation reviewed on November 21, 2026. They keep the recorded testing limitations. The diagrams explain the projects; they are not screenshots of running tools. The UI recording is the existing portfolio video.

Old anchors for the three selected projects still work. All other projects remain available on GitHub.
