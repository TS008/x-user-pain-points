# X User Pain Points — AI agents / assistants / coding agents

Rounds: 1–4 = pp-1..pp-959; Round 5 (2026-10-16, Asia/Shanghai) = pp-960..pp-1552; Round 6 top-up = pp-1553..pp-1660; Round 7 (2026-10-17) = pp-1661..pp-2488

## Stats
- Total rows: 2488 (round 7 added 828)
- Language split (all): {'en': 2102, 'zh': 298, 'other': 1, 'ja': 87}
- Language split (round 7): {'en': 716, 'zh': 91, 'ja': 21}
- Language split (round 6): {'en': 89, 'zh': 17, 'ja': 2}
- Language split (round 5): {'en': 523, 'ja': 30, 'zh': 40}
- X reads today (2026-10-17): 76 used / 924 left (daily cap 1000)
- Cumulative search calls: 2356; cumulative posts scanned: 48629

## Category counts (all rows)
- quota: 425
- reliability: 424
- UX: 276
- integration: 260
- billing: 185
- support: 140
- cost: 100
- tools: 76
- memory: 71
- workflow: 61
- observability: 60
- context: 48
- browser: 48
- permissions: 47
- sandbox: 44
- multi-agent: 43
- voice: 40
- security: 39
- scheduling: 36
- ToB: 28
- privacy: 18
- evals: 13
- deploy: 6

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
- Rows: pp-1661..pp-2488 (+828); categories: quota 181, reliability 178, support 83, billing 78, UX 71, integration 48, cost 20, browser 17, permissions 16, observability 15, tools 15, voice 14, memory 14, context 13, sandbox 12, workflow 10, security 9, scheduling 9, multi-agent 8, privacy 8, ToB 5, evals 3, deploy 1
- Angles: compaction/context loss, MCP bloat/disconnects, git/reset disasters, scope creep, overnight runs stalled on permissions, ZH/JA variants (额度/封号/中转/压缩; 使用量/コンテキスト/MCP設定), staff/product reply mining (to:thsottiaux, to:cursor_ai, to:claudeai, to:ClaudeDevs, to:GeminiApp, to:OfficialLoganK, to:poteto, to:bot, to:elonmusk, to:Subscriptions, to:sama), high-reply conversation threads (Codex Day 11/12).
- Themes: Codex weekly quota suddenly dropping to 0% (Oct 16-17) and then burning paid credits, AI-only support replies; X unified subscription migration chaos (Cursor plan not updated, merge errors, lost bots/history, shared usage pool exhausted in days, Grok Bot webhook/routine rate limits); Gemini 4 Argon quota exhaustion in 1-5 prompts and quota-bucket confusion; context compaction dropping hard constraints / re-running prompts; Claude account bans & verification lockouts with charges continuing; Claude desktop redesign (Routines hidden, nested convos); ChatGPT Work runs stuck "Working…" losing work; agents ignoring instructions (hand-writing code instead of using CLI, 23-file PR for a typo, git reset --hard); sites blocking agents (Tesla, Spokeo).
- Continuation (batches 13-16, pp-2061..pp-2283, +223): reply-mining with new angles: Codex/Claude Code/Cursor/xAI/Google staff accounts (keyanzhang, pakrym, trq212, _catwu, mntruell, ericzakariasson, embirico, gdb, joshwoodward, nikitabier), feature wishes, destructive edits, account bans, desktop apps, connectors, company AI support bots; ZH/JA variants for each.
- New themes: Codex quota suddenly 50-60% to 0 / compaction counted against quota / Sol 6.1 at 20-30 tps and 'model at capacity'; ChatGPT desktop app (chats vanish, laggy, WSL breaks monthly); Dots (forgets tasks, automation fails, no secure secret input); Grok Bot computers stuck starting / memory leak / browser ERR_CONNECTION_CLOSED, restarts admitted as bug with no fix; X subscription unification errors ('account already selected by another unification flow', SuperGrok Heavy silently cancelled, no partial refunds); Antigravity Pro users left with only 3.8 Flash; Claude identity-verification loops, accounts locked while still charging, Fin support bot loops; consumer AI support bots (PayPal, rideshare, retail) blocking humans.
- Stopped at 541 reads left (above the 100 floor) because the agent's context window was nearly full; remaining quota unused.
