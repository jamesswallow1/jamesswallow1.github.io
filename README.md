# James Swallow — Geography Educator

A compact, one-page, mobile-friendly personal website, ready to publish with **GitHub Pages**. Built with just HTML/CSS and a tiny piece of JavaScript for the copyright year: no build tools, external fonts, cookies or analytics.

## Files

- `index.html` — webpage and styles
- `profile-sketch.svg` — **temporary, non-personalised** ink-style illustration
- `favicon.svg` — browser tab icon

## Finishing the portrait and contact links

The sketch is a stand-in, **not a portrait of James**. To make it look like you, supply a photograph and have a sketch made from that photo. Name the finished image `profile-sketch.png` and change `src="profile-sketch.svg"` in `index.html` to `src="profile-sketch.png"`. Alternatively replace the existing SVG illustration with your personalised vector drawing.

To enable the two footer links, find the `pending-contact` spans near the bottom of `index.html` and replace them with:

```html
<a href="mailto:YOUR_EMAIL_ADDRESS">Email ↗</a>
<a href="https://www.linkedin.com/in/YOUR_PROFILE" target="_blank" rel="noopener noreferrer">LinkedIn ↗</a>
```

These are intentionally left inactive until you provide your details, rather than inventing them.

## Publishing with GitHub Pages

1. Create a public GitHub repository. For a site at `https://YOURUSERNAME.github.io/`, name your repository `YOURUSERNAME.github.io`. Or use any repository name to publish to a subpath.
2. Upload `index.html`, `profile-sketch.svg` and `favicon.svg` to the **root** of the repository.
3. In **Settings → Pages**, select **Deploy from a branch**, then **main** and **/(root)**; save.
4. GitHub will show you the address when deployment has completed.

All images use relative paths, so the website works with either kind of GitHub Pages URL.

## Profile and links

- Role: Geography Educator
- Location: Bristol, South West England
- Interests: climate change pedagogy; learning outside the classroom; inclusion; wellbeing; digital tools
- TES: https://www.tes.com/member/jamesgeography
- Blooket: https://dashboard.blooket.com/user/MrSwallowTeach
- Teaching Geography: https://portal.geography.org.uk/journal/view/J9781899086463
- Routes: https://routesjournal.org/2024/11/24/james-swallow/

The entire site is designed for a single typical desktop screen. Smaller screens can scroll naturally to keep text legible.


## Contact details currently configured

- Email: james@jamesswallow.uk
- LinkedIn: https://uk.linkedin.com/in/james-swallow-5274aa1ab
