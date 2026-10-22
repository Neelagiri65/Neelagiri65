## Srinathprasanna Shanmugam — Independent Security Research

I do authorised, scope-limited security research, primarily source-code review of
open-source software and coordinated disclosure of reproducible vulnerabilities
(SSRF, deserialization RCE, authorisation bypass). I also build small, focused
developer and compliance tools.

Operating as **Nativerse Ventures** · London · Human-in-the-loop, in-scope only.

---

### Selected security work

- **Google Agent Development Kit** — authored the SSRF-protection fix for `RestApiTool` / `OpenAPIToolset` (blocks loopback, private, link-local and cloud-metadata targets by default), merged upstream → [commit 30726ea](https://github.com/google/adk-python/commit/30726ea) via [#6003](https://github.com/google/adk-python/pull/6003)
- **picklescan** (Hugging Face Hub's pickle malware scanner) — reporter on a denylist-bypass code-execution advisory, `GHSA-x5w2-265w-4cph` *(in maintainer triage)*
- **dexidp/dex** — reporter on an OAuth connector-ACL bypass, `GHSA-gqgv-7xgf-8w9m` *(in maintainer triage)*
- **[gmail-oauth-research](https://github.com/Neelagiri65/gmail-oauth-research)** — a large-scale code-pattern audit surfacing open-source projects that key Google OAuth on the mutable `email` field instead of the stable `sub` claim
- **[authdrift](https://github.com/Neelagiri65/authdrift)** — static analysis for OAuth handlers that break when a user changes their Gmail address

### Tools I maintain

- **[mcpgawk](https://github.com/gawk-dev/mcpgawk)** — a local gateway in front of the MCP servers your agents use: baselines each server's tools, flags changes since you approved them, and holds calls to changed tools until you re-approve
- **[equiv](https://github.com/Neelagiri65/equiv)** — deterministic checker for behaviour-preserving code changes: runs old and new versions on the same generated inputs and emits a signed, re-runnable receipt
- **[bharataddress](https://github.com/Neelagiri65/bharataddress)** — deterministic, offline parser for messy Indian addresses (26,711 pincodes, DIGIPIN encode/decode, phonetic alias matching, zero required dependencies)
- **[aipulse](https://github.com/Neelagiri65/aipulse)** — real-time observatory for the global AI ecosystem; figures link to their sources

Early / experimental: [privacylint](https://github.com/Neelagiri65/privacylint) — SwiftSyntax scanner for App Store privacy-manifest issues (ITMS-91053 / 91061)

### Working with

`Python` · `TypeScript` · `Swift` · `Elixir / Phoenix`

---

Contact: **brindha [at] nativerse-ventures.com** · [nativerse-ventures.com](https://nativerse-ventures.com)

All research is conducted within authorised programme scope or via coordinated disclosure with maintainers.
