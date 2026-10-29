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

<!-- git-law-stats:begin -->

## Git for Global Law in numbers

Commits are laws taking effect. "Per hour" counts commits added to GitHub over the last 2.5 hours. Updated 29 Oct 2026, 00:52 UTC.

| | Commits | Per hour |
|---|---:|---:|
| **All 66 countries** | **306,974** | **80,274** |
| France | 187,164 | 74,866 |
| Czechia | 33,641 | 0 |
| Spain | 16,737 | 0 |
| Armenia | 14,423 | 0 |
| Georgia | 11,819 | 0 |
| Switzerland | 11,509 | 0 |
| Azerbaijan | 10,867 | 4,346 |
| Malta | 7,255 | 0 |
| Germany | 3,305 | 0 |
| Turkey | 2,362 | 539 |
| Chile | 1,456 | 29 |
| Fiji | 1,295 | 0 |
| Mongolia | 980 | 392 |
| Brazil | 753 | 44 |
| Colombia | 737 | 0 |
| Austria | 301 | 0 |
| Italy | 243 | 0 |
| Argentina | 203 | 0 |
| Peru | 152 | 0 |
| Portugal | 149 | 0 |
| Canada | 147 | 0 |
| Australia | 146 | 0 |
| Luxembourg | 126 | 0 |
| Paraguay | 120 | 0 |
| Denmark | 109 | 0 |
| Liechtenstein | 103 | 0 |
| Ecuador | 78 | 0 |
| Uruguay | 65 | 0 |
| Estonia | 62 | 0 |
| Slovakia | 59 | 0 |
| Kenya | 48 | 19 |
| United States | 47 | 0 |
| South Africa | 42 | 4 |
| Monaco | 41 | 0 |
| Slovenia | 34 | 0 |
| Greenland | 32 | 0 |
| Japan | 31 | 0 |
| Ireland | 27 | 0 |
| Hong Kong | 26 | 0 |
| Poland | 22 | 0 |
| Kyrgyzstan | 17 | 0 |
| United Kingdom | 16 | 0 |
| Nicaragua | 16 | 6 |
| Thailand | 16 | 0 |
| Uganda | 15 | 6 |
| Gibraltar | 15 | 0 |
| Nauru | 13 | 5 |
| Saudi Arabia | 13 | 0 |
| Zambia | 12 | 0 |
| Croatia | 11 | 0 |
| Guyana | 10 | 0 |
| Madagascar | 10 | 2 |
| Finland | 9 | 0 |
| Rwanda | 9 | 0 |
| China | 8 | 0 |
| Lesotho | 8 | 3 |
| Timor-Leste | 8 | 0 |
| Liberia | 7 | 3 |
| Venezuela | 7 | 0 |
| Bermuda | 7 | 3 |
| Namibia | 6 | 2 |
| Vatican City | 6 | 2 |
| Taiwan | 6 | 0 |
| Bolivia | 5 | 0 |
| Dominican Republic | 4 | 2 |
| Suriname | 4 | 0 |

<!-- git-law-stats:end -->
