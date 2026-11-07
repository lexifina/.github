## Git for Global Law

The world's law in one git history. Every word traced to the law that wrote it, for any country and any date.

Each country's law is its own repository: one file per provision, one commit per law taking effect, dated by the day it came into force and authored by the law that made it. [global-law](https://github.com/lexifina/global-law) joins them in one history, so each commit is the world's law on one day. Every repository's `REPRODUCE.md` lists the sources, commands and tool versions to rebuild it hash for hash.

<p>
  <a href="https://github.com/lexifina/global-law">Global law</a> ·
  <a href="https://github.com/lexifina/global-law/blob/main/MCP.md">MCP</a> ·
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
| [global-law](https://github.com/lexifina/global-law) | Every country in one history. Read any provision on any date with `tools/law.py` or the MCP server. |
| [Legislation](https://github.com/orgs/lexifina/repositories?q=law&sort=stargazers) | `lexifina/<place>-law`: 726 repositories, every country and many states, provinces and cities. Those without law yet record where it is published. |
| [Case law](https://github.com/orgs/lexifina/repositories?q=caselaw&sort=stargazers) | `lexifina/<country>-<court>-caselaw`: 97 repositories, one commit per court decision, for Switzerland, the Netherlands, France, Germany, Austria, Finland, Poland and the United States. |

### Discussions

[Hacker News](https://news.ycombinator.com/item?id=50268380) · [Reddit, r/ClaudeAI](https://www.reddit.com/r/ClaudeAI/comments/1xiz1vy/using_claude_to_put_all_global_law_into_git/) · [X](https://x.com/RoundtableSpace/status/2116104070029292024)

## The Lexifina workspace

Lexifina is where a law firm drafts, reviews and runs its matters. Documents, matters and clients live in one workspace, with provenance, so that every clause shows who wrote it and when.

### Where Lexifina works

| Where | What it does |
|---|---|
| [In your browser](https://app.lexifina.com) | A fully customisable legal workspace. |
| [In Chrome](https://lexifina.com/chrome) | The legal agent mounted on any web page. |
| [In Microsoft Word](https://lexifina.com/features) | Turns Word into a collaborative workspace tool. |
| [In Claude and ChatGPT](https://lexifina.com/connectors) | Every feature from your AI platform. |
| [On Android](https://lexifina.com/android) | Documents and conversations on your phone. |

### For developers

- [Developer API](https://lexifina.com/api): your documents, matters and agents, from your own apps.
- [Connectors](https://lexifina.com/connectors): connect Claude or ChatGPT to Lexifina through MCP.
- [Status](https://status.lexifina.com): live service status and incident history.

### Company

- [Website](https://lexifina.com) · [Changelog](https://lexifina.com/changelog) · [Blog](https://lexifina.com/blog) · [Security](https://lexifina.com/security) · [Contact](https://lexifina.com/contact)
- [Terms](https://lexifina.com/terms-of-service) · [Privacy](https://lexifina.com/privacy-policy)

### Follow

[X](https://x.com/lexifinadotcom) · [LinkedIn](https://www.linkedin.com/company/lexifina) · [YouTube](https://www.youtube.com/channel/UCcnDS5YaeegY-8rqyarAJbg)

Questions: [hello@lexifina.com](mailto:hello@lexifina.com)
