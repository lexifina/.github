<h1 align="center">Git for Global Law</h1>

<p align="center">The world's legislation as git history: one commit per law taking effect.</p>

<p align="center">
  <a href="https://lexifina.com/watch">Read it on lexifina.com</a> ·
  <a href="https://github.com/lexifina/global-law">global-law</a>
</p>

Each repo holds one jurisdiction's law, with one file per provision and one commit per law taking effect. Every commit is dated by the day the change came into force, and its author is the law that made the change, so `git blame` shows which law wrote each line and `git log` shows a provision's history. Each repo has a `REPRODUCE.md` that lists its sources, commands and tool versions, so anyone can rebuild it hash for hash.

| | |
|---|---|
| [global-law](https://github.com/lexifina/global-law) | Every corpus as a submodule, by country and level, with one history in in-force order. Read any provision on any date with `tools/law.py`, or through an MCP server. |
| [us-code-history](https://github.com/lexifina/us-code-history) · [reader](https://lexifina.com/watch/us-code) | The United States Code. |
| [uk-law-history](https://github.com/lexifina/uk-law-history) · [reader](https://lexifina.com/watch/uk-law) | UK legislation from legislation.gov.uk. |
| [grundgesetz](https://github.com/lexifina/grundgesetz) · [reader](https://lexifina.com/watch/grundgesetz) | Germany's Basic Law and its amendments. |
| [swiss-law](https://github.com/lexifina/swiss-law) | Swiss federal law from Fedlex. |
| [estonia-law](https://github.com/lexifina/estonia-law) · [luxembourg-law](https://github.com/lexifina/luxembourg-law) · [liechtenstein-law](https://github.com/lexifina/liechtenstein-law) | Constitutions and key acts of Estonia, Luxembourg and Liechtenstein. |
| One repo per country | A repo for each of the 193 UN member states and 16 other jurisdictions, recording where its law is published and what a build needs. |

The repos are private while we finish them. The readers on lexifina.com are open to everyone.

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

Commits are laws taking effect. "Per hour" counts commits added to GitHub over the last 3.0 hours. Updated 28 Oct 2026, 23:52 UTC.

| | Commits | Per hour |
|---|---:|---:|
| **All 57 countries** | **119,586** | **10,637** |
| Czechia | 33,641 | 0 |
| Spain | 16,737 | 5,581 |
| Armenia | 14,423 | -1 |
| Georgia | 11,819 | 0 |
| Switzerland | 11,509 | 0 |
| Azerbaijan | 10,867 | 3,623 |
| Malta | 7,255 | -63 |
| Germany | 3,305 | 0 |
| Turkey | 2,362 | 787 |
| Chile | 1,456 | 99 |
| Fiji | 1,295 | 0 |
| Mongolia | 980 | 327 |
| Colombia | 737 | 42 |
| Brazil | 642 | 0 |
| Austria | 301 | 100 |
| Italy | 243 | 0 |
| Argentina | 203 | 2 |
| Peru | 152 | 9 |
| Portugal | 149 | 36 |
| Canada | 147 | 49 |
| Australia | 146 | 0 |
| Luxembourg | 126 | 1 |
| Paraguay | 120 | 0 |
| Denmark | 109 | 0 |
| Liechtenstein | 103 | 0 |
| Ecuador | 78 | 6 |
| Uruguay | 65 | 0 |
| Estonia | 62 | 0 |
| Slovakia | 59 | 0 |
| United States | 47 | 0 |
| South Africa | 42 | 12 |
| Monaco | 41 | 0 |
| Slovenia | 34 | 0 |
| Greenland | 32 | 0 |
| Japan | 31 | 0 |
| Ireland | 27 | 1 |
| Hong Kong | 26 | 0 |
| Poland | 22 | 0 |
| Kyrgyzstan | 17 | 0 |
| United Kingdom | 16 | 0 |
| Thailand | 16 | 5 |
| Uganda | 15 | 5 |
| Gibraltar | 15 | 0 |
| Saudi Arabia | 13 | 4 |
| Zambia | 12 | 4 |
| Croatia | 11 | 0 |
| Guyana | 10 | 0 |
| Finland | 9 | 0 |
| Rwanda | 9 | 0 |
| China | 8 | 0 |
| Madagascar | 8 | 1 |
| Timor-Leste | 8 | 3 |
| Venezuela | 7 | 0 |
| Taiwan | 6 | 0 |
| Bolivia | 5 | 0 |
| Dominican Republic | 4 | 1 |
| Suriname | 4 | 0 |

<!-- git-law-stats:end -->
