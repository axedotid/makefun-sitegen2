# makefun-sitegen2

A faster drop-in clone of makefun-site 1.0.0: `run(input)` in `solve.js` returns the exact output
tree makefun-site 1.0.0's `build` returns, byte for byte, as a dependency-free ES module. `main.ts`
is the harness driver.

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/axedotid/makefun-sitegen2/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/axedotid/makefun-sitegen2/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

Bounty: https://make.fun/bounty/site-generator-speed-01-run-20261122

## Dialect supported

Front matter (7 keys, strict subset), template engine (`{{ }}`/`{{{ }}}`, `{% for %}`, `{% if %}`/`{% else %}`,
`{% include %}`, standalone-tag line eating), Markdown subset (ATX headings with ids, fenced code, thematic
breaks, blockquotes, flat lists, paragraphs; inline code spans, strong, emphasis, links, backslash escapes),
slug rule (NFKD, marks dropped, 64-char cap), unique slugs, collections, tags, index pagination, report.

## License

MIT — see [LICENSE](LICENSE).