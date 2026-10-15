# X user pain points: AI agents and dev tooling

File: `x-user-pain-points.csv`, **875** rows (pp-001..pp-875).
- pp-001..pp-080: round 1
- pp-081..pp-772: round 2 (deep mining earlier on 2026-10-15)
- pp-773..pp-875: round 3 (this pass, 2026-10-15 evening CST)

Window: posts from 2026-07-17 to 2026-10-15, retweets excluded. Every row links to a real post returned by the X API.

## Stats
- Total rows: **875** (772 before this pass, **+103** new)
- Languages: en 702, zh 144, ja 28, other 1
- X read calls today: **899 of 1000 used**, **101 left** (stopped at ~100 remaining; did not go below 100)
- This pass used about **115** reads (started near 216 left)
- Raw posts scanned (cumulative extract counter): **15843**; unique pool size: **11998**
- Cumulative extract call files processed: 828 (advisory; authoritative daily usage is 1000−left)

## Category counts (all rows)
quota 146, integration 117, reliability 97, UX 78, cost 64, billing 56, support 32, workflow 30, memory 28, tools 27, observability 25, sandbox 23, multi-agent 21, browser 20, permissions 19, scheduling 18, voice 18, context 15, security 11, ToB 10, evals 9, privacy 6, deploy 5.

## Top new themes (round 3)
1. **Quota cliffs mid-task**: Codex/Claude now stop halfway instead of finishing after a limit; GPT Plus/Pro burn a week in a day; Claude $108/mo still interrupts with no transparent meter; Antigravity collapses Gemini CLI’s former huge daily input into minutes.
2. **Claude geo bans & support (ZH)**: Pro-ready accounts banned; enterprise Claude banned after HK VPN; one-account ToS with no mainland/HK support; refunds only reliable via Apple IAP; regional chat cues suspected as ban signals.
3. **OS / phone agent walls**: Third-party agents stuck at iOS edges; 157 taps vs a five-second voice prompt; permission UX feels like onboarding a roommate; liability when a phone agent taps a bank app.
4. **Harness security & silent installs**: Coze/Mirasim-style CLIs silently inject or relocate skills/MCP; lack of transparency about what executes where.
5. **Grok Bot / Cursor unify mess**: Paid Ultra+Cursor still cannot run Grok Bot on computer; Premium→Plus breaks third-party models; shared global 18k rate limit reports; cloud PC / computer-use still too slow.
6. **Memory of “why” not “what”**: New sessions remember code but forget architectural decisions; concurrent agents corrupt shared memory files; need append-only decision receipts.
7. **Observability & silent failure**: Green unit tests while signup is broken; agents run weeks then fail silently; cron agents swallow alerts or rerun prod migrations from stale shell access.
8. **Spend / YOLO fear**: Agents max AWS on a personal card; airline-ticket agents feel untrustworthy; YOLO almost wiped a drive of sensitive data; agentic payments need human-readable receipts.
9. **Tooling friction**: MCP re-auth forces full login; Playwright sessions kill each other’s tabs; Claude Code deletes worktrees on shutdown; App Store Connect screens invisible to computer use.
10. **Voice / always-on**: Full voice stack still feels slow despite fast TTS; want native always-on device agents instead of a separate app; overnight agents should BLOCK rather than burn hours.

## Query angles used (round 3)
- Reply-thread mining via `conversation_id:` on high-reply seeds (Muse/iOS agents, Codex quota, Coze hijack, Claude ban wave, multi-agent, observability, architecture-memory).
- `get_posts_quoted_posts` on selected seeds.
- Fresh angles: CAPTCHA/browser, secrets/transcripts, HITL permissions, voice latency, deploy/CI, evals, Antigravity/Gemini CLI, Grok Bot unify, ZH/JA authentic complaints, YOLO/sandbox, cron/always-on, effort-based billing.
- Filters: ~90-day window, `-is:retweet`, max_results 25, paced under 30/min.

## Caveats
- Stopped with **101** reads left today (hard floor: do not go below 100).
- Manual triage preferred quality over quantity; ads, course sellers, bots, slogans, crypto, and news echoes were excluded.
- Engagement figures are snapshots at fetch time; impressions sometimes missing.
- Product/model names appear as users wrote them.
- Raw data: `raw/pool.jsonl`, `raw/picks.txt`, `build.py`. Backup of first 80 rows: `raw/base80.csv`.
- **GitHub push was not done** (per task instructions).
