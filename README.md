# Brackroot ✦ — an Obsidian theme

A cozy pixel-storybook theme, ported from the Brackroot Academy app design system.
Pixel chrome (DotGothic16 / Silkscreen) over a readable storybook body face
(Literata). Radius 0 everywhere, stepped keylines, hard offset shadows.

Two moods: **Day** (warm cream) on the light scheme, **Night** (plum-dark) on the
dark scheme. Obsidian swaps them automatically with the base color scheme.

## Install

1. Download this repo (**Code → Download ZIP**, or clone it).
2. Copy the folder into `YOUR_VAULT/.obsidian/themes/Brackroot/` — `theme.css`
   and `manifest.json` must sit directly inside, no nested folder.
3. Obsidian → **Settings → Appearance → Themes** → pick **Brackroot**.
4. Toggle **Base color scheme** between Light and Dark for Day / Night.

## Fonts

The pixel faces (DotGothic16, Silkscreen) are base64-embedded, so the chrome
looks right on any machine with no setup — `theme.css` is fully self-contained.

Body faces are **not** embedded. Install **Literata** locally for the intended
look (Nunito and Zilla Slab are the alternates in Style Settings). Without them
the theme rides metric-safe serif/sans fallbacks and still reads fine.

## Style Settings (optional)

With the **Style Settings** community plugin, Brackroot exposes knobs under
**Settings → Style Settings → Brackroot ✦**:

- **Body face** — Literata (default), Nunito, Zilla Slab, or full pixel
- **De-yellowed ivory paper** — light scheme, for monitors that run warm
- **Dusk mode** — light scheme, deeper amber-parchment palette
- **Star checkboxes** — ✦ instead of a checkmark on done tasks
- **Plain horizontal rules** — plain line instead of the checker dither
- **Thin frames** — 1px quiet keylines, no drop shadows
- **Callout title size** — 10–20px slider (default 16)
- **Accent override** — replaces the Stardust gold

Everything works without the plugin; the defaults are the intended look.

## What's styled

Typography and headings · editor surfaces (properties, code, tables, embeds,
quotes, footnotes) · pixel checkboxes · ten callout families · file explorer ·
tabs, title bar, status bar · right sidebar (backlinks, outline, tags) · modals,
menus, command palette, settings · graph · canvas (checker ground, pixel-framed
cards, triad swatches) · Dataview and obsidian-git.

Callouts render the type as a tiny ✦ chip above the title, so title text stays
at reading size — useful if you write full sentences on the callout title line.
Callout icons are left to Obsidian/your snippets.

## Known gaps

- Only light and dark are verified in a real vault; the dusk and ivory knobs,
  canvas, and graph are lightly tested.
- Community plugins beyond Dataview / obsidian-git / Admonition aren't styled.
