<h1 align="center">Git for Global Law</h1>

<p align="center">The world's law in one git history. Every word traced to the law that wrote it, for any country and any date.</p>

<p align="center">
  <a href="https://github.com/lexifina/global-law">global-law</a> ·
  <a href="https://github.com/lexifina/global-law/blob/main/MCP.md">MCP server</a> ·
  <a href="https://lexifina.com/watch">Readers</a> ·
  <a href="https://news.ycombinator.com/item?id=50268380">Hacker News</a>
</p>

Each country's law is its own repository, with one file per provision and one commit per law taking effect. Every commit is dated by the day the change came into force, and its author is the law that made the change, so `git blame` shows which law wrote each line and `git log` shows a provision's history. [global-law](https://github.com/lexifina/global-law) brings every country together in one history, in the order the changes took force, so one commit is the state of the world's law on one day.

Every repository has a `REPRODUCE.md` that lists its sources, commands and tool versions, so anyone can rebuild it hash for hash.

### Ask your AI about the law

global-law ships an MCP server, so Claude, ChatGPT or any MCP client can read the law directly: what a provision said on a date, which law wrote its words, whether the text a judgment relied on still stands, and whether every citation in a brief is correct.

```sh
git clone --recurse-submodules https://github.com/lexifina/global-law && cd global-law
claude mcp add global-law -- python tools/mcp_server.py
```

### The repositories

| | |
|---|---|
| [global-law](https://github.com/lexifina/global-law) | Every country's law in one history, by country and level. Read any provision on any date with `tools/law.py` or the MCP server. |
| [united-states-law](https://github.com/lexifina/united-states-law) · [reader](https://lexifina.com/watch/us-code) | The United States Code, every change traced to the public law that made it. |
| [united-kingdom-law](https://github.com/lexifina/united-kingdom-law) · [reader](https://lexifina.com/watch/uk-law) | UK legislation from legislation.gov.uk. |
| [germany-law](https://github.com/lexifina/germany-law) · [reader](https://lexifina.com/watch/grundgesetz) | The Basic Law since 1949 and German federal law. |
| [switzerland-law](https://github.com/lexifina/switzerland-law) | The whole Swiss federal statute book, from Fedlex. |
| [czechia-law](https://github.com/lexifina/czechia-law) · [spain-law](https://github.com/lexifina/spain-law) · [armenia-law](https://github.com/lexifina/armenia-law) · [georgia-law](https://github.com/lexifina/georgia-law) · [malta-law](https://github.com/lexifina/malta-law) | Whole statute books, every consolidated version. |
| `lexifina/<country>-law` | One repository for each of the 193 UN member states and 16 other jurisdictions. Those without law yet record where it is published and what a build needs. |

---

<p align="center">
  <a href="https://lexifina.com"><img src="https://lexifina.com/favicon-256x256.png" width="96" height="96" alt="Lexifina"></a>
</p>

<h1 align="center">Lexifina</h1>

<p align="center">The legal workspace built for your practice.</p>

<p align="center">
  <a href="https://lexifina.com">Website</a> ·
  <a href="https://app.lexifina.com">Open the app</a> ·
  <a href="https://lexifina.com/changelog">Changelog</a> ·
  <a href="https://lexifina.com/blog">Blog</a> ·
  <a href="https://status.lexifina.com">Status</a>
</p>

Lexifina is where a law firm drafts, reviews and runs its matters. Documents, matters and clients live in one workspace, and a legal agent reads documents and proposes redlines that you accept or reject. Every change records who made it, person or agent, so a contract can be traced back to the person who drafted each part.

## Where Lexifina works

| | |
|---|---|
| [In your browser](https://app.lexifina.com) | The full workspace, with live editing alongside colleagues. |
| [In Microsoft Word](https://lexifina.com/features) | Lexifina opens beside your document and shows edits from colleagues as they type. |
| [On Android](https://lexifina.com/android) | Your documents and conversations in the same editor as the web. |
| [In Claude and ChatGPT](https://lexifina.com/connectors) | Ask about your documents, matters and clients in the chat you already use. |
| [In Chrome](https://lexifina.com/chrome) | The legal agent in Chrome’s side panel, beside the page you are reading. |

## For developers

- [Developer API](https://lexifina.com/api): connect your applications to documents, matters, clients, agents and workflows with scoped API keys.
- [Connectors](https://lexifina.com/connectors): connect Claude or ChatGPT to Lexifina through MCP.
- [Status](https://status.lexifina.com): live service status and incident history.

## Free tools

- [Document tools](https://lexifina.com/tools): check Word files and PDFs for hidden data, compare drafts, build court bundles, redact and sign. Files stay on your device.
- [Contract templates](https://lexifina.com/templates): NDAs, contractor, employment and loan agreements you fill in online and download as Word documents.

## Company

- [Pricing](https://lexifina.com/pricing) · [Security](https://lexifina.com/security) · [Careers](https://lexifina.com/careers) · [Media kit](https://lexifina.com/media-kit) · [Contact](https://lexifina.com/contact)
- [Terms](https://lexifina.com/terms-of-service) · [Privacy](https://lexifina.com/privacy-policy)

## Follow

[X](https://x.com/lexifinadotcom) · [LinkedIn](https://www.linkedin.com/company/lexifina) · [YouTube](https://www.youtube.com/channel/UCcnDS5YaeegY-8rqyarAJbg)

Questions: [hello@lexifina.com](mailto:hello@lexifina.com)
