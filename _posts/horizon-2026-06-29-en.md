# Horizon Daily - 2026-06-29

> From 64 items, 35 important content pieces were selected

---

1. [Supreme Court rules geofence warrants need constitutional protections](#item-1) ⭐️ 9.0/10
2. [Claude Code Tricked into Running Hidden Malware via DNS Prompt Injection](#item-2) ⭐️ 9.0/10
3. [llama.cpp b9840 Adds DeepSeek V4 Support](#item-3) ⭐️ 8.0/10
4. [Rocket Lab Acquires Iridium in Historic $8B Deal](#item-4) ⭐️ 8.0/10
5. [Game Boy Emulator JITs to WASM, Outperforms Native Interpreter](#item-5) ⭐️ 8.0/10
6. [Deep Dive into CUDA Kernel Execution Pipeline](#item-6) ⭐️ 8.0/10
7. [Fraudulent DMCA Claim Targets Blog Post, Google Complicit](#item-7) ⭐️ 8.0/10
8. [HackerRank's Open-Source ATS Shows LLM Scoring Is Wildly Inconsistent](#item-8) ⭐️ 8.0/10
9. [Ornith-1.0: Open-Source LLMs for Agentic Coding](#item-9) ⭐️ 8.0/10
10. [Deloitte warns consultants: AI will kill the billable hour by 2035](#item-10) ⭐️ 8.0/10
11. [US military AI targeting system misses school label, hits school](#item-11) ⭐️ 8.0/10
12. [Samsung and SK Hynix Plan $590B Chip Investment](#item-12) ⭐️ 8.0/10
13. [Arena AI Leaderboard Reaches $100M Valuation](#item-13) ⭐️ 8.0/10
14. [Qwen 3.6 27B: Local Dev Sweet Spot or Costly Tradeoff?](#item-14) ⭐️ 7.0/10
15. [Article Challenges Exaggerated Radiation Risk Perception](#item-15) ⭐️ 7.0/10
16. [European ISPs Seek Rightsholder Liability for Overblocking](#item-16) ⭐️ 7.0/10
17. [Formal Verification's Promise and AI Automation](#item-17) ⭐️ 7.0/10
18. [Sandia's SA3000: A Radiation-Hardened 8085 from the 1970s](#item-18) ⭐️ 7.0/10
19. [Instagram Uses User Photos in Meta Glasses Ads](#item-19) ⭐️ 7.0/10
20. [Tidal Adopts AI Music Policy with Higher Standards](#item-20) ⭐️ 7.0/10
21. [Samsung, SK Hynix, Micron Sued in US for Memory Price Fixing](#item-21) ⭐️ 7.0/10
22. [Mullvad CEO Funds Swedish Örebro Party](#item-22) ⭐️ 7.0/10
23. [Mag 7 Stocks Show Historical Tendency to Underperform](#item-23) ⭐️ 7.0/10
24. [Jon Udell: Keep Humans in Control, Invite Agents In](#item-24) ⭐️ 7.0/10
25. [Amazon engineers distill Anthropic models to cut costs](#item-25) ⭐️ 7.0/10
26. [Meta bans engineers from using rival AI coding tools](#item-26) ⭐️ 7.0/10
27. [Anthropic and Newsom Deal: California Gets Claude at Half Price](#item-27) ⭐️ 7.0/10
28. [Quera Claims Leapfrog with Error-Corrected Qubits by 2029](#item-28) ⭐️ 7.0/10
29. [NASA's X-59 Tests Supersonic Flight Without Sonic Boom](#item-29) ⭐️ 7.0/10
30. [Porting Principia Game Engine to Windows XP](#item-30) ⭐️ 6.0/10
31. [EU seeks AI independence as Austria proposes luring Anthropic](#item-31) ⭐️ 6.0/10
32. [Waymo and Uber End Phoenix Partnership](#item-32) ⭐️ 6.0/10
33. [Cursor launches mobile app for remote coding agent oversight](#item-33) ⭐️ 6.0/10
34. [Trump admin red tape threatens 92 GW of new solar and wind](#item-34) ⭐️ 6.0/10
35. [Google Warns EU Plans to Weaken Its Monopoly Could Expose User Data](#item-35) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Supreme Court rules geofence warrants need constitutional protections](https://www.theguardian.com/us-news/2026/jun/29/supreme-court-geofence-warrants-case-decision) ⭐️ 9.0/10

The US Supreme Court ruled in Chatrie v. United States that geofence warrants are subject to Fourth Amendment protections, requiring law enforcement to obtain a warrant based on probable cause and to limit the scope of data collected. This landmark decision significantly curtails the government's ability to conduct mass location surveillance without individualized suspicion, setting a crucial precedent for digital privacy in the era of ubiquitous smartphone tracking. The case involved a bank robbery where Google provided location data of 19 accounts within 150 meters of the bank; the court ruled that such sweeping requests require a warrant with particularized suspicion. Google has since removed its centralized location history feature to reduce exposure to these warrants.

hackernews · cdrnsf · Jun 29, 15:54 · [Discussion](https://news.ycombinator.com/item?id=48720924)

**Background**: Geofence warrants allow police to demand that tech companies like Google provide location data for all devices within a defined geographic area and time period. Critics argue they amount to mass surveillance without individualized suspicion, potentially violating the Fourth Amendment's protection against unreasonable searches. The Supreme Court's ruling clarifies that such warrants must meet constitutional standards.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/04/28/scotus-chatrie-geofence-search-warrant-ruling-arguments/">US Supreme Court appears split over controversial use of ' geofence ...</a></li>
<li><a href="https://www.culawreview.org/journal/mapping-the-future-of-surveillance-geofence-warrants-and-the-risks-of-chatrie">Mapping the Future of Surveillance: Geofence Warrants and the Risks...</a></li>
<li><a href="https://www.tampacriminallawyer-blog.com/geofence-warrants-what-your-phone-reveals-and-how-to-prevent-bad-evidence-from-coming-in/">Geofence Warrants : What Your Phone Reveals and How to Prevent...</a></li>

</ul>
</details>

**Discussion**: Commenters expressed relief that the court limited geofence warrants, with some noting that even without a phone, individuals can be tracked via other means (e.g., hotel guest lists). Others questioned whether the ruling extends to other surveillance tools like automated license plate readers (Flock), and debated the dissenting opinions of Justices Alito, Thomas, and Barrett.

**Tags**: `#privacy`, `#supreme court`, `#geofence warrants`, `#digital rights`, `#law enforcement`

---

<a id="item-2"></a>
## [Claude Code Tricked into Running Hidden Malware via DNS Prompt Injection](https://the-decoder.com/claude-code-runs-a-github-repos-hidden-malware-without-verification-giving-attackers-full-control/) ⭐️ 9.0/10

Security researchers at Mozilla's 0DIN platform demonstrated that Claude Code can be tricked into executing hidden malware from a compromised GitHub repo via DNS TXT record-based prompt injection, giving attackers full control over a developer's machine. This is the first public demonstration of DNS-based prompt injection through the repository initialization pathway, highlighting a critical supply chain vulnerability in AI coding tools that bypasses traditional scanners and AI agent verification. The malicious code only loads at runtime via a DNS query, remaining invisible in the repository, to scanners, and to the AI agent itself. The attack exploits the trust model of AI coding tools that inherit the repository's apparent cleanliness.

rss · The Decoder — AI新闻 · Jun 29, 10:04

**Background**: Prompt injection is a security vulnerability that targets large language models (LLMs) by crafting malicious prompts to bypass safety filters and execute unintended instructions. AI coding tools like Claude Code operate on repositories and can execute code during setup, making them susceptible to indirect prompt injection attacks.

<details><summary>References</summary>
<ul>
<li><a href="https://dailysecurityreview.com/cyber-security/mozilla-0din-shows-ai-coding-agents-can-be-tricked-via-dns-txt/">Mozilla 0DIN Shows AI Coding Agents Can Be Tricked via DNS ...</a></li>
<li><a href="https://owasp.org/www-community/attacks/PromptInjection">Prompt Injection - OWASP Foundation</a></li>

</ul>
</details>

**Tags**: `#AI security`, `#prompt injection`, `#supply chain attack`, `#Claude Code`, `#vulnerability disclosure`

---

<a id="item-3"></a>
## [llama.cpp b9840 Adds DeepSeek V4 Support](https://github.com/ggml-org/llama.cpp/releases/tag/b9840) ⭐️ 8.0/10

llama.cpp release b9840 introduces support for the DeepSeek V4 model architecture, including conversion, inference, and optimization features. The release also includes contributions from multiple developers for bug fixes and performance improvements. This release enables local, efficient inference of DeepSeek V4, a 1 trillion parameter model, on consumer hardware via llama.cpp. It broadens access to cutting-edge LLM architectures for developers and researchers. The implementation includes a new conversion script, graph input for DeepSeek V4, support for the Pro model, and integration of Sinkhorn epsilon for improved quantization. Flash attention and graph reuse are enabled, with padding to 256 for KV cache to support flash attention.

github · github-actions[bot] · Jun 29, 10:25

**Background**: llama.cpp is an open-source C/C++ library for efficient LLM inference on CPUs and GPUs. DeepSeek V4 is a 1 trillion parameter model with a novel Engram memory architecture, representing a significant advancement in large language models.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/ggml-org/llama.cpp">GitHub - ggml-org/llama.cpp: LLM inference in C/C++</a></li>
<li><a href="https://deepseek.ai/deepseek-v4">DeepSeek V 4 (2026) — 1T Params, Benchmarks & Pricing</a></li>
<li><a href="https://huggingface.co/deepseek-ai/DeepSeek-V4-Pro">deepseek -ai/ DeepSeek - V 4 -Pro · Hugging Face</a></li>

</ul>
</details>

**Tags**: `#llama.cpp`, `#DeepSeek V4`, `#LLM inference`, `#open-source`, `#machine learning`

---

<a id="item-4"></a>
## [Rocket Lab Acquires Iridium in Historic $8B Deal](https://investors.rocketlabcorp.com/news-releases/news-release-details/rocket-lab-acquire-iridium-historic-deal-creating-fully) ⭐️ 8.0/10

Rocket Lab announced an all-stock acquisition of Iridium Communications valued at $8 billion, gaining Iridium's satellite constellation, spectrum licenses, and manufacturing capabilities. The deal creates a fully integrated space company with a guaranteed launch customer. This acquisition positions Rocket Lab to compete more directly with SpaceX and Amazon by securing a steady launch cadence and expanding into satellite services. It also provides Rocket Lab with valuable L-band spectrum and a profitable satellite business, strengthening its end-to-end space offerings. The all-stock deal values Iridium at $8 billion, and Rocket Lab gains Iridium's 66-satellite LEO constellation, spectrum, and satellite manufacturing expertise. Rocket Lab also announced Flatellite, a new satellite designed for mass manufacture of large constellations, aligning with its strategy to operate its own constellation.

hackernews · everfrustrated · Jun 29, 14:09 · [Discussion](https://news.ycombinator.com/item?id=48719485)

**Background**: Iridium operates a 66-satellite LEO constellation providing global voice and data coverage via L-band, including inter-satellite links for polar and remote areas. Rocket Lab is a leading small launch provider with the Electron rocket and has been expanding into satellite manufacturing and space systems.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Iridium_satellite_constellation">Iridium satellite constellation</a></li>
<li><a href="https://en.wikipedia.org/wiki/Rocket_Lab">Rocket Lab - Wikipedia</a></li>
<li><a href="https://rocketlabcorp.com/updates/rocket-lab-announces-flatellite-a-new-satellite-designed-for-mass-manufacture-and-tailored-for-large-constellations/">Rocket Lab Announces Flatellite: A New Satellite Designed for Mass ...</a></li>

</ul>
</details>

**Discussion**: Commenters see the deal as a strategic move to emulate SpaceX's Starlink launch leverage, providing Rocket Lab with guaranteed launch demand. Some express concern about space debris and commercialization, while others note the loss of Rocket Lab's New Zealand identity as it becomes more American.

**Tags**: `#space`, `#acquisition`, `#satellite`, `#Rocket Lab`, `#Iridium`

---

<a id="item-5"></a>
## [Game Boy Emulator JITs to WASM, Outperforms Native Interpreter](https://humphri.es/blog/WATaBoy/) ⭐️ 8.0/10

WATaBoy, a Game Boy emulator, uses JIT compilation to translate Game Boy instructions into WebAssembly, achieving performance that beats native interpreters. This cleverly bypasses iOS JIT restrictions by leveraging the browser's WASM support. This demonstrates a novel approach to high-performance emulation on platforms like iOS that restrict JIT compilation, potentially enabling more complex emulators on mobile devices. It also highlights the growing capability of WebAssembly as a compilation target. The emulator compiles Game Boy instructions to WASM at runtime, and the resulting performance exceeds that of a native interpreter due to WASM's low overhead (~20%) compared to interpreter overhead (~1000%). Firefox was observed to be 25% slower than Chrome/Safari in this context.

hackernews · energeticbark · Jun 29, 15:02 · [Discussion](https://news.ycombinator.com/item?id=48720190)

**Background**: JIT (Just-In-Time) compilation compiles code at runtime for faster execution, but iOS restricts JIT for non-browser apps. WebAssembly (WASM) is a low-level binary format that runs in browsers with near-native performance. Emulators typically use interpretation or JIT to run old game code; JIT is faster but harder to implement on restricted platforms.

<details><summary>References</summary>
<ul>
<li><a href="https://snyk.io/blog/webassembly-security-concerns/">How secure is WebAssembly ? 5 security concerns unique to... | Snyk</a></li>
<li><a href="https://8bitworkshop.com/docs/posts/2021/webassembly-vs-javascript-emulator-performance.html">Emulator Performance: WebAssembly vs. JavaScript</a></li>

</ul>
</details>

**Discussion**: Commenters praised the project as impressive for an undergraduate, and noted that WASM's low overhead naturally beats interpreters. One commenter wondered why Firefox was slower, while another wished for iOS-native comparisons.

**Tags**: `#emulation`, `#WebAssembly`, `#JIT`, `#iOS`, `#game boy`

---

<a id="item-6"></a>
## [Deep Dive into CUDA Kernel Execution Pipeline](https://fergusfinn.com/blog/what-happens-when-you-run-a-gpu-kernel/) ⭐️ 8.0/10

A detailed blog post explains the full pipeline of GPU kernel execution, from CPU launch through driver interaction, stream semantics, and warp scheduling on NVIDIA hardware. This article fills a critical gap in understanding for HPC practitioners, as GPU kernel execution internals are often opaque, and such knowledge is essential for performance optimization. The post covers implicit synchronization via semaphores in the default stream, warp eligibility criteria, and the role of the GPU's hardware scheduler in selecting warps for execution.

hackernews · mezark · Jun 29, 13:11 · [Discussion](https://news.ycombinator.com/item?id=48718863)

**Background**: CUDA kernels are functions that run on NVIDIA GPUs. When launched, the CPU enqueues the kernel to a stream, and the GPU driver manages execution asynchronously. The GPU's streaming multiprocessors (SMs) execute groups of 32 threads called warps, and a hardware scheduler selects eligible warps each cycle to hide latency.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.nvidia.com/cuda/cuda-programming-guide/03-advanced/advanced-kernel-programming.html">3.2. Advanced Kernel Programming — CUDA Programming Guide</a></li>
<li><a href="https://docs.nvidia.com/cuda/cuda-programming-guide/02-basics/asynchronous-execution.html">2.5. Asynchronous Execution — CUDA Programming Guide</a></li>
<li><a href="https://stevengong.co/notes/Warp-Scheduling">Warp Scheduling (GPU Thread Scheduling) - stevengong.co</a></li>

</ul>
</details>

**Discussion**: Commenters appreciated the article's depth, with one noting it would have been helpful during their HPC master's. Another highlighted that using the CUDA driver API instead of runtime API provides better visibility into execution. A discussion also emerged about whether kernel optimization companies will be disrupted by open-source libraries.

**Tags**: `#CUDA`, `#GPU`, `#HPC`, `#kernel execution`, `#NVIDIA`

---

<a id="item-7"></a>
## [Fraudulent DMCA Claim Targets Blog Post, Google Complicit](https://blog.pragmaticengineer.com/pollen-tried-to-remove-my-article-about-callum-negus-fancey-and-google-is-assisting-to-it/) ⭐️ 8.0/10

A blog post on The Pragmatic Engineer details how a fraudulent DMCA takedown notice was filed against an article about Callum Negus-Fancey, with Google processing the removal request despite its apparent lack of merit. This incident highlights systemic abuse of the DMCA takedown process, where platforms like Google facilitate censorship without verifying claims, threatening free speech and investigative journalism. The fraudulent claim was likely filed by a reputation management firm, and Google's automated system processed the takedown without human review, demonstrating the ease of exploiting the process.

hackernews · taubek · Jun 29, 09:28 · [Discussion](https://news.ycombinator.com/item?id=48716902)

**Background**: The DMCA (Digital Millennium Copyright Act) allows copyright holders to request removal of infringing content. However, the process is often abused through false claims, as platforms rarely verify the legitimacy of notices due to safe harbor protections.

<details><summary>References</summary>
<ul>
<li><a href="https://bolster.ai/blog/what-is-a-dmca-takedown">What is a DMCA Takedown ? | Notice, Requirements & More</a></li>
<li><a href="https://patentpc.com/blog/the-legal-consequences-of-filing-false-dmca-claims">The Legal Consequences of Filing False DMCA Claims | PatentPC</a></li>
<li><a href="https://en.wikipedia.org/wiki/Copyfraud">Copyfraud - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters expressed outrage at the abuse, with many calling for mandatory government ID verification for takedown notices and stronger penalties for fraudulent claims. Some noted the Streisand effect, as the attempt to suppress the article only increased its visibility.

**Tags**: `#DMCA`, `#Google`, `#content moderation`, `#free speech`, `#reputation management`

---

<a id="item-8"></a>
## [HackerRank's Open-Source ATS Shows LLM Scoring Is Wildly Inconsistent](https://danunparsed.com/p/hackerrank-open-source-ats) ⭐️ 8.0/10

HackerRank open-sourced its AI-powered Applicant Tracking System (ATS), and an investigation found that LLM-based resume scoring is highly inconsistent: the same resume scored 90, 74, and 88 on different runs. This exposes critical flaws in AI-based resume screening, which is increasingly used by companies and may lead to unfair hiring decisions, legal risks under anti-discrimination laws, and wasted candidate effort. The scoring rubric weights open-source contributions highest (35/120 points), while technical skills are lowest (10/120). The investigation used temperature 0.1, yet still observed large score variations, indicating inherent stochasticity.

hackernews · sambellll · Jun 29, 01:44 · [Discussion](https://news.ycombinator.com/item?id=48713832)

**Background**: Applicant Tracking Systems (ATS) are used by employers to filter and rank resumes. HackerRank's ATS uses a Large Language Model (LLM) to score resumes against a predefined rubric. LLMs are stochastic by nature, meaning their outputs can vary even with the same input, which raises concerns about reliability and fairness in hiring.

<details><summary>References</summary>
<ul>
<li><a href="https://byteiota.com/hackerrank-ats-open-source-the-hiring-rubric-inside/">HackerRank ATS Open Source: The Hiring Rubric Inside</a></li>
<li><a href="https://arxiv.org/html/2506.22316v2">Evaluating Scoring Bias in LLM-as-a-Judge - arXiv.org</a></li>
<li><a href="https://re-cinq.github.io/hiring-bias/">Bias Research, Counterfactual Audit of LLM Résumé Scoring</a></li>

</ul>
</details>

**Discussion**: Commenters expressed alarm that LLM-based screening is unreliable and potentially illegal in the EU due to anti-discrimination laws. Some noted that even a 35% pass rate is considered acceptable by hiring managers overwhelmed by applicants, while others highlighted biases favoring AI-generated content and open-source contributions.

**Tags**: `#AI`, `#hiring`, `#LLM`, `#bias`, `#resume screening`

---

<a id="item-9"></a>
## [Ornith-1.0: Open-Source LLMs for Agentic Coding](https://simonwillison.net/2026/Jun/29/ornith/#atom-everything) ⭐️ 8.0/10

DeepReinforce released Ornith-1.0, a family of MIT-licensed open-weight LLMs (9B to 397B parameters) built on Gemma 4 and Qwen 3.5, achieving state-of-the-art coding benchmark performance among open-source models of comparable size. This release significantly advances open-source AI coding agents by providing permissively licensed, high-performing models that can self-scaffold—improving their own tool-use capabilities during inference. The model family includes dense 9B and 31B variants, plus 35B and 397B Mixture-of-Experts (MoE) configurations. Early user tests show strong performance on multi-step agentic tasks, such as navigating a codebase and executing tool calls.

rss · Simon Willison — AI工具 · Jun 29, 16:17

**Background**: Self-scaffolding refers to a model's ability to generate and refine its own reasoning steps or tool-use plans during inference, improving performance on complex tasks without external scaffolding. Ornith-1.0 is built on Gemma 4 (Apache 2.0) and Qwen 3.5 (Apache 2.0), ensuring license compatibility. The model is available via Hugging Face and can be run locally with tools like LM Studio.

<details><summary>References</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Jun/29/ornith/">Ornith-1.0: Self - Scaffolding LLMs for Agentic Coding</a></li>
<li><a href="https://news.ycombinator.com/item?id=48709744">Ornith-1.0: Self - Scaffolding LLMs for Agentic Coding | Hacker News</a></li>
<li><a href="https://www.ornith.site/">Ornith 1 . 0 — Open-Source Agentic Coding Models</a></li>

</ul>
</details>

**Discussion**: Community reactions are mixed: some praise its coding performance and creative solutions, while others note it may be overfit to benchmarks and prone to hallucination in chat without tools. Questions remain about the identity of DeepReinforce and the self-improvement mechanism.

**Tags**: `#LLM`, `#open-source`, `#coding`, `#AI agents`, `#model release`

---

<a id="item-10"></a>
## [Deloitte warns consultants: AI will kill the billable hour by 2035](https://the-decoder.com/deloitte-tells-its-own-consultants-ai-is-coming-for-the-billable-hour/) ⭐️ 8.0/10

An internal Deloitte presentation projects that the consulting industry's traditional hourly billing model will shrink to a small fraction of the market by 2035, replaced by AI agents. The presentation reportedly stated, 'Our model is toast.' This signals a paradigm shift for the consulting industry, as the billable hour has been the core revenue model for decades. If AI can automate tasks that consultants bill for, firms like Deloitte, McKinsey, and BCG must find new ways to monetize their expertise. The projection comes from an internal Deloitte presentation, and competitors McKinsey and BCG are already searching for alternative revenue models. The article does not specify which AI agents or technologies are expected to replace consultants, but the trend toward AI-driven automation in professional services is accelerating.

rss · The Decoder — AI新闻 · Jun 29, 15:14

**Background**: The billable hour model charges clients based on the time consultants spend on a project, incentivizing longer hours rather than efficiency. AI agents—software that can perform tasks autonomously—are increasingly capable of data analysis, report generation, and other consulting deliverables. Major consulting firms are investing heavily in AI to improve efficiency, which threatens the traditional billing structure.

<details><summary>References</summary>
<ul>
<li><a href="https://firmsconsulting.com/quarterly/billable-hours-strategy-consulting/">Consulting Billable Hours Model In Management Consulting</a></li>
<li><a href="https://projectcor.com/blog/billable-hours-in-consulting-firms-tips-for-driving-success/">Billable Hours in Consulting Firms: Tips for Driving Success - COR</a></li>
<li><a href="https://www.linkedin.com/pulse/ai-big-consulting-what-large-players-all-doing-5st4c/">AI in Big Consulting: What the Large Players Are All Doing in ...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#consulting`, `#business model`, `#automation`, `#industry disruption`

---

<a id="item-11"></a>
## [US military AI targeting system misses school label, hits school](https://the-decoder.com/the-us-military-used-ai-to-pick-thousands-of-targets-but-missed-a-note-saying-one-was-a-school/) ⭐️ 8.0/10

A US military AI-assisted targeting system selected a school in Iran as a target, ignoring a note identifying it as a school, leading to a missile strike on the building. This incident exposes critical flaws in AI-assisted military targeting, raising urgent ethical and operational concerns about accountability and the reliability of AI in life-and-death decisions. The AI system, part of the Maven Smart System, processed thousands of targets but failed to incorporate a human-added note that flagged the location as a school. The Pentagon is revising its targeting principles to allow AI to initiate actions with human monitoring.

rss · The Decoder — AI新闻 · Jun 29, 12:30

**Background**: The US military has been increasingly using AI systems like the Maven Smart System to analyze intelligence and recommend targets. These systems are designed to speed up targeting but can miss contextual information that a human analyst would catch. The incident highlights the tension between efficiency and accuracy in AI-assisted warfare.

<details><summary>References</summary>
<ul>
<li><a href="https://www.bloomberg.com/news/articles/2026-06-25/pentagon-sees-broader-role-for-ai-in-setting-military-targets">Pentagon Sees Broader Role for AI in Setting Military Targets - Bloomberg</a></li>
<li><a href="https://www.brennancenter.org/our-work/research-reports/militarys-use-ai-explained">The Military’s Use of AI, Explained | Brennan Center for Justice</a></li>

</ul>
</details>

**Tags**: `#AI ethics`, `#military AI`, `#targeting systems`, `#accountability`, `#AI failure`

---

<a id="item-12"></a>
## [Samsung and SK Hynix Plan $590B Chip Investment](https://the-decoder.com/samsung-and-sk-hynix-plan-590-billion-chip-investment-as-ai-demand-sends-memory-prices-soaring/) ⭐️ 8.0/10

Samsung and SK Hynix, with South Korean government backing, announced a $590 billion investment in new chip factories and packaging centers to meet surging AI demand for high-bandwidth memory (HBM). This massive investment underscores the critical role of memory chips in AI infrastructure and could reshape the global semiconductor supply chain, potentially alleviating the ongoing memory shortage that has driven prices up 50% per quarter. The two companies control nearly 80% of the global HBM market, and Jefferies analysts predict memory prices could rise 40-50% in Q3 2026 and continue climbing through 2027.

rss · The Decoder — AI新闻 · Jun 29, 08:17

**Background**: High-bandwidth memory (HBM) is a cutting-edge 2.5D/3D memory architecture with a wide data path, essential for AI accelerators like GPUs. The current memory shortage, sometimes called 'RAMmageddon,' began in 2025 due to manufacturing capacity being reallocated to high-margin AI memory products, causing scarcity in consumer and enterprise PCs.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/HBM_memory_shortage">HBM memory shortage</a></li>
<li><a href="https://en.wikipedia.org/wiki/High_Bandwidth_Memory">High Bandwidth Memory - Wikipedia</a></li>
<li><a href="https://wccftech.com/jefferies-warns-memory-prices-surge-50-percent-q3-40-in-q4-2026-no-relief-until-2028/">Jefferies Warns Memory Prices Will Surge 50% in Q3 2026 and...</a></li>

</ul>
</details>

**Tags**: `#AI hardware`, `#semiconductors`, `#memory`, `#investment`, `#HBM`

---

<a id="item-13"></a>
## [Arena AI Leaderboard Reaches $100M Valuation](https://techcrunch.com/2026/06/29/arena-the-ai-leaderboard-everyone-uses-is-now-a-100m-business/) ⭐️ 8.0/10

Arena, the crowdsourced AI leaderboard that started as a UC Berkeley research project in 2023, has reached $100 million in annualized revenue just eight months after launching its first commercial product, AI Evaluations, in September 2025. This milestone validates the market demand for standardized, community-driven AI model evaluation, and signals that independent benchmarking platforms can become sustainable businesses in the rapidly growing AI industry. Arena's free leaderboard remains publicly accessible, while its commercial AI Evaluations service offers deep-dive performance analysis for model labs and enterprises. The company achieved this revenue run rate in under a year from launch.

rss · TechCrunch — 科技创投 · Jun 29, 17:39

**Background**: Arena is a crowdsourced platform where users chat with and compare AI models, voting to create a public leaderboard. It was originally developed by researchers at UC Berkeley and has become a widely referenced benchmark in the AI community. The platform covers LLMs, image, and code models.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/06/29/arena-the-ai-leaderboard-everyone-uses-is-now-a-100m-business/">Arena, the AI leaderboard everyone uses, is now a $100M business | TechCrunch</a></li>
<li><a href="https://thenextweb.com/news/arena-ai-leaderboard-100-million-revenue-evaluation">Arena, the AI leaderboard everyone uses, just became a 100 million dollar business</a></li>
<li><a href="https://arena.ai/">Arena AI: The Official AI Ranking & LLM Leaderboard</a></li>

</ul>
</details>

**Tags**: `#AI`, `#startup`, `#valuation`, `#leaderboard`

---

<a id="item-14"></a>
## [Qwen 3.6 27B: Local Dev Sweet Spot or Costly Tradeoff?](https://quesma.com/blog/qwen-36-is-awesome/) ⭐️ 7.0/10

Qwen 3.6 27B is a newly released dense 27-billion-parameter multimodal model that achieves 77.2% on SWE-bench Verified, outperforming the much larger Qwen 3.5 397B MoE model on coding benchmarks. This model makes flagship-level coding performance accessible to developers running LLMs locally, but practical hardware constraints—thermal throttling, fan noise, and high cost—may push users toward cloud alternatives. Running Qwen 3.6 27B on a 128GB MacBook Pro (starting at $6,699) is technically possible but causes severe thermal and noise issues during sustained use; a Mac Mini M4 is recommended as a more practical alternative.

hackernews · stared · Jun 29, 17:05 · [Discussion](https://news.ycombinator.com/item?id=48721903)

**Background**: Large language models (LLMs) like Qwen 3.6 27B require significant GPU memory and compute power. Running them locally on consumer hardware often involves tradeoffs between model size, speed, and usability. The 27B parameter size is considered a sweet spot for balancing capability and hardware feasibility.

<details><summary>References</summary>
<ul>
<li><a href="https://qwen.ai/blog?id=qwen3.6-27b">Qwen3.6-27B: Flagship-Level Coding in a 27B Dense Model</a></li>
<li><a href="https://github.com/QwenLM/Qwen3.6">GitHub - QwenLM/Qwen3.6: Qwen3.6 is the large language model ...</a></li>
<li><a href="https://www.aimadetools.com/blog/qwen-3-6-27b-complete-guide/">Qwen 3.6-27B Complete Guide: 77.2% SWE-bench in a 27B Dense ...</a></li>

</ul>
</details>

**Discussion**: Community comments highlight that the MacBook Pro's thermal and noise issues make it unsuitable for serious local LLM work, and that the high hardware cost could instead buy substantial cloud credits. Some users suggest using sparse MoE models like DeepSeek-V4-Flash for better performance per dollar.

**Tags**: `#local LLM`, `#Qwen`, `#hardware`, `#cost analysis`, `#developer experience`

---

<a id="item-15"></a>
## [Article Challenges Exaggerated Radiation Risk Perception](https://worksinprogress.co/issue/how-to-lie-about-radiation/) ⭐️ 7.0/10

An article titled 'The Radiation Exposure Lie' argues that public perception of radiation risk is exaggerated compared to other health risks like smoking and obesity. This matters because it challenges common narratives about radiation, potentially influencing public policy and personal health decisions regarding nuclear energy and medical procedures. The article references Geraldine Thomas of the Chernobyl Tissue Bank, who stated that smoking and obesity are more harmful than radiation, and discusses the Linear No Threshold model's limitations.

hackernews · duffydotsvg · Jun 29, 16:27 · [Discussion](https://news.ycombinator.com/item?id=48721308)

**Background**: Radiation risk perception is often shaped by high-profile events like Chernobyl and Fukushima, leading to fear disproportionate to actual health impacts. The Linear No Threshold (LNT) model assumes any radiation exposure carries risk, but some research suggests low doses may be less harmful or even beneficial.

**Discussion**: Commenters debate the evidence, with some supporting the article's claims by citing experts like Geraldine Thomas, while others accuse the author of cherry-picking data, particularly regarding childhood thyroid cancer rates after Chernobyl.

**Tags**: `#radiation`, `#health`, `#nuclear`, `#risk perception`, `#science communication`

---

<a id="item-16"></a>
## [European ISPs Seek Rightsholder Liability for Overblocking](https://torrentfreak.com/european-isps-want-rightsholders-held-accountable-for-overblocking-damage/) ⭐️ 7.0/10

European ISPs are arguing that rightsholders should be held legally and financially accountable for damages caused by overblocking legitimate content, shifting the current liability-free approach. This could rebalance the power dynamic between rightsholders and ISPs, reducing censorship of lawful material and forcing rightsholders to be more precise in takedown requests. Overblocking occurs when site-blocking orders intended to target piracy also block legitimate content, causing economic or reputational harm to innocent third parties.

hackernews · Brajeshwar · Jun 29, 16:07 · [Discussion](https://news.ycombinator.com/item?id=48721072)

**Background**: Currently, rightsholders can push for broad blocking orders without facing direct liability if overblocking occurs. ISPs often bear the burden of implementing these blocks and dealing with complaints from affected users. This proposal aims to introduce accountability for rightsholders, similar to calls from Cloudflare and others.

<details><summary>References</summary>
<ul>
<li><a href="https://torrentfreak.com/european-isps-want-rightsholders-held-accountable-for-overblocking-damage/">European ISPs Want Rightsholders Held Accountable... * TorrentFreak</a></li>
<li><a href="https://nsanedown.theproxy.ws/news/file-sharing-news/cloudflare-warns-eu-about-extensive-piracy-overblocking-calls-for-safeguards-r29608/">Cloudflare Warns EU About Extensive Piracy Overblocking , Calls for...</a></li>

</ul>
</details>

**Discussion**: Commenters largely support the move, noting that current systems like the US DMCA lack liability for overblocking, leading to censorship. Some suspect the timing is influenced by AI companies seeking data access, while others criticize ISPs for initially caving to blocking demands.

**Tags**: `#ISP`, `#copyright`, `#censorship`, `#DMCA`, `#EU policy`

---

<a id="item-17"></a>
## [Formal Verification's Promise and AI Automation](https://queue.acm.org/detail.cfm?id=3819084) ⭐️ 7.0/10

An article in ACM Queue explores the current state of formal verification, arguing that while it remains limited to toy examples for most developers, AI has the potential to automate the verification process and make it accessible beyond safety-critical systems. This matters because formal verification can mathematically prove software correctness, preventing costly bugs and security flaws; if AI can reduce the effort required, it could transform software reliability across the industry. The article notes that even in verified systems, UI, network calls, and database interactions typically remain outside the verification boundary, so verification makes the core airtight but doesn't guarantee overall system correctness.

hackernews · eatonphil · Jun 29, 14:12 · [Discussion](https://news.ycombinator.com/item?id=48719521)

**Background**: Formal verification uses mathematical methods to prove that a system behaves correctly according to a specification. It has been used in safety-critical domains like aerospace and hardware, but its high cost and complexity have limited adoption in general software development. Recent advances in AI, particularly large language models, are being explored to automate parts of the verification process.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2506.10998v1">Towards Automated Formal Verification of Backend Systems with...</a></li>
<li><a href="https://logicalintelligence.com/blog/automatic-formal-verification-for-code-generation">Automatic Formal Verification for Code Generation</a></li>
<li><a href="https://www.toolmage.com/en/tool/imandra/">Imandra: AI -Powered Formal Verification & Automated ... - ToolMage</a></li>

</ul>
</details>

**Discussion**: Commenters debate the practical applicability of formal verification: some argue it's still too limited for most app developers, while others see AI as a promising way to automate tedious verification tasks. One commenter shares their own project on formally verified web frontends, and another with extensive experience in formal verification provides nuanced perspectives.

**Tags**: `#formal verification`, `#AI`, `#software engineering`, `#security`, `#programming languages`

---

<a id="item-18"></a>
## [Sandia's SA3000: A Radiation-Hardened 8085 from the 1970s](https://www.cpushack.com/2026/06/03/sandia-national-labs-sa3000-8085-cpu/) ⭐️ 7.0/10

An article on CPU Shack details Sandia National Labs' SA3000, a radiation-hardened CMOS version of the Intel 8085 CPU developed in the late 1970s and released in 1982. This historical example highlights early government investment in in-house radiation-hardened chip design, a capability still critical for space and defense systems today. The SA3000 used a 3μm process on 4-inch wafers, increased transistor count from 6,500 to 18,000, and operated at 4.5-11V to tolerate up to 1×10^6 rads with only a 25% performance drop.

hackernews · rbanffy · Jun 29, 10:20 · [Discussion](https://news.ycombinator.com/item?id=48717287)

**Background**: Radiation hardening is the process of making electronics resistant to ionizing radiation, essential for satellites and nuclear systems. The Intel 8085 was a popular 8-bit microprocessor from 1977. Sandia National Labs developed the SA3000 by converting the 8085 design to CMOS and adding guard rings and hardened oxides for latchup control.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cpushack.com/2026/06/03/sandia-national-labs-sa3000-8085-cpu/">Sandia National Labs SA3000 8085 CPU | The CPU Shack Museum</a></li>
<li><a href="https://hb.int2inf.com/en/s/item/8JpZpT1LXsdZasFHBhjJo5-Sandia-SA3000-8085-CPU-radiation-hardened-history">Sandia National Labs SA3000 8085 CPU | Hasty Briefs</a></li>
<li><a href="https://en.wikipedia.org/wiki/Radiation_hardening">Radiation hardening - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters noted modern rad-hard processors like the MOOG BRE440 and BAE RAD5500, which use IBM POWER architecture, and debated the merits of government in-house technical capability versus outsourcing. Some expressed surprise that nuclear weapons systems relied on such simple processors.

**Tags**: `#hardware`, `#history`, `#radiation-hardened`, `#CPUs`, `#government`

---

<a id="item-19"></a>
## [Instagram Uses User Photos in Meta Glasses Ads](https://twitter.com/i/status/2071277885646868536) ⭐️ 7.0/10

Instagram is incorporating users' profile pictures into advertisements for Meta's Ray-Ban smart glasses, reviving privacy concerns about using personal content without explicit consent. This practice highlights ongoing tensions between user privacy and Meta's advertising model, potentially eroding trust and prompting users to reconsider their participation on the platform. The ads appear on users' feeds and may feature friends' photos, as Meta's Terms of Service grant permission to use user content in commercial contexts. Similar controversies occurred with Facebook in 2013.

hackernews · notRobot · Jun 29, 13:26 · [Discussion](https://news.ycombinator.com/item?id=48719027)

**Background**: Meta's Ray-Ban smart glasses, released in 2023, allow users to take photos and videos, livestream, and access AI features. Instagram's ad system leverages user data for targeted advertising, which has historically sparked privacy debates.

<details><summary>References</summary>
<ul>
<li><a href="https://www.indiatimes.com/trending/why-is-instagram-facing-backlash-over-metas-ai-glasses-ads-user-claims-her-profile-picture-was-used-in-a-targeted-ad-on-her-boyfriends-feed-amid-privacy-concerns/articleshow/132075679.html">Why is Instagram facing backlash over Meta's AI glasses ads ...</a></li>
<li><a href="https://www.fashiontimes.co.uk/meta-ai-glasses-ad-privacy-debate-1760716">Meta AI Glasses Ad on Instagram Sparks Backlash for Using ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Meta_glasses">Meta glasses</a></li>

</ul>
</details>

**Discussion**: Commenters recall Facebook's similar 2013 ad controversy and express frustration, with some noting the Terms of Service allow it but questioning the ethics. Others suggest creating shell accounts or leaving the platform entirely.

**Tags**: `#privacy`, `#social media`, `#Meta`, `#advertising`, `#user rights`

---

<a id="item-20"></a>
## [Tidal Adopts AI Music Policy with Higher Standards](https://tidal.com/ai-policy) ⭐️ 7.0/10

Tidal has announced a policy that accepts AI-generated music but holds it to higher standards to prevent exploitation, deception, and quality degradation. This policy sets a precedent for how streaming platforms can balance AI innovation with content integrity, potentially influencing industry-wide norms. The policy explicitly prohibits AI music that exploits an individual's or group's music, name, or likeness, deceives listeners, or diminishes service quality.

hackernews · hn8726 · Jun 29, 13:09 · [Discussion](https://news.ycombinator.com/item?id=48718840)

**Background**: AI-generated music has raised concerns about copyright infringement and authenticity. Tidal's approach aims to allow AI music while protecting artists and listeners.

**Discussion**: Commenters generally support the policy as reasonable, but some express skepticism about enforcement and a desire for human-only music platforms.

**Tags**: `#AI`, `#music`, `#policy`, `#copyright`, `#ethics`

---

<a id="item-21"></a>
## [Samsung, SK Hynix, Micron Sued in US for Memory Price Fixing](https://en.sedaily.com/international/2026/06/29/samsung-sk-hynix-micron-sued-in-us-over-memory-price-fixing) ⭐️ 7.0/10

Samsung, SK Hynix, and Micron have been sued in the United States for allegedly conspiring to fix memory chip prices, including DRAM and HBM products. This lawsuit could impact the global memory market, potentially leading to price adjustments and increased scrutiny of pricing practices among major manufacturers. A similar lawsuit in 2022 failed due to lack of evidence of an agreement. The current case also involves HBM, which is a type of DRAM, and questions the discontinuation of older DDR3 and DDR4 products.

hackernews · donohoe · Jun 29, 11:58 · [Discussion](https://news.ycombinator.com/item?id=48718102)

**Background**: Memory price fixing has a history in the industry, with a major scandal in the early 2000s. DRAM is a key component in computers and servers, and HBM is used in high-performance computing and AI accelerators.

**Discussion**: Community comments note that a similar attempt in 2022 failed, and some argue that discontinuing older products is not price fixing but a natural market shift. Others question whether Samsung and SK Hynix could simply stop selling to the US.

**Tags**: `#memory`, `#price fixing`, `#lawsuit`, `#hardware`, `#industry`

---

<a id="item-22"></a>
## [Mullvad CEO Funds Swedish Örebro Party](https://det.social/@lostgen/116820546568940358) ⭐️ 7.0/10

It has been revealed that Fredrik Strömberg, CEO of Mullvad VPN, is the main financier of the Swedish Örebro Party, a local nationalist political party. This news sparks debate about the political influence of tech leaders and raises questions about the alignment of a privacy-focused company's values with a nationalist party's platform. The Örebro Party is a local party in Örebro, Sweden, described as nationalist but not far-right, and plans to run in the 2026 Swedish general election.

hackernews · Risse · Jun 29, 10:45 · [Discussion](https://news.ycombinator.com/item?id=48717469)

**Background**: Mullvad VPN is a well-known privacy-focused VPN service based in Sweden, praised for its strong commitment to anonymity and open-source software. The Örebro Party is a local political party with nationalist leanings, and its leader Markus Allard announced intentions to run nationally in 2026.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mullvad_VPN">Mullvad VPN</a></li>

</ul>
</details>

**Discussion**: Community comments express disappointment and concern, with some users stating they will stop using Mullvad due to the CEO's political involvement. Others debate the party's ideology, noting it is nationalist but not far-right, and question the broader trend of tech leaders funding political parties.

**Tags**: `#politics`, `#privacy`, `#Mullvad`, `#Sweden`, `#CEO`

---

<a id="item-23"></a>
## [Mag 7 Stocks Show Historical Tendency to Underperform](https://www.apollo.com/content/dam/apolloaem/pdf/daily-spark/2026/jun/28/062826-Mag7.pdf) ⭐️ 7.0/10

A report from Apollo highlights that historically, top-performing stocks like the Mag 7 tend to underperform the broader market over the subsequent decade, with median ten-year market-adjusted returns of -17.8% for recent winners. This analysis challenges the assumption that the Mag 7 will continue to lead, especially amid massive AI capex spending, and suggests investors may need to reassess their portfolios for potential underperformance. The data covers U.S. stocks since 1926, showing that stocks in the top 20% of past five-year performance have a median ten-year market-adjusted return of -17.8%, underperforming by 1.94% per year.

hackernews · mooreds · Jun 29, 14:12 · [Discussion](https://news.ycombinator.com/item?id=48719532)

**Background**: The Mag 7 refers to the seven largest U.S. tech stocks: Apple, Microsoft, Alphabet, Amazon, Nvidia, Meta, and Tesla. AI capex (capital expenditure) is the massive spending by Big Tech on AI infrastructure, which has raised concerns about returns on investment.

<details><summary>References</summary>
<ul>
<li><a href="https://www.investopedia.com/magnificent-seven-stocks-8402262">investopedia.com/magnificent- seven - stocks -8402262</a></li>
<li><a href="https://fourweekmba.com/the-ai-capex-race/">The AI Capex Race - FourWeekMBA</a></li>
<li><a href="https://www.investing.com/analysis/ai-capex-the-new-arms-race-in-tech-200664346">AI Capex: The New Arms Race in Tech? - Investing.com</a></li>

</ul>
</details>

**Discussion**: Commenters debate whether AI capex will generate returns, with some noting that downstream companies benefit, while others question Google's valuation increase. There is also discussion about market discipline and the impact of stock buybacks.

**Tags**: `#finance`, `#stock market`, `#Mag 7`, `#investing`, `#market analysis`

---

<a id="item-24"></a>
## [Jon Udell: Keep Humans in Control, Invite Agents In](https://simonwillison.net/2026/Jun/28/jon-udell/#atom-everything) ⭐️ 7.0/10

Jon Udell reframes 'human in the loop' as 'agent in the loop', arguing that agent-assisted development should keep humans in control and invite agents into the existing workflow rather than excluding humans. This perspective challenges the dominant narrative of autonomous AI agents, emphasizing human agency and reviewability in software development, which is crucial for code quality and trust in AI-assisted workflows. Udell specifically warns against agents creating 'unreviewable PRs' with thousands of lines of LLM-generated code, and suggests using reviewer agents to scan and triage issues instead of removing humans from the loop.

rss · Simon Willison — AI工具 · Jun 28, 21:57

**Background**: The phrase 'human in the loop' traditionally means a human oversees AI decisions. Udell argues this phrasing cedes authority to machines. He proposes flipping the narrative: developers work as usual, but recruit AI agents as team members, keeping the loop human-owned.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.jonudell.net/2026/06/28/doctor-it-hurts-when-agents-create-unreviewable-prs-dont-do-that/">“Doctor, it hurts when agents create unreviewable PRs.” “Don ...</a></li>
<li><a href="https://dev.to/denlava/ai-generated-prs-lack-human-oversight-leading-to-poor-code-quality-implementing-review-guidelines-12ni">AI-Generated PRs Lack Human Oversight, Leading to Poor Code ...</a></li>
<li><a href="https://medium.com/@abhilash_m/your-ai-coding-agent-is-a-100x-developer-but-your-code-review-process-isnt-87f09e82fc73">Your AI coding agent is a 100x developer. But your code ...</a></li>

</ul>
</details>

**Tags**: `#AI-assisted development`, `#human-agent collaboration`, `#software engineering`, `#coding agents`

---

<a id="item-25"></a>
## [Amazon engineers distill Anthropic models to cut costs](https://the-decoder.com/amazon-engineers-are-reportedly-distilling-anthropic-models-to-cut-costs-before-new-token-based-pricing-kicks-in/) ⭐️ 7.0/10

Amazon engineers are reportedly distilling Anthropic's large language models into smaller, cheaper versions for internal use, ahead of a shift to token-based pricing in 2026. This move signals that even major cloud customers are seeking ways to reduce AI inference costs, and it could pressure AI providers to offer more flexible pricing or risk losing business to competitors like OpenAI. Starting next year, Amazon will pay Anthropic based on tokens processed rather than compute hours, which could significantly increase costs. Amazon is also exploring alternatives like OpenAI.

rss · The Decoder — AI新闻 · Jun 29, 18:05

**Background**: Model distillation is a technique where a smaller, cheaper model is trained to mimic the outputs of a larger, more capable model, preserving performance on specific tasks at a fraction of the cost. Token-based pricing charges per unit of text processed, which can be more expensive for high-volume users compared to fixed compute-hour pricing.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Knowledge_distillation">Knowledge distillation - Wikipedia</a></li>
<li><a href="https://openai.com/index/api-model-distillation/">Model Distillation in the API - OpenAI</a></li>

</ul>
</details>

**Tags**: `#AI`, `#model distillation`, `#pricing`, `#Amazon`, `#Anthropic`

---

<a id="item-26"></a>
## [Meta bans engineers from using rival AI coding tools](https://the-decoder.com/meta-restricts-use-of-claude-code-and-codex-to-keep-rival-ai-out-of-its-training-data/) ⭐️ 7.0/10

Meta has restricted its engineers from using Anthropic's Claude Code and OpenAI's Codex to prevent the outputs of these rival AI tools from being incorporated into Meta's own training data. This policy highlights the growing competitive tensions among major AI companies, where protecting proprietary training data is becoming a strategic priority. It could influence how other tech giants manage internal use of external AI tools. The restriction applies to Claude Code, an AI coding agent from Anthropic, and Codex, a suite of AI-driven coding agents from OpenAI. Meta's move aims to keep rival AI outputs out of its training pipeline, though the exact enforcement mechanisms are not detailed.

rss · The Decoder — AI新闻 · Jun 29, 15:47

**Background**: Large language models like those powering Claude and Codex are trained on vast amounts of text and code. If Meta engineers used these tools to generate code or text, that output could later be used to train Meta's own models, potentially introducing biases or dependencies on rival technology. By banning such use, Meta seeks to maintain the purity and independence of its training data.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Code">Claude Code</a></li>
<li><a href="https://openai.com/codex/">Codex | AI Coding Partner from OpenAI</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Meta`, `#training data`, `#competition`, `#policy`

---

<a id="item-27"></a>
## [Anthropic and Newsom Deal: California Gets Claude at Half Price](https://techcrunch.com/2026/06/29/anthropic-and-gov-newsom-forge-deal-allowing-california-government-to-use-claude-at-half-price/) ⭐️ 7.0/10

Anthropic has struck a deal with California Governor Gavin Newsom to offer its AI model Claude to the state government at half the standard price. This deal strengthens Anthropic's ties with California while the company faces opposition from the federal government, potentially setting a precedent for state-level AI procurement. The agreement allows California government agencies to use Claude at a 50% discount, though specific terms and duration of the deal have not been disclosed.

rss · TechCrunch — 科技创投 · Jun 29, 18:10

**Background**: Anthropic is an AI company founded by former OpenAI employees, known for its Claude model focused on safety and reliability. California is a major tech hub and has been active in AI regulation, while the federal government has taken a more adversarial stance toward some AI companies.

**Tags**: `#AI`, `#Anthropic`, `#government`, `#policy`, `#business`

---

<a id="item-28"></a>
## [Quera Claims Leapfrog with Error-Corrected Qubits by 2029](https://arstechnica.com/science/2026/06/quera-promises-thousands-of-error-corrected-qubits-by-2029/) ⭐️ 7.0/10

Quantum computing startup Quera announced plans to achieve thousands of error-corrected qubits by 2029, claiming it will leapfrog competitors. However, the claim requires a massive leap from its existing hardware. If successful, this would mark a major milestone in quantum computing, enabling practical error-corrected computations. It could shift the competitive landscape among quantum computing firms. Quera's neutral-atom quantum computers currently have limited qubit counts and no error correction. Achieving thousands of error-corrected qubits by 2029 would require significant advances in hardware and error correction techniques.

rss · ArsTechnica — 深度科技 · Jun 29, 17:59

**Background**: Quantum error correction uses multiple physical qubits to create one logical qubit that is resilient to errors. Neutral-atom quantum computers, like those from Quera, use lasers to trap and manipulate individual atoms as qubits. Current quantum computers are noisy and error-prone, limiting their practical use.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/QuEra_Computing_Inc.">QuEra Computing Inc. - Wikipedia</a></li>
<li><a href="https://www.quera.com/">Quantum Computing with Neutral Atoms | QuEra</a></li>
<li><a href="https://en.wikipedia.org/wiki/Quantum_error_correction">Quantum error correction - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#quantum computing`, `#startup`, `#error correction`, `#hardware`

---

<a id="item-29"></a>
## [NASA's X-59 Tests Supersonic Flight Without Sonic Boom](https://arstechnica.com/gadgets/2026/06/nasas-x-59-frankenjet-tests-supersonic-flight-without-the-sonic-boom/) ⭐️ 7.0/10

NASA's X-59 QueSST experimental aircraft has begun test flights demonstrating supersonic flight that produces a quiet 'thump' instead of a loud sonic boom. If successful, this technology could overturn the ban on supersonic flight over land, enabling faster commercial air travel and reducing flight times significantly. The X-59 uses a long, needle-like nose and carefully shaped fuselage to prevent shock waves from coalescing into a sonic boom. The aircraft is a joint project between NASA and Lockheed Martin under the Low-Boom Flight Demonstrator program.

rss · ArsTechnica — 深度科技 · Jun 29, 10:30

**Background**: When an aircraft exceeds the speed of sound, it creates shock waves that merge into a loud sonic boom, which can disturb people and damage property. This has led to regulations banning supersonic flight over land. NASA's X-59 QueSST (Quiet SuperSonic Technology) aims to demonstrate that supersonic aircraft can be designed to produce a much quieter sound, potentially paving the way for new regulations.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Lockheed_Martin_X-59_Quesst">Lockheed Martin X - 59 Quesst - Wikipedia</a></li>
<li><a href="https://www.space.com/nasa-x-59-quesst-supersonic-jet-unveiled">NASA unveils its revolutionary X - 59 Quesst ' quiet ' supersonic jet...</a></li>
<li><a href="https://simpleflying.com/what-we-know-supersonic-x-59-quesst/">What We Know About The Mysterious Supersonic Lockheed Martin...</a></li>

</ul>
</details>

**Tags**: `#aerospace`, `#supersonic`, `#NASA`, `#engineering`

---

<a id="item-30"></a>
## [Porting Principia Game Engine to Windows XP](https://voxelmanip.se/2026/06/28/building-principia-for-windows-xp/) ⭐️ 6.0/10

A developer documented the process of building the open-source Principia game engine to run on Windows XP, overcoming challenges like missing APIs and compiler compatibility. This effort extends the life of a popular physics sandbox game for a legacy OS still used by enthusiasts, and provides a reference for others interested in retrocomputing and software preservation. The port required patching dependencies to avoid Windows 7-era APIs, and the build uses MSVC 14.27 redistributable with UCRT for compatibility. The result is experimental, with some dialogs not yet implemented.

hackernews · LorenDB · Jun 29, 13:23 · [Discussion](https://news.ycombinator.com/item?id=48718995)

**Background**: Principia is a free, open-source physics-based sandbox game originally released in 2013, inspired by the Android game Apparatus. It was open-sourced in August 2022 and runs on Windows, Linux, and Android. Windows XP, released in 2001, ended mainstream support in 2009 but retains a niche community of users.

<details><summary>References</summary>
<ul>
<li><a href="https://rollerozxa.itch.io/principia">Principia by ROllerozxa - Itch.io</a></li>
<li><a href="https://principia-web.se/">Principia - Physics-based sandbox game</a></li>
<li><a href="https://github.com/Bithack/principia">GitHub - Bithack/principia: Open source physics-based sandbox ... Download Principia - Principia Principia - GitHub principia/principia: Open source physics-based sandbox game ... Principia - Libregamewiki</a></li>

</ul>
</details>

**Discussion**: Commenters expressed admiration for the effort, noting the thriving XP community and tools like Legacy Update for post-install issues. Some shared their own experiences porting software to XP, while others noted the experimental nature of the port and missing features.

**Tags**: `#Windows XP`, `#retrocomputing`, `#game engine`, `#porting`, `#legacy software`

---

<a id="item-31"></a>
## [EU seeks AI independence as Austria proposes luring Anthropic](https://the-decoder.com/eu-seeks-ai-independence-as-austria-proposes-luring-anthropic-to-europe/) ⭐️ 6.0/10

Austria's State Secretary for Digitalization, Alexander Pröll, has called on the European Commission to explore bringing Anthropic to Europe in response to the U.S. ban on advanced AI models from OpenAI and Anthropic for foreign users. This proposal highlights the EU's desire to reduce AI dependency on the US and China, but faces significant practical hurdles such as Anthropic's US-based operations and the complexity of relocating an AI company. The U.S. government ordered Anthropic to restrict foreign access to its most advanced AI models, citing national security concerns. The alternative of adopting Chinese AI models would merely replace one dependency with another.

rss · The Decoder — AI新闻 · Jun 29, 17:58

**Background**: Anthropic is an American AI safety and research company based in San Francisco, known for its Claude large language models. The EU has been seeking strategic autonomy in AI, but currently lacks major homegrown AI companies comparable to US or Chinese firms.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Anthropic">Anthropic - Wikipedia</a></li>
<li><a href="https://www.theguardian.com/technology/2026/jun/13/anthropic-disable-advanced-ai-models-us-government-order">Anthropic to disable its most advanced AI models after US ...</a></li>
<li><a href="https://www.bloomberg.com/news/articles/2026-06-15/anthropic-block-marks-us-reversal-warning-to-silicon-valley">Anthropic Faces US Ban on Foreign Use of Advanced AI After ...</a></li>

</ul>
</details>

**Tags**: `#AI policy`, `#European Union`, `#Anthropic`, `#geopolitics`

---

<a id="item-32"></a>
## [Waymo and Uber End Phoenix Partnership](https://techcrunch.com/2026/06/29/waymo-and-uber-quietly-part-ways-in-phoenix/) ⭐️ 6.0/10

Waymo and Uber have quietly ended their three-year partnership in Phoenix, as confirmed by TechCrunch. This dissolution signals a shift in autonomous vehicle industry alliances, potentially affecting future ride-hailing and self-driving integration strategies. The partnership, which began nearly three years ago, allowed Uber users to hail Waymo self-driving taxis in Phoenix. The companies did not disclose the reason for the split.

rss · TechCrunch — 科技创投 · Jun 29, 18:45

**Background**: Waymo is a leading autonomous driving technology company, while Uber operates a major ride-hailing platform. Their partnership was seen as a way to combine Waymo's self-driving tech with Uber's vast user base. The end of this collaboration may lead to new competitive dynamics in the AV space.

**Tags**: `#autonomous vehicles`, `#Waymo`, `#Uber`, `#partnership`, `#Phoenix`

---

<a id="item-33"></a>
## [Cursor launches mobile app for remote coding agent oversight](https://techcrunch.com/2026/06/29/cursor-now-has-a-mobile-app-for-guiding-your-coding-agent-on-the-go/) ⭐️ 6.0/10

Cursor has released a mobile app that allows developers to remotely oversee and guide their coding agents from a smartphone. This enables developers to monitor and intervene in AI-assisted coding tasks while away from their desktop, increasing flexibility and productivity. The app is designed for remote oversight, not full coding, and likely integrates with Cursor's existing agent-based development environment.

rss · TechCrunch — 科技创投 · Jun 29, 17:03

**Background**: Cursor is an AI-powered coding agent that assists developers by writing, reviewing, and debugging code. It has gained rapid adoption, with over half of the Fortune 500 using it. The mobile app extends its accessibility beyond the desktop.

<details><summary>References</summary>
<ul>
<li><a href="https://cursor.com/">Cursor : AI coding agent</a></li>

</ul>
</details>

**Tags**: `#Cursor`, `#mobile app`, `#coding agent`, `#AI-assisted development`

---

<a id="item-34"></a>
## [Trump admin red tape threatens 92 GW of new solar and wind](https://techcrunch.com/2026/06/29/trump-administration-threatens-92-gw-of-new-electricity-supply-with-red-tape/) ⭐️ 6.0/10

The Trump administration's regulatory policies threaten to block 92 GW of new solar and wind capacity, representing $121 billion in investment. This could significantly slow U.S. renewable energy growth, impacting climate goals and energy transition efforts. The 92 GW figure represents the majority of new electricity capacity planned in the U.S., with solar and wind being the largest contributors.

rss · TechCrunch — 科技创投 · Jun 29, 16:58

**Background**: Solar and wind power have become the cheapest sources of new electricity in many regions. The Trump administration has implemented policies that add regulatory hurdles, such as permitting delays and tariff threats, which could stall projects.

**Tags**: `#energy policy`, `#renewable energy`, `#solar`, `#wind`, `#regulation`

---

<a id="item-35"></a>
## [Google Warns EU Plans to Weaken Its Monopoly Could Expose User Data](https://arstechnica.com/gadgets/2026/06/google-warns-eus-plans-to-weaken-its-monopoly-could-expose-user-data/) ⭐️ 6.0/10

Google has warned that EU proposals under the Digital Markets Act to force it to share search data with competitors and open up AI on Android could compromise user privacy. This debate could reshape how search and AI markets operate in the EU, potentially affecting competition, innovation, and privacy protections for millions of users. The EU wants Google to share anonymized search data (rankings, queries, clicks) with rivals on FRAND terms, and to allow third-party AI services deeper integration into Android.

rss · ArsTechnica — 深度科技 · Jun 29, 18:21

**Background**: The Digital Markets Act (DMA) is an EU law aimed at making digital markets fairer and more contestable. It has already forced Apple to open iOS to third-party app stores and required Meta to offer ad-free options. Now it targets Google's search data and Android AI integration as potential bottlenecks.

<details><summary>References</summary>
<ul>
<li><a href="https://www.xari.ai/post/could-you-soon-use-dma-search-data-to-outrank-competitors-in-the-eu">Could You Soon Use DMA Search Data to Outrank Competitors in the...</a></li>
<li><a href="https://head-post.com/brussels-goes-all-in-eu-to-force-google-to-share-search-data-with-ai-rivals/">Brussels goes all in: EU to force Google to share search data with AI...</a></li>
<li><a href="https://en.cryptonomist.ch/2026/04/28/android-ai-openness-eu/">EU pressures Google to open Android AI under DMA rules</a></li>

</ul>
</details>

**Tags**: `#privacy`, `#regulation`, `#Google`, `#EU`, `#monopoly`

---

