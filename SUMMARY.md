# X User Pain Points — AI agents / assistants / coding agents

Rounds: 1–4 = pp-1..pp-959; Round 5 (2026-10-16, Asia/Shanghai) = pp-960..pp-1552; Round 6 top-up = pp-1553..pp-1660; Round 7 (2026-10-17) = pp-1661..pp-2687; Round 8 (2026-10-18) = pp-2688..pp-2944

## Stats
- Total rows: 2944 (round 8 added 257)
- Language split (all): {'en': 2475, 'zh': 353, 'other': 1, 'ja': 115}
- Language split (round 8): {'en': 220, 'zh': 26, 'ja': 11}
- Language split (round 7): {'en': 869, 'zh': 120, 'ja': 38}
- Language split (round 6): {'en': 89, 'zh': 17, 'ja': 2}
- Language split (round 5): {'en': 523, 'ja': 30, 'zh': 40}
- X reads today (2026-10-18): 94 used / 906 left (daily cap 1000)
- Cumulative search calls: 2616; cumulative posts scanned: 53744

## Category counts (all rows)
- quota: 533
- reliability: 493
- UX: 315
- integration: 294
- billing: 230
- support: 182
- cost: 116
- tools: 95
- memory: 77
- observability: 71
- workflow: 64
- permissions: 63
- context: 59
- multi-agent: 54
- browser: 50
- sandbox: 46
- security: 46
- voice: 45
- scheduling: 39
- ToB: 29
- privacy: 21
- evals: 15
- deploy: 7

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
- Rows: pp-1661..pp-2687 (+1027); categories: quota 219, reliability 212, support 119, billing 90, UX 86, integration 62, cost 27, permissions 24, tools 19, memory 18, browser 18, observability 17, voice 17, context 17, multi-agent 15, sandbox 14, workflow 12, security 11, scheduling 11, privacy 10, ToB 5, evals 3, deploy 1
- Angles: compaction/context loss, MCP bloat/disconnects, git/reset disasters, scope creep, overnight runs stalled on permissions, ZH/JA variants (额度/封号/中转/压缩; 使用量/コンテキスト/MCP設定), staff/product reply mining (to:thsottiaux, to:cursor_ai, to:claudeai, to:ClaudeDevs, to:GeminiApp, to:OfficialLoganK, to:poteto, to:bot, to:elonmusk, to:Subscriptions, to:sama), high-reply conversation threads (Codex Day 11/12).
- Themes: Codex weekly quota suddenly dropping to 0% (Oct 16-17) and then burning paid credits, AI-only support replies; X unified subscription migration chaos (Cursor plan not updated, merge errors, lost bots/history, shared usage pool exhausted in days, Grok Bot webhook/routine rate limits); Gemini 4 Argon quota exhaustion in 1-5 prompts and quota-bucket confusion; context compaction dropping hard constraints / re-running prompts; Claude account bans & verification lockouts with charges continuing; Claude desktop redesign (Routines hidden, nested convos); ChatGPT Work runs stuck "Working…" losing work; agents ignoring instructions (hand-writing code instead of using CLI, 23-file PR for a typo, git reset --hard); sites blocking agents (Tesla, Spokeo).
- Continuation (batches 13-16, pp-2061..pp-2283, +223): reply-mining with new angles: Codex/Claude Code/Cursor/xAI/Google staff accounts (keyanzhang, pakrym, trq212, _catwu, mntruell, ericzakariasson, embirico, gdb, joshwoodward, nikitabier), feature wishes, destructive edits, account bans, desktop apps, connectors, company AI support bots; ZH/JA variants for each.
- New themes: Codex quota suddenly 50-60% to 0 / compaction counted against quota / Sol 6.1 at 20-30 tps and 'model at capacity'; ChatGPT desktop app (chats vanish, laggy, WSL breaks monthly); Dots (forgets tasks, automation fails, no secure secret input); Grok Bot computers stuck starting / memory leak / browser ERR_CONNECTION_CLOSED, restarts admitted as bug with no fix; X subscription unification errors ('account already selected by another unification flow', SuperGrok Heavy silently cancelled, no partial refunds); Antigravity Pro users left with only 3.8 Flash; Claude identity-verification loops, accounts locked while still charging, Fin support bot loops; consumer AI support bots (PayPal, rideshare, retail) blocking humans.
- Stopped at 541 reads left (above the 100 floor) because the agent's context window was nearly full; remaining quota unused.
- Third segment (batches 17-20, pp-2284..pp-2519, +236: b17 +80, b18 +69, b19 +56, b20 +31): new reply-mining accounts (GoogleDeepMind, NotebookLM, Kimi/DeepSeek/Qwen/Z.ai/MiniMax, Manus/Genspark, Cline/Warp/Zed/v0/Bolt, Notion, Meta/Muse, Apple, Figma, Raycast, Brave/Opera, GitHub, X Support, YouTube/Instagram AI support), fresh-window replies to staff accounts, ZH/JA variants.
- New themes: Gemini 4 Argon quota drain (one prompt to a week of quota, Ultra not exempt) and Antigravity model auto-switching; GitHub suspending accounts over agent-generated commits; Muse VM wipes/disconnects and age-verification walls; Meta AI's 3 separate subscriptions; Figma/Runway agents burning credits on unrequested work; ChatGPT Pro/Codex weekly quota suddenly 0 or zeroed on downgrade; Grok Bot webhook rate-limit false positives and unified-plan upgrade bugs; AI-only customer support (airlines, payments, YouTube) with no human path.
- Stopped at 323 reads left (above the 100 floor) because the agent's context window was nearly full.
- Fourth segment (batches 21-23, pp-2520..pp-2612, +93: b21 +27, b22 +48, b23 +18): new reply-mining accounts (Perplexity/AravSrinivas, Suno, Kling/Hailuo, Trae/Qoder, koraykv/JeffDean, telecom/bank/retail support handles, Roblox/Meta, Hostinger/registrars, Cursor/Anthropic/OpenAI staff not mined before, ZH/JA AI bloggers) plus new keyword angles (AI receptionists/phone bots, AI interviewers, deep research, regional pricing, agent acting without permission, agents lying about fixes).
- New themes: company AI phone/chat support that hangs up, mishears digits, or loops links with no human path; AI moderation ban waves (Roblox, Meta) with appeals auto-rejected by AI; OpenAI/Codex/ChatGPT Business account bans right after renewal with no refund; Grok Bot restarts wiping files, iOS blank chats, local-execution setting ignored, connector state reverting; unified X/Cursor plan billing (old overage settings silently spending credits, failed unification removing paid access, cloud agents burning ~3%/hour); Opus 5.5 / GPT-6 Pro quality regressions; agents invoking other paid tools (Codex, Higgsfield) without asking.
- Stopped at 217 reads left (above the 100 floor) to stay within the agent's context window.
- Scope note: batches 21-23 used a wider scope than the dataset definition and mixed in posts about company AI customer-support phone/chat bots and platform AI moderation bans (Roblox, Meta, telecom/bank/retail support). Those rows are not first-person pain with AI agents/assistants/dev tools; filter them out (category 'support' in b21-b23) when analysing agent/dev-tool pain.
- Final segment (batch 24, pp-2613..pp-2687, +75; en 50 / zh 14 / ja 11): scope tightened back to the original definition (real users' own pain with AI agents, assistants and coding/dev tools; no company AI support or AI moderation). ~109 reads of fresh keyword angles (since 2026-10-12): Xcode/iOS, Playwright, lint/as any, MCP crashes/re-auth, headless -p, subagent cost/opacity, skills ignored, plan mode, resume, token-usage visibility, Copilot review/autocomplete, memory, scheduled tasks, sandbox/Docker/WSL, Co-Authored-By, Codex cloud, desktop-app RAM/battery, connectors; ZH (子代理/规则/测试/沙盒/定时任务/MCP/记忆/上下文/额度) and JA (スキル/ルール/テスト/MCP接続/メモリ/定期実行/トークン/git 勝手に/コンテキスト).
- New themes: subagents dominating cost and quota (40.8% of Claude Code spend; 64-subagent 'ultracode' burning a 5-hour window in minutes; parallel subtasks re-reading the repo) and opaque sub-agent results; Codex cloud as a black box (no commands/edits shown, vanished messages, no local-to-cloud handoff); desktop agent apps eating RAM/battery (Codex app 8-15 GB, Claude Desktop Code tab); plan mode / approval behaviour (Claude Code starting to implement unasked, Copilot plan mode can't read tickets, Codex approve-everything); Codex scheduled runs stuck 'Reconnecting'; Gemini 4 Argon not available in Antigravity on Pro; agents bumping unrelated dependencies or wiping uncommitted edits via git checkout; Grok Bot VM RAM exhaustion, lost inbox/mentions after account merge.
- Round 7 total (2026-10-17): pp-1661..pp-2687, +1027 rows across 24 batches; X reads used today 892 / 1000, stopped at 108 left (100 floor).

## Round 8 (2026-10-18)
- Rows: pp-2688..pp-2944 (+257); categories: quota 70, reliability 35, billing 33, UX 24, integration 20, tools 15, observability 9, cost 9, permissions 8, context 7, support 6, security 5, multi-agent 4, voice 2, memory 2, evals 2, workflow 1, browser 1, privacy 1, scheduling 1, deploy 1, ToB 1
- X reads today: 94 used / 906 left
- Batch 1 (pp-2688..pp-2848, +161): fresh window since 2026-10-16T12Z; product x frustration/wish keyword sweeps (Codex, Claude Code/desktop, Cursor, Copilot, Gemini/Antigravity, ChatGPT Work/Dots, Grok Bot; EN+ZH+JA), plus reply mining of new seeds: thsottiaux Day 13 reset (2111492673890824348) + "Done" (2111566005684289735) + work/personal dot (2111495392559067199), poteto "is chat the final form of agent ui?" (2111321176769442251), CodexResets1 Plus drain (2111396596386611652), elonmusk "Grok Bot got much faster" (2111239586873745604) and X DMs (2111239205951086616), GoogleAIStudio Argon for AI Pro (2111240722426802258), quotes of Day 13.
- New themes: ChatGPT Dots approval loops (auto-approver overriding explicit approvals, Codex-session approvals looping, "Waiting for approval" forever), Dots forgetting tasks / 429 outages / no done-notification / can't remove lost devices; Codex surprise early resets shifting the weekly window and wasting banked reset cards, $500 plan draining like $20, image-containing threads bloating, Computer Use locking the Mac, Windows Explorer freezes; Claude desktop next-step/question box skipping replies and hiding intermediate actions; chat-as-agent-UI breaking down for many parallel topics/swarms.
- Also: Gemini 4 Argon weekly quota gone in 1-3 prompts on AI Pro, Argon missing in Antigravity / bundle (Jio, Coursera, student) accounts, Antigravity real context 256K vs advertised 1M; unified X/Grok/Cursor plan: less usage, lost credits/benefits, wrong-account linking, India checkout failures, Cursor/Grok Bot bans with only AI support replies; Grok Bot can't post to X or read encrypted DMs, background tasks stop at ~50 min, no per-bot token usage.
- Used ~56 X reads (944 left), under the 125 budget, stopped to keep context small.
