---
layout: post
title: "Technical Debt: The Silent Killer in Scaling Software"
date: 2021-8-11
categories: 
---

The functions of a modern software organization are like welding, assembling, and finishing a cruise ship, while simultaneously launching and forcing a departure from harbor—the crew scrambling to update components and utilities. Lots will go wrong not only now, but ramifications are also a guarantee in the future.

As we come to realize critical footnotes to the quasi-tautological practice of “move fast and break things,” the statement’s fallacies and overlooked nuances are apparent. So it begs the question: how do we ship software, proceed in production safely, and maintain quality, without compromising speed? 


### The weight of technical debt

An essential part to the answer is how teams quantify, manage, and reduce technical debt. Technical debt refers to the cost of refactoring or redesigning code tomorrow because of short-cuts taken today due to constraints in the delivery timeline.

I came across the concept when first reading the paper, “Machine Learning: The High Interest Credit Card of Technical Debt,” and learning about the construction of AI systems. Because of the alluring nature and magical promises of ML pipelines, we often ignore its high maintenance behavior, which requires extensive attention, time, money, effort, and arguably emotional anguish. The same can be said for distributed systems, streaming infrastructure, or other applications of technologies with entangled architectures and designs. 

The accumulation of debt is inevitable. However, contemplating (and procrastinating) on resolving previous compounding debt and not proactively creating processes to manage new debt—the default behavior of startups that are primarily heads down on revenue-generating operations—is dangerous in systems that are only becoming more complex. 

Early debt can be almost invisible, but will always eventually turn into irreparable smithereens scattered across the codebase. 

Accrued debt will directly increase costs, stifle innovation, and elevate security risks—all factors decrease and flatline revenue growth. 


### Ways to better manage technical debt

As an engineer, regardless of stage in your career, there are ways you can engage in keeping technical debt in check when you code. Just like how agile and the lean startup methodologies are not skills taught in school classes yet still integral on the job, technical debt management is inseparable to a company’s long term success, and it’s one of the mental frameworks you must  adopt if to contribute in any cross-functional managerial capacity. So how can you help as an individual?

- Attend technology-specific conferences and forums to start the conversation
- Talk to others who’ve experienced consequences of debt and learn preventive measures
- Start with small, dynamic, and easy changes or habits

Note that best practices are often domain-specific. For a concrete example, here are some steps you can take to manage feature flags recommended in the LD Galaxy Conference by Mark Burry from iPipeline:

- Implement code references around relevant blocks and frequently think about flag removals as part of feature management
- Tag your flags with descriptive labels such as project/team, repo, in progress removal, awaiting third party
- Adhere to an appropriate fitness function for consistent flagging conventions
- Enable visibility of your flags through web hooks and other notifications

At LaunchDarkly, there are a number of forthcoming projects related to controlling technical debt, both on the individual flag level (for engineers) or the environment level (for managers). (Some debt management solutions are even being brainstormed and executed in the writing of this post as part of our quarterly Hackathon, Moonshots!) This is why Forrester scored LaunchDarkly the highest for managing feature flag technical debt in the recent report, “The Forrester New Wave™: Feature Management And Experimentation.”

While it could be satisfying to write new code, recall the last time you spent days debugging confusing dependencies or agonizing over the inefficiencies of old deprecated functions around the code-base. 

If you are still not convinced on the importance of technical debt, envision the psychological pain and monotony your future self will endure. Establish guidelines and habits now to chip away at debt as you scale, and consequently reduce your system’s risk of implosion. 