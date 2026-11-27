*Daily digest - 2026-11-27*

_TL;DR: Google sets a 1 Feb 2027 deadline forcing AI agents onto its Workspace MCP servers, an FBI sting leads to a wire-fraud indictment of a ransomware "recovery" firm CTO, and an unreviewed preprint claims a faster discrete-log algorithm._

1. *Google forces AI agents onto Workspace MCP servers from 1 Feb 2027*
   Google made eight Workspace MCP servers GA on 24 Nov. From 1 Feb 2027, tools "driven by an AI Agent" must use them, or direct REST calls get Standard-tier quotas (5,000 MCP requests/project/day; a Gmail search counts as 10). The public Gmail server cannot send, reply, forward, or edit drafts; those need partner access.
   Why it matters: any agent that sends Gmail or calls Workspace REST APIs needs migrating or a partner-access request before February. Paid Scaled-tier billing starts 1 Apr 2027.
   https://techstackups.com/articles/google-workspace-ai-agents-mcp/

2. *RansomwareHelp CTO indicted for wire fraud after FBI sting*
   Juan Ricardo Palacio Escobar is charged in Rhode Island. The firm told victims it used "advanced cryptographic tools" but allegedly paid the ransomware groups for keys. In the sting it quoted 0.2 BTC (~$13k), negotiated to ~$6k, and billed the "victim" $16,010. Related cases: Cybersteward (Oct 2026), MonsterCloud (paid $8M, charged $19M).
   Why it matters: if you hire a ransomware recovery vendor, ask whether they negotiate with the attackers.
   https://krebsonsecurity.com/2026/11/cto-of-ransomwarehelp-indicted-for-wire-fraud/

3. *Preprint claims deterministic subexponential discrete-log algorithm (unverified)*
   IACR ePrint 2026/3020 (Zhejiang University) claims 2^{O(b/√loglog b)} time for prime fields and prime-order elliptic curves, conditional on a construction it attributes to OpenAI. Received 24 Nov, not peer reviewed, and I could not verify the attribution.
   Why it matters: if it held up, it would threaten ECC and DH. Treat it as a claim to watch for expert rebuttal, not a reason to change anything yet.
   https://eprint.iacr.org/2026/3020

*Also worth a glance:* [US Air Force cloud platform reported hacked (Sky News; I could not fetch details)](https://news.sky.com/story/us-air-forces-cloud-computing-platform-hacked-13617163) · [AMD-specific llama.cpp fork](https://devnull.land/amd-specific-llama-cpp) · [NY and CA age-gating rules take effect in the new year (EFF)](https://www.eff.org/deeplinks/2026/11/new-york-and-california-age-gating-rules-go-effect-new-year)