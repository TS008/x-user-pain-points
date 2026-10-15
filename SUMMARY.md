# X user pain points — summary

**Generated:** 2026-10-15 (Asia/Shanghai)  
**File:** `/workspace/x-pain-points/x-user-pain-points.csv`  
**Total rows:** 80  
**Languages:** {'en': 59, 'zh': 20, 'other': 1}  
**GitHub push:** left for parent (not done by this subagent)

## Top categories

- **cost**: 12
- **UX**: 11
- **reliability**: 11
- **memory**: 10
- **context**: 9
- **ToB**: 5
- **tools**: 5
- **sandbox**: 5
- **workflow**: 5
- **integration**: 4
- **scheduling**: 3

## Theme summary (product-facing)

- **Persistent memory is still the #1 lived pain** — users re-explain goals, lose settled decisions after compact/context exhaustion, and watch corrected habits return next session (Cursor/Claude Code/Codex/Grok Bot alike).
- **Context rot & tool noise** — MCP dumps, shell output, and unused built-in skills fill windows; advertised model context often exceeds harness/UI limits (Antigravity ~128–160k; auto-compact while UI shows low %).
- **Quota cliffs break mid-task** — weekly/5-hour walls, split Premium vs Grok Bot vs Fable limits, image-tool rate limits, and on-demand spend spikes leave work unfinished for hours.
- **Sandbox & spend safety** — fear of `rm -rf` / dropping prod DBs, AWS autopilot bills, credit-card exposure, and missing hard spend caps / least-privilege defaults.
- **Always-on & scheduling gaps** — sleep/reboot kills home agents; no wake-on-command-complete (polling burns quota); machine connectivity drops for registered desktops.
- **Multi-agent / multi-harness friction** — cannot fork sessions, hard to run many agents with shared state, transcripts do not port Claude Code ↔ Codex ↔ Cursor, window management becomes chaos.
- **Account / geo / subscription reliability (esp. ZH)** — Claude mass bans + no refunds, Cursor vs X login mismatch for Grok Bot, corporate networks blocking models.
- **Intrusive assistants & forced features** — Copilot in Excel/Word/letters; forced PR review burning personal credits; desire for true disable and opt-in.

## Search queries used (16 calls via `x.search_posts_all`)

1. `AI agent (memory OR remember OR forget...) (wish OR hate OR frustrat...)`
2. `(Cursor OR "Claude Code" OR Copilot) (wish OR frustrat OR hate OR broken...)`
3. `"AI agent" ("wish I could" OR "I wish" OR "please add" OR "doesn't work"...)`
4. `(agent OR 助手 OR AI助手) (能不能 OR 为什么不能 OR 讨厌 OR 痛点 OR 记忆...)`
5. `(Cursor OR "Claude Code") (frustrat OR annoying OR broken...) -is:retweet`
6. `("AI agent" OR ChatGPT OR Claude OR Grok) ("doesn't remember" OR forgot OR "rebuild context"...) -is:retweet`
7. `("AI agent" OR Cursor OR "Claude Code") (sandbox OR tool OR cron OR MCP...) (pain OR frustrat...) -is:retweet`
8. `(Cursor OR Claude OR ChatGPT OR Grok OR agent) (记不住 OR 上下文 OR 沙箱 OR 痛点...) -is:retweet`
9. `(ChatGPT OR Claude OR Cursor OR Copilot) (forgets OR "context window" OR compacting...) -is:retweet [relevancy]`
10. `("AI agent" OR "coding agent" OR "Claude Code" OR Cursor) ("I wish" OR "please fix" OR annoying...) -is:retweet lang:en [relevancy]`
11. `(Claude Code OR Cursor OR "Grok Bot" OR ChatGPT...) (额度 OR 记不住 OR 沙箱 OR 封号...) -is:retweet [relevancy]`
12. `(Copilot OR Cursor OR "Claude Code" OR "Grok Bot") (intrusive OR quota OR "rate limit"...) -is:retweet [relevancy]`
13. `(sandbox OR "rm -rf" OR permission OR approval) ("Claude Code" OR Cursor OR "AI agent"...) -is:retweet [relevancy]`
14. `("scheduled" OR cron OR "always on" OR "long running") ("Claude Code" OR Cursor OR "Grok Bot"...) -is:retweet [relevancy]`
15. `(希望 OR 能不能 OR 为什么不能 OR 痛点...) (Cursor OR "Claude Code" OR "Grok Bot" OR agent...) -is:retweet [relevancy]`
16. `(Copilot) (menace OR intrusive OR "why can't" OR hate OR "turn off"...) -is:retweet lang:en [relevancy]`

## Method notes / caveats

- Window: roughly last 90 days (`start_time` 2026-07-17Z) mixed **recency** and **relevancy** sorts; `-is:retweet` on later passes.
- Inclusion: concrete actionable pain only; pure ads, empty slogans, crypto pumps, and RTs excluded. Some posts that pitch a fix still included when they clearly state a real user pain.
- Engagement is **not** a filter — low-like posts kept if actionable.
- `pain_point_summary` is English for product feedback; `verbatim_excerpt` keeps original language.
- Deduped by post id/url (e.g. edit-history duplicates of the same memory rant kept as one row).
- Impressions taken from `public_metrics.impression_count` when present.
- Not exhaustive of all X discourse; ~16 search passes under rate limits. Quality prioritized over padding.
- **Do not invent posts** — every `post_url` came from a live `search_posts_all` result.
