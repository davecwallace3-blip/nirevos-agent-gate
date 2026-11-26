# nirevos-agent-gate

Authorization records for the NirevOS development agent. Public on purpose: it holds only Linear issue numbers and
dates, nothing else. Never add code, secrets, player data, security findings or links to private material.

Only David edits `authorizations.txt`, directly on `main`. The Claude GitHub App must **not** have access to this
repository, so agents can read it but never write to it. The checker in Nirevos-staging
(`tools/agents/check-authorization.mjs`) reads this file and fails closed.
