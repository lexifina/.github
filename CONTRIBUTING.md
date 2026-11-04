# Contributing

This applies to every Lexifina repository that has no contributing guide of its own, including each country's law
repository (`lexifina/<country>-law`). The full guidelines are in
[global-law's CONTRIBUTING.md](https://github.com/lexifina/global-law/blob/main/CONTRIBUTING.md); in short:

- **Anyone can propose a change** as an issue or a pull request. Lexifina reviews each one.
- **A wrong text or date:** open an issue here with the path, the date and the official page it should match.
  Lexifina appends a correction commit that names the commit it corrects. Law files are never edited by hand.
- **A builder fix:** a pull request or issue here. `tools/` is a published copy of Lexifina's builder, so the fix is
  applied there and ships in the next documentation commit; it is not merged as it is.
- **A missing jurisdiction, or a change to the tools or the MCP server:** in
  [lexifina/global-law](https://github.com/lexifina/global-law).
- **History only grows:** published commits are never changed or force-pushed.
- **Credit** goes in a `Contributed-by: Your Name (@your-github-handle)` trailer, with no email address.
- **Licence:** your contribution is dedicated to the public domain under CC0; law text stays under its publisher's
  terms (this repository's `SOURCES.md`).
- **Security problems:** report them privately, as [SECURITY.md](SECURITY.md) says.
