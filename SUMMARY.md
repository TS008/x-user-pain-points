# X user pain points: AI agents and dev tooling

File: `x-user-pain-points.csv`, 329 rows. Rows pp-001..pp-080 come from round 1; rows pp-081..pp-329 come from round 2 (deep mining, 2026-10-15).
Window: posts from 2026-07-17 to 2026-10-15, retweets excluded. Every row links to a real post returned by the X API.

## Stats
- Total rows: 329 (80 old, 249 new)
- Languages: en 261, zh 55, ja 12, other 1 (no KO rows survived triage)
- X read calls used today: 133 of 1000 (counter at 867 left). About 82 tool-result files were processed in this mining work; the 1000-minus-left figure is the authoritative count.
- Raw posts scanned in round 2: 1,956 (1,893 unique posts in the pool)

## Category counts (all rows)
integration 45, quota 42, reliability 41, cost 35, UX 28, tools 16, memory 15, context 11, workflow 10, billing 10, multi-agent 10, scheduling 9, observability 9, browser 9, ToB 8, sandbox 8, permissions 5, security 4, support 3, voice 3, evals 3, privacy 3, deploy 2.
New categories in round 2: quota, billing, multi-agent, observability, browser, permissions, security, support, voice, evals, privacy, deploy. Round-1 rows are unchanged.

## Top new themes
1. Quota shock across tools: Codex weekly and 5-hour limits, Claude Code cuts, the Cursor plan change that dropped Opus and third-party models, Grok Bot / X Subscription weekly quota gone in a day, and the tight Gemini 4 Argon quota in Antigravity. Strong in ZH and JA.
2. Opaque or wrong billing: Antigravity billing cached tokens at full price, banked resets being deleted, Windsurf credits changing after the Devin takeover, failed retries eating the limit.
3. Model regressions and over-engineering: Codex Sol updates, Devin regression, GPT slowness. Over-engineering loops also burn credits.
4. Multi-agent coordination: no view of which parallel agent is stuck or waiting for input, context sync between agents, shared memory vaults corrupted by concurrent edits.
5. Observability: a clean diff hides the retries and model switches behind it, LangGraph/LangChain failures are hard to trace, agent failures are silent.
6. Grok Bot specifics: slow computer use and cloud PC, no SSH, built-in skills that can't be deleted, weekly quota too small.
7. Security and privacy: secrets kept in agent transcripts, weak AI-written auth and webhook code, liability for phone agents.

## Query angles used (round 2)
- Products: Cursor, Claude Code, Codex, Copilot, Windsurf, Devin, Replit, Lovable, Bolt, v0, Manus, Grok/Grok Bot, Gemini CLI, Antigravity, n8n, LangGraph/CrewAI/LangChain, MCP, OpenClaw/Hermes.
- Pains: memory, context, compaction, quota, cost, sandbox, permissions, scheduling, browser, evals, observability, deploy, enterprise, multi-agent, voice, privacy.
- Phrasing: English plus ZH (额度, 降智, 太贵, 坑, 隐私), JA (制限, 使えない, 困る) and KO.
- Reply mining with `conversation_id:` on about 9 high-reply seeds, plus `get_posts_quoted_posts`. Sort orders mixed between relevancy and recency.

## Caveats
- Only about 13% of today's quota was used, well short of the 90% target. Triaging every batch by hand was the bottleneck, so I stopped early.
- Keyword filters and a manual pass removed ads, course sellers, bots and news echoes. Some judgment calls remain.
- Engagement figures are a snapshot taken at fetch time. Impressions are sometimes missing.
- Product and model names (e.g. Sol, Argon, Opus 5.5) are as the users wrote them.
- Raw data: `raw/pool.jsonl` (all scanned posts), `raw/picks.txt` (picks), `build.py` (rebuilds the CSV). Backup of the first 80 rows: `raw/base80.csv`.
