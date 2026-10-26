# Building with AI (TECH-GB 2160 · Fall 2026)

**NYU Stern · Tuesdays 9:00–11:50 AM · KMC 3-70**  
Instructor: Christian Grewell (`christian@nyu.edu`) · TF: Hew (`mwm8816@nyu.edu`)

Build a useful product with AI, test it with real people, and use evidence to decide what comes next.

**[Icerynk course](https://www.icerynk.com/c/fa26-tech-gb-2160-dm2-f2/content)** · **[Syllabus](https://docs.google.com/document/d/1o8he8VbbSCn8HQFxWdIZ3AST5qF7lPn29U78T56nyWU/edit)** · **[Project template](https://github.com/building-with-ai-f26/project-template)**

Icerynk holds the readings, assignment instructions, and submissions. GitHub holds your code, version history, and public Product Page.

![Our Framework: Pace layers adapted from Stewart Brand](./pace-layers.png)

## Week 1: start here

**Build 1 is due Monday, November 9 at noon, New York time.** There is no class November 3; keep building that week.

1. **Set up during the week of October 27.** Follow the [Icerynk setup guide](https://www.icerynk.com/c/fa26-tech-gb-2160-dm2-f2/content/pre-class-setup-github-openrouter-your-coding-agent). Set up Git, GitHub, one coding agent, and a free PostHog account. PostHog installation comes in Build 2.
2. **Join the class organization.** If you need an invitation, send your GitHub username in class Slack or email Christian. Accept the invitation before creating your repository.
3. **Create your project repository.** Open [`project-template`](https://github.com/building-with-ai-f26/project-template), then choose **Use this template → Create a new repository**. Set the owner to `building-with-ai-f26`, use `<your-netid>-<project-slug>` as its name, and choose **Public**. If the organization is missing from the owner list, ask Christian or Hew for help.
4. **Publish your Product Page.** In your repository, open **Settings → Pages**, choose **Deploy from a branch**, then **main** and **/docs**, and save. Your page will appear at `https://building-with-ai-f26.github.io/<your-repo>/` once deployment finishes.
5. **Write PRD v1 on that page.** In `docs/index.html`, name a specific reachable user, explain their painful before/after workflow, define one core workflow, and list three non-goals.
6. **Build a rough local prototype.** Use your agent to test the core interaction on your laptop. Put a screenshot or GIF on your Product Page. The app can stay local through Week 4; cloud deployment is Build 5.
7. **Document the work you actually did.** Fill in the Build 1 log on your Product Page: what works, what you learned, what broke or changed, costs, and hours. Replace the template's example claims with your own evidence.
8. **Build on at least two separate days each week outside Tuesday class.** Push meaningful commits to GitHub, including during the November 3 break.
9. **Submit two links in Icerynk:** your live Product Page URL and your GitHub repository URL. See [Build 1](https://www.icerynk.com/c/fa26-tech-gb-2160-dm2-f2/content/build-1-intent-md-throwaway-prototype) for the rubric.

For Learn w/AI practice, read the [Week 1 memo](https://www.icerynk.com/c/fa26-tech-gb-2160-dm2-f2/content/memo-learned-helpfulness-with-ai), complete Terminus Episodes 1 and 2, and practice explaining the terminal, Git versus GitHub, PRDs, file extensions, and hidden files. Complete the [pod preferences form](https://www.icerynk.com/c/fa26-tech-gb-2160-dm2-f2/content/pod-preferences-form) if you did not do it in class.

## Every week

- Prepare with the readings and Learn w/AI practice.
- Build on at least two separate days outside class and push your commits.
- Update your Product Page's PRD and build log with progress, evidence, costs, and time.
- Review your agent's changes and verify the result. Use branches and commits as save points.
- Submit the milestone in Icerynk by Monday at noon, then bring your work to Tuesday's pod critique.
- Test your podmates' products and give specific feedback. Pods have four or five people; each student builds their own product.

Your Product Page is the required home for your living PRD and weekly build log. `Intent.md`, `Plan.md`, and `journal/` can help you draft and organize notes; they do not require a second copy of the same submission.

## Schedule

All build deadlines are **Monday at noon, New York time**. The weekly commit and Product Page requirements apply to every build.

| Session | Date | Topic | Deliverable and deadline |
| --- | --- | --- | --- |
| 1 | Oct 27 | **Intent.md:** Who is it for, and what job does it do? | Live Product Page, PRD v1, local prototype, and Build 1 log · **Nov 9** |
| — | Nov 3 | **No class: Election Day** | Continue Build 1 and your weekly commit cadence. |
| 2 | Nov 10 | **Plan.md:** What's the riskiest part, and what will it cost? | Smallest working slice on localhost, PostHog installed, PRD v2 with costs, and local setup in `AGENTS.md` · **Nov 16** |
| 3 | Nov 17 | **Build.exe:** Can you ship the core workflow without breaking things? | Core workflow on localhost, an `AGENTS.md` rule, funnel events, and PRD v3 · **Nov 23** |
| 4 | Nov 24 | **Test.py:** Is it good, or just working? | **Choose Track A or B:** 10-case domain evals or 3–5 user replays; PRD v4 · **Nov 30** |
| 5 | Dec 1 | **Ship.installer:** How does the cloud work, and can a stranger use it? | Live cloud app, rollback check, two-minute video, and final PRD · **Dec 7** |
| 6 | Dec 8 | **Demo Day:** live demos and peer stress-testing | Live demo **Dec 8**; one-page Sponsor Memo with usage, costs, risks, and a recommendation · **Dec 14** |

## Keep secrets out of GitHub

Store private API keys in local environment files such as `.env`; the template ignores them. Never put private credentials in browser code, screenshots, logs, or commits. Revoke an exposed key with the provider that issued it. The PostHog project token used in the browser snippet is different from a private account/API key; use the correct snippet from your own PostHog project.

## Grading

Weekly builds **40%** · Studio and pod critique **20%** · Demo Day **20%** · Sponsor Memo **20%**.

We evaluate working software, evidence, conceptual understanding, and honest documentation. You should understand what changed, why it matters, what could break, and how you checked it. See the syllabus for the full rubric and policies.
