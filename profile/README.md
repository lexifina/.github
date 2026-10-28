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

Commits are laws taking effect. "Per hour" counts commits added to GitHub over the last 1.7 hours. Updated 28 Oct 2026, 20:52 UTC.

| | Commits | Per hour |
|---|---:|---:|
| **All 49 countries** | **87,689** | **37,418** |
| Czechia | 33,641 | 19,769 |
| Armenia | 14,425 | 1 |
| Georgia | 11,819 | 6,946 |
| Switzerland | 11,509 | 6,750 |
| Malta | 7,444 | 0 |
| Germany | 3,305 | 1,899 |
| Fiji | 1,295 | 761 |
| Chile | 1,158 | 393 |
| Brazil | 642 | 249 |
| Colombia | 611 | 139 |
| Italy | 243 | 143 |
| Argentina | 197 | 26 |
| Australia | 145 | 85 |
| Luxembourg | 124 | 1 |
| Peru | 124 | 49 |
| Paraguay | 120 | 27 |
| Denmark | 108 | 1 |
| Liechtenstein | 103 | 1 |
| Uruguay | 65 | 20 |
| Estonia | 62 | 1 |
| Ecuador | 61 | 29 |
| Slovakia | 59 | 1 |
| United States | 47 | 0 |
| Monaco | 41 | 1 |
| Portugal | 40 | 24 |
| Slovenia | 34 | 1 |
| Japan | 31 | 18 |
| Greenland | 31 | 18 |
| Hong Kong | 26 | 1 |
| Ireland | 23 | 14 |
| Poland | 22 | 13 |
| Kyrgyzstan | 17 | 10 |
| United Kingdom | 16 | 0 |
| Gibraltar | 15 | 1 |
| Croatia | 11 | 1 |
| Guyana | 10 | 0 |
| China | 8 | 5 |
| Finland | 8 | 1 |
| Rwanda | 8 | 5 |
| Venezuela | 7 | 0 |
| South Africa | 6 | 4 |
| Taiwan | 6 | 4 |
| Bolivia | 5 | 0 |
| Madagascar | 5 | 3 |
| Suriname | 4 | 0 |
| Azerbaijan | 2 | 1 |
| Costa Rica | 2 | 1 |
| Samoa | 2 | 1 |
| Turkey | 2 | 1 |

<!-- git-law-stats:end -->
