# Aaron

I build AI systems that can be trusted with real work: models draft, fixed
rules decide, people approve anything consequential, and everything leaves an
audit trail.

**Latest:** [seamscan](https://github.com/technoir7/seamscan) 1.0, a checker for
the security mistakes AI coding tools ship: open Supabase tables, open Firebase
rules, leaked secrets. I measured it on 120 public apps, and
[the write-up](https://github.com/technoir7/seamscan/blob/main/docs/writeup.md)
covers what that showed and what I changed because of it.

**Also:** [chess_coach](https://github.com/technoir7/chess_coach), a chess
coach where engines establish the facts and a language model only puts them
into words. Over twelve blind-labelled rounds on fresh positions, explanations
that say something false went from 32 in 100 to 1 in 100.

**And:** [exception_resolution_model_orchestrator](https://github.com/technoir7/exception_resolution_model_orchestrator),
which checks supplier invoices before payment: rules flag what doesn't match,
Claude reads the documents and says pay or hold. On 200 hard test invoices it
caught all 58 bad payments the rules let through, held just 2 payable ones for
a person, and the cheapest model did it for $0.62 per thousand invoices.

**Recently:** lead engineer (contract) taking an AI-built startup app to
launch, with security audits, payments, CI gates and a suite of about 8k tests.
Also built a governed multi-agent system with approval gates, a kill switch
and evals.

**Background:** UC Berkeley. TypeScript, Python, Postgres.

**Open to** full-time AI engineering roles, and to consulting: hardening
AI-built apps, agent guardrails and evals. Reach me at aaronfung77@gmail.com.
