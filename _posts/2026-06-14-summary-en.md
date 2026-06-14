---
layout: default
title: "Horizon Summary: 2026-06-14 (EN)"
date: 2026-06-14
lang: en
---

> From 36 items, 19 important content pieces were selected

---

1. [Pyodide 314.0 Enables Direct WASM Wheel Publishing to PyPI](#item-1) ⭐️ 9.0/10
2. [Rio's homegrown LLM alleged to be a merge of existing models](#item-2) ⭐️ 8.0/10
3. [Jane Street on Formal Methods in an AI-Driven Era](#item-3) ⭐️ 8.0/10
4. [2014 Talk on JavaScript's Rise and Fall Revisited](#item-4) ⭐️ 8.0/10
5. [How to Build a Billion-Dollar Startup](#item-5) ⭐️ 8.0/10
6. [Mirage: Persistent Spatial Memory for Video Generation](#item-6) ⭐️ 8.0/10
7. [Google Cloud's Open Knowledge Format standardizes docs for AI agents](#item-7) ⭐️ 8.0/10
8. [KPMG fabricated AI case studies in report](#item-8) ⭐️ 8.0/10
9. [Amazon, others triggered US crackdown on Anthropic's Fable model](#item-9) ⭐️ 8.0/10
10. [Meta unwinds $2B Manus deal after Beijing demand](#item-10) ⭐️ 8.0/10
11. [Developer indexes 669 GB of GoPro videos locally on M1 Max](#item-11) ⭐️ 7.0/10
12. [AI Adoption: Not Everyone Uses It Frequently](#item-12) ⭐️ 7.0/10
13. [Mapping SQLite Result Columns to Source Tables with AI](#item-13) ⭐️ 7.0/10
14. [AI coding agents find files but miss critical lines, study shows](#item-14) ⭐️ 7.0/10
15. [UK Considers Banning Social Media for Under-16s](#item-15) ⭐️ 7.0/10
16. [llama.cpp b9637 Adds Cohere2MoE Parser](#item-16) ⭐️ 6.0/10
17. [Kage: Shadow Any Website into a Single Binary for Offline Viewing](#item-17) ⭐️ 6.0/10
18. [Zeroserve Boosts Caddy Performance but Lacks ACME](#item-18) ⭐️ 6.0/10
19. [Perlisisms: Timeless Epigrams on Programming](#item-19) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Pyodide 314.0 Enables Direct WASM Wheel Publishing to PyPI](https://simonwillison.net/2026/Jun/13/publishing-wasm-wheels/#atom-everything) ⭐️ 9.0/10

Pyodide 314.0, released in June 2026, allows package maintainers to publish WebAssembly (WASM) wheels directly to PyPI using the new PyEmscripten platform tag defined in PEP 783, eliminating the previous bottleneck where the Pyodide core team had to manually build and host over 300 packages. This shift decentralizes package maintenance, enabling individual maintainers to distribute WASM-compiled Python packages (including C/C++/Rust extensions) just like native wheels, which significantly accelerates the growth of the Python-in-browser ecosystem and reduces the burden on Pyodide maintainers. The PyPI support for WASM wheels was implemented via PR #19804 to the PyPI warehouse, which landed on April 21, 2026. The new platform tag follows the format pyemscripten_<year>_<patch>_wasm32, and tools like cibuildwheel and maturin now support building these wheels.

rss · Simon Willison — AI工具 · Jun 13, 23:55

**Background**: Pyodide is a port of CPython to WebAssembly/Emscripten, enabling Python to run in the browser. Previously, the Pyodide team maintained a custom repository of over 300 pre-built WASM packages, which required manual review for each new package. PEP 783, accepted in March 2025, standardized the PyEmscripten platform tag, paving the way for direct PyPI publishing.

<details><summary>References</summary>
<ul>
<li><a href="https://peps.python.org/pep-0783/">PEP 783 – Emscripten Packaging | peps.python.org</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion (item 48462759) was highly positive, with many users celebrating the removal of a long-standing bottleneck. Some commenters noted the importance of PEP 783 and the collaborative effort between Pyodide and PyPI teams, while others shared their own experiments with publishing WASM wheels.

**Tags**: `#Python`, `#WebAssembly`, `#Pyodide`, `#PyPI`, `#Package Management`

---

<a id="item-2"></a>
## [Rio's homegrown LLM alleged to be a merge of existing models](https://github.com/nex-agi/Nex-N2/issues/4) ⭐️ 8.0/10

Rio de Janeiro's IT company IplanRIO released Rio-3.5-Open-397B, claiming it as a homegrown fine-tune of Qwen3.5, but community analysis suggests it is a weighted merge of approximately 60% Nex-N2 Pro and 40% Qwen3.5-397B-A17B, with no additional training. This controversy highlights transparency issues in claimed homegrown AI models, potentially undermining trust in open-source AI development and raising questions about proper attribution when merging existing models. The analysis shows that every weight tensor in Rio matches a 0.6/0.4 blend of Nex and Qwen across all 60 layers, which cannot be explained by typical fine-tuning. The community also notes that Nex-N2 itself is based on Qwen, complicating attribution.

hackernews · unrvl22 · Jun 14, 15:37 · [Discussion](https://news.ycombinator.com/item?id=48528371)

**Background**: Model merging is a technique that combines the weights of multiple LLMs to create a new model without additional training, often using methods like linear interpolation. The Rio model was presented as a homegrown achievement for the city, but the evidence suggests it is simply a merge of two existing open-source models.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.nvidia.com/blog/an-introduction-to-model-merging-for-llms/">An Introduction to Model Merging for LLMs | NVIDIA Technical Blog</a></li>
<li><a href="https://github.com/nex-agi/Nex-N2">GitHub - nex-agi/ Nex - N 2 · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/Qwen">Qwen - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The community is divided: some argue that merging is a legitimate technique and the lack of disclosure is the real issue, while others criticize the city for claiming originality without proper attribution. Technical users point out that the weight patterns are too consistent to be a fine-tune, and the debate centers on whether merging without training constitutes a new model.

**Tags**: `#LLM`, `#open-source`, `#model merging`, `#attribution`, `#controversy`

---

<a id="item-3"></a>
## [Jane Street on Formal Methods in an AI-Driven Era](https://blog.janestreet.com/formal-methods-at-jane-street-index/?from_theconsensus=1) ⭐️ 8.0/10

Jane Street published a blog post discussing their use of formal methods in production, emphasizing a shift from code generation to verification as AI generates more code. This discussion highlights a critical industry trend: as AI-generated code proliferates, human effort must shift toward verification to ensure correctness and security, making formal methods more relevant than ever. The post references practical use of formal methods at Jane Street, including integration with OCaml and tools like Imandra, and notes that verification is becoming the bottleneck as generation becomes cheap.

hackernews · eatonphil · Jun 14, 12:35 · [Discussion](https://news.ycombinator.com/item?id=48526633)

**Background**: Formal methods are mathematically rigorous techniques for specifying, developing, and verifying software and hardware systems. Unlike testing, they can prove the absence of certain bugs. With AI generating code at scale, verification becomes more critical yet more expensive, a challenge Jane Street addresses by integrating formal verification into their development workflow.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Formal_methods">Formal methods - Wikipedia</a></li>
<li><a href="https://www.darpa.mil/research/research-spotlights/formal-methods/examples">Formal Methods Examples | DARPA</a></li>
<li><a href="https://signalandintent.substack.com/p/generation-is-cheap-verification">Generation Is Cheap, Verification Is Expensive: The Real Cost of AI</a></li>

</ul>
</details>

**Discussion**: Commenters shared diverse perspectives: one recalled early proof automation with SAT solvers and the Boyer-Moore prover, noting the human effort in suggesting lemmas. Another praised using expressive types in Scala 3 for compile-time proofs to prevent AI-generated code quality issues. A third noted the challenge for non-English speakers in learning programming and the need for verification over generation.

**Tags**: `#formal methods`, `#programming`, `#verification`, `#AI`, `#software engineering`

---

<a id="item-4"></a>
## [2014 Talk on JavaScript's Rise and Fall Revisited](https://www.destroyallsoftware.com/talks/the-birth-and-death-of-javascript) ⭐️ 8.0/10

A 2014 talk by Gary Bernhardt predicting JavaScript's dominance as a compilation target and its eventual replacement by WebAssembly has resurfaced, with the community reflecting on its accuracy given WebAssembly's current limitations. This retrospective highlights how prescient the talk was about web development trends, while also revealing that WebAssembly has not yet fully replaced JavaScript due to missing DOM access, keeping JavaScript relevant as glue code. The talk correctly predicted JavaScript becoming a compilation target via asm.js, which later evolved into WebAssembly, but WebAssembly still lacks direct DOM manipulation, requiring JavaScript for web interactions.

hackernews · subset · Jun 14, 12:38 · [Discussion](https://news.ycombinator.com/item?id=48526661)

**Background**: JavaScript was originally a scripting language for browsers but became a compilation target for languages like C++ via asm.js, a low-level subset. WebAssembly (Wasm) is a binary format designed for near-native performance, but it cannot directly access the DOM, so JavaScript remains necessary for many web tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.devgenius.io/webassembly-how-emscripten-and-assemblyscript-achieve-near-native-performance-27f64a13b338">WebAssembly : How Emscripten and AssemblyScript... | Dev Genius</a></li>
<li><a href="https://en.wikipedia.org/wiki/Asm.js">asm . js - Wikipedia</a></li>
<li><a href="https://motherduck.com/learn/web-assembly/">What is WebAssembly ?</a></li>

</ul>
</details>

**Discussion**: Commenters noted the talk's eerie prediction of a global disaster between 2020-2025, albeit the wrong type. Others observed that WebAssembly has not advanced as fast as hoped, and that JavaScript remains essential as glue code, with some suggesting alternatives like rendering everything on a canvas.

**Tags**: `#JavaScript`, `#WebAssembly`, `#web development`, `#programming languages`, `#tech predictions`

---

<a id="item-5"></a>
## [How to Build a Billion-Dollar Startup](https://paulgraham.com/earn.html) ⭐️ 8.0/10

Paul Graham published an essay titled 'How to Earn a Billion Dollars' on his website, outlining a framework for building a billion-dollar startup by creating scalable wealth through a combination of a great idea, a large market, and relentless execution. This essay provides a high-profile, practical blueprint for aspiring entrepreneurs, sparking debate on wealth creation, startup ethics, and economic impact within the tech community. The essay emphasizes that earning a billion dollars typically requires building a company that creates significant new wealth, not merely redistributing existing wealth, and highlights the importance of scalability and market size.

hackernews · kingstoned · Jun 14, 11:50 · [Discussion](https://news.ycombinator.com/item?id=48526360)

**Background**: Paul Graham is a well-known venture capitalist, essayist, and co-founder of Y Combinator, a startup accelerator that has funded companies like Airbnb and Dropbox. His essays on startups and entrepreneurship are widely read and influential in the tech industry.

**Discussion**: The Hacker News community engaged in a heated debate, with some praising the essay's insights while others criticized it for ignoring the negative externalities of wealth creation, such as market saturation and displacement of workers. A few commenters also questioned the ethics of founders retaining large equity stakes while employees receive minimal shares.

**Tags**: `#startups`, `#wealth`, `#entrepreneurship`, `#essay`, `#hackernews`

---

<a id="item-6"></a>
## [Mirage: Persistent Spatial Memory for Video Generation](https://the-decoder.com/microsoft-researchs-mirage-gives-video-generation-a-persistent-spatial-memory-that-doesnt-forget-whats-around-the-corner/) ⭐️ 8.0/10

Microsoft Research and university collaborators introduced Mirage, a video world model that stores scene information directly in latent space instead of pixel-based point clouds, enabling persistent spatial memory across long camera moves. This approach significantly reduces compute time and memory footprint—up to 10.57× faster generation and 55× less memory—while maintaining spatial consistency, making high-quality video generation more accessible on available hardware. Mirage constructs latent spatial memory by lifting latent tokens into 3D via depth-guided back-projection and queries it through direct latent-space warping. However, it still cannot reliably track moving objects across segments.

rss · The Decoder — AI新闻 · Jun 14, 13:58

**Background**: Traditional video world models often use pixel-based memory (e.g., point clouds or voxel grids), which is computationally expensive and memory-intensive. Latent space is a compressed representation where diffusion models operate more efficiently. Mirage leverages this by storing and updating a persistent latent cache, avoiding repeated encoding and rendering.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2606.09828">[2606.09828] Latent Spatial Memory for Video World Models</a></li>
<li><a href="https://microsoft.github.io/LatentSpatialMemory/">Mirage | Latent Spatial Memory for Video World Models</a></li>
<li><a href="https://the-decoder.com/microsoft-researchs-mirage-gives-video-generation-a-persistent-spatial-memory-that-doesnt-forget-whats-around-the-corner/">Microsoft Research's Mirage gives video generation a ...</a></li>

</ul>
</details>

**Tags**: `#video generation`, `#spatial memory`, `#latent space`, `#Microsoft Research`, `#AI`

---

<a id="item-7"></a>
## [Google Cloud's Open Knowledge Format standardizes docs for AI agents](https://the-decoder.com/google-clouds-open-knowledge-format-turns-scattered-docs-into-markdown-files-for-ai-agents/) ⭐️ 8.0/10

Google Cloud has introduced the Open Knowledge Format (OKF) v0.1, a vendor-neutral specification that standardizes organizational knowledge as Markdown files with YAML frontmatter, designed to be consumed by AI agents. This formalizes a pattern popularized by Andrej Karpathy's 'LLM Wiki' concept. OKF provides a portable, human- and agent-friendly format for knowledge sharing across teams and organizations, potentially improving how AI agents access and utilize curated organizational knowledge. It could become a standard for AI agent memory and knowledge management, reducing fragmentation in the ecosystem. OKF is an open specification hosted on GitHub under GoogleCloudPlatform/knowledge-catalog, currently in draft v0.1. It defines a structure where each knowledge unit is a Markdown file with YAML frontmatter containing metadata like title, description, tags, and relationships.

rss · The Decoder — AI新闻 · Jun 14, 13:29

**Background**: Andrej Karpathy recently popularized the 'LLM Wiki' concept, where personal or organizational knowledge is stored as Markdown files for easy consumption by large language models. This pattern contrasts with traditional RAG (Retrieval-Augmented Generation) approaches, offering simplicity and reliability for smaller knowledge bases. OKF formalizes this pattern into a standard that can be adopted across the industry.

<details><summary>References</summary>
<ul>
<li><a href="https://cloud.google.com/blog/products/data-analytics/how-the-open-knowledge-format-can-improve-data-sharing/">Introducing the Open Knowledge Format - Google Cloud Blog</a></li>
<li><a href="https://github.com/GoogleCloudPlatform/knowledge-catalog/blob/main/okf/SPEC.md">Open Knowledge Format (OKF) - GitHub</a></li>
<li><a href="https://www.explainx.ai/blog/google-open-knowledge-format-okf-ai-agents-2026">Open Knowledge Format (OKF): Google AI Agent Standard - explainx.ai</a></li>

</ul>
</details>

**Tags**: `#Google Cloud`, `#AI agents`, `#knowledge management`, `#Markdown`, `#LLM Wiki`

---

<a id="item-8"></a>
## [KPMG fabricated AI case studies in report](https://the-decoder.com/kpmg-fabricated-ai-case-studies-in-a-report-designed-to-sell-clients-on-ai-adoption/) ⭐️ 8.0/10

KPMG published a report on AI in business that contained fabricated case studies involving UBS, the NHS, and other organizations, which was later retracted after being exposed by GPTZero CEO Edward Tian. This incident undermines trust in consulting firms and highlights the risk of 'secondary hallucinations'—flawed claims from trusted sources that spread unchecked, potentially misleading businesses in their AI adoption decisions. The report was designed to sell clients on AI adoption, and the fabricated case studies were uncovered by GPTZero's CEO, who warned of secondary hallucinations. KPMG has since pulled the report.

rss · The Decoder — AI新闻 · Jun 14, 09:40

**Background**: KPMG is one of the Big Four accounting firms, offering audit, tax, and advisory services including AI consulting. 'Secondary hallucinations' refer to false or misleading claims generated by AI that are then repeated and amplified by humans or organizations, gaining undeserved credibility.

<details><summary>References</summary>
<ul>
<li><a href="https://gptzero.me/news/author/edward/">Edward Tian - AI Detection Resources | GPTZero</a></li>

</ul>
</details>

**Tags**: `#AI ethics`, `#consulting`, `#hallucination`, `#KPMG`, `#fraud`

---

<a id="item-9"></a>
## [Amazon, others triggered US crackdown on Anthropic's Fable model](https://the-decoder.com/amazon-and-five-other-companies-reportedly-triggered-the-government-crackdown-on-anthropics-fable-model/) ⭐️ 8.0/10

Amazon CEO Andy Jassy and executives from five other tech companies reportedly warned the Trump administration about security vulnerabilities in Anthropic's Fable AI model, leading the White House to force the model offline via an export control order within hours. This incident highlights the growing influence of private corporations in shaping AI regulation and raises concerns about potential anti-competitive behavior, especially given Amazon's dual role as both an investor in Anthropic and a competitor in the AI space. The export controls were imposed under the Biden administration's first-ever AI model export controls, and Anthropic had just released Claude Fable 5, its most powerful public model, days before the crackdown.

rss · The Decoder — AI新闻 · Jun 14, 08:35

**Background**: Anthropic's Claude Fable 5 is a Mythos-class AI model with advanced capabilities but also guardrails to block high-risk responses. The US government has been tightening export controls on advanced AI models and chips to prevent adversaries from accessing sensitive technology. Amazon is a major investor in Anthropic but also competes with it in the AI market.

<details><summary>References</summary>
<ul>
<li><a href="https://www.politico.com/news/2026/06/13/inside-the-whirlwind-24-hours-that-led-the-white-house-to-slap-export-controls-on-anthropic-00961519">Inside the whirlwind 24 hours that led the White House to slap export ...</a></li>
<li><a href="https://techcrunch.com/2026/06/09/anthropic-released-claude-fable-5-its-most-powerful-model-publicly-days-after-warning-ai-is-getting-too-dangerous/">Anthropic releases Claude Fable, a version of Mythos, days after warning AI is becoming too dangerous</a></li>

</ul>
</details>

**Tags**: `#AI regulation`, `#Anthropic`, `#Amazon`, `#export controls`, `#AI security`

---

<a id="item-10"></a>
## [Meta unwinds $2B Manus deal after Beijing demand](https://techcrunch.com/2026/06/13/meta-reportedly-moves-to-unwind-2b-manus-deal-after-beijings-demand/) ⭐️ 8.0/10

Meta has begun dismantling its $2 billion acquisition of AI startup Manus after Beijing ordered the deal reversed, cutting Manus off from internal data systems and instructing staff to stop using the platform. This marks a rare instance of a major tech acquisition being unwound due to geopolitical pressure, highlighting the increasing regulatory risks in cross-border AI deals and the growing tension between the US and China over technology. The $2 billion deal was announced in December 2025, and China's Ministry of Commerce has been reviewing it for potential export control violations. Meta has taken concrete steps to reverse the acquisition, including cutting off Manus from its systems.

rss · TechCrunch — 科技创投 · Jun 14, 00:03

**Background**: Manus is a Singapore-based developer of general-purpose AI agents, known for its 'truly autonomous' agent technology. Meta acquired Manus in late 2025 to integrate its AI agents into Facebook, Instagram, and WhatsApp. However, Chinese regulators scrutinized the deal due to Manus's Chinese founding team and potential export control issues.

<details><summary>References</summary>
<ul>
<li><a href="https://qz.com/meta-manus-acquisition-unwind-china-beijing-061226">Meta unwinds $2 billion Manus acquisition after China order</a></li>
<li><a href="https://www.bbc.com/news/articles/cj0v0gr2yz7o">China blocks Meta's $2bn acquisition of AI start-up Manus</a></li>

</ul>
</details>

**Tags**: `#Meta`, `#Manus`, `#acquisition`, `#geopolitics`, `#regulation`

---

<a id="item-11"></a>
## [Developer indexes 669 GB of GoPro videos locally on M1 Max](https://news.ycombinator.com/item?id=48528029) ⭐️ 7.0/10

A developer indexed 628 GoPro videos (669 GB, 15+ hours of footage) on an M1 Max MacBook using open-source ML models, enabling semantic search and automatic clip compilation to DaVinci Resolve timeline. This demonstrates that large-scale video indexing and search can be done locally on consumer hardware, reducing reliance on cloud services and preserving privacy. It also highlights the growing ecosystem of open-source ML tools for video analysis. The pipeline processed 57,537 frames at 1 fps, taking 67 hours and 40 minutes of compute time. The project uses open-source models for scene detection, object recognition, and semantic embedding.

hackernews · iliashad · Jun 14, 15:13

**Background**: Video indexing typically requires cloud-based AI services or powerful servers. The M1 Max's unified memory and Neural Engine enable running large ML models locally. Open-source models like CLIP and YOLO can extract semantic meaning from video frames without sending data to external APIs.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/HuaizhengZhang/Awsome-Deep-Learning-for-Video-Analysis">HuaizhengZhang/Awsome-Deep-Learning-for-Video-Analysis - GitHub</a></li>
<li><a href="https://pytorchvideo.org/">PyTorchVideo · A deep learning library for video ...</a></li>
<li><a href="https://www.edenai.co/post/top-free-video-analysis-tools-apis-and-open-source-models">Top Free Video Analysis tools, APIs, and Open Source models</a></li>

</ul>
</details>

**Discussion**: Commenters noted similar projects (e.g., Framedex) and pointed out that DaVinci Resolve 21 already has built-in AI indexing (IntelliSearch). Some discussed the practicality of processing time and file sizes, while others expressed enthusiasm for local AI video tools.

**Tags**: `#machine learning`, `#video indexing`, `#local AI`, `#GoPro`, `#M1 Max`

---

<a id="item-12"></a>
## [AI Adoption: Not Everyone Uses It Frequently](https://gabrielweinberg.com/p/people-are-consuming-ai-like-they) ⭐️ 7.0/10

Gabriel Weinberg argues that despite widespread AI hype, many people use AI infrequently, and true adoption may come from embedding AI into existing software rather than standalone chat interfaces. This analysis challenges the dominant narrative of universal AI adoption, urging a more nuanced understanding of how AI integrates into daily life and work, which could influence product development and investment strategies. The post cites a study showing over 50% of people use AI less than once per week, and suggests that embedding AI features into existing software (e.g., search, office tools) will drive broader adoption than chat interfaces alone.

hackernews · yegg · Jun 14, 14:44 · [Discussion](https://news.ycombinator.com/item?id=48527700)

**Background**: Since the launch of ChatGPT in late 2022, there has been intense hype around generative AI, with many assuming everyone is using it. However, actual usage data shows a more mixed picture, with many users trying AI occasionally but not integrating it into daily routines.

**Discussion**: Commenters largely agree with the post's thesis, sharing personal experiences of selective AI use in coding and job interviews. Some note that AI's true impact will come from integration into existing tools, while others express skepticism about its necessity in their workflows.

**Tags**: `#AI adoption`, `#LLMs`, `#software engineering`, `#technology trends`

---

<a id="item-13"></a>
## [Mapping SQLite Result Columns to Source Tables with AI](https://simonwillison.net/2026/Jun/13/sqlite-column-provenance/#atom-everything) ⭐️ 7.0/10

Simon Willison used Claude Code (Opus 4.8) to explore methods for programmatically mapping SQL query result columns back to their source table.column, enabling richer metadata in tools like Datasette. This approach could significantly enhance Datasette and similar tools by automatically providing column provenance, making SQL query results more informative and enabling features like column-level metadata display. The research explored three solutions: using the apsw library, using ctypes to call SQLite's sqlite3_column_table_name() C function, and interrogating the output of EXPLAIN. The work is part of Simon's research repository on GitHub.

rss · Simon Willison — AI工具 · Jun 13, 23:05

**Background**: Datasette is an open-source tool for exploring and publishing tabular data, allowing users to run arbitrary SQL queries. Column provenance refers to identifying which source table and column each result column originates from, which is not trivial when queries involve joins, subqueries, or CTEs.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.datasette.io/en/stable/sql_queries.html">Running SQL queries - Datasette documentation</a></li>

</ul>
</details>

**Tags**: `#SQL`, `#Datasette`, `#AI-assisted development`, `#column provenance`, `#research`

---

<a id="item-14"></a>
## [AI coding agents find files but miss critical lines, study shows](https://the-decoder.com/ai-coding-agents-find-the-right-file-but-miss-the-exact-lines-that-matter-study-shows/) ⭐️ 7.0/10

A new benchmark called SWE-Explore isolates code search from repair, revealing that AI coding agents like Claude Code and Codex reliably find the correct file but miss most of the critical lines within it. This finding highlights a fundamental limitation in current AI coding agents: without precise line-level localization, even the best repair attempts will fail, underscoring the need for improved code search capabilities before automated bug fixing can be truly effective. SWE-Explore requires agents to return a ranked list of relevant code regions within a line budget, and results show that agentic exploration outperforms traditional retrieval methods but still falls short on exact line identification.

rss · The Decoder — AI新闻 · Jun 14, 08:54

**Background**: AI coding agents are tools that use large language models to assist with software development tasks like writing, debugging, and fixing code. Traditionally, benchmarks evaluate end-to-end performance, combining code search and repair into one score, which masks weaknesses in the search phase. SWE-Explore is the first benchmark to isolate repository exploration, measuring how well agents can locate the exact lines that need changes.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2606.07297">[2606.07297] SWE-Explore: Benchmarking How Coding Agents Explore Repositories</a></li>
<li><a href="https://the-decoder.com/ai-coding-agents-find-the-right-file-but-miss-the-exact-lines-that-matter-study-shows/">AI coding agents find the right file but miss the exact lines ...</a></li>

</ul>
</details>

**Tags**: `#AI coding agents`, `#benchmark`, `#code search`, `#software engineering`

---

<a id="item-15"></a>
## [UK Considers Banning Social Media for Under-16s](https://techcrunch.com/2026/06/14/uk-may-ban-social-media-for-children-under-16/) ⭐️ 7.0/10

The UK government is reportedly considering a ban on social media for children under 16, following a similar move by Australia. If enacted, this would be one of the strictest age-based social media restrictions in the Western world, potentially reshaping how platforms design their services for younger users. The proposal is still under consideration and no specific legislation has been introduced yet. It is unclear how enforcement would work, including age verification methods.

rss · TechCrunch — 科技创投 · Jun 14, 20:17

**Background**: Social media platforms like Instagram, TikTok, and Snapchat have faced growing scrutiny over their impact on children's mental health and safety. Australia recently passed a law banning social media for children under 16, which the UK appears to be studying as a model.

**Tags**: `#social media`, `#regulation`, `#child safety`, `#UK policy`

---

<a id="item-16"></a>
## [llama.cpp b9637 Adds Cohere2MoE Parser](https://github.com/ggml-org/llama.cpp/releases/tag/b9637) ⭐️ 6.0/10

llama.cpp release b9637 introduces a dedicated parser for the Cohere2MoE (North Code) architecture, enabling chat functionality for this model family. This update expands llama.cpp's support for Mixture-of-Experts (MoE) models, specifically the Cohere2MoE architecture, making it easier for users to run these efficient models locally. The parser is part of pull request #24615 and includes renames to satisfy code review. The release also provides prebuilt binaries for multiple platforms including macOS, Linux, Windows, Android, and iOS.

github · github-actions[bot] · Jun 14, 18:50

**Background**: llama.cpp is an open-source C++ implementation for running large language models (LLMs) locally on consumer hardware. Mixture of Experts (MoE) is a technique where multiple specialized sub-models (experts) are activated selectively for each input, improving efficiency. Cohere2MoE is a specific MoE architecture from Cohere that uses a shared expert mechanism.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.vllm.ai/en/latest/api/vllm/model_executor/models/cohere2_moe/">cohere2_moe - vLLM</a></li>
<li><a href="https://en.wikipedia.org/wiki/Mixture_of_experts">Mixture of experts - Wikipedia</a></li>
<li><a href="https://www.ibm.com/think/topics/mixture-of-experts">What is mixture of experts? | IBM</a></li>

</ul>
</details>

**Tags**: `#llama.cpp`, `#machine learning`, `#open source`, `#release`

---

<a id="item-17"></a>
## [Kage: Shadow Any Website into a Single Binary for Offline Viewing](https://github.com/tamnd/kage) ⭐️ 6.0/10

Kage is a new open-source CLI tool that clones any website into a self-contained folder with JavaScript stripped out, and can optionally package the archive into a single executable binary for offline serving. This tool simplifies offline web archiving and distribution, enabling users to share entire websites as single binaries that require no dependencies, which is especially useful for areas with limited connectivity or for preserving documentation. Kage uses headless Chrome to render pages, localizes CSS, images, and fonts, and removes all JavaScript. The --format binary flag produces a standalone executable that serves the site when run, requiring no additional software on the recipient's machine.

hackernews · tamnd · Jun 14, 17:25 · [Discussion](https://news.ycombinator.com/item?id=48529990)

**Background**: Offline web archiving tools like HTTrack and SingleFile have existed for years, but they typically produce folders or single HTML files that require a browser or server to view. Kage's approach of bundling the archive with a lightweight Go server into a single binary offers a novel distribution method.

<details><summary>References</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=48529990">Show HN: Kage – Shadow any website to a single binary for offline viewing | Hacker News</a></li>
<li><a href="https://github.com/tamnd/kage">GitHub - tamnd/kage: Shadow any website for offline viewing , with...</a></li>
<li><a href="https://kage.tamnd.com/">kage</a></li>

</ul>
</details>

**Discussion**: Commenters noted practical uses like offline access to company wikis, and compared Kage to SingleFile and HTTrack. Some questioned the need for a server process, suggesting a pure HTML output would be more portable. The author's demo GIF generation tool also drew interest.

**Tags**: `#offline browsing`, `#web archiving`, `#static site`, `#CLI tool`, `#open source`

---

<a id="item-18"></a>
## [Zeroserve Boosts Caddy Performance but Lacks ACME](https://su3.io/posts/zeroserve-caddy-compat) ⭐️ 6.0/10

Zeroserve, a Rust-based io_uring HTTPS server, now supports Caddy compatibility, achieving 3x throughput and 70% lower latency compared to standard Caddy. This performance leap could make Zeroserve an attractive alternative for high-traffic websites, but the lack of ACME support limits its practicality for automatic HTTPS certificate management. Zeroserve uses Linux's io_uring interface for asynchronous I/O, which can improve performance but raises security concerns. The Caddy compatibility is partial, missing ACME and plugin support.

hackernews · losfair · Jun 14, 13:43 · [Discussion](https://news.ycombinator.com/item?id=48527145)

**Background**: Caddy is a popular web server known for its automatic HTTPS via ACME. io_uring is a Linux kernel interface for efficient asynchronous I/O, but it has been criticized for potential security risks. Zeroserve is a zero-config HTTPS server written in Rust that leverages io_uring for high performance.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/losfair/zeroserve">GitHub - losfair/zeroserve: Zero-config, fast `io_uring`-based HTTPS server. · GitHub</a></li>
<li><a href="https://su3.io/posts/introducing-zeroserve">zeroserve: a zero-config web server you can script with eBPF</a></li>
<li><a href="https://en.wikipedia.org/wiki/Io_uring">Io uring</a></li>

</ul>
</details>

**Discussion**: Community comments are mixed: some users praise the performance but many consider the lack of ACME a dealbreaker. There are also concerns about io_uring security and comparisons to Nginx, which still performs well.

**Tags**: `#web server`, `#performance`, `#Caddy`, `#io_uring`, `#Rust`

---

<a id="item-19"></a>
## [Perlisisms: Timeless Epigrams on Programming](https://www.cs.yale.edu/homes/perlis-alan/quotes.html) ⭐️ 6.0/10

A collection of 120 aphorisms by Alan Perlis, titled 'Epigrams in Programming,' originally published in 1982, continues to circulate online and spark discussion among programmers. These epigrams offer enduring insights into programming languages, software design, and the nature of computation, remaining relevant decades later as technology evolves. The collection includes famous lines such as 'A language that doesn't affect the way you think about programming, is not worth knowing' and 'A programming language is low level when its programs require attention to the irrelevant.'

hackernews · tosh · Jun 14, 14:56 · [Discussion](https://news.ycombinator.com/item?id=48527820)

**Background**: Alan Perlis was a pioneering computer scientist and the first Turing Award winner (1966). He contributed to early compilers, ALGOL, and helped establish computer science as an academic discipline. His 'Epigrams in Programming' reflect his deep experience and wit.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Alan_Perlis">Alan Perlis</a></li>

</ul>
</details>

**Discussion**: Commenters appreciated the timelessness of the quotes, with some noting their relevance to modern AI and LLMs. One user humorously misread the title as 'Perlism,' while another created a dedicated domain to display the epigrams.

**Tags**: `#programming`, `#computer science`, `#quotes`, `#history`

---