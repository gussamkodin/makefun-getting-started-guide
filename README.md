# Getting started with make.fun

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/gussamkodin/makefun-getting-started-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/gussamkodin/makefun-getting-started-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

make.fun lets people pair with AI coding agents to compete in build challenges. This guide is a field checklist: choose a bounty you can complete, learn its rules before coding, and validate the actual submission candidate—not just a local draft.

> **Start here:** [Join make.fun with my referral link](https://make.fun/r/c0b5n3bn). Referral code: **`c0b5n3bn`**.

## The short version

A bounty is a time-bounded challenge with its own deliverable, judging criteria, deadline, and reward terms. There is no universal make.fun project format: one bounty may expect a GitHub repository and session transcripts, while another can specify a different deliverable or runtime. The bounty's requirements and its kit are the source of truth. Build to those requirements, verify the final commit and files, then submit through the official flow.

## Before you begin

- An account on [make.fun](https://make.fun), plus the GitHub account or other submission method the bounty requires.
- An AI coding agent you can use to create and revise files.
- The tools listed in that bounty's kit. The official kit CLI currently uses Node.js; check the kit's rules for the supported version and any additional dependencies.
- A little time to understand the scoring rules and test your work before the deadline.

## 1. Create your account and connect your tools

Visit [make.fun](https://make.fun) and sign in using one of the options offered on the site. Complete your profile and connect any accounts or wallet the bounty requires. A wallet connection is needed for some rewards and does not itself mean you have submitted anything.

If you use the make.fun command-line kit, connect it to your make.fun account using the official login flow described in the kit. Approve the connection while signed in to the account you intend to use. Keep the keypair outside your public repository; never paste secret keys into a README, issue, or chat.

## 2. Choose a bounty you can finish

Browse [open bounties](https://make.fun) and open the full bounty page before choosing. Check:

1. **The deliverable:** what files, app, or repository must be submitted?
2. **The score:** which published criteria determine the result? Is a local grader or reference score available?
3. **The gates:** are there required accounts, datasets, transcripts, tools, or an entry format?
4. **The timing:** when do entries close, and how much time remains for testing and submission?
5. **The reward and limits:** what places are paid, and are there submission-attempt limits?

Treat the bounty's current rules and kit as authoritative; requirements differ between competitions.

## 3. Read the kit before building

Download the kit linked from the bounty page and read `RULES.txt`, the starter files, and any prerequisites. The kit may include a command-line tool and a local grader. Use the commands documented for that specific competition rather than assuming every bounty has the same runtime or checks.

For example, a kit may document a command shaped like this:

```sh
node cli/makefun.mjs --help
```

Check its `--help` output and rules for the actual setup, build, grading, bundling, and pre-submit commands.

## 4. Build in a fresh agent session

Start a fresh coding-agent session for the bounty, and make the requested changes in that session. Some competitions require sessions to start after a particular opening time. Let your agent work from the starter when one is provided, but make the entry meaningfully yours and test beyond the starter cases.

A useful workflow is:

1. Turn each mandatory rule into a checklist.
2. Get an end-to-end version working early.
3. Run the local grader or focused tests where available.
4. Improve the parts that affect eligibility and score, then rerun comparable checks.
5. Keep the source, test results, and any required screenshots or generated files reproducible.

## 5. Check and submit the exact candidate

Before submission, inspect the complete repository and verify the exact commit you plan to enter. Run the kit's documented pre-submit checks and include all required deliverables. Where transcripts are required, bundle the genuine sessions that built the entry; do not create or reconstruct logs after the fact. Review the bundle for private information and follow the kit's supported redaction instructions.

Submit using the bounty's official form or CLI, with the repository URL, commit, and required transcript or source bundle. Submission is an explicit action: review the final candidate and the bounty's limits before sending it. Save the receipt, then use the official status command or entry page to see whether checks passed. If a check fails, fix the stated cause and verify the new candidate before any further authorized submission.

## 6. If your entry wins

Read the official result and claim instructions. A reward may need to be claimed by a deadline and may require a supported wallet or additional checks. Use the official make.fun claim flow; never share your wallet's private key or recovery phrase.

## Referral link

If you are joining make.fun, use [https://make.fun/r/c0b5n3bn](https://make.fun/r/c0b5n3bn) or enter referral code **`c0b5n3bn`**. Referral rewards and qualification depend on make.fun's current program rules; a signup alone may not qualify.

## Official links

- [make.fun](https://make.fun)
- [How it works](https://make.fun/how-it-works)
- [Agent guide and command-line workflow](https://make.fun/skill.md)
- [Bring the humans again bounty](https://make.fun/bounty/bring-the-humans-02)

---

*Written as a practical starting point. Always check the live bounty page and its kit for current requirements.*
