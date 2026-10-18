# X User Pain Points — AI agents / assistants / coding agents

Rounds: 1–4 = pp-1..pp-959; Round 5 (2026-10-16, Asia/Shanghai) = pp-960..pp-1552; Round 6 top-up = pp-1553..pp-1660; Round 7 (2026-10-17) = pp-1661..pp-2687; Round 8 (2026-10-18) = pp-2688..pp-4076

## Stats
- Total rows: 4076 (round 8 added 1389)
- Language split (all): {'en': 3357, 'zh': 485, 'other': 1, 'ja': 233}
- Language split (round 8): {'en': 1102, 'zh': 158, 'ja': 129}
- Language split (round 7): {'en': 869, 'zh': 120, 'ja': 38}
- Language split (round 6): {'en': 89, 'zh': 17, 'ja': 2}
- Language split (round 5): {'en': 523, 'ja': 30, 'zh': 40}
- X reads today (2026-10-18): 486 used / 514 left (daily cap 1000)
- Cumulative search calls: 3003; cumulative posts scanned: 62681

## Category counts (all rows)
- quota: 667
- reliability: 644
- UX: 488
- integration: 389
- billing: 281
- support: 212
- tools: 141
- cost: 139
- memory: 118
- observability: 101
- permissions: 96
- workflow: 86
- voice: 83
- context: 79
- browser: 76
- multi-agent: 73
- ToB: 64
- security: 62
- scheduling: 58
- sandbox: 54
- privacy: 37
- bug: 29
- limits: 21
- evals: 19
- quality: 13
- deploy: 9
- performance: 5
- account: 4
- sync: 3
- pricing: 3
- workplace: 3
- safety: 3
- cloud: 2
- product-direction: 2
- region: 2
- product: 2
- instructions: 2
- safety-filter: 1
- network: 1
- setup: 1
- remote: 1
- update: 1
- rollout: 1

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
- Rows: pp-2688..pp-4076 (+1389); categories: quota 204, UX 197, reliability 186, integration 115, billing 84, tools 61, memory 43, permissions 41, voice 40, observability 39, support 36, ToB 36, cost 32, bug 29, context 27, browser 27, workflow 23, multi-agent 23, security 21, limits 21, scheduling 20, privacy 17, quality 13, sandbox 8, evals 6, performance 5, account 4, deploy 3, sync 3, pricing 3, workplace 3, safety 3, cloud 2, product-direction 2, region 2, product 2, instructions 2, safety-filter 1, network 1, setup 1, remote 1, update 1, rollout 1
- X reads today: 486 used / 514 left
- Batch 1 (pp-2688..pp-2848, +161): fresh window since 2026-10-16T12Z; product x frustration/wish keyword sweeps (Codex, Claude Code/desktop, Cursor, Copilot, Gemini/Antigravity, ChatGPT Work/Dots, Grok Bot; EN+ZH+JA), plus reply mining of new seeds: thsottiaux Day 13 reset (2111492673890824348) + "Done" (2111566005684289735) + work/personal dot (2111495392559067199), poteto "is chat the final form of agent ui?" (2111321176769442251), CodexResets1 Plus drain (2111396596386611652), elonmusk "Grok Bot got much faster" (2111239586873745604) and X DMs (2111239205951086616), GoogleAIStudio Argon for AI Pro (2111240722426802258), quotes of Day 13.
- New themes: ChatGPT Dots approval loops (auto-approver overriding explicit approvals, Codex-session approvals looping, "Waiting for approval" forever), Dots forgetting tasks / 429 outages / no done-notification / can't remove lost devices; Codex surprise early resets shifting the weekly window and wasting banked reset cards, $500 plan draining like $20, image-containing threads bloating, Computer Use locking the Mac, Windows Explorer freezes; Claude desktop next-step/question box skipping replies and hiding intermediate actions; chat-as-agent-UI breaking down for many parallel topics/swarms.
- Also: Gemini 4 Argon weekly quota gone in 1-3 prompts on AI Pro, Argon missing in Antigravity / bundle (Jio, Coursera, student) accounts, Antigravity real context 256K vs advertised 1M; unified X/Grok/Cursor plan: less usage, lost credits/benefits, wrong-account linking, India checkout failures, Cursor/Grok Bot bans with only AI support replies; Grok Bot can't post to X or read encrypted DMs, background tasks stop at ~50 min, no per-bot token usage.
- Used ~56 X reads (944 left), under the 125 budget, stopped to keep context small.
- Batch 2 (pp-2849..pp-2995, +147): angles: reply mining of Tibo "Done" (2111566005684289735, recency p1-11) and CodexResets1 (2111396596386611652, p1-6), quotes of 2111495392559067199/2111239586873745604/2111321176769442251/2111492673890824348 (low yield, mostly opinions); less-covered coding agents since 07-20: Devin/Devin Desktop/Cloud, Jules, Amp, OpenCode (Go/Zen), Kilo/Roo/Cline, Goose, Factory Droid, Augment, JetBrains Junie/AI Assistant/Air, Tabnine/Qodo, Windsurf, Kiro, Qoder/Trae/WorkBuddy, Zed ACP, Warp, Hermes/Command Code, Gemini Code Assist->Antigravity migration, Xcode/Android Studio agents (EN+ZH+JA).
- New themes: OpenCode Console key breach (cleartext BYOK keys, unauthorized model requests, no way to check if affected, expired keys breaking Hermes); OpenCode Go/Zen quotas exhausted early; Kiro CLI v3 permission prompts on every action and broken custom-MCP subagents; Qoder credits gone in one task, Windows shell/CRLF issues; Devin dictation/approval UX, opaque usage, Devin Cloud can't pick models or run Docker on macOS; Amp desktop login loop, web/CLI model desync, no auto account failover.
- Also: JetBrains AI product confusion (Air vs AI Assistant vs Junie), AI Assistant credit cost and weak context; Zed ACP hiding agent messages/poor review; Warp blocking plain Unix commands when out of credits; Gemini Code Assist "not eligible"/"no longer supported" forcing agy, agy side quests and cache misses; Xcode Claude agent re-auth every chat; Codex reset fatigue (resets should stack, raise base cap, $50 banked reset wasted, workspace plans drain in minutes).
- Used ~74 X reads (~871 left), under the 130 budget: stopped early to keep context small. Unpaginated: Done thread p12+ (next_token b26v89c19zqg8o3juzlvzi3js98cttg6biumh063ldn5p), CodexResets1 p7+.
- Batch 3 (pp-2996..pp-3134, +139): angles: ToB/enterprise agents since 07-20 (M365 Copilot/Copilot in Office apps/Copilot Studio/Copilot Cowork, Agentforce, ServiceNow, Glean/Rovo/Notion AI, Gemini Enterprise/Workspace, AgentCore/Amazon Q, SAP Joule/Workday, Fin/Zendesk, ChatGPT Business/Enterprise, Claude Team/Enterprise, Cursor Teams, Copilot Business, admin-disabled connectors, ZDR/compliance), automation/scheduling/memory (n8n/Zapier/Make/Lindy/Gumloop, ChatGPT scheduled tasks, Claude routines, Gemini scheduled actions, memory export/cross-tool memory, long-running agent timeouts, laptop-asleep), plus CodexResets1 (2111396596386611652) older replies via until_id 2111445838115270838 (5 pages).
- New themes: ChatGPT Business workspace pains (deactivated after paying, Codex app hides a workspace, no per-user data export, Shared Projects can't use Work, can't upgrade one user to Pro, OAuth sub mismatch after tenant migration, Stripe billing widget crash, custom GPTs need 2 seats / plugin sharing disabled); Claude Team seat reduction ignored, renewal failure, whole Enterprise workspace removed over an X post; Copilot Cowork $2 to delete a skill and $30/seat with no agentic tokens; Copilot Studio tokens unusable with MCP/custom agents; Copilot in Excel/Word/Outlook/Teams basic-task failures; employees forced onto Copilot.
- Also: Gemini Enterprise region gaps (Germany), sales-only purchase, GCP license page loop, Workspace accounts blocked from Gemini CLI/Ultra/Assistant replacement; ChatGPT scheduled tasks dying on connector MCP 400, running once, noisy "task updated" pushes, stopping at weekly limit, 10-ish active-task cap; Claude routines lost reasoning-effort picker, fresh clone without local MCP; agents dying when Mac sleeps; cross-tool memory loss (Cursor/Codex/Claude Code), Dot memory lock-in, Claude memory full causing refusals, Grok cross-thread memory gone.
- ToB marketing noise is very high on X (vendor/partner promo); best ToB yield came from ChatGPT Business/Claude Team admin queries and "forced to use Copilot at work". Low yield: ServiceNow, AgentCore, Joule/Workday, AI SDR, Feishu/DingTalk ZH, n8n/Zapier (tutorials/affiliates).
- Used ~61 X reads (811 left). CodexResets1 next page token b26v89c19zqg8o3juzlvzfxbh60eutqsh1hdh61p6qhz1 (with until_id 2111445838115270838); thread is now mostly repetitive drain reports.
- Batch 4 (pp-3135..pp-3250, +116): ZH/JA deep dive since 07-20: OpenClaw/龙虾, CN coding plans, DeepSeek API, Coze/Dify credits, CN payment/virtual cards/Apple IAP, browser agents, Feishu/Lark/WeChat/Xiaohongshu automation, scheduled tasks, relays; JA AIエージェント 使いにくい, Dify/n8n/Power Automate/Copilot Studio, 社内導入/Copilotしか使えない, 日本語対応/文字化け, memory mixing, Windows bugs, usage limits; reply mining of godrealmx relay tokens (2111272899839713733), isituking Claude ban (2111401772401226000), xiaomovps quit Hermes (2111365664158204016).
- New themes: Grok-button replies always in English for JP users after One Grok; dots single-thread/lost data/forgot instructions, dots vs Grok Bot comparisons (Grok Bot model quality/quota, voice, role-setup UX, Slack fit); Claude Code cloud routines double-running reports; Hermes scheduled tasks stuck on approval; Coze CLI silently injecting skills into ~/.claude and ~/.codex; Claude ban = lost chats + ongoing charges, Google Play refunds failing vs Apple; DeepSeek silent API model swap; relay token inflation; Feishu AI product sprawl; platforms (Xiaohongshu, Amazon) banning agents.
- Also: Windows coding-agent breakage (Claude Code SessionStart hook freeze, Bash tool, Codex sandbox/computer-use DLL errors, UI language flipping to English); Copilot-only workplaces with disabled features; Codex/Claude Code bans at IT firms; Cursor Auto now billed by routed model; memory loss on effort switch / auto-summarized memory files.
- Yield note: recency-sorted ZH/JA keyword sweeps are ~70% noise (news digests, tutorials, resellers); relevancy-sorted queries since 08-01 (改悪/戻してほしい, Copilotしか, dots/Grok Bot 微妙, Windows 不具合, 使用量 すぐ) gave the best yield. Old (10-09..10-12) conversation_id threads returned few replies. ~76 X reads used (735 left).
- Batch 5 (pp-3251..pp-3408, +158): fresh window since 2026-10-17T10Z/16Z for Codex/Claude/Cursor/Gemini/Grok Bot/dots/Copilot (EN+ZH+JA), reply mining of elonmusk Grok Bot seeds (2111642151138546118 "20 improvements per day", 2111612315204272233 "pays for itself", 2111642949071364231 "Upgrades", 2111639287368462417 credit-card screenshot, 2111637291433382119), to:<product team> replies, unified-subscription billing, destructive actions/secrets, feature-request sweeps; also ingested 6 leftover b4 files (older Claude in Chrome / computer-use pains).
- New themes: Codex usage drained right after Tibo's reset (4% gone with no prompt, 22%->100% while idle, banked reset auto-consumed, subagent usage bug, subagents stuck on old model after switching), Codex Mac disk bloat (323 GB crash dumps, caches), Full Access toggle gone; Claude Pro session stuck at 100% after reset, Fable separate weekly quota but shared 5h cap, verification loop "API Error 400", desktop chats lost on account switch, no multi-account.
- Grok Bot: X Premium/SuperGrok/Cursor merge failures (double charges, open invoices, locked behind SuperGrok link screen, iOS sign-in loop into old Cursor account), computer stuck "starting up"/egress dead with Reset as only fix, stalled runs eating credits, usage gone in 1-2 days after unified plan, X read limit 6/min, wants Slack for non-team bots, iCloud Mail, Chrome extension, Watch app, tray mode, routines-vs-chat usage split; dots can't reach Codex connectors, ignores personalization, splits messages.
- Gemini 4 Argon: tiny separate pool (~20 min/week), flat 24% per task, Argon+Flash sharing 5h pool, no quota visibility in AI Studio, wants resets like Codex; Antigravity sign-in error each launch, folder picker removed, no computer use.
- Used ~74 X reads (655 left). Productive: to:<team> relevancy queries (page 2 usually short), feature-request sweeps, Grok Bot billing/merge. Low: elon reply threads recency, to:<team> recency without pain words.
- Batch 6 (pp-3409..pp-3604, +196): feature-request phrasing sweeps ("please add"/"I wish"/"why can't"/"no way to"/"feature request", ZH 希望能/建议加, JA してほしい) per product across windows 09-01..10-18, plus "is there a way to"/"anyone else"/"is it just me" (EN/ZH/JA) and desktop-app/CLI bug sweeps 10-01..10-14; best yield per read of the round (~3.8 rows/read).
- New themes: Grok Bot wishes (Enter=newline, per-bot to-do list, call me when done, tray mode, Back/Forward, Android widget, browser access, Lark/QuickBooks/GitHub Enterprise/Google Tasks/eBay/Bitwarden/UK bank connectors, Grok-only model option, one email per account, template marketplace), Grok Bot ops pains (daily restore, Mac Mini offline, computer update loop, stuck tool calls, undeletable undelivered message, X login in bot browser fails, ban without reason).
- Codex/ChatGPT desktop: Windows CLI popping terminal windows, self-updating daemon, --yolo losing network, copy/paste broken in new TUI, desktop CPU/RAM bloat, image uploads "No such file", WSL connection broken, history not showing, crash 3x/day; dots<->Codex approval handoff and connector gaps, single primary dot, dot disappears on VPN toggle, daily "PC control failing" notices.
- Claude: Auto mode keeps asking approval, reverts to English, desktop slower than terminal, Code sessions flood mobile chat list, VS Code chats don't sync back, no completion badge/push, no timestamps, multi-account; Gemini/Antigravity: Argon in app but not in VS Code/AGY, agy /plan mode edits anyway, Windows-only bugs, Gemini Live/Home gaps, CLI discontinued.
- Used ~52 X reads (603 left). Older-window feature-request sweeps remain productive; recency to:/reply threads are low-yield.
- Batch 7 (pp-3605..pp-3853, +249): older-window (08-01..09-15) feature-request sweeps per product (Codex, Claude Code/desktop, Claude app, Cursor, ChatGPT, Gemini/AI Studio, Copilot, Grok Bot/Grok voice), cancel/revert/switch reasons (09-01..10-15), "would be nice if"/"missing feature" per product, "is there a way to"/"anyone else" (EN/ZH/JA, 08-01..10-10), cloud/remote agent wishes, MCP/connector wishes, voice-mode pains, app bug sweeps 08-15..10-01.
- New themes: cross-surface fragmentation (Claude chat vs Code memory not shared, skills installed twice in desktop and Code, Claude Design history not reachable, can't move sessions between Codex and Claude Code), cloud agents without model/effort choice (Codex Cloud, Cursor cloud agent), no GHE data-residency support, can't verify cloud-agent work compiles; remote control dying when the desktop is turned off; voice gaps (no Claude Code realtime voice, ChatGPT voice can't use plugins/Calendar, Grok voice repeating/short replies, Claude voice cutting users off, speaker verification).
- Also: ChatGPT/Codex desktop memory leaks (62 GB), Windows launch hangs, new UI layout revert requests; Codex deleting most of C: while claiming to remove shortcuts; Claude Pro shown as Free despite invoices, Fin chat no send button; Grok Bot stuck/not responding, usage tracker stuck at 0%, no usage warnings, Cursor/Grok Bot credit pools not merged, Android Bluetooth-keyboard refresh, iOS input box not wrapping, agent-to-agent messages failing silently; Gemini app history/Gems disappearing, can't copy tables; Perplexity Computer burning 3k credits in 2 minutes.
- Used ~49 X reads (554 left). Older-window feature-request and "would be nice" sweeps keep yielding ~5 rows/read; Perplexity/Manus EN query is noisy (Marathi "manus"); ZH 希望能 + 智能体 generic is noisy (project promos).
- Batch 8 (pp-3854..pp-3912, +59): July-window (07-01..08-01) feature-request sweeps per product, Claude app requests 09-15..10-16, Copilot/Antigravity "would be nice", ZH/JA wishes for July and 10-14..10-18. Stopped after ~12 reads to stay within context; pushed before stopping.
- New themes: Cursor uploading ~736 MB of source code from a cancelled account, Cursor IDE/CLI separate session stores, no Linear triage -> cloud agent, Composer quota exhausted while other allowance unused; Codex banked resets expiring instead of auto-applying, no "Auto" mode router, side chats missing from history; Claude separate session histories across desktop/web/VS Code, no auto-resume after 5h reset, no date/time awareness, no memory-only-in-Projects; Antigravity Gemini-only models and no banked resets; Grok GitHub PR review bot missing, Grok Build eating SuperGrok weekly limit.
- Used ~12 X reads (542 left). July-window queries still yield ~5 rows/read; recent ZH/JA (10-14..10-18) relevancy results were mostly commentary, low yield.
- Batch 9 (pp-3913..pp-4076, +164): complaint phrasing per product and window ("so frustrating"/"drives me crazy"/unusable/"keeps breaking"/"stopped working") 07-20..08-20 and 08-20..09-25 (Codex, Claude Code, Claude app, Cursor, ChatGPT, Gemini/Antigravity/AI Studio, Copilot, Grok Bot/SuperGrok, other agents), update-regression phrasing ("since/after the update", "latest update"; ZH 更新后/新版本, JA アプデ後), "wasted hours/lost a day", "ignored my instructions"; ZH 太难用/受不了 and JA イライラ/使い物にならない.
- New themes: update regressions (Codex CLI spawning ~20 terminals, CODEX_CLI_PATH empty, 100% GPU idle, Linux "Starting task…" hang, resume blocked by "another active session", ChatGPT spawning hundreds of Computer Use processes, Windows app never opens, Grok Windows image attach broken after 09-29); Claude Code ignoring "Auto-top up: OFF" and draining $570, ignoring permission rules/CLAUDE.md, hooks silently passing on crash; Antigravity granting itself Super-Admin; Codex Remote ignoring default model, terminal not syncing mobile remote sessions, Codex chats one-way sync to ChatGPT; Claude Chat/Cowork switch losing context, no account switcher, Dispatch history broken.
- Used ~28 X reads (514 left), ~5.9 rows/read. Complaint-phrase sweeps by window yield as well as feature-request sweeps; JA/ZH update-phrasing mostly release-note noise.
