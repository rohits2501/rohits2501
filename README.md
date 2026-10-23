# Rohit Singh

Staff frontend engineer. I build accessible web and mobile interfaces, and I contribute to the component libraries those interfaces sit on.

## Open source

Merged this month:

- [Base UI](https://github.com/mui/base-ui/pull/6022) — a disabled radio group leaves the tab order.
- [Material UI](https://github.com/mui/material-ui/pull/49504) — WCAG 2.2 assessment and axe tests for CircularProgress.
- [Material UI](https://github.com/mui/material-ui/pull/49526) — a shared axe file counts only that component’s demos.

In review:

- [Base UI](https://github.com/mui/base-ui/pull/6072) — Shift+Tab stays inside an open context menu.
- [Material UI](https://github.com/mui/material-ui/pull/49524) — the same assessment for FormControlLabel.
- [Radix Primitives](https://github.com/radix-ui/primitives/pull/4243) — the select trigger id reaches the native select, so a label and native required checks work.
- [shadcn/ui](https://github.com/shadcn-ui/ui/pull/12356) — keyboard focus stays visible on invalid controls.

## Projects

Pull requests on these repos comment with the bundle delta against main. House also reports catalog bench times, and the console reports how many times a fixture mounts. The gzip ceiling still fails the build.

### [House](https://github.com/rohits2501/design-system)

One visual language for the apps below: semantic tokens, light, dark, and high contrast, theme presets, and a small set of React primitives. A check fails the build when a second palette appears.

### [Document Intelligence Console](https://github.com/rohits2501/ai-document-intelligence-console)

Operators upload a file, follow job progress streamed from an append-only event log, and review extracted fields in a virtualized viewer. The default extractor is a mock, and the app says so. [Live](https://ai-document-intelligence-console.vercel.app).

### [AudioForge](https://github.com/rohits2501/audioforge)

Upload a script and get a multi-character audio episode. [Live](https://op-scout-five.vercel.app/).

### [Bol](https://github.com/rohits2501/bol)

Hindi, Hinglish, and English dictation. The speech key stays on the server. [Live](https://bol-ashy.vercel.app/).
