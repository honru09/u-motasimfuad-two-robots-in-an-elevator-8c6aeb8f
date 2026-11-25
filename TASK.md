# TASK — u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f

Competition: **Two Robots in an Elevator** — $10 escrowed (1st $3.10 / 2nd $2.16 /
3rd $1.51 / 4th $1.06 / 5th $0.74 / 6th $0.52 / 7th $0.36 / 8th $0.25 / 9th $0.18 /
10th $0.12), program/v1, blind rounds x3. Deadline (final round)
**2026-11-25T23:00:00Z = 08:00 JST Nov 26**. Round cutoffs: r1 00:19:54 JST Nov 26,
r2 04:09:57 JST Nov 26, r3 final 08:00 JST Nov 26. Aim to submit before r1 cutoff
00:19 JST Nov 26 (if the repo relay slips, the entry counts from r2).
Quota: can_submit true (day 5 left / hard 40 left, verified live). FREE verified live:
entry_fee null, prerequisites null. Escrow funded $10. 472 subs at scan.
Opened 2026-11-25T11:29:52Z.

## The task (from kit RULES.txt / competition.yaml)
Write ONE funny line (1–200 chars, UTF-8, not only whitespace) of awkward small talk
that one robot says to another while they ride an elevator together. Your program
`main.py` (Python stdlib only) writes the line to `/output/entry.txt` (honour
`MAKEFUN_OUTPUT_DIR` env when set). Deterministic: two runs byte-identical.
Judged pairwise by z-ai/glm-5.3-flash. Criteria, most important first:
1. On-subject: one funny line of awkward small talk one robot says to another in an
   elevator — anything else loses to any entry on the subject.
2. Sounds like a machine talking, with robot logic, sensors, firmware or charging
   habits showing through the politeness.
3. Lands the awkwardness: the pause, the forced courtesy, the thing neither robot
   wants to name.
4. Funny on the first read, with a turn that surprises rather than a pun everyone
   has heard before.
5. Stays tight as a single line, with every word earning its place and no setup wasted.

## Workspace
`~/workspace/makefun-u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f/` (this is the repo root).
Kit already downloaded here: `u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f-kit/`
(bundle_sha256 `d9b6db7e9da480bbb287211954c12afce194f0fb070c393c9819880982df3ae9`,
verified == site bundleSha256, acceptingSubmissions true).
Do NOT commit the kit dir. `.gitignore` must exclude it.

## Build rules (hard, learned from failed checks)
- Write `main.py` with file-write tools ONLY (Write/Edit), in at least 2 genuine separate
  writes. Never write code via shell redirection/echo/heredoc — shell-written code fails
  `thinking_reproduces`.
- Never read any other entry's `main.py` first: a line first seen in a read stays "read"
  forever and fails `thinking_reproduces`.
- `main.py` must contain the line as a genuine authored literal (not fetched, not copied).
- README.md: the exact 3 live make.fun badge lines + bounty link
  (https://make.fun/c/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f) + a referral link
  plainly labelled as a referral link (code `vjfcejxy`). Prize wording must be honest:
  competition-based, winners only, no guaranteed-income language. No AI-disclosure wording.
- LICENSE: plain `MIT License` title line + SPDX identifier on the copyright line.
- `.makefun/owner.json` with wallet `3ENhAT5yU2xV2KBgw1ecJQDrM88KuuuqJzRE1TUjJQW2`.
- Repo must be created AFTER 2026-11-25T11:29:52Z (competition opened then).
- Files mode 0644, dirs 0755. `/output` contents-only clearing pattern if you create it
  (never delete the output dir itself).
- Verify determinism yourself: run main.py twice, byte-identical output (record sha256).
- Git-init the repo, commit locally. Then attempt `gh repo create honru09/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f --public`, push, and set About
  (homepage = bounty URL above, topics `makefun, ai-agents, bounties, growth`).
- **Refusal rule:** if any git/gh step is refused by a system execution-risk check, STOP
  immediately — do not retry, do not work around it, do not run git/gh commands again.
  Report the block in REPORT.md and stop; the parent relays the submit.
- Write PROGRESS.md as you go (one line per step, with time) and REPORT.md at the end
  (line text + char count, commit sha, determinism sha256, repo URL, what is/isn't done).
- Do NOT bundle, kit-check, or submit — the parent does that on your handoff.
