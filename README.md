# A marketer who ships the measurement

Growth and product marketing lead at Musicow, a music-royalty investing marketplace. Paid acquisition across six channels, go-to-market, and the six systems the marketing runs on: outcome measurement, financial control, daily campaign optimization, portfolio impact, attribution and planning, and an owned-audience web product. Six problems, six architectures, on purpose. Before that, product marketing for the Media and Entertainment vertical at TikTok, and programmatic at Sony Pictures.

Los Angeles, CA

Five of the six are production systems, architected, specced, directed and shipped with Claude Code. Sixty-three merged pull requests and 161 commits over five weeks, all of it private, because the systems run on licensed data. The method does not have to be. These are the parts I would hand to someone starting the same work.

- **[metrics-framework](https://github.com/TC1588/metrics-framework)**. Designing a North Star that survives an executive asking where the number came from. Input metrics as levers, health guardrails tied to the failure each one guards against, and modeled numbers kept visibly separate from measured ones.
- **[never-fabricate](https://github.com/TC1588/never-fabricate)**. What a data pipeline should do when a source fails, and what it should do when a source succeeds and returns nothing. A four-step degrade ladder, an empty-result guard, and the capture-and-pin discipline underneath both.
- **[delivery-vs-cash](https://github.com/TC1588/delivery-vs-cash)**. Reconciling ad spend on two bases at once. The delivered-to-cash bridge, why receipts restate instead of adding, and the four checks that have to pass before a number gets used.
- **[decision-rubric](https://github.com/TC1588/decision-rubric)**. A verdict framework for a live ad account. Four states on account-relative triggers, goal-aware tests so a campaign is judged on the metric its objective earns, and every verdict printing the arithmetic that produced it.
- **[refutation-review](https://github.com/TC1588/refutation-review)**. A 35-agent code review where every finding had to survive a second agent trying to disprove it. 407 tool calls, 28 confirmed bugs, about fifteen minutes.
- **[agent-build-patterns](https://github.com/TC1588/agent-build-patterns)**. Five build patterns matched to the five problems that earned them, when not to use agents at all, and the merge discipline nobody writes about.

Currently:

- Building marketing measurement that reconciles to the source it came from
- Running paid acquisition across six channels, and writing the tooling when the reporting does not exist
- Working out where multi-agent orchestration pays for itself and where it burns tokens for nothing

Find me on [LinkedIn](https://www.linkedin.com/in/terenzecoleman) and at [Terenze.co](https://terenze.co).
