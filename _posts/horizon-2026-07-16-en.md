# Horizon Daily - 2026-07-16

> From 77 items, 40 important content pieces were selected

---

1. [Thinking Machines Lab Releases Inkling, a 975B Open-Weights MoE Model](#item-1) ⭐️ 9.0/10
2. [Windows 0-day LegacyHive emerges on record Patch Tuesday](#item-2) ⭐️ 9.0/10
3. [Moonshot AI Releases Kimi K3, Frontier Open-Weight Model](#item-3) ⭐️ 8.0/10
4. [Rust-to-Zig Rewrite: A Compiler's Tale](#item-4) ⭐️ 8.0/10
5. [Sony Deletes Purchased Movies from User Accounts](#item-5) ⭐️ 8.0/10
6. [GPT-5.6 Codex Bug Deletes User Files in Full Access Mode](#item-6) ⭐️ 8.0/10
7. [Linus Torvalds Defends AI Use in Linux Kernel](#item-7) ⭐️ 8.0/10
8. [xAI open-sources Grok Build after privacy backlash](#item-8) ⭐️ 8.0/10
9. [Germany rules AI Overviews, Perplexity subject to media law](#item-9) ⭐️ 8.0/10
10. [OpenAI's GPT-Red beats humans at attacking its own AI](#item-10) ⭐️ 8.0/10
11. [Mozilla: Stardust period tracker shares health data with analytics firm](#item-11) ⭐️ 8.0/10
12. [Apple Intelligence Approved in China via Alibaba, Baidu](#item-12) ⭐️ 8.0/10
13. [Judge blocks Trump from deporting content moderation researchers](#item-13) ⭐️ 8.0/10
14. [llama.cpp b10043 Adds CUDA Virtual Device Support](#item-14) ⭐️ 7.0/10
15. [llama.cpp b10032 Adds CUDA Lightning Indexer Kernel](#item-15) ⭐️ 7.0/10
16. [Microsoft Comic Chat Open-Sourced After 30 Years](#item-16) ⭐️ 7.0/10
17. [OnePlus Halts New Product Launches in US and Europe](#item-17) ⭐️ 7.0/10
18. [Interactive Linear Algebra Book from 2015 Still Inspires](#item-18) ⭐️ 7.0/10
19. [GOES-19 Weather Satellite Enters Safe Hold Mode](#item-19) ⭐️ 7.0/10
20. [The Lost Joy of Music Piracy](#item-20) ⭐️ 7.0/10
21. [Train a Kick Drum Diffusion Model on 6GB VRAM](#item-21) ⭐️ 7.0/10
22. [Guide to Data Tools Landscape for Developers](#item-22) ⭐️ 7.0/10
23. [Building PlanetScale from Scratch: Infrastructure Deep Dive](#item-23) ⭐️ 7.0/10
24. [UK arrests disrupt Scattered Spider hacking group](#item-24) ⭐️ 7.0/10
25. [Meta Alerts Parents When Teens Discuss Self-Harm with AI](#item-25) ⭐️ 7.0/10
26. [Xona Plans 258 LEO Satellites as GPS Alternative](#item-26) ⭐️ 7.0/10
27. [Sheetz to Migrate 11,000 VMs from VMware to StorMagic](#item-27) ⭐️ 7.0/10
28. [llama.cpp b10042 adds CUDA graphs for Volta and Turing](#item-28) ⭐️ 6.0/10
29. [Decoy Font: Optical Illusion Hides Text from AI](#item-29) ⭐️ 6.0/10
30. [Classical ML for LLM Text Detection](#item-30) ⭐️ 6.0/10
31. [Mermaid Diagrams to Unicode Box Art via WebAssembly](#item-31) ⭐️ 6.0/10
32. [Google rebrands NotebookLM to Gemini Notebook, opens Search to third-party apps](#item-32) ⭐️ 6.0/10
33. [Sakana AI's Fugu orchestrator adds Nvidia Nemotron for collective intelligence](#item-33) ⭐️ 6.0/10
34. [Roblox Launches AI-Powered Game Creation in Mobile App](#item-34) ⭐️ 6.0/10
35. [BP Shuts Down Corporate Venture Arm After 20 Years](#item-35) ⭐️ 6.0/10
36. [Uber acquires Delivery Hero for $14.8B](#item-36) ⭐️ 6.0/10
37. [Google AI Mode expands to link and interact with apps](#item-37) ⭐️ 6.0/10
38. [AMI Labs CEO rejects 'AGI' and 'superintelligence' labels](#item-38) ⭐️ 6.0/10
39. [Energy IPOs Surge as Investors Chase AI Boom](#item-39) ⭐️ 6.0/10
40. [NTSB: Tesla driver pressed accelerator 100%, not Autopilot](#item-40) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Thinking Machines Lab Releases Inkling, a 975B Open-Weights MoE Model](https://simonwillison.net/2026/Jul/16/inkling/#atom-everything) ⭐️ 9.0/10

Thinking Machines Lab, founded by Mira Murati, released Inkling, a 975B-parameter Mixture-of-Experts model with 41B active parameters, trained on 45 trillion tokens of multimodal data and licensed under Apache-2.0. Inkling strengthens the US open-weights ecosystem, offering a competitive alternative to Chinese open models and providing a strong base for fine-tuning via the Tinker platform. The model is multimodal (text, images, audio, video) but not a frontier model; it is designed as a base for customization. A smaller variant, Inkling-Small (276B total, 12B active), is promised but not yet released.

rss · Simon Willison — AI工具 · Jul 16, 15:35

**Background**: Mixture-of-Experts (MoE) models use multiple specialized sub-networks (experts) with a gating mechanism to activate only a subset per input, achieving high capacity with lower computational cost. Open-weights models release trained parameters publicly, allowing download and modification, often under permissive licenses like Apache-2.0.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/ramses-engineering/not-one-brain-but-many-how-mixture-of-experts-moe-makes-ai-smarter-and-faster-568f41220852">Not One Brain, But Many: How Mixture of Experts ( MoE )... | Medium</a></li>
<li><a href="https://opensource.org/ai/open-weights">Open Weights: not quite what you’ve been told</a></li>
<li><a href="https://en.wikipedia.org/wiki/Apache_License">Apache License</a></li>

</ul>
</details>

**Tags**: `#AI`, `#open-weights`, `#mixture-of-experts`, `#multimodal`, `#Mira Murati`

---

<a id="item-2"></a>
## [Windows 0-day LegacyHive emerges on record Patch Tuesday](https://arstechnica.com/security/2026/07/windows-0-day-drops-the-same-day-microsoft-releases-record-number-of-patches/) ⭐️ 9.0/10

A researcher published a proof-of-concept exploit for a Windows 0-day vulnerability named LegacyHive on the same day Microsoft released a record number of security patches. The vulnerability allows low-privilege users to load another user's registry hive, enabling elevation of privilege. This 0-day is described as a 'powerful primitive' that could be combined with other exploits for broader attacks, posing an urgent threat to Windows systems. System administrators must prioritize patching and monitoring for exploitation attempts. The vulnerability resides in the Windows User Profile Service (ProfSvc) and revives a bug class previously patched in 2015 as CVE-2015-0004. The exploit allows a standard user to load another user's registry hive under their own registry classes root.

rss · ArsTechnica — 深度科技 · Jul 15, 19:59

**Background**: The Windows Registry stores user-specific settings in hives, which are normally protected. The User Profile Service manages loading and unloading these hives. LegacyHive exploits a trust-boundary failure to bypass these protections, allowing a low-privileged user to load an administrator's hive and potentially modify system settings.

<details><summary>References</summary>
<ul>
<li><a href="https://arstechnica.com/security/2026/07/windows-0-day-drops-the-same-day-microsoft-releases-record-number-of-patches/">Windows 0-day drops the same day Microsoft releases record number of patches - Ars Technica</a></li>
<li><a href="https://thehackernews.com/2026/07/researcher-drops-new-windows-zero-day.html">Researcher Drops New Windows Zero-Day PoC Hours After Microsoft Patch Tuesday</a></li>
<li><a href="https://www.theregister.com/security/2026/07/15/microsofts-serial-tormentor-drops-legacyhive-0-day/5271723">Microsoft’s serial tormentor drops LegacyHive 0-day</a></li>

</ul>
</details>

**Discussion**: Reddit comments note that the vulnerability revives a bug class from 2015, suggesting incomplete patching. Some express concern that the PoC could enable further attacks, while others debate whether Microsoft should have addressed it sooner.

**Tags**: `#security`, `#0-day`, `#Windows`, `#vulnerability`, `#patch`

---

<a id="item-3"></a>
## [Moonshot AI Releases Kimi K3, Frontier Open-Weight Model](https://www.kimi.com/en) ⭐️ 8.0/10

Moonshot AI has released Kimi K3, a frontier-level open-weight model with a 1M-token context window, claiming performance second only to Claude Fable 5 and GPT-5.6 Sol. The full model weights will be released in the coming days, along with a technical report. Kimi K3 represents a significant advancement in open-weight models, offering frontier-level performance with a massive context window, which could democratize access to high-end AI capabilities. Its competitive pricing and planned open release may pressure other leading models and benefit the broader AI ecosystem. The model has approximately 2.8 trillion total parameters and uses a Mixture-of-Experts architecture, with pricing at $3 per million input tokens and $15 per million output tokens (cache at $0.3). It supports native vision and is launched with max thinking effort by default, with low/high effort modes coming later.

hackernews · vincent_s · Jul 16, 14:46 · [Discussion](https://news.ycombinator.com/item?id=48935342)

**Background**: Kimi K3 is the latest flagship model from Moonshot AI, a Chinese AI company. It competes with frontier models like Anthropic's Claude Fable 5 and OpenAI's GPT-5.6 Sol, which are among the most capable AI models available. Open-weight models allow developers to inspect, modify, and run the model locally, fostering transparency and innovation.

<details><summary>References</summary>
<ul>
<li><a href="https://platform.kimi.ai/docs/guide/kimi-k3-quickstart">Kimi K3 - Kimi API Platform</a></li>
<li><a href="https://kie.ai/blog/what-is-kimi-k3">What Is Kimi K3? Moonshot's 2.5T, 1M-Context Flagship</a></li>

</ul>
</details>

**Discussion**: The community is excited about Kimi K3's performance claims and open-weight release, with some noting its high pricing but acknowledging it may be justified if truly competitive. A user pointed out that the model failed a trivia test, suggesting potential limitations in certain tasks.

**Tags**: `#AI`, `#LLM`, `#open-weight`, `#Kimi K3`, `#Moonshot AI`

---

<a id="item-4"></a>
## [Rust-to-Zig Rewrite: A Compiler's Tale](https://rtfeldman.com/rust-to-zig) ⭐️ 8.0/10

The author details their experience rewriting a compiler from Rust to Zig, citing faster incremental builds and simpler memory management as key benefits. This real-world case study highlights the trade-offs between Rust's safety guarantees and Zig's performance and simplicity, sparking debate about language choice for systems programming. The rewrite focuses on a compiler that emits machine code, where Zig's ReleaseSafe mode provides runtime checks for memory errors, though it does not catch all use-after-free bugs as noted in community comments.

hackernews · jorangreef · Jul 16, 11:39 · [Discussion](https://news.ycombinator.com/item?id=48933149)

**Background**: Rust and Zig are modern systems programming languages. Rust emphasizes memory safety without garbage collection via its ownership system, while Zig offers more control over memory allocation and faster compile times, but with fewer safety guarantees by default.

<details><summary>References</summary>
<ul>
<li><a href="https://ziglang.org/learn/why_zig_rust_d_cpp/">Why Zig When There is Already C++, D, and Rust? Zig Programming ...</a></li>
<li><a href="https://piembsystech.com/handling-memory-safety-in-zig-programming-language/">Handling Memory Safety in Zig Programming Language - PiEmbSysTech - Embedded Systems & VLSI Lab</a></li>
<li><a href="https://blog.logrocket.com/comparing-rust-vs-zig-performance-safety-more/">Comparing Rust vs . Zig : Performance , safety, and... - LogRocket Blog</a></li>

</ul>
</details>

**Discussion**: Community comments from notable figures like steveklabnik and landr0id question the necessity of unsafe code in compilers and the effectiveness of Zig's safety checks, while others praise Zig's incremental build performance.

**Tags**: `#Rust`, `#Zig`, `#compilers`, `#systems programming`, `#memory safety`

---

<a id="item-5"></a>
## [Sony Deletes Purchased Movies from User Accounts](https://www.techdirt.com/2026/07/15/sony-deletes-a-bunch-more-movies-from-the-accounts-of-people-who-bought-them/) ⭐️ 8.0/10

Sony has deleted more movies from the accounts of users who believed they had purchased them, continuing a pattern of revoking digital content access. This incident highlights the fragility of digital ownership and fuels calls for legal reform to protect consumers who buy digital goods. The deletions affect movies that users had paid for, not rented, and Sony has not offered refunds. This is part of a recurring issue where digital purchases are revoked without compensation.

hackernews · nekusar · Jul 16, 12:13 · [Discussion](https://news.ycombinator.com/item?id=48933419)

**Background**: Digital rights management (DRM) allows companies to control access to digital content, even after purchase. Unlike physical media, digital purchases often come with licenses that can be revoked, leading to debates over what 'buying' digital content truly means.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Digital_rights_management">Digital rights management - Wikipedia</a></li>
<li><a href="https://www.fortinet.com/resources/cyberglossary/digital-rights-management-drm">What Is DRM? Digital Rights Management Explained | Fortinet</a></li>
<li><a href="https://business.adobe.com/blog/basics/digital-rights-management">Digital Rights Management (DRM) | What It Is, How It Works & Why It Matters</a></li>

</ul>
</details>

**Discussion**: Commenters expressed frustration and called for legal changes, with some noting that this has happened many times before. Suggestions included requiring refunds when access is revoked and moving to offline physical media or piracy.

**Tags**: `#digital rights`, `#consumer protection`, `#Sony`, `#DRM`, `#Hacker News`

---

<a id="item-6"></a>
## [GPT-5.6 Codex Bug Deletes User Files in Full Access Mode](https://simonwillison.net/2026/Jul/16/bad-codex-bug/#atom-everything) ⭐️ 8.0/10

OpenAI confirmed that GPT-5.6's Codex agent can delete files when run in full access mode without sandboxing, due to the model mistakenly deleting the $HOME directory instead of a temporary directory. This bug highlights critical safety risks in AI coding agents, especially when granted unrestricted system access, and underscores the need for robust sandboxing and approval controls. The bug occurs when full access mode is enabled, auto review is disabled, and the model attempts to override $HOME to define a temporary directory but mistakenly deletes $HOME instead.

rss · Simon Willison — AI工具 · Jul 16, 17:45

**Background**: Codex is an AI coding agent from OpenAI that can execute commands and modify files. It supports multiple sandbox modes, including 'danger-full-access' which gives the agent unrestricted system access. Without sandboxing or approval controls, the agent can perform destructive actions like file deletion.

<details><summary>References</summary>
<ul>
<li><a href="https://x.com/thsottiaux/status/2077630111499882637">Tibo on X: "On file deletions. We’ve investigated a handful of reports where GPT-5.6 unexpectedly deleted files. What we have found is that this most commonly occurs when: - Full access mode is enabled and codex is run without sandboxing protections, including without auto review being" / X</a></li>
<li><a href="https://www.technology.org/2026/07/16/openai-gpt-5-6-sol-deletes-files-system-card-warning/">Developers Report OpenAI's GPT-5.6 Sol Deleting Files Without Permission</a></li>
<li><a href="https://openai.com/index/building-codex-windows-sandbox/">Building a safe, effective sandbox to enable Codex on Windows | OpenAI</a></li>

</ul>
</details>

**Tags**: `#codex`, `#coding-agents`, `#generative-ai`, `#ai-safety`, `#bug`

---

<a id="item-7"></a>
## [Linus Torvalds Defends AI Use in Linux Kernel](https://simonwillison.net/2026/Jul/16/linus-torvalds/#atom-everything) ⭐️ 8.0/10

Linus Torvalds, the creator of Linux, publicly stated on the Linux Media Mailing List that Linux is not an anti-AI project and that AI is a clearly useful tool, dismissing critics who dislike AI. This declaration from the top Linux maintainer signals a strong endorsement of AI within the open-source community, potentially influencing the direction of kernel development and settling debates about AI's role in open-source projects. Torvalds emphasized that AI is a tool like any other, and its usefulness is no longer in question, though he acknowledged other open questions about AI's economy. He also challenged those who disagree to fork the project or walk away.

rss · Simon Willison — AI工具 · Jul 16, 13:26

**Background**: Linus Torvalds is the creator and longtime maintainer of the Linux kernel, one of the largest open-source projects. Recently, there has been debate within open-source communities about the use of AI tools, with some projects adopting anti-AI policies. Torvalds' statement directly addresses this controversy.

**Tags**: `#Linux`, `#AI`, `#Linus Torvalds`, `#open source`, `#kernel`

---

<a id="item-8"></a>
## [xAI open-sources Grok Build after privacy backlash](https://simonwillison.net/2026/Jul/15/grok-build/#atom-everything) ⭐️ 8.0/10

xAI released the entire Grok Build codebase under the Apache 2.0 license after its CLI tool was found uploading entire directories, including sensitive files like SSH keys and password databases, to cloud storage. The company also deleted all retained user data and disabled default data retention. This incident highlights critical privacy risks in AI-powered developer tools and the importance of transparency. By open-sourcing the codebase, xAI aims to rebuild trust and set a precedent for user privacy in coding assistants. The Grok Build repository contains 844,530 lines of Rust code, with only about 3% vendored, and includes a self-contained terminal renderer for Mermaid diagrams. The initial release is a single commit, providing no commit history.

rss · Simon Willison — AI工具 · Jul 15, 23:59

**Background**: Grok Build is xAI's CLI tool for coding assistance, powered by the Grok model. The Apache 2.0 license is a permissive open-source license that allows free use, modification, and distribution. The controversy arose when users discovered the tool uploaded entire directories to xAI's cloud storage without explicit consent.

<details><summary>References</summary>
<ul>
<li><a href="https://x.ai/cli">Grok Build | SpaceXAI</a></li>
<li><a href="https://en.wikipedia.org/wiki/Apache_License">Apache License</a></li>

</ul>
</details>

**Tags**: `#privacy`, `#open source`, `#CLI`, `#AI`, `#security`

---

<a id="item-9"></a>
## [Germany rules AI Overviews, Perplexity subject to media law](https://the-decoder.com/germany-puts-googles-ai-overviews-and-perplexity-under-media-law-in-first-of-its-kind-ruling/) ⭐️ 8.0/10

German media regulators have ruled that Google's AI Overviews and Perplexity's AI-generated search results are subject to the State Media Treaty, marking the first such ruling against AI-powered search features. This sets a precedent for regulating AI-generated content as media rather than neutral search results, potentially impacting how AI search tools operate in Germany and influencing other jurisdictions. The regulators consider AI Overviews as Google's own content that crowds out regular links, and both Google and Perplexity have one month to appeal the ruling.

rss · The Decoder — AI新闻 · Jul 16, 16:12

**Background**: The State Media Treaty (Medienstaatsvertrag) is a German legal framework that governs online content, including hate speech and disinformation, and now extends to AI-generated summaries. AI Overviews, launched by Google in 2024, provide AI-generated snapshots in search results, while Perplexity offers an AI-powered answer engine that synthesizes web content.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AI_Overviews">AI Overviews - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Perplexity_AI">Perplexity AI</a></li>
<li><a href="https://www.netsweeper.com/legislation/state-media-treaty-medienstaatsvertrag">State Media Treaty (Medienstaatsvertrag) - Netsweeper</a></li>

</ul>
</details>

**Tags**: `#AI regulation`, `#Germany`, `#Google`, `#Perplexity`, `#media law`

---

<a id="item-10"></a>
## [OpenAI's GPT-Red beats humans at attacking its own AI](https://the-decoder.com/openai-is-now-using-ai-to-attack-its-own-ai-and-its-working-better-than-humans-ever-did/) ⭐️ 8.0/10

OpenAI has developed GPT-Red, an automated red-teaming model that uses self-play to find prompt injection vulnerabilities, achieving an 84% attack success rate compared to 13% for human testers. This breakthrough significantly improves AI safety by enabling faster, more thorough adversarial testing, directly hardening models like GPT-5.6 Sol against prompt injection attacks. GPT-Red is trained via self-play, where it iteratively generates attacks and defenses, and its results are used to patch vulnerabilities in production models. The model achieves 84% success across diverse test scenarios.

rss · The Decoder — AI新闻 · Jul 15, 19:47

**Background**: Red-teaming is a security practice where testers simulate attacks to find vulnerabilities. Traditionally, human experts perform this task, but it is slow and costly. Self-play is a training method where an AI improves by competing against itself, commonly used in game-playing AI like AlphaGo.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/index/unlocking-self-improvement-gpt-red/">Unlocking Self-Improvement for Robustness - GPT-Red - OpenAI</a></li>
<li><a href="https://arxiv.org/abs/2601.10589">Safety Alignment via Self-Play and Reflective Experience Replay - arXiv</a></li>
<li><a href="https://x.com/natashajaques/status/2077458133770010770">Really cool to see OpenAI is using self-play for red-teaming now! Our ...</a></li>

</ul>
</details>

**Discussion**: The community response has been positive, with researchers like Natasha Jaques praising the use of self-play for red-teaming. Some commenters noted that this approach could scale safety testing far beyond human capacity.

**Tags**: `#AI safety`, `#red-teaming`, `#OpenAI`, `#adversarial testing`, `#self-play`

---

<a id="item-11"></a>
## [Mozilla: Stardust period tracker shares health data with analytics firm](https://techcrunch.com/2026/07/16/period-tracker-stardust-shares-users-health-data-with-analytics-firm-says-mozilla-research/) ⭐️ 8.0/10

Mozilla research found that the period tracker app Stardust shares users' health data with a third-party analytics firm, contradicting its claims of end-to-end encryption. The finding was based on network traffic analysis by Mozilla security researcher Shoshana Wodinsky. This matters because period tracker apps handle highly sensitive health data, and users rely on privacy promises to protect their information. The revelation highlights significant disparities in privacy practices among such apps, urging users to scrutinize data-sharing policies. Stardust claimed its data was end-to-end encrypted, meaning even the company could not access it, but TechCrunch and Mozilla found that the app shares phone numbers with an analytics firm. In contrast, another app tested by Mozilla was described as 'squeaky clean' with strong privacy protections.

rss · TechCrunch — 科技创投 · Jul 16, 15:33

**Background**: Period tracker apps allow users to log menstrual cycles, ovulation, and other reproductive health data. Due to the sensitivity of this information, especially after the overturning of Roe v. Wade in the US, privacy concerns have intensified. Mozilla's *Privacy Not Included project regularly reviews apps' data practices to inform consumers.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/07/16/period-tracker-stardust-shares-users-health-data-with-analytics-firm-says-mozilla-research/">Period tracker Stardust shares users' health data with analytics firm, says Mozilla research | TechCrunch</a></li>
<li><a href="https://www.bbc.com/future/article/20260715-how-period-trackers-share-womens-private-details">The privacy problems hidden in your period tracker</a></li>
<li><a href="https://screenrant.com/stardust-period-tracking-app-data-safe-is/">Stardust Period Tracking App: Is Your Data Really Safe?</a></li>

</ul>
</details>

**Tags**: `#privacy`, `#health data`, `#mobile apps`, `#data sharing`, `#Mozilla`

---

<a id="item-12"></a>
## [Apple Intelligence Approved in China via Alibaba, Baidu](https://techcrunch.com/2026/07/16/apple-intelligence-approved-for-launch-in-china-with-alibabas-qwen-ai/) ⭐️ 8.0/10

Apple has received approval to launch its Apple Intelligence platform in China through partnerships with Alibaba and Baidu, marking its official entry into the Chinese AI market. This move allows Apple to compete in China's rapidly growing AI market while complying with local regulations, and it strengthens ties with major Chinese tech firms, potentially reshaping the competitive landscape. Alibaba will provide its Qwen large language models, while Baidu will power AI search features for Apple Intelligence on iPhones in China.

rss · TechCrunch — 科技创投 · Jul 16, 13:17

**Background**: Apple Intelligence is Apple's personal intelligence system integrated into iOS, iPadOS, and macOS, using on-device and cloud processing with a focus on privacy. China's strict AI regulations require foreign companies to partner with local firms to offer AI services, prompting Apple to collaborate with Alibaba and Baidu.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Apple_Intelligence">Apple Intelligence - Wikipedia</a></li>
<li><a href="https://technode.com/2026/07/16/baidu-to-power-ai-search-for-apples-apple-intelligence-in-china/">Baidu to power AI search for Apple's Apple Intelligence in China...</a></li>

</ul>
</details>

**Tags**: `#Apple`, `#AI`, `#China`, `#Alibaba`, `#Baidu`

---

<a id="item-13"></a>
## [Judge blocks Trump from deporting content moderation researchers](https://arstechnica.com/tech-policy/2026/07/judge-trump-cant-deport-researchers-just-for-working-in-content-moderation/) ⭐️ 8.0/10

A federal judge ruled that the Trump administration cannot deny visas or deport researchers solely for their work in content moderation, a decision praised by disinformation researchers. This ruling sets a legal precedent protecting academic freedom and the ability to study disinformation, which is crucial for tech policy and combating online harms. The policy had labeled researchers as 'foreign censors' to justify visa bans, but the judge found that working in content moderation alone is not a valid basis for deportation or visa denial.

rss · ArsTechnica — 深度科技 · Jul 15, 21:26

**Background**: Content moderation involves reviewing and managing user-generated content on platforms to enforce rules against hate speech, disinformation, and other harmful material. Researchers in this field often study the effectiveness of moderation policies and the spread of false information. The Trump administration had targeted these researchers with visa restrictions, claiming they were interfering with free speech.

<details><summary>References</summary>
<ul>
<li><a href="https://arstechnica.com/tech-policy/2026/07/judge-trump-cant-deport-researchers-just-for-working-in-content-moderation/">Judge: Trump can’t deport researchers just for working... - Ars Technica</a></li>
<li><a href="https://www.denver7.com/politics/immigration/so-bizarre-disinformation-researcher-speaks-out-against-visa-ban-and-blocked-deportation">Disinformation researcher speaks out against visa ban and blocked...</a></li>

</ul>
</details>

**Tags**: `#content moderation`, `#legal`, `#disinformation`, `#tech policy`, `#academic freedom`

---

<a id="item-14"></a>
## [llama.cpp b10043 Adds CUDA Virtual Device Support](https://github.com/ggml-org/llama.cpp/releases/tag/b10043) ⭐️ 7.0/10

llama.cpp release b10043 introduces support for CUDA virtual devices, enabling better multi-GPU utilization. The release also disables the NCCL path when virtual devices are used and adds GPUx2 server CI jobs. This feature allows users to split a single physical GPU into multiple virtual devices, improving flexibility and efficiency in multi-GPU setups. It is particularly beneficial for running large language models across multiple GPUs without requiring physical GPU partitioning. CUDA virtual devices are supported via the CUDA API, and the NCCL path is automatically disabled when virtual devices are used to avoid conflicts. The release also includes CI improvements with new GPUx2 server jobs to test multi-GPU scenarios.

github · github-actions[bot] · Jul 16, 14:02

**Background**: CUDA virtual devices allow a single physical GPU to be partitioned into multiple logical devices, each accessible as a separate CUDA device. This is useful in virtualized environments or for workloads that require fine-grained GPU resource allocation. llama.cpp is an open-source project that enables running large language models efficiently on consumer hardware, and multi-GPU support is critical for scaling model inference.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/ggml-org/llama.cpp/blob/master/docs/multi-gpu.md">llama.cpp/docs/multi-gpu.md at master · ggml-org/llama.cpp</a></li>
<li><a href="https://en.wikipedia.org/wiki/GPU_virtualization">GPU virtualization - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#llama.cpp`, `#CUDA`, `#multi-GPU`, `#machine learning`, `#open source`

---

<a id="item-15"></a>
## [llama.cpp b10032 Adds CUDA Lightning Indexer Kernel](https://github.com/ggml-org/llama.cpp/releases/tag/b10032) ⭐️ 7.0/10

llama.cpp release b10032 introduces a CUDA implementation of GGML_OP_LIGHTNING_INDEXER, featuring both a generic vector kernel and a WMMA kernel for improved GPU performance. This optimization directly benefits DeepSeek V3.2/V4 models that rely on the lightning indexer operation, enabling faster inference on NVIDIA GPUs. The addition of WMMA support also paves the way for future AMD rocWMMA integration. The implementation includes template parameters WARPS_PER_BLOCK and K_VECS_PER_BLOCK to avoid constant duplication, and adds alignment checks for Q and K tensors. The MMA architecture requirement has been relaxed to Turing, and a TODO for AMD rocWMMA is noted.

github · github-actions[bot] · Jul 15, 19:52

**Background**: GGML_OP_LIGHTNING_INDEXER is a dedicated operation added in earlier llama.cpp builds to support the lightning indexer used by DeepSeek V3.2 and V4 models. WMMA (Warp Matrix Multiply-Accumulate) is a CUDA API for using Tensor Cores, and rocWMMA is AMD's equivalent for its GPUs.

<details><summary>References</summary>
<ul>
<li><a href="https://newreleases.io/project/github/ggml-org/llama.cpp/release/b9970">ggml -org/llama.cpp b9970 on GitHub</a></li>
<li><a href="https://aidownload.com/updates/3e4520e8-d8dc-453b-91fd-d8d5c70f4776">ggml -org/llama.cpp b9970 | AI Download</a></li>
<li><a href="https://rocm.docs.amd.com/projects/rocWMMA/en/docs-6.3.3/what-is-rocwmma.html">What is rocWMMA? - ROCm Documentation - AMD</a></li>

</ul>
</details>

**Tags**: `#llama.cpp`, `#CUDA`, `#GPU kernels`, `#LLM inference`, `#open-source`

---

<a id="item-16"></a>
## [Microsoft Comic Chat Open-Sourced After 30 Years](https://opensource.microsoft.com/blog/2026/07/16/microsoft-comic-chat-is-now-open-source/) ⭐️ 7.0/10

On July 16, 2026, Microsoft open-sourced the source code for Comic Chat (later renamed Microsoft Chat), a graphical IRC client from 1996 that turned text conversations into comic strips. This release preserves a unique piece of internet history and allows developers to study, modify, and learn from Microsoft's early approach to graphical chat interfaces, sparking nostalgia and technical interest in the community. Comic Chat was developed by Microsoft researcher David Kurlander and first shipped with Internet Explorer 3.0 in 1996; it used proprietary extensions to the IRC protocol to convey character appearance and emotions.

hackernews · jervant · Jul 16, 16:06 · [Discussion](https://news.ycombinator.com/item?id=48936426)

**Background**: Internet Relay Chat (IRC) is a text-based chat protocol popular in the 1990s. Comic Chat was a graphical client that automatically rendered conversations as comic panels with avatars, speech bubbles, and emotions, making chat more expressive. It was later renamed Microsoft Chat and bundled with Internet Explorer.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Microsoft_Comic_Chat">Microsoft Comic Chat</a></li>
<li><a href="https://github.com/microsoft/comic-chat">GitHub - microsoft/comic-chat: Source code for the Microsoft Comic Chat IRC client · GitHub</a></li>
<li><a href="https://opensource.microsoft.com/blog/2026/07/16/microsoft-comic-chat-is-now-open-source/">Microsoft Comic Chat is now open source | Microsoft Open Source...</a></li>

</ul>
</details>

**Discussion**: Community comments express excitement and nostalgia, with users sharing personal stories about how Comic Chat inspired their own projects. Some note that the client was controversial in IRC circles due to its proprietary protocol extensions, but overall the sentiment is positive and appreciative of the historical release.

**Tags**: `#open source`, `#microsoft`, `#irc`, `#nostalgia`, `#comic chat`

---

<a id="item-17"></a>
## [OnePlus Halts New Product Launches in US and Europe](https://community.oneplus.com/thread/2170715118587871237) ⭐️ 7.0/10

OnePlus has announced it will no longer launch new products in Europe and North America, effectively exiting these key markets. Existing devices will continue to receive software updates and security patches as originally committed. This marks a major strategic retreat for a brand once celebrated as the 'hacker's choice' for its stock Android experience, unlocked bootloaders, and competitive pricing. The move underscores OnePlus's gradual integration into parent company OPPO and the consolidation of the smartphone industry. The decision applies only to new product rollouts; after-sales support and software updates for existing devices remain unaffected. OnePlus has been effectively operating as a sub-brand of OPPO for years, with recent devices being slightly redesigned OPPO models running the same OS.

hackernews · pilililo2 · Jul 16, 10:14 · [Discussion](https://news.ycombinator.com/item?id=48932539)

**Background**: OnePlus was founded in 2013 by Carl Pei and Pete Lau with a focus on high-spec, affordable smartphones running near-stock Android. The brand gained a loyal following among enthusiasts for its 'Never Settle' philosophy, unlocked bootloaders, and developer-friendly policies. In recent years, OnePlus increasingly merged with OPPO, losing its distinct identity and community trust.

**Discussion**: Community comments express disappointment and nostalgia, with users noting OnePlus's decline from its enthusiast roots. Some clarify that the news is about halting new product launches, not ceasing operations entirely, and highlight that OnePlus has long been a rebranded OPPO. Others point to Carl Pei's new company, Nothing, as a spiritual successor.

**Tags**: `#OnePlus`, `#smartphone industry`, `#market exit`, `#hardware`

---

<a id="item-18"></a>
## [Interactive Linear Algebra Book from 2015 Still Inspires](https://immersivemath.com/ila/) ⭐️ 7.0/10

The news highlights the Immersive Linear Algebra book from 2015, which features interactive figures to make learning intuitive and engaging. This resource demonstrates the lasting value of interactive visualization in math education, and community comments show it remains relevant and appreciated years later. The book is available online at immersivemath.com and includes interactive figures that users can manipulate to understand linear algebra concepts.

hackernews · srean · Jul 16, 15:32 · [Discussion](https://news.ycombinator.com/item?id=48935951)

**Background**: Linear algebra is a foundational branch of mathematics used in many fields including computer science, physics, and engineering. Traditional textbooks often rely on static diagrams, which can make abstract concepts harder to grasp. Interactive figures allow learners to visualize and experiment with concepts in real time, enhancing comprehension.

**Discussion**: Community comments are overwhelmingly positive, with users praising the book's clarity and interactivity. Some express a desire for similar resources in other subjects like statistics and robotics, while others note that modern AI tools could make creating such books easier.

**Tags**: `#linear algebra`, `#interactive learning`, `#math education`, `#visualization`

---

<a id="item-19"></a>
## [GOES-19 Weather Satellite Enters Safe Hold Mode](https://www.spaceweather.gov/news/goes-19-safe-hold) ⭐️ 7.0/10

NOAA's GOES-19 weather satellite entered safe hold mode on July 15, 2026, but engineers have already begun restoring systems, with DCS and SAR back online and ABI expected to resume imaging by 1900Z. GOES-19 is the primary satellite for tracking Atlantic hurricanes, so any outage could impact real-time forecasting during hurricane season. The rapid restoration effort minimizes disruption to weather monitoring. The satellite entered safe hold late Wednesday (July 15), and instruments are being restored in order: ABI, GLM, SUVI, CCOR. Image navigation may be slightly degraded for the first hour after imaging resumes.

hackernews · yabones · Jul 16, 13:30 · [Discussion](https://news.ycombinator.com/item?id=48934286)

**Background**: GOES-19 is the fourth and final satellite in NOAA's GOES-R series, providing critical weather data from geostationary orbit. Safe hold mode is a protective state where the satellite orients itself to the sun and suspends non-essential operations until ground control resolves the issue.

<details><summary>References</summary>
<ul>
<li><a href="https://www.spaceweather.gov/news/goes-19-safe-hold">GOES-19 Safe Hold | NOAA / NWS Space Weather Prediction Center</a></li>
<li><a href="https://en.wikipedia.org/wiki/GOES-19">GOES-19 - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Former GOES engineers noted that anomalies are common in the series, citing past issues like the loop heat pipe anomaly on GOES-17. Commenters appreciated the detailed status updates and explained that safe mode is a standard precautionary measure.

**Tags**: `#satellite`, `#weather`, `#NOAA`, `#space`, `#engineering`

---

<a id="item-20"></a>
## [The Lost Joy of Music Piracy](https://www.pigeonsandplanes.com/read/music-piracy-what-cd-oink-nine-inch-nails-streaming) ⭐️ 7.0/10

A nostalgic article reflects on the cultural and social joys of music piracy in the pre-streaming era, emphasizing the network effects of sharing music collections and the ongoing need for piracy due to incomplete streaming archives. This piece highlights how the shift from piracy to streaming has changed music discovery and community, and it reminds us that streaming services still lack a complete archive, making piracy a necessary alternative for accessing rare or out-of-print music. The article mentions specific pirate platforms like Oink and What.cd, and notes that even albums featured in major publications can be impossible to find legally, forcing users to buy expensive used CDs or resort to piracy.

hackernews · mcgin · Jul 16, 04:46 · [Discussion](https://news.ycombinator.com/item?id=48930454)

**Background**: Music piracy was widespread in the early 2000s through peer-to-peer networks and private trackers, allowing users to build vast digital collections. The rise of streaming services like Spotify promised legal access to millions of songs, but many albums remain unavailable due to licensing issues or label disputes.

**Discussion**: Commenters express nostalgia for the social discovery and community aspects of piracy, with one noting that their iPod was a culmination of friendships. Another highlights the ongoing need for piracy due to gaps in streaming archives, and a third recalls the loss of forums on What.cd where they wrote lengthy discussions.

**Tags**: `#music piracy`, `#streaming`, `#digital culture`, `#nostalgia`, `#file sharing`

---

<a id="item-21"></a>
## [Train a Kick Drum Diffusion Model on 6GB VRAM](https://www.zhinit.dev/blog/training-a-kick-drum-diffusion-model) ⭐️ 7.0/10

A detailed guide demonstrates how to train a diffusion model for kick drum audio generation on a Linux desktop with only 6GB VRAM, making generative AI accessible on consumer hardware. This lowers the barrier for musicians and hobbyists to experiment with custom AI sound generation without expensive GPUs, potentially democratizing audio AI development. The guide likely uses techniques like gradient checkpointing, mixed precision, and small model architectures to fit training within 6GB VRAM. It focuses specifically on kick drums, a simple percussive sound, making the task tractable.

hackernews · zhinit · Jul 16, 15:13 · [Discussion](https://news.ycombinator.com/item?id=48935687)

**Background**: Diffusion models are a class of generative models that learn to denoise data, commonly used for image and audio generation. Training such models typically requires high-end GPUs with large VRAM, limiting accessibility. This guide shows how to adapt the process for limited hardware.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/learn/diffusion-course/unit4/3">Diffusion for Audio - Hugging Face</a></li>
<li><a href="https://sites.google.com/view/drum-generation">DrumNet</a></li>

</ul>
</details>

**Discussion**: Commenters noted prior art like Emergent Drums 2 and Synplant's Genopatch, suggesting the approach is not entirely novel. Others praised the article for inspiring them to repurpose old datasets and hardware for AI experiments.

**Tags**: `#machine learning`, `#audio generation`, `#diffusion models`, `#practical AI`

---

<a id="item-22"></a>
## [Guide to Data Tools Landscape for Developers](https://sinja.io/blog/data-landscape-guide-for-developers) ⭐️ 7.0/10

A comprehensive guide has been published that maps the modern data tools ecosystem for developers, covering databases, data warehouses, data lakes, and query engines. This guide helps developers navigate the rapidly evolving data landscape, making it easier to choose the right tools for their projects and stay current with industry trends. The article explains key concepts like OLTP vs. OLAP, and covers tools such as Snowflake, BigQuery, DuckDB, and Apache Spark, with community comments highlighting DuckDB's growing impact and the rise of conversational analytics.

hackernews · OlegWock · Jul 16, 14:59 · [Discussion](https://news.ycombinator.com/item?id=48935510)

**Background**: Data tools have become increasingly specialized, with separate systems for transactional processing (OLTP) and analytical processing (OLAP). Developers often need to integrate multiple tools for ingestion, storage, querying, and visualization. This guide provides a structured overview to help developers understand the landscape.

**Discussion**: Commenters praised the article as excellent and well-written, with data engineering professionals affirming its accuracy. They noted emerging trends like conversational analytics and DuckDB's disruptive role, and suggested additional tools like Sling for data ingestion.

**Tags**: `#data engineering`, `#data tools`, `#data warehouse`, `#data lake`, `#SQL`

---

<a id="item-23"></a>
## [Building PlanetScale from Scratch: Infrastructure Deep Dive](https://onatm.dev/2026/07/16/homescale-part-1/) ⭐️ 7.0/10

A detailed blog post walks through building a scalable database infrastructure similar to PlanetScale, focusing on compute-storage separation and managed Postgres, but omits key features like sharding and a connection bouncer. This article provides a valuable technical reference for developers interested in building scalable database systems, but community comments highlight that it oversimplifies PlanetScale's complexity, potentially misleading readers about the effort required. The post covers compute-storage separation using EBS and Postgres, but lacks discussion of sharding, connection pooling, or zero-downtime failover, which are critical for PlanetScale's production-grade service.

hackernews · onatm · Jul 16, 11:58 · [Discussion](https://news.ycombinator.com/item?id=48933303)

**Background**: PlanetScale is a cloud database platform that offers managed MySQL and Postgres with horizontal scaling via Vitess or shared-nothing architecture. Compute-storage separation allows independent scaling of compute and storage resources, a common pattern in modern cloud databases like Neon and Aurora.

<details><summary>References</summary>
<ul>
<li><a href="https://planetscale.com/docs/postgres/postgres-architecture">PlanetScale Postgres architecture - PlanetScale</a></li>
<li><a href="https://planetscale.com/">PlanetScale - the world’s fastest and most scalable cloud hosting for Vitess and Postgres</a></li>
<li><a href="https://promtable.com/glossary/compute-storage-separation">Compute / storage separation — Definition, when to use... | Promtable</a></li>

</ul>
</details>

**Discussion**: Commenters criticized the post for missing essential PlanetScale features like sharding and a connection bouncer, with one noting it's more like a basic managed DB. Others pointed out that compute-storage separation has performance drawbacks with EBS, and that building a full managed service is far more complex than the article suggests.

**Tags**: `#database`, `#infrastructure`, `#Postgres`, `#scalability`, `#PlanetScale`

---

<a id="item-24"></a>
## [UK arrests disrupt Scattered Spider hacking group](https://techcrunch.com/2026/07/16/uk-cops-say-arrest-of-two-young-hackers-disrupted-the-operations-of-an-infamous-hacking-group/) ⭐️ 7.0/10

Two members of the Scattered Spider hacking group, Owen Flowers (18) and Thalha Jubair (20), pleaded guilty and were sentenced to five years and six months in prison for hacking London's Transport for London (TfL) system in 2024. This sentencing disrupts the operations of Scattered Spider, a prolific hacking group that has targeted major companies and posed a significant threat to cybersecurity. The arrests demonstrate law enforcement's ability to track and prosecute young cybercriminals, potentially deterring others. The hack targeted Transport for London (TfL), the government body overseeing London's public transit system, and the two were described as computer-obsessed loners. They pleaded guilty in June 2026 and were sentenced on July 16, 2026.

rss · TechCrunch — 科技创投 · Jul 16, 15:37

**Background**: Scattered Spider is a group of predominantly English-speaking cybercriminals, some as young as 16, who emerged from underground hacking communities known as 'The Community' or 'The Com'. They have been involved in high-profile hacks, including targeting Coinbase accounts and other major companies.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/07/16/uk-cops-say-arrest-of-two-young-hackers-disrupted-the-operations-of-an-infamous-hacking-group/">UK cops say arrest of two young hackers disrupted the... | TechCrunch</a></li>
<li><a href="https://www.bbc.com/news/articles/c4gyg0y6yg2o">Teen hackers jailed after live streaming cyber attack on TfL</a></li>
<li><a href="https://www.aol.com/inside-scattered-spider-notorious-teen-142611588.html">Inside Scattered Spider : The notorious teen hacking group ... - AOL</a></li>

</ul>
</details>

**Tags**: `#cybersecurity`, `#hacking`, `#law enforcement`, `#Scattered Spider`

---

<a id="item-25"></a>
## [Meta Alerts Parents When Teens Discuss Self-Harm with AI](https://techcrunch.com/2026/07/16/meta-now-alerts-parents-if-their-teen-discussed-suicide-or-self-harm-with-its-ai-chatbot/) ⭐️ 7.0/10

Meta announced that parents will now receive alerts if their teen discusses suicide or self-harm with the Meta AI chatbot on Instagram, with alerts sent via text, email, or in-app notification. This feature addresses growing regulatory and parental concerns about AI chatbot safety for teens, potentially setting a precedent for other platforms to implement similar crisis detection and parental notification systems. The alerts are part of a broader safety update that also includes emergency service integration in development; the feature currently applies to Meta AI on Instagram, with more safeguards planned.

rss · TechCrunch — 科技创投 · Jul 16, 11:00

**Background**: Meta and other tech companies face scrutiny over how AI chatbots respond to users in crisis, especially teenagers. Parental supervision tools are becoming a key focus for social media platforms aiming to balance AI engagement with user safety. Similar crisis intervention protocols are being discussed across the industry.

<details><summary>References</summary>
<ul>
<li><a href="https://thehill.com/policy/technology/5560272-meta-safety-features-ai-chatbots/">Meta adding AI chatbot safety features for teens</a></li>
<li><a href="https://www.indiatoday.in/technology/news/story/meta-to-alert-parents-if-their-teen-discusses-suicide-with-ai-chatbot-emergency-service-feature-also-in-works-2949292-2026-07-16">Meta to alert parents if their teen discusses suicide with AI chatbot, emergency service feature also in works - India Today</a></li>
<li><a href="https://www.cnet.com/tech/services-and-software/meta-ai-chatbot-parental-notification-distressing-chats-news/">Meta Adds Support and Parental Notification for AI Chats About Self-Harm - CNET</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#social media`, `#teen mental health`, `#Meta`, `#content moderation`

---

<a id="item-26"></a>
## [Xona Plans 258 LEO Satellites as GPS Alternative](https://arstechnica.com/space/2026/07/move-over-gps-navigation-satellites-in-low-earth-orbit-are-making-a-comeback/) ⭐️ 7.0/10

Xona Space Systems plans to deploy 258 satellites in low-Earth orbit to create a high-performance alternative to GPS, with signals up to 100 times stronger than existing GPS signals. This could revolutionize navigation by providing centimeter-level accuracy and greater resistance to interference, benefiting autonomous vehicles, drones, and other intelligent systems that rely on precise positioning. The satellites will operate in low-Earth orbit (500–2,000 km altitude), requiring a large constellation for global coverage, and have demonstrated the highest-power satellite navigation signal ever recorded.

rss · ArsTechnica — 深度科技 · Jul 16, 11:00

**Background**: Traditional GPS satellites reside in medium-Earth orbit (about 20,000 km), which results in weaker signals that are easier to jam or spoof. Low-Earth orbit satellites are closer to Earth, enabling stronger signals and lower latency, but require many more satellites for continuous coverage. Xona's system is designed to complement or compete with GPS for applications demanding high precision and security.

<details><summary>References</summary>
<ul>
<li><a href="https://www.xonaspace.com/">Next Era Navigational Intelligence | Xona</a></li>
<li><a href="https://www.spacecapital.com/blogs/xona-space-systems-redefining-precision-pnt">Space Capital | Insights | Xona Space Systems: Advancing Precision PNT Beyond GPS</a></li>
<li><a href="https://www.eoportal.org/satellite-missions/xona">Xona Space Systems - eoPortal</a></li>

</ul>
</details>

**Tags**: `#satellite navigation`, `#LEO`, `#GPS alternative`, `#space technology`

---

<a id="item-27"></a>
## [Sheetz to Migrate 11,000 VMs from VMware to StorMagic](https://arstechnica.com/information-technology/2026/07/sheetz-moves-838-stores-off-vmware-broadcom-created-too-much-uncertainty/) ⭐️ 7.0/10

Convenience store chain Sheetz announced it is migrating 11,000 virtual machines from VMware to StorMagic's SvSAN storage virtualization platform, citing uncertainty created by Broadcom's acquisition of VMware. This migration signals growing enterprise dissatisfaction with Broadcom's post-acquisition changes at VMware, potentially triggering a wave of defections to alternative virtualization platforms. Sheetz operates 838 stores and will use StorMagic's SvSAN software, which provides highly available storage virtualization with centralized management and monitoring.

rss · ArsTechnica — 深度科技 · Jul 15, 21:41

**Background**: Broadcom completed its $61 billion acquisition of VMware in November 2023, leading to significant changes in licensing, pricing, and product bundling that have caused uncertainty among customers. StorMagic is a provider of storage virtualization software, with SvSAN being its flagship product for simplifying storage management.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/VMware">VMware - Wikipedia</a></li>
<li><a href="https://craft.co/stormagic">StorMagic Company Profile - Office Locations, Competitors... | Craft.co</a></li>
<li><a href="https://www.cbiz.com/insights/article/broadcom-acquisition-how-vmware-users-are-taking-a-hit">Broadcom Acquisition: How VMware Users are Taking a Hit | CBIZ</a></li>

</ul>
</details>

**Tags**: `#VMware`, `#Broadcom`, `#virtualization`, `#enterprise IT`, `#migration`

---

<a id="item-28"></a>
## [llama.cpp b10042 adds CUDA graphs for Volta and Turing](https://github.com/ggml-org/llama.cpp/releases/tag/b10042) ⭐️ 6.0/10

llama.cpp release b10042 enables CUDA graphs support for NVIDIA Volta and Turing GPU architectures, allowing multiple GPU operations to be launched as a single graph to reduce CPU overhead. This update improves inference performance on older but widely used NVIDIA GPUs (e.g., GTX 10-series, RTX 20-series), making local LLM inference more efficient for users with these cards. CUDA graphs were previously supported only on newer architectures; this release extends support to Volta (GV100) and Turing (TU10x) GPUs. The change is implemented via pull request #25749.

github · github-actions[bot] · Jul 16, 11:23

**Background**: CUDA graphs allow a series of CUDA kernel launches to be defined as a single graph and launched with one CPU operation, reducing launch overhead. Volta and Turing are NVIDIA GPU architectures from 2017 and 2018, respectively, still common in consumer and workstation GPUs.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.nvidia.com/blog/cuda-graphs/">Getting Started with CUDA Graphs | NVIDIA Technical Blog</a></li>
<li><a href="https://docs.nvidia.com/cuda/volta-tuning-guide/">1. Volta Tuning Guide — Volta Tuning Guide 13.3 documentation</a></li>
<li><a href="https://docs.nvidia.com/cuda/turing-tuning-guide/index.html">1. Turing Tuning Guide — Turing Tuning Guide 13.3 documentation</a></li>

</ul>
</details>

**Tags**: `#llama.cpp`, `#CUDA`, `#GPU acceleration`, `#machine learning`

---

<a id="item-29"></a>
## [Decoy Font: Optical Illusion Hides Text from AI](https://www.mixfont.com/experiments/decoy-font) ⭐️ 6.0/10

Mixfont released Decoy Font, a typeface that embeds a secret message in the blurred background of visible text, creating an optical illusion that humans can read when squinting but AI text extractors cannot easily parse. This experiment highlights the growing tension between human-readable content and AI-driven data extraction, offering a playful but limited approach to protecting text from automated reading. The font uses a hybrid image technique, similar to the Einstein-Monroe illusion, where high-frequency details form one message and low-frequency blur forms another; however, AI can still read the hidden text by resizing or analyzing individual channels.

hackernews · ray__ · Jul 16, 16:18 · [Discussion](https://news.ycombinator.com/item?id=48936584)

**Background**: Optical illusions in typography exploit the difference between human visual perception and machine vision. Hybrid images combine two images at different spatial frequencies, so the brain perceives one at close range and another at a distance or when blurred. Decoy Font applies this concept to text, embedding a secondary message in the low-frequency components.

<details><summary>References</summary>
<ul>
<li><a href="https://forgeeks.dev/decoy-font-hides-text-ai/">Decoy Font hides text from AI in plain sight — for(geeks)</a></li>
<li><a href="https://www.popsci.com/technology/font-optical-illusion-hide-ai/">This font uses an optical illusion to hide from AI | Popular Science</a></li>

</ul>
</details>

**Discussion**: Comments are lighthearted and appreciative of the novelty, with users calling it 'cool' and noting 'They Live' vibes. Some point out that AI can still read the hidden text by resizing, confirming it's not a serious anti-AI tool.

**Tags**: `#typography`, `#optical illusion`, `#AI`, `#creative coding`, `#font`

---

<a id="item-30"></a>
## [Classical ML for LLM Text Detection](https://blog.lyc8503.net/en/post/llm-classifier/) ⭐️ 6.0/10

A blog post explores using classical machine learning methods, such as TF-IDF and logistic regression, to detect LLM-generated text, achieving promising results on a small dataset. This approach offers a lightweight, transparent alternative to deep learning detectors, potentially enabling browser extensions or real-time spam filters. However, the community debate highlights fundamental doubts about the long-term viability of any detection method. The classifier uses TF-IDF features and logistic regression, trained on a dataset of human-written and LLM-generated texts. The model is small enough to run client-side, but its accuracy may degrade as LLMs evolve.

hackernews · uneven9434 · Jul 16, 16:41 · [Discussion](https://news.ycombinator.com/item?id=48936880)

**Background**: LLM-generated text detection is an active research area, with methods divided into black-box (API-level) and white-box (model-internal) approaches. Classical ML techniques like TF-IDF and logistic regression have been widely used for text classification tasks before the deep learning era.

<details><summary>References</summary>
<ul>
<li><a href="https://cacm.acm.org/research/the-science-of-detecting-llm-generated-text/">The Science of Detecting LLM-Generated Text – Communications of the ACM</a></li>
<li><a href="https://github.com/NLP2CT/LLM-generated-Text-Detection">GitHub - NLP2CT/LLM-generated-Text-Detection: A survey and reflection on the latest research breakthroughs in LLM-generated Text detection, including data, detectors, metrics, current issues and future directions. · GitHub</a></li>
<li><a href="https://medium.com/better-programming/detecting-llm-generated-texts-befce4426da9">Detecting LLM - Generated Texts . Is it possible to differentiate between</a></li>

</ul>
</details>

**Discussion**: Commenters are skeptical: some call detection a 'losing battle' and compare it to 'tarot card reading', arguing that text lacks information density for reliable provenance. Others see value in imperfect tools for reducing spam, similar to adblockers.

**Tags**: `#LLM detection`, `#machine learning`, `#AI-generated text`, `#NLP`

---

<a id="item-31"></a>
## [Mermaid Diagrams to Unicode Box Art via WebAssembly](https://simonwillison.net/2026/Jul/16/grok-mermaid/#atom-everything) ⭐️ 6.0/10

Simon Willison ported a Rust-based Mermaid terminal renderer from the Grok CLI codebase to WebAssembly, creating a browser tool that converts Mermaid diagram source code into Unicode box art. This demonstrates how Rust code can be repurposed for the web via WebAssembly, enabling terminal-style diagram rendering directly in the browser without server-side processing. The tool uses the xai-grok-markdown crate's Mermaid renderer compiled to WebAssembly, and includes features like adjustable max width, copy-as-text, and shareable diagram links.

rss · Simon Willison — AI工具 · Jul 16, 00:33

**Background**: Mermaid is a JavaScript-based diagramming tool that uses a Markdown-like syntax to generate flowcharts, sequence diagrams, and more. WebAssembly allows code written in languages like Rust to run in the browser with near-native performance. Unicode box-drawing characters are used in text-based interfaces to create simple visual frames and diagrams.

<details><summary>References</summary>
<ul>
<li><a href="https://mermaid.js.org/intro/syntax-reference.html">Diagram Syntax | Mermaid</a></li>
<li><a href="https://developer.mozilla.org/en-US/docs/WebAssembly">WebAssembly - MDN Web Docs - Mozilla</a></li>
<li><a href="https://en.wikipedia.org/wiki/Box-drawing_characters">Box -drawing characters - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#WebAssembly`, `#Mermaid`, `#Rust`, `#tool`, `#diagram`

---

<a id="item-32"></a>
## [Google rebrands NotebookLM to Gemini Notebook, opens Search to third-party apps](https://the-decoder.com/google-rebrands-notebooklm-as-gemini-notebook-and-opens-its-search-app-to-third-party-integration/) ⭐️ 6.0/10

Google has renamed NotebookLM to Gemini Notebook and introduced a new feature that gives each notebook its own cloud computer for writing and running code, initially available for AI Ultra and Workspace customers. Additionally, Google Search is now open to third-party integrations via app connections. This rebranding and deeper integration into the Gemini ecosystem signals Google's push to unify its AI tools under a single brand, making them more accessible and powerful for users. Opening Google Search to third-party apps could significantly expand its utility and create new use cases for developers. The cloud compute feature per notebook is initially limited to AI Ultra and Workspace subscribers, with broader availability expected later. NotebookLM, now Gemini Notebook, runs on Gemini 3.5 models as of June 2026 and retains features like Audio Overviews and Video Overviews.

rss · The Decoder — AI新闻 · Jul 16, 17:22

**Background**: NotebookLM is an AI-powered research and note-taking tool from Google Labs that uses retrieval-augmented generation to help users interact with their documents. It was originally launched as a standalone product and is known for generating podcast-like audio summaries and video overviews from uploaded content. The rebranding to Gemini Notebook aligns it with Google's broader Gemini AI family.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/NotebookLM">Gemini Notebook - Wikipedia</a></li>
<li><a href="https://blog.google/innovation-and-ai/products/gemini-app/notebooks-gemini-notebooklm/">Google introduces Notebooks in Gemini , a project management tool...</a></li>

</ul>
</details>

**Tags**: `#Google`, `#NotebookLM`, `#Gemini`, `#AI`, `#product update`

---

<a id="item-33"></a>
## [Sakana AI's Fugu orchestrator adds Nvidia Nemotron for collective intelligence](https://the-decoder.com/sakana-ais-fugu-adds-nvidia-nemotron-to-prove-collective-intelligence-can-rival-single-frontier-models/) ⭐️ 6.0/10

Sakana AI has integrated Nvidia's open-source Nemotron models into its Fugu orchestrator, which dynamically combines multiple language models to tackle complex tasks. The company argues that coordinated open models can rival frontier systems, though specific benchmark results are not yet provided. This move challenges the dominance of single frontier models by demonstrating that a collective of open models can achieve competitive performance. It could reduce dependency on proprietary AI systems and promote a more modular, collaborative AI ecosystem. Fugu is a language model trained to call, coordinate, and synthesize outputs from other AI models, acting as an intelligent conductor. The integration of Nemotron models expands the pool of available open models, but no benchmark comparisons have been released yet.

rss · The Decoder — AI新闻 · Jul 16, 14:02

**Background**: Collective intelligence refers to the ability of groups to solve problems more effectively than individuals. In AI, model orchestration systems like Fugu combine multiple specialized models to achieve better results. Nvidia's Nemotron family is a set of open-weight multimodal models designed for agentic AI tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://sakana.ai/fugu/">Sakana Fugu — Multi-agent System as A Model</a></li>
<li><a href="https://developer.nvidia.com/topics/ai/nemotron?ncid=no-ncid">Nemotron AI Models | NVIDIA Developer</a></li>
<li><a href="https://en.wikipedia.org/wiki/Collective_intelligence">Collective intelligence</a></li>

</ul>
</details>

**Tags**: `#AI`, `#model orchestration`, `#open-source`, `#collective intelligence`

---

<a id="item-34"></a>
## [Roblox Launches AI-Powered Game Creation in Mobile App](https://techcrunch.com/2026/07/16/roblox-launches-an-ai-powered-game-creation-feature-in-its-mobile-app/) ⭐️ 6.0/10

Roblox announced a new feature called "Build" that allows users to generate basic games from text prompts directly within the mobile app, with a public alpha launching in New Zealand on July 28, 2026. This lowers the barrier to game creation, enabling anyone without programming experience to build games on Roblox, potentially expanding the platform's creator base and accelerating content generation. The Build feature is mobile-first and will be released alongside a new suite of AI-powered tools in Roblox Studio, catering to creators of all levels. The alpha test begins July 28 in New Zealand.

rss · TechCrunch — 科技创投 · Jul 16, 18:22

**Background**: Roblox is a user-generated content platform where players can create and play games. Traditionally, game creation required using Roblox Studio on a desktop, which involves scripting in Lua. The new AI feature simplifies this by generating game logic and assets from natural language prompts.

<details><summary>References</summary>
<ul>
<li><a href="https://about.roblox.com/newsroom/2026/07/build-without-limits-on-roblox">Introducing Build : Mobile-First AI Creation on Roblox</a></li>
<li><a href="https://insider-gaming.com/robloxs-new-ai-tool-builds-games-from-text-prompts/">Roblox 's New AI Tool Builds Games From Text... - Insider Gaming</a></li>
<li><a href="https://techcrunch.com/2026/07/16/roblox-launches-an-ai-powered-game-creation-feature-in-its-mobile-app/">Roblox launches an AI -powered game creation feature ... | TechCrunch</a></li>

</ul>
</details>

**Tags**: `#AI`, `#game development`, `#Roblox`, `#mobile app`

---

<a id="item-35"></a>
## [BP Shuts Down Corporate Venture Arm After 20 Years](https://techcrunch.com/2026/07/16/oil-giant-bp-shutters-its-corporate-venture-arm-after-20-years/) ⭐️ 6.0/10

BP is shutting down BP Ventures, its corporate venture capital arm, after nearly 20 years of operation, reportedly due to poor returns. This closure signals a shift in BP's strategy away from external startup investments, potentially reducing funding for cleantech and energy transition startups. It also reflects broader challenges in corporate venture capital when returns are lackluster. BP Ventures had been operating for nearly 20 years, investing in private high-growth technology companies in the energy sector. The decision to shut down was reportedly driven by lackluster financial returns.

rss · TechCrunch — 科技创投 · Jul 16, 17:37

**Background**: Corporate venture capital (CVC) is when large corporations invest directly in external startups to gain strategic advantages. BP Ventures was BP's venturing arm, backing innovative technologies to revolutionize the energy sector. Many CVCs, like GV and Intel Capital, have been successful, but BP's experience shows that not all CVCs achieve desired returns.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Corporate_venture_capital">Corporate venture capital</a></li>
<li><a href="https://www.bp.com/about-us/what-we-do/bp-ventures">bp Ventures</a></li>

</ul>
</details>

**Tags**: `#corporate venture capital`, `#energy`, `#BP`, `#cleantech`, `#investment`

---

<a id="item-36"></a>
## [Uber acquires Delivery Hero for $14.8B](https://techcrunch.com/2026/07/16/ubers-14-8b-delivery-hero-deal-would-nearly-double-its-global-footprint/) ⭐️ 6.0/10

Uber has agreed to acquire Delivery Hero in a $14.8 billion all-stock deal, which would nearly double its global food-delivery footprint. This acquisition would create one of the world's largest food-delivery platforms outside China, significantly intensifying competition in the global food-delivery market. The deal is structured as an all-stock transaction, and Delivery Hero operates in over 60 countries across multiple continents, with a strong presence in quick commerce.

rss · TechCrunch — 科技创投 · Jul 16, 17:12

**Background**: Delivery Hero is a German multinational online food ordering and delivery company founded in 2011, operating in over 60 countries. Uber has been expanding its food delivery business through acquisitions, having completed 23 acquisitions to date.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Delivery_Hero">Delivery Hero</a></li>
<li><a href="https://tracxn.com/d/acquisitions/acquisitions-by-uber/__wAOgbkstxol2NgmW5SFgVp8zBi7klH1GO5ziIlSERR4">List of 23 Acquisitions by Uber (May 2026) - Tracxn</a></li>

</ul>
</details>

**Tags**: `#acquisition`, `#food-delivery`, `#Uber`, `#business`

---

<a id="item-37"></a>
## [Google AI Mode expands to link and interact with apps](https://techcrunch.com/2026/07/16/googles-ai-mode-now-lets-you-link-and-interact-with-select-apps/) ⭐️ 6.0/10

Google has updated its AI Mode to allow users to link and interact with select apps, enabling task completion beyond answering questions. This update transforms AI Mode from a passive Q&A tool into an active productivity assistant, potentially streamlining workflows across Google's ecosystem. The feature is an incremental update to Google's AI Mode, which was launched experimentally in March 2025 and uses the Gemini model for complex queries.

rss · TechCrunch — 科技创投 · Jul 16, 16:00

**Background**: AI Mode is a search feature within Google Search that uses the Gemini model to handle complex, multi-part queries and provide AI-generated responses. Initially available to Google One AI Premium subscribers in the US, it now expands to app interactions, allowing users to perform tasks like managing tasks or sending messages through linked apps.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Google_AI_Mode">Google AI Mode</a></li>
<li><a href="https://search.google/ways-to-search/ai-mode/">Google AI Mode - a new way to search, whatever’s on your mind</a></li>

</ul>
</details>

**Tags**: `#Google`, `#AI`, `#app integration`, `#productivity`

---

<a id="item-38"></a>
## [AMI Labs CEO rejects 'AGI' and 'superintelligence' labels](https://techcrunch.com/2026/07/16/why-ami-labs-alexandre-lebrun-wont-call-his-ai-agi-or-superintelligence/) ⭐️ 6.0/10

Alexandre LeBrun, CEO of Yann LeCun's world model startup AMI Labs, publicly dismisses the terms 'AGI' and 'superintelligence' as hype, advocating for a more grounded approach to AI development. This stance from a prominent figure in AI challenges the prevailing narrative in the industry, potentially influencing how other companies and researchers frame their AI goals and communicate with the public. LeBrun's comments come as AMI Labs, which raised $1.03B at a $3.5B valuation, focuses on world models that learn physical laws from video, a paradigm distinct from large language models.

rss · TechCrunch — 科技创投 · Jul 16, 14:40

**Background**: World models aim to build AI systems that understand the real world by learning its underlying physics and causal relationships, unlike LLMs which predict text tokens. AMI Labs, backed by Yann LeCun, is a leading proponent of this approach, targeting applications in robotics, healthcare, and industry.

<details><summary>References</summary>
<ul>
<li><a href="https://amilabs.xyz/">AMI Labs : Real World . Real Intelligence.</a></li>
<li><a href="https://techcrunch.com/2026/01/23/whos-behind-ami-labs-yann-lecuns-world-model-startup/">Who's behind AMI Labs , Yann LeCun's ‘ world model ... | TechCrunch</a></li>

</ul>
</details>

**Tags**: `#AI`, `#AGI`, `#superintelligence`, `#Yann LeCun`, `#AMI Labs`

---

<a id="item-39"></a>
## [Energy IPOs Surge as Investors Chase AI Boom](https://arstechnica.com/information-technology/2026/07/energy-ipos-surge-as-investors-hunt-for-ways-to-play-ai-boom/) ⭐️ 6.0/10

Energy companies are going public at the fastest pace this century, driven by investor demand to capitalize on the AI boom's surging power needs. This trend highlights the growing intersection between AI and energy sectors, as AI's massive computational demands require substantial electricity, creating new investment opportunities. The article notes that companies are raising money at the fastest pace this century, but does not specify exact numbers or names of IPOs.

rss · ArsTechnica — 深度科技 · Jul 16, 15:48

**Background**: AI models, especially large language models, require enormous amounts of energy for training and inference. This has led to increased demand for power generation and infrastructure, making energy companies attractive to investors seeking exposure to the AI boom.

**Tags**: `#AI`, `#energy`, `#IPOs`, `#finance`

---

<a id="item-40"></a>
## [NTSB: Tesla driver pressed accelerator 100%, not Autopilot](https://arstechnica.com/tech-policy/2026/07/tesla-driver-who-blamed-crash-on-autopilot-pressed-accelerator-100-ntsb-finds/) ⭐️ 6.0/10

The NTSB investigation found that the Tesla driver pressed the accelerator pedal 100% before the crash, contradicting claims that Autopilot caused the accident. This finding reinforces that driver error, not autonomous system failure, was the cause, which is significant for ongoing debates about the safety and liability of Tesla's Full Self-Driving (FSD) technology. The NTSB's analysis showed the accelerator was fully depressed, supporting Elon Musk's claim that the driver manually overrode the FSD system. The crash involved a Tesla vehicle operating with Full Self-Driving (Supervised) mode.

rss · ArsTechnica — 深度科技 · Jul 16, 14:48

**Background**: Tesla's Full Self-Driving (Supervised) is an advanced driver-assistance system that requires active driver supervision. The NTSB investigates transportation accidents to determine probable cause. This case highlights the importance of driver responsibility even when using automated features.

<details><summary>References</summary>
<ul>
<li><a href="https://www.ntsb.gov/investigations/process/Pages/default.aspx">The Investigative Process</a></li>
<li><a href="https://www.tesla.com/fsd">Full Self - Driving (Supervised) | Tesla</a></li>

</ul>
</details>

**Tags**: `#Tesla`, `#Autopilot`, `#NTSB`, `#autonomous driving`, `#safety`

---

