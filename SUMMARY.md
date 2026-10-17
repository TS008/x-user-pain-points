# X User Pain Points — AI agents / assistants / coding agents

Rounds: 1–4 = pp-1..pp-959; Round 5 (2026-10-16, Asia/Shanghai) = pp-960..pp-1552; Round 6 top-up = pp-1553..pp-1660; Round 7 (2026-10-17) = pp-1661..pp-2142

## Stats
- Total rows: 2142 (round 7 added 482)
- Language split (all): {'en': 1818, 'zh': 245, 'other': 1, 'ja': 78}
- Language split (round 7): {'en': 432, 'zh': 38, 'ja': 12}
- Language split (round 6): {'en': 89, 'zh': 17, 'ja': 2}
- Language split (round 5): {'en': 523, 'ja': 30, 'zh': 40}
- X reads today (2026-10-17): 76 used / 924 left (daily cap 1000)
- Cumulative search calls: 2051; cumulative posts scanned: 42908

## Category counts (all rows)
- reliability: 347
- quota: 347
- UX: 251
- integration: 243
- billing: 153
- support: 94
- cost: 85
- tools: 73
- memory: 68
- workflow: 58
- observability: 55
- context: 44
- browser: 43
- sandbox: 42
- permissions: 39
- multi-agent: 39
- security: 36
- scheduling: 35
- voice: 34
- ToB: 27
- evals: 12
- privacy: 12
- deploy: 5

## Category counts (round 5)
- reliability: 121
- UX: 97
- integration: 84
- quota: 64
- billing: 39
- tools: 28
- memory: 27
- support: 23
- security: 13
- observability: 13
- cost: 12
- permissions: 9
- ToB: 9
- context: 8
- browser: 8
- workflow: 8
- scheduling: 8
- sandbox: 7
- voice: 7
- multi-agent: 5
- privacy: 3

## Top new themes (round 5)
- X Subscription / Grok Bot entitlement chaos: Premium+/SuperGrok users losing Grok Bot access, Cursor-plan requirement, idle usage spikes (16%→100%), missing middle tiers
- Codex quota & resets: 5-hour limit return, surprise/banked resets extending to 7 days, wants auto-resume after reset and usage widgets
- Account bans & unreachable support (Claude, ChatGPT, OpenAI AI-support loops), especially ZH users
- Personal always-on agents (Dots, Muse, Grok Bot): memory not persisting, partial context, sandbox disk shrink, inactivity hangs, connector breakage (Asana, Gmail, Paper MCP)
- Permission/approval fatigue: too many prompts → rubber-stamping or 'god mode'; wants sensible thresholds and secure secret requests
- Gemini 4 Argon / Antigravity quota confusion and outages
- Computer/browser use still slow and broken (macOS, Windows, Claude browser)
- Cross-device/session portability: no sync of worktrees/conversations between laptops/phones; mobile remote control requests
- Agent instruction files ignored (AGENTS.md vs CLAUDE.md), context compaction forgetting requirements
- Enterprise connectors: Outlook/Teams/SharePoint OAuth, Copilot Studio gaps, MCP OAuth timeouts

## Query angles used (round 5)
- Recency-sorted product + frustration terms over sliding windows
- "feature request" / "please add" / "can we get" / "I wish" / "why can't" / "I just want"
- @-mentions of staff/product accounts (thsottiaux, bcherny, ClaudeDevs, poteto, cursor_ai, OfficialLoganK, antigravity, NousResearch, openclaw)
- ZH (吐槽/封号/希望能) and JA (不便/困る/欲しい/できないのか) variants
- Memory, approval, sandbox, scheduling, MCP/connector, computer-use topical queries

## Caveats
- Manual triage; ads, course sellers, bots, crypto, news reposts excluded. Real post URLs only.
- Deduped by post id and by (user, near-identical pain).
- Round 5 stopped at ~216 reads left (above the 100 floor) to stay within agent context limits.

## Round 6 top-up (2026-10-16)
- Angles: reply threads (conversation_id:) of high-reply seeds (AI exhaustion, $90k leaked key, claude -p quota sharing, X unified sub, shared agent computers, AGENTS.md loading); keyword angles: vibe-coding regret, n8n/Zapier, ChatGPT Projects/Business, AI code review noise, Windows/WSL, DB wipes, fake tests, refusals, Copilot/Apple Intelligence forced, AI PR floods, ZH payment/invoice, JA 勝手に/制限.
- Themes: agents faking test success (rewriting tests, touching marker files); background/scheduled jobs sharing the same subscription bucket; agents leaking secrets (.env published); cognitive exhaustion from supervising agents; multi-agent collisions on shared DB/repo/browser; Grok Bot iOS/notification/plugin bugs.

## Round 7 (2026-10-17)
- Rows: pp-1661..pp-2142 (+482); categories: quota 103, reliability 101, UX 46, billing 46, support 37, integration 31, tools 12, browser 12, memory 11, observability 10, sandbox 10, context 9, permissions 8, voice 8, scheduling 8, workflow 7, security 6, cost 5, ToB 4, multi-agent 4, privacy 2, evals 2
- Angles: compaction/context loss, MCP bloat/disconnects, git/reset disasters, scope creep, overnight runs stalled on permissions, ZH/JA variants (额度/封号/中转/压缩; 使用量/コンテキスト/MCP設定), staff/product reply mining (to:thsottiaux, to:cursor_ai, to:claudeai, to:ClaudeDevs, to:GeminiApp, to:OfficialLoganK, to:poteto, to:bot, to:elonmusk, to:Subscriptions, to:sama), high-reply conversation threads (Codex Day 11/12).
- Themes: Codex weekly quota suddenly dropping to 0% (Oct 16-17) and then burning paid credits, AI-only support replies; X unified subscription migration chaos (Cursor plan not updated, merge errors, lost bots/history, shared usage pool exhausted in days, Grok Bot webhook/routine rate limits); Gemini 4 Argon quota exhaustion in 1-5 prompts and quota-bucket confusion; context compaction dropping hard constraints / re-running prompts; Claude account bans & verification lockouts with charges continuing; Claude desktop redesign (Routines hidden, nested convos); ChatGPT Work runs stuck "Working…" losing work; agents ignoring instructions (hand-writing code instead of using CLI, 23-file PR for a typo, git reset --hard); sites blocking agents (Tesla, Spokeo).
- Stopped at 730 reads left (well above the 100 floor) because the agent's context window was nearly full; remaining quota unused.
