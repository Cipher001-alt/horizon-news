# Horizon Daily - 2026-07-28

> From 75 items, 38 important content pieces were selected

---

1. [Anthropic's Claude Discovers Novel Cryptographic Weaknesses](#item-1) ⭐️ 9.0/10
2. [Moonshot AI Releases 2.8 Trillion Parameter Kimi K3 Model](#item-2) ⭐️ 9.0/10
3. [uv 0.12.0 released with breaking changes for correctness](#item-3) ⭐️ 8.0/10
4. [Zig's Incremental Compilation Internals](#item-4) ⭐️ 8.0/10
5. [XY: GPU-Accelerated Plotting Library for Billions of Data Points](#item-5) ⭐️ 8.0/10
6. [Novel HIV vaccine shows 44% efficacy in macaques](#item-6) ⭐️ 8.0/10
7. [Kimi Linear: A Hybrid Attention Architecture Outperforming Full Attention](#item-7) ⭐️ 8.0/10
8. [7.1 Earthquake in Japan Damages Infrastructure, Evacuates Tech Plants](#item-8) ⭐️ 8.0/10
9. [Nvidia invests in Ilya Sutskever's AI lab, shifting SSI away from Google chips](#item-9) ⭐️ 8.0/10
10. [NASA's robot to lift orbital telescope tumbles out of control](#item-10) ⭐️ 8.0/10
11. [Waymo and Robotaxi Operators Face New Federal Safety Bill](#item-11) ⭐️ 8.0/10
12. [Data centers may face temporary power cuts on largest US grid](#item-12) ⭐️ 8.0/10
13. [Recursive Superintelligence signs $410M compute deal with Amazon](#item-13) ⭐️ 8.0/10
14. [Missing Underscore Sends Innocent Man to Prison for 18 Months](#item-14) ⭐️ 8.0/10
15. [Court Ruling Limits DMCA Use Against Web Scraping](#item-15) ⭐️ 8.0/10
16. [eBay and Execs Settle Cyberstalking Case for $55.7 Million](#item-16) ⭐️ 8.0/10
17. [llama.cpp b10171 Fixes Adreno GPU Multi-Stream Bug](#item-17) ⭐️ 7.0/10
18. [Deflock Casa Grande Exposes Flock Camera Expansion](#item-18) ⭐️ 7.0/10
19. [DeltaNet Linear Attention Variants Explained](#item-19) ⭐️ 7.0/10
20. [How to Profile eBPF Code: Tools & Techniques](#item-20) ⭐️ 7.0/10
21. [DMARC enforcement remains low despite being a decade-old standard](#item-21) ⭐️ 7.0/10
22. [EU Initiative Opposes Mandatory Digital ID and Age Verification](#item-22) ⭐️ 7.0/10
23. [Una GPS Smartwatch: Repairable, USB-C, Developer-Friendly](#item-23) ⭐️ 7.0/10
24. [Google's Beyond Zero: Real-Time Security for AI Agents](#item-24) ⭐️ 7.0/10
25. [Amazon scales back Nova AI models, bets on new frontier research](#item-25) ⭐️ 7.0/10
26. [Taiwan detains Nvidia employee in chip smuggling probe](#item-26) ⭐️ 7.0/10
27. [Lyft and Baidu Begin Robotaxi Testing in London](#item-27) ⭐️ 7.0/10
28. [Anthropic CEO clarifies stance on open-weight models, warns of Chinese AI](#item-28) ⭐️ 7.0/10
29. [Nadella warns against relying on a single AI model](#item-29) ⭐️ 7.0/10
30. [Substack writers urged to own their content with personal websites](#item-30) ⭐️ 6.0/10
31. [SBCL 2.6.7 Adds SIMD Support for ARM64 and AVX512](#item-31) ⭐️ 6.0/10
32. [Slow Journalism Magazine Prides Itself on Being Last to Breaking News](#item-32) ⭐️ 6.0/10
33. [Harmony Explained: A Mathematical Theory of Music](#item-33) ⭐️ 6.0/10
34. [Now Is the Time to Give LLMs Access to the ACM Digital Library](#item-34) ⭐️ 6.0/10
35. [Apple Releases Security Update for macOS Tahoe 26.6](#item-35) ⭐️ 6.0/10
36. [Ethan Mollick's AI Guide Shifts to Agentic Systems](#item-36) ⭐️ 6.0/10
37. [Fish Audio raises $52M seed for AI voice models](#item-37) ⭐️ 6.0/10
38. [Thea Energy wins $20M ARPA-E grant for fusion magnets](#item-38) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Anthropic's Claude Discovers Novel Cryptographic Weaknesses](https://www.anthropic.com/research/discovering-cryptographic-weaknesses) ⭐️ 9.0/10

Anthropic researchers used their LLM, Claude, to autonomously discover novel cryptographic attacks, including a new attack on AES and an improved attack on the post-quantum signature scheme HAWK, at a cost of roughly $100,000 per result. This demonstrates that LLMs can autonomously discover novel cryptographic weaknesses, raising important questions about AI safety, national security, and the future of cryptography research. The AES attack was discovered fully autonomously by Claude using a multi-agent scaffold, while the HAWK attack was developed in collaboration with a human researcher. Each result cost roughly $100,000 in API costs.

hackernews · gslin · Jul 28, 17:22 · [Discussion](https://news.ycombinator.com/item?id=49087091)

**Background**: Cryptographic algorithms like AES and HAWK are used to secure online data. Discovering weaknesses in these algorithms typically requires deep expertise and significant manual effort. This research shows that LLMs can now contribute to such discoveries, potentially accelerating the pace of cryptographic analysis.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/research/discovering-cryptographic-weaknesses">Discovering cryptographic weaknesses with Claude \ Anthropic</a></li>
<li><a href="https://www.kucoin.com/news/flash/anthropic-s-ai-identifies-security-weaknesses-in-encryption-methods">Anthropic’s AI Identifies Security Weaknesses in Encryption Methods | KuCoin</a></li>

</ul>
</details>

**Discussion**: Commenters noted the impressive scale of token usage ($100k in a week) and the interesting multi-agent dynamics where one worker prematurely rejected an idea but another exploited it. Some expressed concern about national security implications and the need for responsible disclosure.

**Tags**: `#AI safety`, `#cryptography`, `#LLM capabilities`, `#Anthropic`, `#security research`

---

<a id="item-2"></a>
## [Moonshot AI Releases 2.8 Trillion Parameter Kimi K3 Model](https://simonwillison.net/2026/Jul/27/kimi-k3/#atom-everything) ⭐️ 9.0/10

Moonshot AI has released the open weights of their 2.8 trillion parameter Kimi K3 model on Hugging Face, a 1.56TB download. The model uses a modified license that requires large commercial entities to enter a separate agreement with Moonshot. This release is a major milestone in AI, as it makes a state-of-the-art 2.8 trillion parameter model freely available for research and development. The modified license, while not fully open source, still enables broad access and could accelerate innovation in the field. The Kimi K3 model features 2.8 trillion parameters, a 1M-token context window, and native visual understanding. It is built on Kimi Delta Attention (KDA), a hybrid linear attention mechanism, and Attention Residuals.

rss · Simon Willison — AI工具 · Jul 27, 23:39

**Background**: Kimi K3 is the latest flagship model from Moonshot AI, a Beijing-based AI company founded in 2023. The company previously released the open-weight Kimi K2 model in July 2025. Open-weight models allow anyone to download and use the trained parameters, but may have usage restrictions, unlike fully open-source models.

<details><summary>References</summary>
<ul>
<li><a href="https://platform.kimi.ai/docs/guide/kimi-k3-quickstart">Kimi K3 - Kimi API Platform</a></li>
<li><a href="https://openrouter.ai/moonshotai/kimi-k3">Kimi K3 - API Pricing & Benchmarks | OpenRouter</a></li>

</ul>
</details>

**Discussion**: One commenter praised the model's architectural choices like KDA and NoPE, noting they translate into strong real-world performance. The overall sentiment appears positive, highlighting impressive engineering.

**Tags**: `#AI`, `#open-source`, `#large language model`, `#Moonshot`, `#Kimi K3`

---

<a id="item-3"></a>
## [uv 0.12.0 released with breaking changes for correctness](https://github.com/astral-sh/uv/releases/tag/0.12.0) ⭐️ 8.0/10

uv 0.12.0 introduces breaking changes focused on correctness and specification compatibility, including default build system definition for uv init, rejection of unsupported archive formats, and rejection of wheel files that could replace the Python interpreter. This release improves uv's adherence to Python packaging standards and security, affecting all users of this widely-used package manager. Most users can upgrade without changes, but those relying on legacy archive formats or certain wheel entry points may need to adjust. The breaking changes include: uv init now creates a packaged project with uv_build build system by default; unsupported source distribution formats like .tar.bz2 and .tar.xz are rejected; wheel files with case-variant entry points named 'python' are rejected on case-insensitive filesystems.

github · astral-automations-bot[bot] · Jul 28, 18:58

**Background**: uv is a fast Python package and project manager developed by Astral. It aims to replace pip, pip-tools, and virtualenv with a single tool. The uv_build backend is a zero-config build system tightly integrated with uv, designed for pure Python projects.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.astral.sh/uv/concepts/build-backend/">Build backend | uv</a></li>
<li><a href="https://medium.com/@dynamicy/python-build-backends-in-2025-what-to-use-and-why-uv-build-vs-hatchling-vs-poetry-core-94dd6b92248f">Python Build Backends in 2025: What to Use and Why (uv_build vs Hatchling vs poetry-core) | by Chris Evans | Medium</a></li>

</ul>
</details>

**Tags**: `#python`, `#package-manager`, `#release`, `#uv`

---

<a id="item-4"></a>
## [Zig's Incremental Compilation Internals](https://mlugg.co.uk/posts/incremental-compilation-internals/) ⭐️ 8.0/10

A detailed technical article by mlugg explains the design and implementation of incremental compilation in the Zig compiler, covering semantic analysis, caching, and dependency tracking. This work significantly improves Zig's compilation speed, making the developer experience faster and more responsive, which is crucial for a systems programming language competing in a space where compile times matter. The incremental compilation currently works only for debug builds and non-binary emitting steps (e.g., zig build check), and may still have bugs or false positives/negatives.

hackernews · garyhtou · Jul 28, 15:46 · [Discussion](https://news.ycombinator.com/item?id=49085666)

**Background**: Incremental compilation reuses previously compiled results when source files change, avoiding full recompilation. Zig is a systems programming language focused on simplicity and performance, and its self-hosted compiler has been under active development.

<details><summary>References</summary>
<ul>
<li><a href="https://ziggit.dev/t/how-zig-incremental-compilation-is-implemented-internally/3543">How Zig incremental compilation is implemented internally? - Explain - Ziggit</a></li>
<li><a href="https://deepwiki.com/ziglang/zig/3.3-incremental-compilation">Incremental Compilation | ziglang/zig | DeepWiki</a></li>
<li><a href="https://www.reddit.com/r/Zig/comments/1ev8mvs/incremental_compilation_merged/">r/Zig on Reddit: Incremental compilation merged</a></li>

</ul>
</details>

**Discussion**: Steve Klabnik praised Zig's toolchain work but noted he won't use Zig due to memory safety concerns. Other commenters asked about C compilation support and release build applicability, while one expressed disappointment at the industry's slow adoption of fast compilation.

**Tags**: `#Zig`, `#compiler`, `#incremental compilation`, `#toolchain`, `#systems programming`

---

<a id="item-5"></a>
## [XY: GPU-Accelerated Plotting Library for Billions of Data Points](https://github.com/reflex-dev/xy) ⭐️ 8.0/10

XY is a new open-source Python library that provides fast, composable, GPU-accelerated interactive plotting, capable of rendering billions of data points with sub-second pan and zoom, including out-of-core rendering of the entire OpenStreetMap dataset. This library addresses a critical gap in Python data visualization by enabling interactive exploration of massive datasets that traditional libraries like Matplotlib cannot handle, potentially becoming a standard tool for data scientists and researchers working with large-scale data. XY leverages GPU acceleration and out-of-core rendering to handle datasets exceeding GPU memory, as demonstrated by rendering 10.7 billion OpenStreetMap nodes. It is built on top of the Reflex framework and is available on GitHub under an open-source license.

hackernews · apetuskey · Jul 28, 15:54 · [Discussion](https://news.ycombinator.com/item?id=49085798)

**Background**: Traditional Python plotting libraries like Matplotlib and Plotly struggle with large datasets due to CPU-bound rendering and memory limitations. GPU-accelerated libraries offload rendering to the graphics card, enabling faster and smoother interactions. Out-of-core rendering allows processing data that does not fit into GPU memory by streaming it in chunks.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/fastplotlib/fastplotlib">GitHub - fastplotlib/fastplotlib: Next-gen fast plotting library running on WGPU using the pygfx rendering engine · GitHub</a></li>
<li><a href="https://github.com/epezent/implot">GitHub - epezent/implot: Immediate Mode Plotting · GitHub</a></li>
<li><a href="https://github.com/KoalaPlot/koalaplot-core">GitHub - KoalaPlot/koalaplot-core: Koala Plot is a Compose Multiplatform based charting and plotting library written in Kotlin · GitHub</a></li>

</ul>
</details>

**Discussion**: Community reactions are mixed: some question the necessity of GPU acceleration for typical dashboard use cases, while others praise XY's potential for massive datasets like OpenStreetMap. There is also curiosity about how it compares to existing libraries like EvilCharts and excitement from academia for a modern alternative to Matplotlib.

**Tags**: `#data visualization`, `#GPU acceleration`, `#Python`, `#open source`, `#plotting`

---

<a id="item-6"></a>
## [Novel HIV vaccine shows 44% efficacy in macaques](https://www.lji.org/news-events/news/post/new-hiv-vaccine-shows-unprecedented-success-in-preclinical-study/) ⭐️ 8.0/10

A novel HIV vaccine series that trains the immune system in stages achieved 44% efficacy in rhesus macaques, with phase I clinical trials already underway in humans. This innovative 'immune system curriculum' approach could overcome decades of challenges in HIV vaccine development, potentially leading to a preventive vaccine that complements existing PrEP therapies. The vaccine consists of a series of shots, each slightly different and targeting different stages of B-cell development, as highlighted by community discussion. The preclinical study was published in Nature, and independent coverage is available from C&EN.

hackernews · codebyaditya · Jul 28, 13:12 · [Discussion](https://news.ycombinator.com/item?id=49083314)

**Background**: HIV vaccine development has been notoriously difficult due to the virus's rapid mutation and ability to evade the immune system. Rhesus macaques are the preferred non-human primate model for HIV/AIDS research because SIV infection in macaques closely mimics HIV infection in humans. Previous vaccine candidates have failed in clinical trials, making any positive signal significant.

<details><summary>References</summary>
<ul>
<li><a href="https://pubmed.ncbi.nlm.nih.gov/40501981/">The genomic legacy of selectively breeding rhesus macaques for HIV/AIDS-related research - PubMed</a></li>

</ul>
</details>

**Discussion**: Commenters expressed cautious optimism, noting that phase I trials are where most HIV vaccines fail. Some pointed out that HIV transmission is already preventable with PrEP, questioning the urgency of a vaccine. Others appreciated the novel 'curriculum' approach and provided links to the original paper and independent analysis.

**Tags**: `#HIV vaccine`, `#preclinical study`, `#immunology`, `#biomedical research`

---

<a id="item-7"></a>
## [Kimi Linear: A Hybrid Attention Architecture Outperforming Full Attention](https://arxiv.org/abs/2510.26692) ⭐️ 8.0/10

Moonshot AI introduced Kimi Linear, a hybrid linear attention architecture that outperforms full attention under fair comparisons across short-context, long-context, and reinforcement learning scaling scenarios. The architecture uses a 3:1 interleave of Kimi Delta Attention (KDA) layers and Multi-Head Latent Attention (MLA) layers, and the team open-sourced the KDA kernel, vLLM implementations, and model checkpoints. This work demonstrates that linear attention can surpass full attention in both efficiency and expressiveness, potentially reducing the computational cost of large language models while maintaining or improving quality. The open-source release enables broader community adoption and further research, and the architecture has already been scaled up in the Kimi K3 model with 2.8 trillion parameters. Kimi Linear uses a 3:1 interleave of KDA layers and NoPE full attention layers (specifically MLA), achieving the best tradeoff between cost and expressivity. The architecture is designed to meet the efficiency demands of agentic AI and supports straightforward context window extension.

hackernews · ronfriedhaber · Jul 28, 10:52 · [Discussion](https://news.ycombinator.com/item?id=49082022)

**Background**: Attention mechanisms are a core component of transformer models, but standard full attention has quadratic complexity with sequence length, making it expensive for long contexts. Linear attention aims to reduce this complexity to linear, but prior linear attention models often underperformed full attention in quality. Kimi Linear is a hybrid approach that combines the efficiency of linear attention with the expressiveness of full attention, achieving state-of-the-art results.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2510.26692">[2510.26692] Kimi Linear: An Expressive, Efficient Attention Architecture</a></li>
<li><a href="https://arxiv.org/pdf/2510.26692">KIMI LINEAR: AN EXPRESSIVE, EFFICIENT ATTENTION ARCHITECTURE</a></li>
<li><a href="https://vizuara.substack.com/p/kimi-linear-an-expressive-efficient">Kimi-Linear : An Expressive, Efficient Attention Architecture</a></li>

</ul>
</details>

**Discussion**: The community reacted positively, with users praising the open-source release and noting that the architecture was scaled up in the Kimi K3 paper. Some users compared it to related work like Gated Deltanet 2, suggesting that Kimi Linear is an evolution in expressiveness.

**Tags**: `#attention`, `#LLM`, `#open-source`, `#architecture`, `#research`

---

<a id="item-8"></a>
## [7.1 Earthquake in Japan Damages Infrastructure, Evacuates Tech Plants](https://www.data.jma.go.jp/multi/quake/quake_detail.html?eventID=20260728163528&lang=en) ⭐️ 8.0/10

A 7.1 magnitude earthquake struck near Kumamoto, Japan, causing at least 50 injuries, 9 missing, collapsed buildings, fires, and evacuations at TSMC, Sony, and Fujifilm facilities. This earthquake disrupts critical semiconductor and imaging sensor supply chains, as TSMC, Sony, and Fujifilm plants are key global suppliers. The damage also highlights Japan's vulnerability to natural disasters despite advanced preparedness. The epicenter was at 32.6N 130.7E, about 20 km south of a previous major earthquake. Ground displacement reached 84 cm, and a shopping mall exploded after evacuation. The Japanese shindo scale registered 7 in parts of Kumamoto, indicating extreme shaking.

hackernews · krembo · Jul 28, 07:44 · [Discussion](https://news.ycombinator.com/item?id=49080664)

**Background**: Japan is located on the Pacific Ring of Fire and experiences frequent earthquakes. The Japanese shindo scale measures seismic intensity at specific locations, with 7 being the highest level. Kumamoto was still recovering from a major earthquake in 2016.

**Discussion**: Commenters reported personal experiences, noting the NERV disaster information service on Twitter provided rapid updates. Some expressed concern about Kumamoto's incomplete recovery from the 2016 quake and ongoing depopulation. The high community engagement (738 points, 193 comments) reflects strong interest in disaster response and infrastructure resilience.

**Tags**: `#earthquake`, `#Japan`, `#disaster`, `#semiconductor`, `#infrastructure`

---

<a id="item-9"></a>
## [Nvidia invests in Ilya Sutskever's AI lab, shifting SSI away from Google chips](https://the-decoder.com/nvidia-invests-in-ilya-sutskevers-ai-lab-shifting-ssi-away-from-google-chips/) ⭐️ 8.0/10

Nvidia has made a substantial investment in Safe Superintelligence (SSI), the AI lab founded by former OpenAI chief scientist Ilya Sutskever, and the lab is shifting its hardware reliance from Google chips to Nvidia's Vera Rubin supercomputing platform. This investment signals a major strategic realignment in the AI hardware landscape, as a high-profile safety-focused lab moves away from Google's TPUs to Nvidia's ecosystem, potentially influencing other AI labs' hardware choices and intensifying competition between Nvidia and Google in AI chips. The investment is reported to be around $5 billion and includes access to Nvidia's Vera Rubin supercomputing infrastructure. SSI, valued at over $30 billion within a year of its founding, focuses exclusively on building safe superintelligence.

rss · The Decoder — AI新闻 · Jul 28, 13:06

**Background**: Safe Superintelligence Inc. (SSI) was co-founded by Ilya Sutskever, Daniel Gross, and Daniel Levy in June 2024, with the singular goal of developing safe superintelligence. Sutskever, a renowned AI researcher and co-creator of AlexNet, previously served as chief scientist at OpenAI and was instrumental in developing GPT models and reasoning models like o1. Nvidia is the dominant supplier of AI training chips, while Google offers its own Tensor Processing Units (TPUs) as an alternative.

<details><summary>References</summary>
<ul>
<li><a href="https://ssi.inc/">Safe Superintelligence Inc.</a></li>
<li><a href="https://www.techtimes.com/articles/321744/20260727/nvidia-backs-sutskevers-ai-safety-lab-5b-vera-rubin-supercompute.htm">NVIDIA Backs Sutskever's AI Safety Lab With $5B and Vera Rubin...</a></li>
<li><a href="https://techcrunch.com/2026/07/27/ilya-sutskevers-safe-superintelligence-partners-with-nvidia-to-scale-its-ai-research/">Ilya Sutskever’s Safe Superintelligence partners with... | TechCrunch</a></li>

</ul>
</details>

**Tags**: `#Nvidia`, `#Ilya Sutskever`, `#AI lab`, `#investment`, `#hardware`

---

<a id="item-10"></a>
## [NASA's robot to lift orbital telescope tumbles out of control](https://techcrunch.com/2026/07/28/the-robot-nasa-hired-to-lift-a-orbital-telescope-is-tumbling-out-of-control/) ⭐️ 8.0/10

NASA's robotic spacecraft, built by Katalyst Space to grab and lift an orbital telescope to a higher orbit, is now tumbling out of control due to failures in two of its three reaction wheels and one of its thruster systems. This failure jeopardizes the first mission where NASA hired a private company to extend the life of an aging telescope, potentially impacting future orbital servicing and debris mitigation efforts. The spacecraft's reaction wheels, which use electric motors to spin flywheels for precise attitude control, have failed on two of three units, and a thruster system also has problems, leaving the robot unable to stabilize itself.

rss · TechCrunch — 科技创投 · Jul 28, 19:07

**Background**: Reaction wheels are flywheels driven by electric motors that provide precise attitude control without expelling propellant. They are commonly used on spacecraft for fine pointing. The Katalyst Space robot was launched to grab onto a space telescope and slowly raise its orbit, a novel commercial servicing mission.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/07/28/the-robot-nasa-hired-to-lift-a-orbital-telescope-is-tumbling-out-of-control/">The robot NASA hired to lift a orbital telescope is tumbling out of control | TechCrunch</a></li>
<li><a href="https://en.wikipedia.org/wiki/Reaction_wheel">Reaction wheel - Wikipedia</a></li>
<li><a href="https://www.bbc.com/news/articles/c0ry4xx7rk8o">Nasa launches robot to save Swift telescope falling to Earth</a></li>

</ul>
</details>

**Tags**: `#NASA`, `#spacecraft`, `#robotics`, `#telescope`, `#failure`

---

<a id="item-11"></a>
## [Waymo and Robotaxi Operators Face New Federal Safety Bill](https://techcrunch.com/2026/07/28/waymo-robotaxi-operators-face-fresh-scrutiny-over-emergency-response-failures/) ⭐️ 8.0/10

Rep. Kevin Mullin (D-California) has proposed a bill that would direct federal regulators to establish minimum national safety standards for autonomous vehicle operators, increasing scrutiny on companies like Waymo. This bill could impose the first federal safety requirements on robotaxi operators, potentially reshaping the autonomous vehicle industry and addressing concerns about emergency response failures. The bill specifically targets how autonomous vehicles interact with emergency responders, following incidents where robotaxis blocked fire trucks or failed to yield to ambulances.

rss · TechCrunch — 科技创投 · Jul 28, 19:06

**Background**: Autonomous vehicle operators like Waymo have been testing robotaxis in several U.S. cities without federal safety standards, relying on state-level permits. Recent incidents, such as a Waymo car spinning in circles with a passenger trapped inside, have raised safety concerns.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/07/28/waymo-robotaxi-operators-face-fresh-scrutiny-over-emergency-response-failures/">Waymo, robotaxi operators face fresh scrutiny over emergency ...</a></li>
<li><a href="https://sfstandard.com/2026/07/10/waymo-robotaxi-emergency-response/">sfstandard.com/2026/07/10/waymo- robotaxi - emergency - response</a></li>

</ul>
</details>

**Tags**: `#autonomous vehicles`, `#regulation`, `#safety`, `#Waymo`, `#robotaxi`

---

<a id="item-12"></a>
## [Data centers may face temporary power cuts on largest US grid](https://techcrunch.com/2026/07/28/data-centers-may-face-temporary-power-cuts-to-prevent-blackouts-on-largest-us-grid/) ⭐️ 8.0/10

PJM Interconnection, the operator of the largest US power grid, may require data centers to participate in demand response programs that could involve temporary power cuts to prevent blackouts. This marks a significant shift in grid management, as data centers—typically seen as critical infrastructure—may now be treated as flexible loads to maintain grid stability, impacting data center operations and the broader tech industry. The decision comes as rapid data center construction strains energy infrastructure, and PJM has already committed 7.9 GW of demand response capacity. Google has announced 1,000 MW of demand response at its data centers.

rss · TechCrunch — 科技创投 · Jul 28, 15:42

**Background**: PJM Interconnection is a regional transmission organization (RTO) that operates the electric grid for 13 states and Washington, D.C. Demand response programs allow grid operators to reduce electricity consumption during peak times by asking participants to cut usage, helping prevent blackouts.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/PJM_Interconnection">PJM Interconnection - Wikipedia</a></li>
<li><a href="https://techcrunch.com/2026/05/08/the-biggest-u-s-power-grid-is-under-strain-from-ai-and-no-one-is-happy/">The biggest US power grid is under strain from AI — and... | TechCrunch</a></li>
<li><a href="https://www.linkedin.com/pulse/two-wildly-different-data-centers-reveal-fork-road-euy7c">Two Wildly Different Data Centers Reveal a ‘Fork in the Road’ on How...</a></li>

</ul>
</details>

**Tags**: `#data centers`, `#energy`, `#infrastructure`, `#grid reliability`, `#policy`

---

<a id="item-13"></a>
## [Recursive Superintelligence signs $410M compute deal with Amazon](https://techcrunch.com/2026/07/28/recursive-superintelligence-signs-400-compute-deal-with-amazon/) ⭐️ 8.0/10

Recursive Superintelligence has signed a $410 million compute deal with Amazon to fuel its self-improving AI systems. This deal underscores the massive compute requirements for recursive self-improving AI and signals growing investment in automating AI development. Recursive focuses on automating its own product development, redirecting budget from headcount and operations into compute resources.

rss · TechCrunch — 科技创投 · Jul 28, 13:19

**Background**: Recursive self-improving AI refers to systems that can autonomously improve their own capabilities, potentially leading to superintelligence. Such systems require enormous computational power for training and iteration.

<details><summary>References</summary>
<ul>
<li><a href="https://www.recursive.com/">Recursive Superintelligence</a></li>
<li><a href="https://www.weforum.org/organizations/recursive-superintelligence/">Recursive Superintelligence - The World Economic Forum</a></li>

</ul>
</details>

**Tags**: `#AI`, `#compute`, `#superintelligence`, `#Amazon`, `#investment`

---

<a id="item-14"></a>
## [Missing Underscore Sends Innocent Man to Prison for 18 Months](https://arstechnica.com/tech-policy/2026/07/police-missed-one-underscore-and-sent-the-wrong-man-to-prison/) ⭐️ 8.0/10

A missing underscore in a police database caused a data matching failure, leading to the arrest and 18-month imprisonment of an innocent man. The error was discovered only after the man had already served his sentence. This case highlights how seemingly trivial software bugs can have devastating real-world consequences, especially in criminal justice systems that increasingly rely on automated data matching. It underscores the urgent need for rigorous testing, human oversight, and accountability in algorithmic decision-making. The error occurred because a database query failed to match a name due to a missing underscore character, causing police to confuse the innocent man with a wanted suspect. The man was arrested, convicted, and spent 18 months in prison before the mistake was identified.

rss · ArsTechnica — 深度科技 · Jul 27, 20:22

**Background**: Law enforcement databases often rely on exact string matching to identify suspects, but such systems are brittle and can fail due to minor data entry errors or formatting inconsistencies. Underscores, spaces, and other characters are frequently used in names but may be omitted or mishandled, leading to false positives or negatives. This incident is a stark reminder of the limitations of automated systems in high-stakes contexts.

**Tags**: `#software reliability`, `#data integrity`, `#criminal justice`, `#algorithmic bias`, `#tech policy`

---

<a id="item-15"></a>
## [Court Ruling Limits DMCA Use Against Web Scraping](https://arstechnica.com/tech-policy/2026/07/google-wont-give-up-odd-war-against-ai-web-scraping-despite-court-loss/) ⭐️ 8.0/10

A court ruled against Google and Reddit's attempt to use the DMCA to block web scraping, setting a precedent that DMCA Section 1201 cannot be broadly applied to prevent scraping of publicly available data for AI training. This ruling is significant because it clarifies that DMCA anti-circumvention provisions are not a catch-all tool to block web scraping, which could impact AI companies' access to training data and uphold internet openness. The case involved Google and Reddit arguing that scraping their sites violated DMCA Section 1201 by circumventing technological measures, but the court found that the measures were not primarily for copyright protection, limiting DMCA's reach.

rss · ArsTechnica — 深度科技 · Jul 27, 20:12

**Background**: Web scraping involves automated extraction of data from websites, often used to train AI models. The DMCA's Section 1201 prohibits circumvention of technological measures that control access to copyrighted works. Recently, companies have increasingly invoked this section to block scrapers, arguing that scraping bypasses access controls like paywalls or login requirements. This ruling clarifies that such measures must be primarily aimed at copyright protection to trigger DMCA liability.

<details><summary>References</summary>
<ul>
<li><a href="https://nortonlaw.com/2026/05/14/dmca-section-1201-claims-the-new-battleground-for-ai-and-data-scraping-litigation/">DMCA Section 1201 Claims: The New Battleground for AI and Data Scraping Litigation - the NORTON law firm</a></li>
<li><a href="https://www.zwillgen.com/alternative-data/how-artificial-intelligence-shaping-web-scraping-litigation/">How Artificial Intelligence is Shaping Web Scraping Litigation</a></li>
<li><a href="https://www.quinnemanuel.com/the-firm/publications/the-legal-landscape-of-web-scraping/">The Legal Landscape of Web Scraping</a></li>

</ul>
</details>

**Tags**: `#web scraping`, `#DMCA`, `#AI training data`, `#legal precedent`, `#internet policy`

---

<a id="item-16"></a>
## [eBay and Execs Settle Cyberstalking Case for $55.7 Million](https://www.ecommercebytes.com/2026/07/27/ebay-and-execs-settle-cyberstalking-case-for-55-7-million-in-compensation-and-charitable-commitments/) ⭐️ 8.0/10

eBay and several former executives have agreed to a $55.7 million settlement in a civil cyberstalking case brought by David and Ina Steiner, founders of EcommerceBytes, over a 2019 harassment campaign. The settlement includes personal financial contributions from former executives, a public statement from eBay, and no confidentiality clause. This landmark settlement underscores corporate accountability for cyberstalking and harassment, sending a strong message that executives can be held personally liable. It also highlights the power of investigative journalism and the legal system in protecting critics from retaliation. The $55.7 million includes compensation for the Steiners and charitable commitments, with former eBay executives contributing personally. The settlement also requires eBay to issue a public statement acknowledging the misconduct, and there is no confidentiality agreement, allowing the Steiners to discuss the case freely.

rss · EcommerceBytes — 电商新闻 · Jul 28, 01:33

**Background**: In 2019, eBay executives orchestrated a cyberstalking campaign against David and Ina Steiner, who ran the ecommerce news site EcommerceBytes and had occasionally criticized eBay. The campaign included sending threatening messages, a bloody pig mask, and even attempting to break into the Steiners' home. Several former eBay employees pleaded guilty in the criminal case, and eBay paid a $3 million criminal penalty in 2024.

<details><summary>References</summary>
<ul>
<li><a href="https://www.ecommercebytes.com/2026/07/27/ebay-and-execs-settle-cyberstalking-case-for-55-7-million-in-compensation-and-charitable-commitments/">eBay and Execs Settle Cyberstalking Case for $55.7 Million in Compensation and Charitable Commitments - EcommerceBytes</a></li>
<li><a href="https://en.wikipedia.org/wiki/EBay_stalking_scandal">eBay stalking scandal - Wikipedia</a></li>
<li><a href="https://www.justice.gov/usao-ma/pr/ebay-inc-pay-3-million-connection-corporate-cyberstalking-campaign-targeting">District of Massachusetts | eBay Inc. to Pay $3 Million in Connection with Corporate Cyberstalking Campaign Targeting Massachusetts Couple | United States Department of Justice</a></li>

</ul>
</details>

**Tags**: `#cyberstalking`, `#legal settlement`, `#eBay`, `#corporate accountability`, `#cybersecurity`

---

<a id="item-17"></a>
## [llama.cpp b10171 Fixes Adreno GPU Multi-Stream Bug](https://github.com/ggml-org/llama.cpp/releases/tag/b10171) ⭐️ 7.0/10

llama.cpp release b10171 fixes a bug where multi-stream batches on Adreno GPUs produced incorrect results due to the KQ/KQV kernels ignoring tensor dimensions. The fix routes tensors with ne03/ne13 > 1 to the general path and properly handles view offsets. This fix is critical for users running multi-sequence batches on Adreno GPUs, such as those using llama-perplexity with multiple sequences or multi-slot llama-server, as it prevents garbage output and restores correct perplexity values. It improves the reliability of llama.cpp on Qualcomm devices. The bug affected Adreno KQ/KQV image1d kernels that ignored dim 3, causing multi-stream batches to read the first stream's K/V for all streams. Flash attention masked the bug when enabled, but devices like Adreno 740 where FA is declined hit it with default settings. The fix was validated with perplexity improvements from ~1800 to ~15.6 on Adreno 740.

github · github-actions[bot] · Jul 28, 18:53

**Background**: llama.cpp is an open-source project for running large language models (LLMs) efficiently on consumer hardware, supporting various backends including GPU acceleration via OpenCL. Adreno GPUs are Qualcomm's graphics processors used in many mobile and embedded devices. Multi-stream batching allows processing multiple sequences simultaneously, improving throughput, but requires correct handling of 4D tensors where the fourth dimension represents the stream index.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Adreno">Adreno - Wikipedia</a></li>
<li><a href="https://github.com/ggml-org/llama.cpp/discussions/4130">Parallelization / Batching Explanation · ggml-org/llama.cpp · Discussion #4130</a></li>

</ul>
</details>

**Tags**: `#llama.cpp`, `#bug-fix`, `#GPU`, `#LLM`, `#OpenCL`

---

<a id="item-18"></a>
## [Deflock Casa Grande Exposes Flock Camera Expansion](https://deflockcg.com/) ⭐️ 7.0/10

A new website, Deflock Casa Grande, documents the expansion of Flock surveillance cameras in Casa Grande, Arizona, highlighting privacy concerns and the privatization of police surveillance. This matters because it raises awareness about the rapid, often unregulated spread of private surveillance technology in US communities, mirroring broader debates on privacy and civil liberties. Flock cameras are primarily marketed for license plate recognition but can be used for broader surveillance, with a 2021 study finding a 10% error rate in camera output.

hackernews · mooreds · Jul 28, 18:41 · [Discussion](https://news.ycombinator.com/item?id=49088148)

**Background**: Flock Safety is a private company that sells automated license plate recognition cameras to police and communities. These cameras are often deployed without public oversight, raising privacy and civil liberties concerns. The privatization of police surveillance allows private companies to collect and share data with law enforcement, sometimes bypassing traditional checks and balances.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Flock_Safety">Flock Safety - Wikipedia</a></li>
<li><a href="https://www.cnet.com/home/security/when-flock-comes-to-town-why-cities-are-axing-the-controversial-surveillance-technology/">When Flock Comes to Your Town: I Asked Experts What to Do... - CNET</a></li>
<li><a href="https://en.wikipedia.org/wiki/Private_police">Private police - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters expressed concerns about police abuse of surveillance, with one sharing a personal story of an officer greeting her by full name while walking her dog. Another noted the irony of US criticism of Chinese surveillance while adopting similar practices through private contracts. A local YouTuber offered to interview the site creator to broadcast the situation.

**Tags**: `#surveillance`, `#privacy`, `#police technology`, `#Flock cameras`, `#civil liberties`

---

<a id="item-19"></a>
## [DeltaNet Linear Attention Variants Explained](https://blog.doubleword.ai/you-could-have-come-up-with-kimi-delta-attention) ⭐️ 7.0/10

A blog post provides a detailed, accessible walkthrough of the DeltaNet family of linear attention mechanisms, including Gated DeltaNet and Kimi Delta Attention, using bra-ket notation to clarify the underlying algorithms. Linear attention mechanisms like DeltaNet offer a path to more efficient transformers by replacing the quadratic-cost softmax attention with linear-time recurrent updates, which is crucial for scaling to long sequences and reducing memory usage in large language models. The article explains how DeltaNet improves upon standard linear attention by using a delta rule for memory updates, and how Gated DeltaNet decouples erase and write operations. Kimi Delta Attention, used in Kimi Linear, refines this with channel-wise gating.

hackernews · AnhTho_FR · Jul 28, 16:02 · [Discussion](https://news.ycombinator.com/item?id=49085909)

**Background**: Standard softmax attention has quadratic complexity in sequence length, making it expensive for long contexts. Linear attention mechanisms address this by replacing the softmax with a kernel function that allows the attention computation to be reformulated as a recurrent update, reducing complexity to linear. DeltaNet is a specific linear attention variant that uses a delta rule to update a fixed-size memory state, enabling efficient in-context retrieval.

<details><summary>References</summary>
<ul>
<li><a href="https://sustcsonglin.github.io/blog/2024/deltanet-1/">DeltaNet Explained (Part I) | Songlin Yang</a></li>
<li><a href="https://research.nvidia.com/publication/2026-05_gated-deltanet-2-decoupling-erase-and-write-linear-attention">Gated DeltaNet-2: Decoupling Erase and Write in Linear Attention | Research</a></li>
<li><a href="https://github.com/rasbt/LLMs-from-scratch/blob/main/ch04/08_deltanet/README.md">LLMs-from-scratch/ch04/08_deltanet/README.md at main · rasbt/LLMs-from-scratch</a></li>

</ul>
</details>

**Discussion**: Commenters expressed gratitude for the clear explanation, with one noting they could not have come up with Kimi Delta Attention themselves. Others discussed the challenge of notation inconsistency in ML papers and praised the author's use of bra-ket notation for clarity. A recurring theme was that innovation is hard and that explaining complex ideas well is valuable.

**Tags**: `#machine learning`, `#attention mechanisms`, `#linear attention`, `#deep learning`, `#research`

---

<a id="item-20"></a>
## [How to Profile eBPF Code: Tools & Techniques](https://naveensrinivasan.com/posts/2026-07-22-how-do-i-profile-ebpf-code/) ⭐️ 7.0/10

A new guide on profiling eBPF code details tools and techniques, with community contributions highlighting the 'brr' profiler and research on eBPF performance overhead. As eBPF becomes critical for observability and performance, understanding how to profile eBPF programs helps developers optimize their code and avoid hidden bottlenecks like TLB misses. The guide covers perf, bpftop, and other tools; community comments add references to papers on LSM hook and map performance, and introduce 'brr' for per-line profiling of eBPF programs.

hackernews · snaveen · Jul 28, 15:55 · [Discussion](https://news.ycombinator.com/item?id=49085811)

**Background**: eBPF (extended Berkeley Packet Filter) is a kernel technology that allows running sandboxed programs in the Linux kernel without changing kernel source code or loading modules. Profiling eBPF code involves measuring its execution time, memory access patterns, and interactions with kernel subsystems to identify performance bottlenecks.

<details><summary>References</summary>
<ul>
<li><a href="https://metoro.io/blog/top-ebpf-observability-tools">Top 8 eBPF Observability Tools in 2026</a></li>
<li><a href="https://www.groundcover.com/ebpf/ebpf-profiling">eBPF Profiling : The Key to System Insights</a></li>
<li><a href="https://ebpf.io/applications/">A directory of eBPF -based open source applications</a></li>

</ul>
</details>

**Discussion**: Community members shared complementary resources: papers on eBPF LSM hook and map performance, the 'brr' profiler for per-line analysis, and advice to monitor TLB miss rates as eBPF maps can cause significant page table walks.

**Tags**: `#eBPF`, `#profiling`, `#performance`, `#kernel`, `#systems`

---

<a id="item-21"></a>
## [DMARC enforcement remains low despite being a decade-old standard](https://ciphercue.com/blog/dmarc-enforcement-gap-rua-fragmentation-2026) ⭐️ 7.0/10

A new analysis reveals that most company domains still do not enforce DMARC, a decade-old email authentication standard, and even when enforced, it often fails to stop spam and phishing while blocking legitimate emails. This persistent security gap leaves organizations vulnerable to email spoofing and phishing, undermining trust in email communication and highlighting the need for better authentication practices and complementary security measures. The article notes that DMARC monitoring is often used but enforcement (p=quarantine or p=reject) is rare, and many organizations lack the expertise to properly configure records. Community comments reveal that even properly configured DMARC can fail to stop spam because attackers easily pass SPF and DKIM checks.

hackernews · adulion · Jul 28, 10:20 · [Discussion](https://news.ycombinator.com/item?id=49081783)

**Background**: DMARC (Domain-based Message Authentication, Reporting, and Conformance) is an email authentication protocol that builds on SPF and DKIM to prevent email spoofing. It allows domain owners to specify how receivers should handle unauthenticated emails (none, quarantine, or reject) and provides reporting. Despite being standardized in 2012, adoption of enforcement policies remains low due to complexity and fear of blocking legitimate emails.

<details><summary>References</summary>
<ul>
<li><a href="https://www.valimail.com/dmarc/">What is DMARC email authentication ?</a></li>
<li><a href="https://www.mailgun.com/blog/deliverability/implement-dmarc/">DMARC Explained: Five Steps to Email Authentication ... | Mailgun</a></li>
<li><a href="https://selzy.com/en/blog/email-authentication/">What Is an Email Authentication and How To Set It Up</a></li>

</ul>
</details>

**Discussion**: Community comments express frustration that DMARC often blocks legitimate emails from customers while failing to stop spam and phishing, as most attacks now pass SPF and DKIM. Some users suggest that the real need is a trust mechanism for senders, not just authentication. Others note that even large companies misconfigure SPF and DKIM, forcing administrators to disregard failures to avoid complaints.

**Tags**: `#email security`, `#DMARC`, `#SPF`, `#DKIM`, `#cybersecurity`

---

<a id="item-22"></a>
## [EU Initiative Opposes Mandatory Digital ID and Age Verification](https://citizens-initiative.europa.eu/initiatives/details/2026/000011_en) ⭐️ 7.0/10

A European Citizens' Initiative has been registered that calls on EU institutions to ensure online services are not conditioned on mandatory digital identification or age checks, sparking debate on privacy and internet freedom. This initiative challenges the EU's push for digital identity wallets and age verification laws, highlighting tensions between security, privacy, and open internet access. Its outcome could influence future EU digital policy and affect how citizens interact with online services. The initiative was registered on June 26, 2026, and asks that access to online services not be conditioned on mandatory digital ID or age checks. It emphasizes that any such systems must be voluntary and privacy-preserving.

hackernews · doener · Jul 28, 14:58 · [Discussion](https://news.ycombinator.com/item?id=49084938)

**Background**: The EU is developing a European Digital Identity Wallet, which will allow citizens to access services and store digital documents, with member states required to make wallets available by end of 2026. Age verification systems are also being considered to restrict minors from accessing inappropriate content, but critics worry about privacy and surveillance risks.

<details><summary>References</summary>
<ul>
<li><a href="https://commission.europa.eu/topics/digital-economy-and-society/european-digital-identity_en">European Digital Identity - European Commission</a></li>
<li><a href="https://idtechwire.com/eu-registers-citizens-initiative-opposing-mandatory-digital-id-and-age-checks/">EU Registers Citizens' Initiative Opposing Mandatory Digital ID and Age Checks - ID Tech</a></li>

</ul>
</details>

**Discussion**: Commenters express mixed views: some support privacy-preserving digital IDs if properly implemented, while others fear dystopian surveillance. There is skepticism about enforcement and concerns that the internet's open nature is already lost to commercialization.

**Tags**: `#digital identity`, `#privacy`, `#age verification`, `#EU policy`, `#internet freedom`

---

<a id="item-23"></a>
## [Una GPS Smartwatch: Repairable, USB-C, Developer-Friendly](https://unawatch.com/) ⭐️ 7.0/10

Una has announced a new GPS smartwatch that is repairable, features USB-C charging, and is designed to be developer-friendly, aiming to compete with Garmin. This watch challenges the closed ecosystems of major brands like Garmin by offering repairability and open design, potentially appealing to users who value sustainability and customization. The watch is IPX5 rated (splash-proof only) and not submersible, meaning it cannot be used for swimming. It lacks the advanced algorithms (e.g., stress level, body battery) that Garmin offers.

hackernews · pimterry · Jul 28, 14:48 · [Discussion](https://news.ycombinator.com/item?id=49084813)

**Background**: Most commercial smartwatches are sealed and difficult to repair, with proprietary charging and software. Open-source smartwatch projects like Open-SmartWatch exist but are niche. Una aims to bridge the gap between repairability and mainstream functionality.

<details><summary>References</summary>
<ul>
<li><a href="https://open-smartwatch.github.io/">Open-SmartWatch</a></li>
<li><a href="https://www.ifixit.com/repairability/smartwatch-repairability-scores">Smartwatch Repairability Scores - iFixit</a></li>

</ul>
</details>

**Discussion**: Commenters praised the repairability and USB-C but criticized the lack of waterproofing and advanced algorithms. Some noted that Garmin's ecosystem and swimming support are hard to replace, while others appreciated the open design for potential customization.

**Tags**: `#smartwatch`, `#repairability`, `#open hardware`, `#GPS`, `#developer-friendly`

---

<a id="item-24"></a>
## [Google's Beyond Zero: Real-Time Security for AI Agents](https://spawn-queue.acm.org/doi/10.1145/3819083) ⭐️ 7.0/10

Google introduced 'Beyond Zero', a real-time security framework for AI agents that shifts trust from applications to individual actions, evaluating and containing requests in the moment rather than after the fact. This framework addresses a critical gap in enterprise security for AI agents, which are increasingly deployed but lack robust runtime protections. If successful, it could set a new standard for securing autonomous AI systems across industries. Beyond Zero augments Google's existing BeyondCorp zero-trust model with a reasoning 'brain' that evaluates context and intent of each request in real time. However, community comments warn that this central brain could become a new attack surface and add significant complexity.

hackernews · jordigg · Jul 28, 09:59 · [Discussion](https://news.ycombinator.com/item?id=49081644)

**Background**: BeyondCorp is Google's zero-trust security framework that shifts access controls from the network perimeter to individual devices and users, allowing secure work without VPN. AI agent security is a growing field focused on protecting autonomous systems that perform tasks on behalf of users. The proposed Beyond Zero extends zero-trust principles to the action level, aiming to detect and contain suspicious behavior in real time.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/BeyondCorp">BeyondCorp - Wikipedia</a></li>
<li><a href="https://beyondcorp.com/">BeyondCorp | Run Zero Trust Security Like Google</a></li>
<li><a href="https://cloud.google.com/beyondcorp">BeyondCorp Zero Trust Enterprise Security | Google Cloud</a></li>

</ul>
</details>

**Discussion**: Commenters raised concerns that Beyond Zero merely shifts the attack vector to the central reasoning brain, which could become a prime target. Others noted the security layer might be more complex than the applications themselves, and questioned how the system itself builds and maintains trust. Some also highlighted the challenge of distinguishing malicious behavior from non-malicious odd behavior in AI agents.

**Tags**: `#AI security`, `#enterprise security`, `#BeyondCorp`, `#zero trust`, `#AI agents`

---

<a id="item-25"></a>
## [Amazon scales back Nova AI models, bets on new frontier research](https://the-decoder.com/amazon-reportedly-scales-back-its-nova-ai-models-and-bets-on-a-new-frontier-research-team/) ⭐️ 7.0/10

Amazon is reportedly scaling back most of its in-house Nova AI models, including Nova Premier, Omni, Reel, and Canvas, moving them to a 'keep the lights on' mode with no active development. Instead, the company is focusing on a new Frontier Model Research group and a flagship foundation model expected to debut at re:Invent this fall. This strategic shift signals Amazon's recognition that its current Nova models may not be competitive, and it is pivoting resources toward a more focused frontier research effort. The move could reshape the AI model landscape, especially for AWS customers who rely on Amazon's foundation models. The Frontier Model Research group is led by Pieter Abbeel, who joined Amazon in 2025, and operates within the AGI organization. The new foundation model for re:Invent is separate from the scaled-back Nova models and represents Amazon's next-generation AI effort.

rss · The Decoder — AI新闻 · Jul 28, 16:03

**Background**: Amazon Nova is a family of foundation models introduced in late 2023, covering text, image, video, and multimodal capabilities. The models have been offered through AWS Bedrock, but recent reports indicate they lag behind competitors like GPT-4 and Claude in performance. The creation of a dedicated Frontier Model Research group mirrors similar moves by other tech giants to centralize cutting-edge AI research.

<details><summary>References</summary>
<ul>
<li><a href="https://www.businessinsider.com/amazon-overhauls-ai-strategy-phasing-out-most-nova-models-2026-7">Amazon Rethinks Its AI Strategy and Winds Down Many in-House Models - Business Insider</a></li>
<li><a href="https://aws.amazon.com/nova/">Amazon Nova foundation models - Generative AI</a></li>
<li><a href="https://nextomoro.com/amazon-agi/">Amazon AGI | nextomoro | AI Research Lab Intelligence</a></li>

</ul>
</details>

**Tags**: `#Amazon`, `#AI models`, `#Nova`, `#Frontier Research`, `#strategic shift`

---

<a id="item-26"></a>
## [Taiwan detains Nvidia employee in chip smuggling probe](https://the-decoder.com/taiwan-detains-nvidia-employee-in-widening-china-chip-smuggling-probe/) ⭐️ 7.0/10

Taiwanese prosecutors have detained an Nvidia employee for allegedly illegally exporting Super Micro AI servers to China, escalating a widening chip smuggling investigation. This case highlights intensifying global efforts to enforce chip export controls amid US-China tech tensions, potentially affecting Nvidia's operations and the broader AI hardware supply chain. The detained employee is accused of smuggling Super Micro AI servers, which contain Nvidia GPUs, to China in violation of export restrictions. Taiwan is considering even stricter AI chip export controls, including criminal penalties for smuggling.

rss · The Decoder — AI新闻 · Jul 28, 13:15

**Background**: The US and its allies, including Taiwan, have imposed export controls on advanced AI chips to prevent China from acquiring technology that could enhance its military capabilities. Nvidia's high-performance GPUs are critical for AI training and are subject to these restrictions. Super Micro is a major server manufacturer that integrates Nvidia GPUs into its AI server solutions.

<details><summary>References</summary>
<ul>
<li><a href="https://www.supermicro.com/en/solutions/ai-deep-learning">AI Infrastructure Server Solutions For Enterprise | Supermicro</a></li>
<li><a href="https://www.taipeitimes.com/News/biz/archives/2026/06/10/2003858815">Taiwan mulls curbs on AI chip exports to China to align with US - Taipei Times</a></li>
<li><a href="https://www.upi.com/Top_News/World-News/2026/06/10/taiwan-ai-chip-export-controls-on-china/1771781134484/">Taiwan weighs tighter rules for AI chip exports to China - UPI.com</a></li>

</ul>
</details>

**Tags**: `#Nvidia`, `#chip export controls`, `#geopolitics`, `#AI hardware`, `#Taiwan`

---

<a id="item-27"></a>
## [Lyft and Baidu Begin Robotaxi Testing in London](https://techcrunch.com/2026/07/28/lyft-and-baidu-enter-londons-robotaxi-battleground-as-testing-begins/) ⭐️ 7.0/10

Lyft and Baidu's Apollo Go autonomous vehicles have begun testing in London, operating through the Freenow mobility network that Lyft acquired in 2025. This marks a significant expansion of autonomous ride-hailing services into a major European market, intensifying competition in London's robotaxi sector and potentially accelerating the adoption of self-driving technology in the region. The testing involves Baidu's Apollo Go robotaxis, which have already conducted commercial pilot programs in China and received test licenses in Dubai. Freenow, now owned by Lyft, operates across 9 European markets and over 180 cities.

rss · TechCrunch — 科技创投 · Jul 28, 08:00

**Background**: Apollo Go is an autonomous ride-hailing service based on Baidu's Apollo autonomous driving platform. It launched its first commercial unmanned pilot in Beijing in July 2022. Freenow is a European mobility super app offering taxis, ride-hailing, e-scooters, and e-bikes.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Apollo_Go">Apollo Go - Wikipedia</a></li>
<li><a href="https://www.free-now.com/at-en/about-us/">Über Freenow | Freenow</a></li>

</ul>
</details>

**Tags**: `#autonomous vehicles`, `#robotaxi`, `#Lyft`, `#Baidu`, `#London`

---

<a id="item-28"></a>
## [Anthropic CEO clarifies stance on open-weight models, warns of Chinese AI](https://techcrunch.com/2026/07/27/anthropics-dario-amodei-responds-doesnt-oppose-open-weight-models-but-fears-chinese-ai/) ⭐️ 7.0/10

Anthropic CEO Dario Amodei published a statement clarifying that he does not support banning open-weight AI models, but expressed concerns that Chinese AI could surpass the US and that open models could be misused for biological or cyberattacks. This statement from a leading AI CEO influences the ongoing debate about open-weight model regulation and US-China AI competition, potentially shaping policy decisions and industry practices. Amodei emphasized that Anthropic has never advocated for a ban on open-weight models, countering accusations that the company seeks to protect its closed-model business. He argued that authoritarian states like China could overtake the US in AI capabilities.

rss · TechCrunch — 科技创投 · Jul 28, 00:13

**Background**: Open-weight AI models release the trained neural network weights, allowing others to run and fine-tune the model, but they are not fully open-source as training data and code may remain proprietary. The debate over open-weight models involves balancing innovation and accessibility against risks of misuse and geopolitical competition.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/07/27/anthropics-dario-amodei-responds-doesnt-oppose-open-weight-models-but-fears-chinese-ai/">Anthropic's Dario Amodei responds: doesn't oppose open-weight models, but fears Chinese AI | TechCrunch</a></li>
<li><a href="https://www.anthropic.com/news/position-open-weights-models">Our position on open-weights models \ Anthropic</a></li>
<li><a href="https://www.axios.com/2026/07/27/anthropic-open-weight-ban-china-dario-amodei">Anthropic CEO Dario Amodei says he does not support open-weight AI ban</a></li>

</ul>
</details>

**Discussion**: Critics argue that Amodei's stance is primarily aimed at protecting Anthropic's business from cheaper open-weight competitors, rather than genuine safety concerns. Some in the AI community support his call for caution, while others see it as fear-mongering.

**Tags**: `#AI`, `#open-weight models`, `#geopolitics`, `#Anthropic`

---

<a id="item-29"></a>
## [Nadella warns against relying on a single AI model](https://techcrunch.com/2026/07/27/satya-nadella-says-companies-that-trust-one-ai-for-everything-may-not-survive/) ⭐️ 7.0/10

Microsoft CEO Satya Nadella stated that companies trusting only one AI model for all tasks may not survive, urging them to develop custom models and adopt AI gateways to separate prompts from models. This insight from a top industry leader highlights a strategic shift toward AI diversity and infrastructure, impacting how enterprises adopt and manage AI technologies. Nadella emphasized the need for AI gateways, which act as middleware to manage, route, and secure API calls to multiple large language models, similar to API gateways in traditional software.

rss · TechCrunch — 科技创投 · Jul 27, 21:17

**Background**: An AI gateway is a specialized middleware that sits between applications and AI service providers, handling rate limits, API keys, and routing requests to different models. Custom models allow enterprises to fine-tune or build models on their own data for specific needs. Nadella's warning reflects growing concerns about vendor lock-in and the need for flexible AI infrastructure.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/API_gateway">API gateway</a></li>
<li><a href="https://grokipedia.com/page/AI_Gateway">AI Gateway</a></li>
<li><a href="https://vercel.com/ai-gateway">AI Gateway - Vercel</a></li>

</ul>
</details>

**Tags**: `#AI strategy`, `#enterprise AI`, `#AI infrastructure`, `#Satya Nadella`

---

<a id="item-30"></a>
## [Substack writers urged to own their content with personal websites](https://elizabethtai.com/2026/06/10/substack-writers-you-need-a-website/) ⭐️ 6.0/10

Elizabeth Tai argues that Substack writers should maintain their own website as the primary home for content, using Substack mainly for email distribution. The article and community discussion explore the tension between platform dependency and content ownership. This debate highlights a fundamental choice for online creators between convenience and control, especially as platforms like Substack grow. It affects how writers manage their digital presence, audience relationships, and long-term content ownership. Simon Willison shares a hybrid approach: publishing first on his personal blog, then copying to Substack weekly for email distribution to 66,000 subscribers. Some writers express concerns about AI scraping and platform lock-in, while others note the difficulty of driving traffic to personal sites.

hackernews · speckx · Jul 28, 16:58 · [Discussion](https://news.ycombinator.com/item?id=49086788)

**Background**: Substack is a platform that combines publishing, email newsletters, and monetization, allowing writers to build a subscriber base and earn revenue. The IndieWeb movement advocates for owning one's online identity and content by using personal websites and open standards, rather than relying solely on centralized platforms.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Substack">Substack - Wikipedia</a></li>
<li><a href="https://indieweb.org/why">why - IndieWeb</a></li>
<li><a href="https://substack.com/features">Substack features: publish, grow, and earn in one place</a></li>

</ul>
</details>

**Discussion**: Commenters express mixed views: some argue that personal websites lack discoverability and that push mechanisms like Substack are essential, while others share successful hybrid strategies. Concerns about AI scraping and platform lock-in are also raised, with some writers choosing to leave the web entirely.

**Tags**: `#blogging`, `#content strategy`, `#Substack`, `#indie web`, `#writing`

---

<a id="item-31"></a>
## [SBCL 2.6.7 Adds SIMD Support for ARM64 and AVX512](https://sbcl.org/all-news.html?2.6.7) ⭐️ 6.0/10

Steel Bank Common Lisp version 2.6.7 has been released, adding SIMD support for ARM64 and AVX512 instructions on x86-64, along with other improvements. This release brings modern SIMD capabilities to Common Lisp, potentially improving performance for numerical and scientific computing, and keeping the language relevant on modern hardware. The SB-SIMD contrib module now supports ARM64, and AVX512 instructions are supported on x86-64, contributed by developers including Sylvia Harrington, Robert Smith, and Arthur Miller.

hackernews · tmtvl · Jul 28, 17:11 · [Discussion](https://news.ycombinator.com/item?id=49086971)

**Background**: SIMD (Single Instruction, Multiple Data) allows a CPU to perform the same operation on multiple data points simultaneously, accelerating tasks like image processing and machine learning. SBCL is a high-performance Common Lisp implementation known for its speed and native code compilation.

<details><summary>References</summary>
<ul>
<li><a href="https://www.sbcl.org/manual/">SBCL 2.6.6 User Manual</a></li>
<li><a href="https://github.com/sbcl/sbcl/releases">Releases · sbcl/sbcl - GitHub</a></li>

</ul>
</details>

**Discussion**: Community members expressed curiosity about how SIMD is implemented in SBCL, whether it auto-vectorizes or requires explicit intrinsics. Some also discussed the hypothetical scenario of a Lisp-optimized cloud infrastructure, while others requested better documentation for the memory arena feature.

**Tags**: `#Common Lisp`, `#SBCL`, `#SIMD`, `#Programming Languages`

---

<a id="item-32"></a>
## [Slow Journalism Magazine Prides Itself on Being Last to Breaking News](https://www.slow-journalism.com/) ⭐️ 6.0/10

The magazine 'Delayed Gratification' positions itself as the last to breaking news, prioritizing in-depth analysis over speed. This approach challenges the 24-hour news cycle and offers an alternative for readers seeking quality over quantity, potentially influencing journalism standards. The magazine is beautifully designed with high production values, but some readers found its stories disconnected or too distant from their interests.

hackernews · speerer · Jul 28, 15:50 · [Discussion](https://news.ycombinator.com/item?id=49085731)

**Background**: Slow journalism is a movement that emphasizes careful reporting and reflection, contrasting with the fast-paced, often superficial coverage of breaking news. 'Delayed Gratification' is a quarterly magazine that exemplifies this philosophy.

**Discussion**: Commenters expressed mixed feelings: some appreciated the concept but found the execution lacking, while others felt the magazine's stories were too remote or the writing style unappealing. A few noted the need to 'deprogram' from the 24-hour news cycle.

**Tags**: `#journalism`, `#media`, `#slow-news`, `#quality-reporting`

---

<a id="item-33"></a>
## [Harmony Explained: A Mathematical Theory of Music](https://arxiv.org/abs/1202.4212) ⭐️ 6.0/10

A 2012 paper titled 'Harmony Explained: Progress Towards a Scientific Theory of Music' attempts to derive musical harmony from harmonic ratios and the harmonic series, proposing a mathematical foundation for consonance and dissonance. The paper offers a rigorous mathematical perspective on music theory, potentially bridging physics and music, but its oversimplification of emotional aspects limits its practical impact on musicians and composers. The paper focuses on just intonation ratios (e.g., 3:2 for perfect fifths) and the harmonic series, but critics note that it ignores frequency-dependent consonance and the role of cultural context in musical perception.

hackernews · surprisetalk · Jul 28, 15:20 · [Discussion](https://news.ycombinator.com/item?id=49085280)

**Background**: Music theory often explains harmony through intervals and chords, but a scientific theory seeks to ground these in acoustics and psychoacoustics. The harmonic series is a natural phenomenon where overtones occur at integer multiples of a fundamental frequency, forming the basis of many musical intervals. However, emotional responses to music involve complex cognitive and cultural factors beyond simple ratios.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Harmonic_series_(music)">Harmonic series (music) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Interval_(music)">Interval (music) - Wikipedia</a></li>
<li><a href="https://microtonal-guitar.com/tutorial/the-harmonic-series-musical-ratios-intervals/">The Harmonic Series, Musical Ratios & Intervals – Microtonal Guitar</a></li>

</ul>
</details>

**Discussion**: Commenters criticize the paper for oversimplifying the happy/sad dichotomy of major/minor chords and for ignoring better resources like Sethares and Tymoczko's work. Some suggest that consonance is frequency-dependent and that the paper's logic is unconvincing for combining dissonant elements in music.

**Tags**: `#music theory`, `#harmonics`, `#mathematics`, `#acoustics`

---

<a id="item-34"></a>
## [Now Is the Time to Give LLMs Access to the ACM Digital Library](https://cacm.acm.org/opinion/now-is-the-time-to-give-llms-access-to-the-acm-digital-library/) ⭐️ 6.0/10

An opinion piece argues that large language models (LLMs) should be granted access to the ACM Digital Library to improve AI training on peer-reviewed research. This could significantly enhance the quality and reliability of LLM outputs by incorporating high-quality, peer-reviewed academic content, potentially reducing misinformation and improving scientific reasoning. The ACM Digital Library contains a vast collection of computing literature, including journals, conference proceedings, and magazines, which are currently behind a paywall and not typically included in LLM training datasets.

hackernews · rbanffy · Jul 28, 15:01 · [Discussion](https://news.ycombinator.com/item?id=49084987)

**Background**: Large language models are trained on massive text corpora from public sources like websites, books, and research papers. However, many high-quality academic papers are behind paywalls, limiting LLM access to cutting-edge research. The ACM Digital Library is a premier source of peer-reviewed computing research.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ACM_Digital_Library">ACM Digital Library</a></li>
<li><a href="https://www.acm.org/publications/digital-library">Information about ACM 's Digital Library</a></li>
<li><a href="https://oxylabs.io/blog/llm-training-data">LLM Training Data: The 8 Main Public Data Sources</a></li>

</ul>
</details>

**Discussion**: Comments are mostly skeptical, with users noting that LLMs may have already scraped the data, questioning the position of ACM and authors, and suggesting that humans should get access first.

**Tags**: `#LLM`, `#ACM`, `#academic publishing`, `#AI training`

---

<a id="item-35"></a>
## [Apple Releases Security Update for macOS Tahoe 26.6](https://support.apple.com/en-us/128067) ⭐️ 6.0/10

Apple released macOS Tahoe 26.6, patching approximately 143 security vulnerabilities across system components including the kernel, WebKit, Wi-Fi, and Siri. This update addresses a large number of vulnerabilities, some of which could lead to arbitrary code execution or privilege escalation, making it critical for users to upgrade to protect their systems. The update includes fixes for path traversal vulnerabilities (e.g., CVE-2026-20625) and memory safety issues, with many entries credited to researchers using AI-assisted vulnerability discovery tools like Claude and Anthropic Research.

hackernews · andor · Jul 28, 09:45 · [Discussion](https://news.ycombinator.com/item?id=49081555)

**Background**: macOS Tahoe is the latest major version of Apple's desktop operating system. Security updates like this one are routine but important, as they patch known vulnerabilities that could be exploited by attackers. The large number of fixes in this release highlights the ongoing challenge of maintaining software security.

<details><summary>References</summary>
<ul>
<li><a href="https://support.apple.com/en-us/128067">About the security content of macOS Tahoe 26.6 - Apple Support</a></li>
<li><a href="https://www.macrumors.com/2026/07/27/ios-26-6-security-fixes/">Update Now: iOS 26.6 and macOS Tahoe 26.6 Patch Hundreds of Security Flaws - MacRumors</a></li>
<li><a href="https://www.techtimes.com/articles/321756/20260728/macos-tahoe-266-closes-143-security-flaws-starts-building-ai-siris-brain.htm">macOS Tahoe 26.6 Closes 143 Security Flaws and Starts Building AI Siri's Brain</a></li>

</ul>
</details>

**Discussion**: Community comments discuss upgrade deferral strategies due to earlier issues with macOS 26, the monetary cost of memory safety fixes in terms of developer time, and the prevalence of path parsing vulnerabilities across operating systems. Some users note the high number of fixes and the involvement of AI tools in vulnerability discovery.

**Tags**: `#macOS`, `#security`, `#Apple`, `#vulnerabilities`

---

<a id="item-36"></a>
## [Ethan Mollick's AI Guide Shifts to Agentic Systems](https://simonwillison.net/2026/Jul/27/an-opinionated-guide-to-which-ai-to-use-to-do-stuff/#atom-everything) ⭐️ 6.0/10

Ethan Mollick updated his opinionated guide to AI tools, moving focus from chat-based models to agentic systems like ChatGPT Work and Claude Cowork, and notably dropping Gemini from his recommendations. This shift reflects the broader industry trend toward autonomous AI agents that can perform complex tasks with minimal supervision, impacting how practitioners choose and use AI tools for productivity. Mollick explains that ChatGPT Work and Claude Cowork allow AI to access a user's computer, with ChatGPT Work on mobile enabling internet access for its Code Interpreter container, while Google's Gemini Spark has yet to prove itself in this category.

rss · Simon Willison — AI工具 · Jul 27, 21:55

**Background**: Agentic AI refers to systems that can perceive, reason, and act autonomously to achieve goals, unlike traditional chatbots that require step-by-step prompting. Major AI companies are releasing agent modes: OpenAI's ChatGPT Work and Codex, and Anthropic's Claude Cowork and Code, each with different capabilities and confusing naming conventions.

<details><summary>References</summary>
<ul>
<li><a href="https://mitsloan.mit.edu/ideas-made-to-matter/agentic-ai-explained">Agentic AI, explained | MIT Sloan</a></li>
<li><a href="https://www.ibm.com/think/topics/agentic-ai">What is Agentic AI? | IBM</a></li>
<li><a href="https://aws.amazon.com/what-is/agentic-ai/">What is Agentic AI? - Agentic AI Explained - AWS</a></li>

</ul>
</details>

**Tags**: `#AI`, `#LLM`, `#agentic systems`, `#opinion`

---

<a id="item-37"></a>
## [Fish Audio raises $52M seed for AI voice models](https://techcrunch.com/2026/07/28/fish-audio-raises-50m-seed-to-build-ai-voice-models-for-creators-and-enterprises/) ⭐️ 6.0/10

Fish Audio has raised a $52 million seed round to develop AI voice models for creators and enterprises, and now serves over 8 million users with $21 million in annual recurring revenue. This large seed round signals strong investor confidence in AI voice technology, which is increasingly used for content creation, customer support, and sales automation. Fish Audio's open-source approach and rapid user growth could disrupt the text-to-speech market. Fish Audio's open-source model, Fish Speech, can clone a voice from just 10-30 seconds of audio and supports over 80 languages with under 150ms latency. The company also offers hosted APIs for enterprise use.

rss · TechCrunch — 科技创投 · Jul 28, 14:00

**Background**: AI voice models use deep learning to synthesize natural speech from text, enabling applications like voice assistants, audiobooks, and dubbing. Fish Audio builds on prior open-source projects like So-VITS-SVC and Bert-VITS2, and its latest model is trained on over 1 million hours of multilingual audio data.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/07/28/fish-audio-raises-50m-seed-to-build-ai-voice-models-for-creators-and-enterprises/">Fish Audio raises $52M seed to build AI voice models ... | TechCrunch</a></li>
<li><a href="https://github.com/fishaudio/fish-speech">GitHub - fishaudio/ fish -speech: SOTA Open Source TTS · GitHub</a></li>
<li><a href="https://fish.audio/">Best AI Text To Speech & Free Voice Cloning | Fish Audio</a></li>

</ul>
</details>

**Tags**: `#AI`, `#voice`, `#funding`, `#startup`

---

<a id="item-38"></a>
## [Thea Energy wins $20M ARPA-E grant for fusion magnets](https://techcrunch.com/2026/07/27/thea-energy-lands-20m-federal-grant-to-build-its-magnets-for-fusion-reactors/) ⭐️ 6.0/10

Thea Energy has received a $20 million award from the U.S. Department of Energy's ARPA-E program to scale production of its high-temperature superconducting (HTS) magnets for fusion reactors. This grant supports a critical component for commercial fusion energy, potentially accelerating the timeline for practical fusion power plants. HTS magnets are key to confining plasma in compact fusion designs. Thea Energy's modular HTS magnets aim to reduce manufacturing costs and improve scalability. The grant specifically targets manufacturing advancements, not reactor design.

rss · TechCrunch — 科技创投 · Jul 27, 20:40

**Background**: High-temperature superconducting magnets can generate strong magnetic fields without the need for expensive cryogenic cooling, making them attractive for compact fusion reactors. In 2021, MIT and Commonwealth Fusion Systems demonstrated a 20-tesla HTS magnet, a milestone for fusion. ARPA-E funds high-risk, high-reward energy technologies.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/07/27/thea-energy-lands-20m-federal-grant-to-build-its-magnets-for-fusion-reactors/">Thea Energy lands $20M federal grant to build its magnets for fusion ...</a></li>
<li><a href="https://nile1.com/en/2026/07/27/thea-energy-secures-20m-federal-award-to-scale-superconducting-magnet-production/">Thea Energy Secures $20M Federal Award to Scale Superconducting...</a></li>

</ul>
</details>

**Tags**: `#fusion energy`, `#superconducting magnets`, `#ARPA-E`, `#startup funding`

---

