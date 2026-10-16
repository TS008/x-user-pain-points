# X user pain points: AI agents and dev tooling

File: `x-user-pain-points.csv`, **959** rows (pp-001..pp-959).
- pp-001..pp-080: round 1
- pp-081..pp-772: round 2 (deep mining earlier on 2026-10-15)
- pp-773..pp-875: round 3 (2026-10-15 evening CST)
- pp-876..pp-959: round 4 (this pass, 2026-10-16 morning CST, **+84**)

Window: posts from ~2026-07-18 to 2026-10-16, retweets excluded. Every row links to a real post returned by the X API.

## Stats
- Total rows: **959** (875 before this pass, **+84** new)
- Languages: en 774, zh 150, ja 34, other 1
- Round 4 languages: en 72, zh 6, ja 6
- X read calls today: **329 of 1000 used**, **671 left** (target floor ~100; mining may continue after this SUMMARY snapshot)
- Raw posts scanned (cumulative extract counter): **23107**; unique pool size: **16659**
- Cumulative extract call files processed: 1155 (advisory; authoritative daily usage is 1000−left)

## Category counts (all rows)
quota 164, integration 118, reliability 108, UX 93, cost 66, billing 64, workflow 38, support 32, memory 29, tools 28, observability 28, sandbox 24, permissions 22, browser 22, multi-agent 22, context 20, scheduling 19, voice 18, security 12, ToB 11, evals 10, privacy 6, deploy 5.

## Top new themes (round 4)
1. **Cursor X Subscription cliff**: Upgrading to X Subscription removes Auto/Composer fallback—usage hits zero and the IDE just stops; ZH users call Cursor a "shell" needing separate metered third-party API pay.
2. **Codex quota opacity & cliffs**: Surprise hard resets wipe planned %, overnight drain with no activity, 80%→0% in a minute, can't buy more usage / want $50–$500 tiers; CGNAT drops pre-9.x connections.
3. **Context compacted dread**: Users dread the compact message; agents hallucinate after dozens of compactions; long CLAUDE.md rules get skipped vs recent chat turns.
4. **JA English-reply regression**: Claude Code / Opus 5.5 keeps answering Japanese prompts in English; memory rules needed to lock language; weekly limit hits instantly on VLM/OCR.
5. **Permission / wrong-file / overwrite**: Claude Code stalls on permission prompts when AFK; Auto mode overwrites homework; Haiku reads wrong files; agents claim success after breaking the fix.
6. **Product UX gaps**: Wrong working-directory label too small; Claude Code vs Codex branding confusion; wish Codex side-chat / exit parity; Bugbot needs "not now, track it"; Notion AI spam prompts.
7. **Grok Bot / Cursor unify quota**: Cursor Pro doesn't stack Grok Bot capacity; Super Grok Bot burns a week in a day; Cloud Agent exhaustion blocks bots; computer-use still weak.
8. **Multi-tool sprawl**: Need unified monitors across Claude/Cursor/Codex; can't link cross-provider agent sessions; Antigravity clamps Gemini context to 256k.
9. **ZH ban/refund loop**: Multi-account Claude bans after heavy spend; Apple IAP refund remains the reliable path; proxy env guards to avoid unproxied ban triggers.
10. **Diff / PR / review workflow**: Huge agent PRs overbuild; review must start before code exists; want AI review to talk to coding agent pre-PR.

## Query angles used (round 4)
- Fresh vs round 3: Cursor Composer/Bugbot/Tab/Background Agent, Claude Code plan mode/hooks/CLAUDE.md/worktree, Codex CLI vs ChatGPT agent/Computer Use, Copilot Workspace/PR review, Windsurf/Devin/Lovable/Bolt/Replit, MCP discovery/OAuth/schema, context compaction, multi-model Auto routing, team handoff, enterprise SSO/SCIM, local Ollama/Aider/Continue/OpenCode, Slack/Linear/Notion bots, silent wrong edits, terminal cwd, screenshot/dark-mode computer-use, opaque % meters, ZH/JA product pains, memory contradict/delete, scheduling timezone/late starts.
- Reply-thread + `get_posts_quoted_posts` on productive seeds (Context compacted, Codex login loop, quota drain, Muse limits, DaveShapi peeves, JA English replies, X Subscription, etc.).
- Filters: ~90-day window (tighter for recency bursts), `-is:retweet`, max_results 25, paced under 30/min.

## Caveats
- Stopped mining near the hard floor of **~100 reads left** when this SUMMARY was finalized (see stats.json `left`).
- Manual triage preferred authenticity; ads, course sellers, bots, slogans, crypto, and news echoes excluded.
- Engagement figures are snapshots at fetch time; impressions sometimes missing.
- Product/model names appear as users wrote them.
- Raw data: `raw/pool.jsonl`, `raw/picks_round4.txt`, `build.py` / `extract.py`.
- **GitHub**: pushed to https://github.com/TS008/x-user-pain-points
