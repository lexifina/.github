<p align="center">
  <a href="https://lexifina.com"><img src="https://lexifina.com/favicon-256x256.png" width="96" height="96" alt="Lexifina"></a>
</p>

<h1 align="center">Lexifina</h1>

## Git for Global Law

The world's law in one git history. Every word traced to the law that wrote it, for any country and any date.

Each country's law is its own repository: one file per provision, one commit per law taking effect, dated by the day it came into force and authored by the law that made it. [global-law](https://github.com/lexifina/global-law) joins them in one history, so each commit is the world's law on one day. Every repository's `REPRODUCE.md` lists the sources, commands and tool versions to rebuild it hash for hash.

<p>
  <a href="https://github.com/lexifina/global-law">Global law</a> ·
  <a href="https://github.com/lexifina/global-law/blob/main/MCP.md">MCP server</a> ·
  <a href="https://github.com/lexifina/global-law/tree/main/visualisations">Visualisations</a> ·
  <a href="https://github.com/lexifina/global-law/blob/main/FAQ.md">FAQ</a>
</p>

### Ask your AI about the law

global-law ships an MCP server, so Claude, ChatGPT or any MCP client can read the law directly: what a provision said on a date, which law wrote its words, whether the text a judgment relied on still stands, and whether every citation in a brief is correct.

```sh
git clone --recurse-submodules https://github.com/lexifina/global-law && cd global-law
claude mcp add global-law -- python tools/mcp_server.py
```

### The repositories

| Repository | What it holds |
|---|---|
| [global-law](https://github.com/lexifina/global-law) | Every country's law in one history, by country and level. Read any provision on any date with `tools/law.py` or the MCP server. |
| [romania-law](https://github.com/lexifina/romania-law) | Romania's primary legislation: the Constitution, laws, emergency ordinances, ordinances and government decisions, with every consolidated form. |
| [united-states-law](https://github.com/lexifina/united-states-law) · [reader](https://lexifina.com/watch/us-code) | The United States Code, every change traced to the public law that made it. |
| [united-kingdom-law](https://github.com/lexifina/united-kingdom-law) · [reader](https://lexifina.com/watch/uk-law) | UK legislation from legislation.gov.uk. |
| [germany-law](https://github.com/lexifina/germany-law) · [reader](https://lexifina.com/watch/grundgesetz) | The Basic Law since 1949 and German federal law. |
| [switzerland-law](https://github.com/lexifina/switzerland-law) | The whole Swiss federal statute book, from Fedlex. |
| [czechia-law](https://github.com/lexifina/czechia-law) · [spain-law](https://github.com/lexifina/spain-law) · [armenia-law](https://github.com/lexifina/armenia-law) · [georgia-law](https://github.com/lexifina/georgia-law) · [malta-law](https://github.com/lexifina/malta-law) | Whole statute books, every consolidated version. |
| The Balkans | [albania-law](https://github.com/lexifina/albania-law) · [bosnia-and-herzegovina-law](https://github.com/lexifina/bosnia-and-herzegovina-law) · [bulgaria-law](https://github.com/lexifina/bulgaria-law) · [croatia-law](https://github.com/lexifina/croatia-law) · [greece-law](https://github.com/lexifina/greece-law) · [kosovo-law](https://github.com/lexifina/kosovo-law) · [montenegro-law](https://github.com/lexifina/montenegro-law) · [north-macedonia-law](https://github.com/lexifina/north-macedonia-law) · [serbia-law](https://github.com/lexifina/serbia-law) · [slovenia-law](https://github.com/lexifina/slovenia-law) |
| Also | [france-law](https://github.com/lexifina/france-law) · [austria-law](https://github.com/lexifina/austria-law) · [poland-law](https://github.com/lexifina/poland-law) · [india-law](https://github.com/lexifina/india-law) · [turkey-law](https://github.com/lexifina/turkey-law) · [israel-law](https://github.com/lexifina/israel-law) · [netherlands-law](https://github.com/lexifina/netherlands-law) · [brazil-law](https://github.com/lexifina/brazil-law) |
| `lexifina/<place>-law` | One repository for every country, and for many states, provinces and cities: 726 in all. Those without law yet record where it is published and what a build needs. |

### Discussions

[Hacker News](https://news.ycombinator.com/item?id=50268380) · [Reddit, r/ClaudeAI](https://www.reddit.com/r/ClaudeAI/comments/1xiz1vy/using_claude_to_put_all_global_law_into_git/) · [X](https://x.com/RoundtableSpace/status/2116104070029292024)

## The Lexifina workspace

Lexifina is where a law firm drafts, reviews and runs its matters. Documents, matters and clients live in one workspace, and a legal agent reads documents and proposes redlines that you accept or reject. Every change records who made it, person or agent, so every clause shows who wrote it and when.

### Where Lexifina works

| Where | What it does |
|---|---|
| [In your browser](https://app.lexifina.com) | The full workspace, edited live with colleagues. |
| [In Microsoft Word](https://lexifina.com/features) | A side panel that shows colleagues' edits as they type. |
| [On Android](https://lexifina.com/android) | Documents and conversations on your phone. |
| [In Claude and ChatGPT](https://lexifina.com/connectors) | Query matters and clients from the chat. |
| [In Chrome](https://lexifina.com/chrome) | The legal agent beside any web page. |
| [Document tools](https://lexifina.com/tools) | Free metadata checks, comparison, bundles, redaction and signing. Files never leave your device. |

### For developers

- [Developer API](https://lexifina.com/api): connect your applications to documents, matters, clients, agents and workflows with scoped API keys.
- [Connectors](https://lexifina.com/connectors): connect Claude or ChatGPT to Lexifina through MCP.
- [Status](https://status.lexifina.com): live service status and incident history.

### Company

- [Website](https://lexifina.com) · [Changelog](https://lexifina.com/changelog) · [Blog](https://lexifina.com/blog) · [Security](https://lexifina.com/security) · [Contact](https://lexifina.com/contact)
- [Terms](https://lexifina.com/terms-of-service) · [Privacy](https://lexifina.com/privacy-policy)

### Follow

[X](https://x.com/lexifinadotcom) · [LinkedIn](https://www.linkedin.com/company/lexifina) · [YouTube](https://www.youtube.com/channel/UCcnDS5YaeegY-8rqyarAJbg)

Questions: [hello@lexifina.com](mailto:hello@lexifina.com)
