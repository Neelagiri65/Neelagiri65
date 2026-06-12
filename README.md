## Srinathprasanna Shanmugam — Independent Security Research

I do authorised, scope-limited security research, primarily source-code review of
open-source software and coordinated disclosure of reproducible vulnerabilities
(SSRF, deserialization RCE, authorisation bypass). I also build small, focused
developer and compliance tools.

Operating as **Nativerse Ventures** · London · Human-in-the-loop, in-scope only.

---

### Selected security work

- **Google Agent Development Kit** — authored an SSRF-protection fix for `RestApiTool._request()` → [google/adk-python#5760](https://github.com/google/adk-python/pull/5760)
- **picklescan** (Hugging Face Hub's pickle malware scanner) — reporter on a denylist-bypass code-execution advisory, `GHSA-x5w2-265w-4cph` *(in maintainer triage)*
- **dexidp/dex** — reporter on an OAuth connector-ACL bypass, `GHSA-gqgv-7xgf-8w9m` *(in maintainer triage)*
- **[gmail-oauth-research](https://github.com/Neelagiri65/gmail-oauth-research)** — code-pattern audit across 2M+ repositories, surfacing 124 open-source projects that key Google OAuth on the mutable `email` field instead of the stable `sub` claim
- **[authdrift](https://github.com/Neelagiri65/authdrift)** — static analysis for OAuth handlers that break when a user changes their Gmail address

### Tools I maintain

- **[privacylint](https://github.com/Neelagiri65/privacylint)** — SwiftSyntax scanner that catches App Store privacy rejections (ITMS-91053 / 91061, tracking domains) before submission · [Homebrew tap](https://github.com/Neelagiri65/homebrew-privacylint)
- **[bharataddress](https://github.com/Neelagiri65/bharataddress)** — deterministic, offline parser for messy Indian addresses (26,711 pincodes, DIGIPIN encode/decode, phonetic alias matching, zero required dependencies)
- **[aipulse](https://github.com/Neelagiri65/aipulse)** — real-time observatory for the global AI ecosystem; every figure cites its source

### Working with

`Python` · `TypeScript` · `Swift` · `Elixir / Phoenix`

---

Contact: **brindha [at] nativerse-ventures.com** · [nativerse-ventures.com](https://nativerse-ventures.com)

All research is conducted within authorised programme scope or via coordinated disclosure with maintainers.
