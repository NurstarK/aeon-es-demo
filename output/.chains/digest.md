*Daily digest - 2026-11-26*

_TL;DR: 1Password disclosed a source-code and CI/CD breach via an employee GitHub account, and Ubuntu is reportedly still unpatched for a remote kernel TCP flaw._

1. *1Password discloses breach of GitHub account, source code and CI/CD*
   Attacker used an employee's GitHub account to push malicious code to backend services, which pulled account records (names, emails, IDs, public keys, SRP parameters) for a subset of customers. Some invitation and recovery tokens were included. 1Password says vault contents were not accessed.
   Why it matters: expect phishing that mentions 1Password invitations or account recovery; the CI/CD secrets exposure is worth watching for follow-up.
   https://1password.com/blog/update-on-nov-2026-security-incident

2. *Researcher: Ubuntu unpatched 9+ days on remote kernel TCP flaw (CVE-2026-99288)*
   Hanno Böck reports Ubuntu had no fix for "NoisyTCP" as of Nov 25 while other distros did, plus an unpatched AMD KVM host escape (CVE-2026-99312). These are his claims; no Ubuntu response was included.
   Why it matters: Ubuntu hosts exposed to the network may need mitigations or a different kernel until fixes ship.
   https://www.openwall.com/lists/oss-security/2026/11/25/9

3. *Aaronson claims AI labs have proven major open math results*
   Scott Aaronson's post asserts OpenAI and Anthropic produced results including a claimed matrix-multiplication exponent and a Riemann Hypothesis proof, many with Lean certificates. Extraordinary claims, not independently verified here; treat as unconfirmed until the proofs are checked.
   https://scottaaronson.blog/?p=10379

*Also worth a glance:* [GPT-6.2 Astra tops Googlers' code golf records](https://bjin.github.io/go-codegolf-benchmark/#leaderboard) · [NYT warns photographers off Photoshop update over AI features](https://www.theverge.com/ai-artificial-intelligence/1041227/the-new-york-times-warns-photographers-not-to-update-photoshop-over-ai-features)