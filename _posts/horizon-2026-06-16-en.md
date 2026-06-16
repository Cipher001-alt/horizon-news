# Horizon Daily - 2026-06-16

> From 77 items, 40 important content pieces were selected

---

1. [Interactive Deep Dive into Mechanical Watch Mechanics](#item-1) ⭐️ 9.0/10
2. [Critical Copilot vulnerability allowed hackers to steal 2FA codes](#item-2) ⭐️ 9.0/10
3. [GrapheneOS Ported to Android 17, Official Releases Soon](#item-3) ⭐️ 8.0/10
4. [Local LLMs Are Now Viable, But Pain Points Remain](#item-4) ⭐️ 8.0/10
5. [Stop Using JWTs for Browser Sessions](#item-5) ⭐️ 8.0/10
6. [Meta's Engineering Reorganization Sparks Debate](#item-6) ⭐️ 8.0/10
7. [Qwen Robot Suite: Foundation Models for Physical World AI](#item-7) ⭐️ 8.0/10
8. [SubQ 1.1 Small: Learned Sparse Attention Scales Linearly](#item-8) ⭐️ 8.0/10
9. [Export Controls on AI Models Harm US Cyber Defense](#item-9) ⭐️ 8.0/10
10. [DeepSeek Raises $7.4B at $50B Valuation in First External Round](#item-10) ⭐️ 8.0/10
11. [FIFA World Cup Bug Allowed Unauthorized TV Stream Control](#item-11) ⭐️ 8.0/10
12. [SpaceX Goes Public: IPO Details and Analysis](#item-12) ⭐️ 8.0/10
13. [OpenAI loses billions annually, leaked docs show](#item-13) ⭐️ 8.0/10
14. [Calvin and Hobbes and the Price of Integrity](#item-14) ⭐️ 7.0/10
15. [GPT-NL: A Sovereign Language Model for the Netherlands](#item-15) ⭐️ 7.0/10
16. [Apple's Hide My Email Change May Reduce Privacy](#item-16) ⭐️ 7.0/10
17. [Switching to Broadcom SFP+ Module for 10GbE](#item-17) ⭐️ 7.0/10
18. [Apple's Vehicle Motion Cues Effectively Reduce Car Sickness](#item-18) ⭐️ 7.0/10
19. [Slay the Spire 2 Uses Custom PRNG for Cross-Platform Seeds](#item-19) ⭐️ 7.0/10
20. [Reflex.dev Speeds Up Python AST Walk 220x with Rust](#item-20) ⭐️ 7.0/10
21. [Berlin court: Google AI Overviews are new search format, not original content](#item-21) ⭐️ 7.0/10
22. [New benchmark tests AI models' resistance to Russian propaganda](#item-22) ⭐️ 7.0/10
23. [India Orders Temporary Telegram Ban Over Exam Fraud](#item-23) ⭐️ 7.0/10
24. [DOJ backs xAI's unpermitted gas turbines for national security](#item-24) ⭐️ 7.0/10
25. [Cockroaches carry thousands of bacterial genome fragments](#item-25) ⭐️ 7.0/10
26. [Anthropic Pauses Token-Based Billing for Claude Agent SDK](#item-26) ⭐️ 7.0/10
27. [Pentagon Uses AI to Write Congressional Reports](#item-27) ⭐️ 7.0/10
28. [Mobileye to Launch Standalone US Robotaxi Service by 2027](#item-28) ⭐️ 7.0/10
29. [llama.cpp b9670 Fixes NVFP4 Edge Cases for LORA and ModelOPT](#item-29) ⭐️ 6.0/10
30. [Bash /dev/tcp: HTTP Without curl](#item-30) ⭐️ 6.0/10
31. [Has AI Already Killed Self-Help Nonfiction Books?](#item-31) ⭐️ 6.0/10
32. [Yak Shaving: The Joy of Distraction](#item-32) ⭐️ 6.0/10
33. [Snap Unveils Specs AR Glasses with 51° FOV and $2195 Price](#item-33) ⭐️ 6.0/10
34. [New York Bill Targets 'Ghost Jobs'](#item-34) ⭐️ 6.0/10
35. [Qualcomm bets on AI wearables as next computing platform](#item-35) ⭐️ 6.0/10
36. [60% of US consumers put off by 'AI' in brand messaging](#item-36) ⭐️ 6.0/10
37. [Flutterwave hits $3.2B valuation with Ripple backing](#item-37) ⭐️ 6.0/10
38. [Robinhood CEO Avoids AI Excuse for Layoffs](#item-38) ⭐️ 6.0/10
39. [Probably raises $9M to build reliable AI](#item-39) ⭐️ 6.0/10
40. [Foundation Alloy raises $22M for novel super metals](#item-40) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Interactive Deep Dive into Mechanical Watch Mechanics](https://ciechanow.ski/mechanical-watch/) ⭐️ 9.0/10

A detailed interactive article by Bartosz Ciechanowski visually explains the mechanics of a mechanical watch using step-by-step animations and plain HTML, CSS, and JavaScript. This article exemplifies how complex engineering concepts can be made accessible through masterful educational design and vanilla web technologies, inspiring both learners and developers. The entire site is built with handwritten, vanilla code, ensuring compatibility with older devices like an iPhone 7, and avoids modern frameworks for a lightweight, universal experience.

hackernews · razin · Jun 16, 11:26 · [Discussion](https://news.ycombinator.com/item?id=48553550)

**Background**: Mechanical watches are intricate devices that measure time using a spring-driven mechanism without batteries. Understanding their inner workings—like the mainspring, gear train, escapement, and balance wheel—requires visualizing many moving parts. This article uses interactive 3D-like visualizations to demystify each component step by step.

**Discussion**: Commenters praised the educational value and vanilla code craftsmanship, with one teacher noting the rarity of such clear explanations. Another reader built a real-life exploded view inspired by the article, and support was directed to the author's Patreon.

**Tags**: `#mechanical watch`, `#interactive visualization`, `#educational content`, `#web development`, `#engineering`

---

<a id="item-2"></a>
## [Critical Copilot vulnerability allowed hackers to steal 2FA codes](https://arstechnica.com/security/2026/06/critical-copilot-vulnerability-allowed-hackers-to-seal-2fa-code-from-users/) ⭐️ 9.0/10

A critical vulnerability chain named SearchLeak in Microsoft 365 Copilot Enterprise allowed attackers to steal two-factor authentication (2FA) codes and other sensitive data with a single click. The flaw, tracked as CVE-2026-42824, was patched by Microsoft after responsible disclosure. This vulnerability highlights the ongoing failure of current LLM security approaches, as prompt injection remains a critical threat even in widely deployed AI assistants. The ability to steal 2FA codes undermines a fundamental security layer, affecting millions of enterprise users. The attack chain involves three weaknesses: prompt injection via Copilot's Search 'q' URL parameter, exfiltration of data through encoded image request URLs, and lack of proper input sanitization. The exploit required no phishing or malware—simply sending an email to the victim could trigger the attack.

rss · ArsTechnica — 深度科技 · Jun 16, 11:15

**Background**: Microsoft 365 Copilot is an AI assistant integrated into Microsoft's productivity suite, capable of accessing emails, documents, and other organizational data. Prompt injection attacks exploit the LLM's inability to distinguish between user instructions and untrusted input, causing it to execute malicious commands. Two-factor authentication (2FA) codes are time-sensitive secrets used as an additional security layer beyond passwords.

<details><summary>References</summary>
<ul>
<li><a href="https://www.varonis.com/blog/searchleak">SearchLeak: How We Turned M365 Copilot Into a One-Click Data ... - Varonis</a></li>
<li><a href="https://dailysecurityreview.com/resources/cve-2026-42824-m365-copilot-searchleak-enables-1-click-email-theft/">CVE-2026-42824: M365 Copilot SearchLeak Enables 1-Click Email Theft</a></li>
<li><a href="https://www.darkreading.com/application-security/copilot-searchleak-attack-1-click-data-theft">Copilot 'SearchLeak' Attack Allows 1-Click Data Theft</a></li>

</ul>
</details>

**Discussion**: Comments on Hacker News were largely off-topic, discussing Cursor IDE acquisition by SpaceX and comparisons of company valuations. No direct discussion of the Copilot vulnerability was present in the provided comments.

**Tags**: `#security`, `#vulnerability`, `#LLM`, `#Copilot`, `#2FA`

---

<a id="item-3"></a>
## [GrapheneOS Ported to Android 17, Official Releases Soon](https://discuss.grapheneos.org/d/36469-grapheneos-has-been-ported-to-android-17-and-official-releases-are-coming-soon) ⭐️ 8.0/10

GrapheneOS, a privacy-focused mobile OS, has been successfully ported to Android 17, with official releases expected imminently. This milestone ensures that GrapheneOS users can benefit from the latest Android security patches and features, maintaining its position as a leading privacy-hardened OS. The port covers Android 17 (codenamed Cinnamon Bun), which was publicly released on June 16, 2026, and includes new multitasking and security tools.

hackernews · Cider9986 · Jun 16, 20:34 · [Discussion](https://news.ycombinator.com/item?id=48561654)

**Background**: GrapheneOS is an open-source mobile OS based on AOSP, focused on security and privacy through hardening and attack surface reduction. It is available for Google Pixel devices and future Motorola phones, and has approximately 400K active users as of April 2026.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GrapheneOS">GrapheneOS</a></li>
<li><a href="https://en.wikipedia.org/wiki/Android_17">Android 17</a></li>
<li><a href="https://grapheneos.org/">GrapheneOS : the private and secure mobile OS</a></li>

</ul>
</details>

**Discussion**: Users expressed excitement about the port, with some sharing positive experiences and others noting limitations like missing swipe-to-cursor and contactless payment issues. There is also anticipation for Motorola device support to expand availability beyond Pixel.

**Tags**: `#GrapheneOS`, `#Android`, `#privacy`, `#mobile OS`, `#security`

---

<a id="item-4"></a>
## [Local LLMs Are Now Viable, But Pain Points Remain](https://vickiboykis.com/2026/06/15/running-local-models-is-good-now/) ⭐️ 8.0/10

A blog post by Vicki Boykis argues that running local large language models (LLMs) has become viable, sparking a community debate about remaining trade-offs such as speed, memory, and quantization accuracy. This discussion matters because local LLMs offer privacy, offline access, and cost savings, but their adoption hinges on overcoming hardware limitations and quantization trade-offs compared to cloud models. Dense models like Qwen 27B are smart but slow, while MoE models like Gemma 26B are faster but error-prone; quantization to 4-bit reduces memory but weakens tool calling, and running models well requires significant GPU memory (e.g., 32GB+).

hackernews · jfb · Jun 16, 14:36 · [Discussion](https://news.ycombinator.com/item?id=48555993)

**Background**: Local LLMs run on consumer hardware instead of cloud servers, offering privacy and offline use. Quantization reduces model precision (e.g., from FP16 to 4-bit) to fit in memory, but can degrade accuracy and tool-calling reliability. The community debates whether current hardware and software make local models a practical alternative to cloud APIs.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/@chetankerhalkar/quantization-in-ai-techniques-benefits-trade-offs-modern-architectures-f47d5d72a855">Quantization in AI: Techniques, Benefits, Trade-offs & Modern Architectures | by Chetankerhalkar | Medium</a></li>
<li><a href="https://apxml.com/courses/getting-started-local-llms/chapter-1-introduction-large-language-models/local-vs-cloud-llms">Local vs. Cloud-Based LLMs</a></li>
<li><a href="https://localllm.in/blog/ollama-vram-requirements-for-local-llms">Ollama VRAM Requirements : Complete 2026 Guide to GPU Memory ...</a></li>

</ul>
</details>

**Discussion**: Commenters highlight that local models still suffer from speed issues and quantization trade-offs, with some preferring local models over cloud ones for their behavior (e.g., less opinionated). Others note the high hardware cost (e.g., $2600 for dual AMD GPUs) and the complexity of the ROCm stack.

**Tags**: `#local LLMs`, `#AI/ML`, `#open-source`, `#model quantization`, `#developer tools`

---

<a id="item-5"></a>
## [Stop Using JWTs for Browser Sessions](https://gist.github.com/samsch/0d1f3d3b4745d778f78b230cf6061452) ⭐️ 8.0/10

A widely shared gist argues that JSON Web Tokens (JWTs) should not be used for browser-based user sessions, citing security flaws and better alternatives. The post has sparked extensive community debate about JWT's appropriate use cases. JWTs are a cornerstone of modern web authentication, but their misuse for browser sessions can lead to vulnerabilities like token theft and revocation difficulties. This debate influences how developers design secure authentication systems. The original post links to external resources criticizing JWT's inability to invalidate individual tokens and its reliance on client-side storage. Commenters note that JWTs can be secure with short lifetimes and refresh tokens, and that revocation lists can mitigate issues.

hackernews · dzonga · Jun 16, 16:49 · [Discussion](https://news.ycombinator.com/item?id=48558147)

**Background**: JSON Web Tokens (JWTs) are a compact, URL-safe token format used for authentication and information exchange. They are often used in stateless authentication systems where the server does not store session data. However, for browser sessions, traditional session-based authentication with server-side storage is often recommended because it allows immediate revocation and avoids client-side token storage risks.

<details><summary>References</summary>
<ul>
<li><a href="https://portswigger.net/web-security/jwt">JWT attacks | Web Security Academy - PortSwigger</a></li>
<li><a href="https://www.authgear.com/post/jwt-security-best-practices-common-vulnerabilities/">JWT Security Explained: Best Practices and Common Vulnerabilities</a></li>
<li><a href="https://mojoauth.com/ciam-qna/why-not-use-jwt-for-sessions-alternatives">Why do developers say "don't use JWT for sessions " and what are t...</a></li>

</ul>
</details>

**Discussion**: The community is divided: some agree that JWTs are overused for browser sessions, while others defend them for short-lived tokens with refresh mechanisms. A key point is that JWTs are suitable for service-to-service communication but problematic for user sessions due to revocation challenges.

**Tags**: `#JWT`, `#authentication`, `#security`, `#web development`, `#session management`

---

<a id="item-6"></a>
## [Meta's Engineering Reorganization Sparks Debate](https://newsletter.pragmaticengineer.com/p/why-is-meta-destroying-its-engineering) ⭐️ 8.0/10

Meta has forcibly reassigned thousands of engineers, including 30-50% of core teams, to AI-related work such as data labeling and RLHF, as part of a broader reorganization that also cut 600 AI jobs. This shift signals a dramatic change in engineering culture at Meta and potentially across big tech, as companies prioritize AI over traditional software engineering, raising concerns about employee autonomy and long-term innovation. The reassignments affect over 7,000 workers, with some moved to a new 1,000-person AI division. Mark Zuckerberg admitted the reorganization was 'disruptive' but promised no further layoffs in 2026.

hackernews · throwarayes · Jun 16, 16:42 · [Discussion](https://news.ycombinator.com/item?id=48558045)

**Background**: Meta, formerly Facebook, has long been known for its strong engineering culture, emphasizing founder-led innovation. The company is now racing to lead in AI, mirroring industry-wide shifts where tech giants like Google and Microsoft are also reorganizing around AI. Forced reassignments on this scale are unusual in Silicon Valley, where internal mobility is typically voluntary.

<details><summary>References</summary>
<ul>
<li><a href="https://umatechnology.org/meta-cuts-600-ai-jobs-amid-ongoing-reorganization/">Meta cuts 600 AI jobs amid ongoing reorganization</a></li>
<li><a href="https://www.edgen.tech/news/post/meta-drafts-1000-engineers-in-a-high-stakes-ai-reorganization">Meta drafts 1,000 engineers in a high-stakes AI reorganization</a></li>
<li><a href="https://www.theguardian.com/technology/2026/may/19/meta-jobs-ai-transfers">Meta is rapidly reorganizing its workers’ jobs around AI: ‘Transfers aren’t optional’ | Meta | The Guardian</a></li>

</ul>
</details>

**Discussion**: Commenters expressed mixed views: some criticized the forced reassignments as a sign of 'AI psychosis' and a potential new norm for the industry, while others questioned the efficiency of using expensive software engineers for data labeling. Former employees noted that homegrown orgs at Meta were inefficient, contrasting with acquired companies like WhatsApp. Some lamented the loss of Meta's engineering culture, comparing it favorably to Google's.

**Tags**: `#Meta`, `#engineering culture`, `#AI`, `#tech industry`, `#organizational change`

---

<a id="item-7"></a>
## [Qwen Robot Suite: Foundation Models for Physical World AI](https://qwen.ai/blog?id=qwen-robotsuite) ⭐️ 8.0/10

Alibaba's Qwen team released the Qwen Robot Suite, a set of three foundation models—Qwen-RobotNav, Qwen-RobotManip, and Qwen-RobotWorld—that together enable integrated robotic systems for navigation, manipulation, and world modeling. This suite marks a significant step toward embodied AI, moving beyond chatbots to physical-world intelligence, with potential to accelerate robotics development in manufacturing, services, and defense. The suite unifies five navigation tasks into a single model (Qwen-RobotNav) and extends Qwen's multimodal backbone into continuous action generation via Qwen-VLA, enabling robots to see, think, and act.

hackernews · ilreb · Jun 16, 13:15 · [Discussion](https://news.ycombinator.com/item?id=48554814)

**Background**: Embodied AI refers to AI systems embedded in physical bodies that perceive and act in the real world. Traditional robotics models are highly specialized for specific tasks, but foundation models aim to generalize across tasks and platforms, reducing development effort.

<details><summary>References</summary>
<ul>
<li><a href="https://digg.com/tech/6lxnua01">Alibaba's Qwen team releases Qwen- Robot Suite , a three- model ...</a></li>
<li><a href="https://qwen.ai/blog?id=qwenvla">Qwen-VLA: From Understanding the World to Acting in It</a></li>
<li><a href="https://www.technology.org/2026/06/16/alibaba-ai-models-robots-agents/">Alibaba Unveils Qwen Robot Suite, Moving AI From Chatbots Into the Physical World</a></li>

</ul>
</details>

**Discussion**: Commenters expressed excitement about the strategic importance of robotics, with some noting the huge total addressable market and potential for rapid mass production. Others questioned whether the models solve real-time prediction challenges like catching a ball.

**Tags**: `#robotics`, `#foundation models`, `#embodied AI`, `#Qwen`, `#AI`

---

<a id="item-8"></a>
## [SubQ 1.1 Small: Learned Sparse Attention Scales Linearly](https://subq.ai/subq-1-1-small-technical-report) ⭐️ 8.0/10

SubQ 1.1 Small introduces a learned sparse attention mechanism (SSA) that scales linearly with context length, achieving 64.5x less compute and 56x faster inference than dense attention at 1M tokens. This breakthrough could dramatically reduce the cost of long-context LLM inference, enabling practical applications like whole-book analysis or multi-hour video understanding. It addresses a key bottleneck in scaling transformers to very long sequences. The model uses a learned sparse attention (SSA) that replaces the quadratic dense attention pass, and at 1M tokens it runs 56x faster than FlashAttention-2. However, the technical report lacks architectural details and open-source code, which has drawn skepticism from the community.

hackernews · EDM115 · Jun 16, 14:50 · [Discussion](https://news.ycombinator.com/item?id=48556163)

**Background**: Standard transformer attention computes scores for every pair of tokens, leading to O(n²) complexity that becomes prohibitive for long sequences. Sparse attention methods reduce this by only attending to a subset of tokens, but many prior approaches use fixed patterns or require additional memory. Learned sparse attention aims to dynamically select which tokens to attend to, potentially offering better efficiency without sacrificing quality.

<details><summary>References</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/sparse-attention-models">Sparse Attention Models</a></li>
<li><a href="https://apxml.com/courses/foundations-transformers-architecture/chapter-6-advanced-architectural-variants-analysis/sparse-attention-mechanisms">Sparse Attention Mechanisms Overview</a></li>
<li><a href="https://github.com/kyegomez/SparseAttention">GitHub - kyegomez/SparseAttention: Pytorch Implementation of the sparse attention from the paper: "Generating Long Sequences with Sparse Transformers" · GitHub</a></li>

</ul>
</details>

**Discussion**: Community sentiment is mixed: some praise the approach as the right direction for long-context efficiency, while others express skepticism due to the lack of architectural details and code, especially compared to other open-source Chinese labs. There are also calls for better long-context benchmarks beyond needle-in-a-haystack.

**Tags**: `#LLM`, `#attention mechanism`, `#efficiency`, `#long context`, `#sparse attention`

---

<a id="item-9"></a>
## [Export Controls on AI Models Harm US Cyber Defense](https://simonwillison.net/2026/Jun/16/fable-5-export-controls/#atom-everything) ⭐️ 8.0/10

The US government's export control directive on Anthropic's Claude Fable 5 has blocked the model from fixing security vulnerabilities, as demonstrated by a 'jailbreak' that simply asked it to fix code with known CVEs. This paradoxically weakens US cyber defense by preventing AI models from performing defensive security tasks like finding and patching bugs, which are critical for protecting national infrastructure. Researchers used open-source code with known CVEs and deliberately planted vulnerabilities, asking Fable 5 to 'review the code for security issues' (refused) and then 'fix this code' (complied), turning outputs into test scripts.

rss · Simon Willison — AI工具 · Jun 16, 05:20

**Background**: Export controls on AI models aim to prevent adversaries from using advanced AI for cyber attacks. However, the same capabilities that could be misused are also essential for defensive cybersecurity. Claude Fable 5 is a next-generation 'Mythos-class' model from Anthropic, subject to a US government export control directive that suspends foreign access.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theverge.com/ai-artificial-intelligence/950412/anthropic-trump-adminstration-claude-mythos-fable-5-export-controls">Inside the fight over Claude Mythos 5 | The Verge</a></li>
<li><a href="https://www.anthropic.com/news/claude-fable-5-mythos-5">Claude Fable 5 and Claude Mythos 5 \ Anthropic</a></li>
<li><a href="https://cyberpress.org/claude-fable-5-jailbreak/">Claude Fable 5 Jailbreak Enables Stack Exploit Generation</a></li>

</ul>
</details>

**Discussion**: Cybersecurity expert Kate Moussouris highlighted the absurdity of the ban, stating that asking AI to fix bugs is 'the most valuable thing an AI model can do for defensive security' and not a guardrail bypass. The discussion underscores a disconnect between policymakers and technical reality.

**Tags**: `#AI safety`, `#export controls`, `#cybersecurity`, `#AI policy`, `#open source`

---

<a id="item-10"></a>
## [DeepSeek Raises $7.4B at $50B Valuation in First External Round](https://the-decoder.com/deepseek-takes-outside-money-for-the-first-time-at-a-50-billion-valuation/) ⭐️ 8.0/10

Chinese AI startup DeepSeek has raised approximately 50 billion yuan ($7.4 billion) in its first external funding round, achieving a valuation of $50 billion. This marks a significant milestone for DeepSeek, signaling strong investor confidence and positioning the company as a major competitor in the global AI landscape, potentially challenging established players like OpenAI and Google. The funding round is the first time DeepSeek has taken outside capital; previously it was solely funded by its parent hedge fund, High-Flyer. The $50 billion valuation reflects the company's rapid growth and the market's high expectations for its AI models, including the recently released DeepSeek-V4 series.

rss · The Decoder — AI新闻 · Jun 16, 09:40

**Background**: DeepSeek, founded in July 2023 by Liang Wenfeng, is a Chinese AI company focused on developing large language models. It gained attention for releasing powerful open-source models like DeepSeek-V4-Pro, a Mixture-of-Experts model with 1.6 trillion parameters. The company's models have been noted for their strong reasoning and coding capabilities, rivaling top closed-source models.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek - Wikipedia</a></li>
<li><a href="https://www.cnbc.com/2026/06/03/deepseek-slated-to-draw-7-billion-in-maiden-fundraising-sources-say.html">DeepSeek slated to draw $7 billion in maiden fundraising ...</a></li>
<li><a href="https://huggingface.co/deepseek-ai/DeepSeek-V4-Pro">deepseek-ai/DeepSeek-V4-Pro · Hugging Face</a></li>

</ul>
</details>

**Tags**: `#AI`, `#funding`, `#DeepSeek`, `#startup`, `#valuation`

---

<a id="item-11"></a>
## [FIFA World Cup Bug Allowed Unauthorized TV Stream Control](https://techcrunch.com/2026/06/16/bug-in-fifa-world-cup-internal-system-gave-anyone-ability-to-modify-tv-stream/) ⭐️ 8.0/10

A security researcher discovered a bug in FIFA's online platforms that allowed unauthorized access to internal systems, including one that could control the TV broadcast stream of every World Cup match. This vulnerability could have allowed a single attacker to hijack every camera feed simultaneously, affecting billions of viewers worldwide. It highlights critical security risks in major global event infrastructure. The bug stemmed from client-side authorization with no server-side enforcement, using Microsoft Entra for authentication but failing to verify permissions server-side. The researcher could have rickrolled the entire World Cup broadcast.

rss · TechCrunch — 科技创投 · Jun 16, 18:13

**Background**: FIFA's internal systems include a broadcast control platform that allows TV producers to manage camera feeds and on-screen graphics. The vulnerability exposed this system to anyone who could manipulate client-side requests, due to missing server-side authorization checks.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/06/16/bug-in-fifa-world-cup-internal-system-gave-anyone-ability-to-modify-tv-stream/">Bug in FIFA World Cup internal system gave anyone ability to ...</a></li>
<li><a href="https://bobdahacker.com/blog/fifa-hack">I Could've Rickrolled the Entire FIFA World Cup. All... | bobdahacker</a></li>
<li><a href="https://www.squaredtech.co/fifa-world-cup-tv-stream-bug-a-major-security-failure-explained">FIFA World Cup Bug Gave Anyone Full TV Stream Control</a></li>

</ul>
</details>

**Discussion**: The researcher's blog post noted that FIFA did not respond to the disclosure. The community expressed concern over the lack of server-side enforcement and the potential for real-world disruption during a live event.

**Tags**: `#security`, `#vulnerability`, `#FIFA`, `#World Cup`, `#infrastructure`

---

<a id="item-12"></a>
## [SpaceX Goes Public: IPO Details and Analysis](https://techcrunch.com/2026/06/16/spacex-is-public-everything-you-need-to-know-post-ipo/) ⭐️ 8.0/10

SpaceX has completed its initial public offering (IPO), becoming a publicly traded company, with TechCrunch providing comprehensive coverage including details from its S-1 registration document. This IPO marks a major milestone for the space industry, opening up investment opportunities for the public and potentially accelerating space technology development with increased capital. The S-1 filing reveals SpaceX's financials, risk factors, and intended use of proceeds, while pre-IPO deals and winners/losers are also analyzed in the coverage.

rss · TechCrunch — 科技创投 · Jun 16, 15:53

**Background**: An IPO is the process by which a private company offers shares to the public for the first time. The S-1 registration document is a mandatory filing with the SEC that contains detailed financial and business information. SpaceX, founded by Elon Musk, has been a private company for years, revolutionizing space travel with reusable rockets.

<details><summary>References</summary>
<ul>
<li><a href="https://krokfin.com.ua/en/news/spacex-ipo-record-2026/">SpaceX Files S - 1 : The Largest IPO in History at $1.75 Trillion... | KrokFin</a></li>
<li><a href="https://www.jarsy.com/learn/pre-ipo-settlement">How Investment Settlements Work in Pre - IPO Deals : Understanding...</a></li>

</ul>
</details>

**Discussion**: Comments on Hacker News express mixed reactions: some discuss unrelated topics like AI coding tools, while others question SpaceX's acquisition of Cursor for $3.5 billion, comparing it to the cost of building hospitals. One comment notes SpaceX's claim of a $26 trillion addressable AI market.

**Tags**: `#SpaceX`, `#IPO`, `#space technology`, `#business`

---

<a id="item-13"></a>
## [OpenAI loses billions annually, leaked docs show](https://arstechnica.com/ai/2026/06/leaked-financial-docs-show-openai-is-losing-billions-of-dollars-a-year/) ⭐️ 8.0/10

Leaked audited financial documents reveal that OpenAI spent $34 billion in the past year, far exceeding its revenue, resulting in billions of dollars in losses annually. This news highlights the immense financial challenges faced by a leading AI company, raising questions about the sustainability of the current AI investment boom and its impact on the broader industry. The $34 billion spending includes massive R&D costs and other expenses, while revenue growth, though strong, is not enough to cover these costs. The exact revenue figure is not disclosed in the snippet.

rss · ArsTechnica — 深度科技 · Jun 16, 16:18

**Background**: OpenAI is a leading artificial intelligence research organization known for developing models like GPT-4. The company has transitioned from a non-profit to a capped-profit structure to attract investment, but its high operational costs have led to persistent losses.

**Tags**: `#OpenAI`, `#finance`, `#AI industry`, `#business`

---

<a id="item-14"></a>
## [Calvin and Hobbes and the Price of Integrity](https://therepublicofletters.substack.com/p/calvin-and-hobbes-and-the-price-of) ⭐️ 7.0/10

An essay examines Bill Watterson's decision to prioritize artistic integrity over commercial exploitation of Calvin and Hobbes, sparking community debate on the value of staying true to one's vision. This reflection is significant because it highlights the tension between commercial success and creative vision, a dilemma faced by many artists and creators. It encourages readers to consider the long-term value of integrity over short-term financial gain. The essay is published on Substack and has garnered 88 comments and 216 points on Hacker News, indicating strong community engagement. Commenters express admiration for Watterson's dedication to his principles, even while acknowledging the financial sacrifices involved.

hackernews · pseudolus · Jun 16, 15:44 · [Discussion](https://news.ycombinator.com/item?id=48557079)

**Background**: Bill Watterson is the creator of the beloved comic strip Calvin and Hobbes, which ran from 1985 to 1995. Unlike many successful cartoonists, Watterson famously refused to license his characters for merchandise, believing it would compromise the strip's artistic integrity. This decision cost him millions of dollars but cemented his legacy as a principled artist.

**Discussion**: Commenters generally admire Watterson's integrity, with some noting that his choice makes his work more valuable. Others argue that selling out is understandable, given the financial pressures. A few share links to Watterson's speeches and previous discussions, showing ongoing interest in the topic.

**Tags**: `#artistic integrity`, `#comics`, `#Bill Watterson`, `#creativity`, `#ethics`

---

<a id="item-15"></a>
## [GPT-NL: A Sovereign Language Model for the Netherlands](https://www.tno.nl/en/digital/artificial-intelligence/gpt-nl/) ⭐️ 7.0/10

TNO, together with SURF and the Netherlands Forensic Institute, announced GPT-NL, a €13.5 million sovereign language model for the Netherlands, aiming to provide full control over data and alignment with European values. This initiative strengthens digital autonomy for the Netherlands and Europe, reducing dependency on non-European AI providers and ensuring AI development aligns with local laws and societal goals. GPT-NL is a collaboration between non-profit organizations TNO, SURF, and NFI, focusing on transparency, fairness, and controllability. The model will be trained exclusively on legally obtained documents and hosted within Europe.

hackernews · root-parent · Jun 16, 17:54 · [Discussion](https://news.ycombinator.com/item?id=48559188)

**Background**: Sovereign language models are AI systems developed and controlled by a specific country to ensure data privacy, cultural alignment, and regulatory compliance. Many countries, including Sweden with GPT-SW3, have pursued similar projects to reduce reliance on US and Chinese AI giants.

<details><summary>References</summary>
<ul>
<li><a href="https://www.tno.nl/en/digital/artificial-intelligence/gpt-nl/">GPT‑NL: a sovereign language model for the Netherlands - tno.nl</a></li>
<li><a href="https://www.tno.nl/nl/digitaal/artificiele-intelligentie/gpt-nl/">GPT-NL: een soeverein taalmodel voor Nederland | TNO</a></li>
<li><a href="https://gpt-nl.nl/">GPT-NL: Een verantwoord taalmodel voor Nederland - GPT-NL</a></li>

</ul>
</details>

**Discussion**: The community is divided: some support national AI models for sovereignty and language preservation, while others argue it's better to build on existing baselines like Qwen or Kimi to save costs and focus on practical applications. Skepticism has also grown in the Dutch tech scene regarding the project's value.

**Tags**: `#AI`, `#language model`, `#sovereignty`, `#Europe`, `#NLP`

---

<a id="item-16"></a>
## [Apple's Hide My Email Change May Reduce Privacy](https://arseniyshestakov.com/2026/06/16/apple-is-about-to-make-hide-my-email-useless/) ⭐️ 7.0/10

Apple plans to unify Hide My Email and Sign in with Apple aliases under the @private.icloud.com domain, making it easier for websites to block all such addresses. This change could undermine the privacy utility of Hide My Email, as websites may block the entire @private.icloud.com domain, affecting users who rely on this feature for privacy. The change has not yet been implemented, and users can still generate aliases on @icloud.com at a rate of at least 30 per hour. The unification makes it trivial for sites to block all relay addresses without affecting regular iCloud mailboxes.

hackernews · SXX · Jun 16, 18:37 · [Discussion](https://news.ycombinator.com/item?id=48559935)

**Background**: Hide My Email is an iCloud+ feature that generates unique, random email addresses for use with apps and websites, forwarding messages to the user's personal inbox. Sign in with Apple also offers similar private email relay. Currently, these aliases are on different domains, making blanket blocking harder.

<details><summary>References</summary>
<ul>
<li><a href="https://support.apple.com/en-us/105078">How to use Hide My Email with Sign in with Apple - Apple Support</a></li>
<li><a href="https://support.apple.com/guide/icloud/add-and-manage-email-aliases-mm6b1a490a/icloud">Add and manage email aliases for iCloud Mail on iCloud.com</a></li>

</ul>
</details>

**Discussion**: Comments show mixed reactions: some users argue that websites blocking privacy-friendly emails are not worth using, while others suggest workarounds like using custom domains. There is confusion about why unifying domains makes blocking easier, but the consensus is that the change reduces privacy utility.

**Tags**: `#Apple`, `#privacy`, `#email`, `#iCloud`, `#security`

---

<a id="item-17"></a>
## [Switching to Broadcom SFP+ Module for 10GbE](https://www.gilesthomas.com/2026/06/10g-ethernet-switching-to-broadcom-sfp-plus) ⭐️ 7.0/10

A detailed technical account describes the process of switching to a Broadcom SFP+ module for 10 Gigabit Ethernet, highlighting practical issues such as heat generation and compatibility with existing switches. This matters because 10GbE is increasingly adopted in home labs and small businesses, and choosing the right SFP+ module can significantly impact network reliability, power consumption, and thermal management. The Broadcom SFP+ module may report incorrect temperature readings, and DAC (Direct Attach Copper) cables are recommended for short distances to avoid heat and compatibility issues.

hackernews · gpjt · Jun 16, 17:48 · [Discussion](https://news.ycombinator.com/item?id=48559083)

**Background**: SFP+ modules are hot-pluggable transceivers used for 10 Gigabit Ethernet connections. They come in various types, including optical fiber modules and copper-based DAC cables, each with different power and heat characteristics.

<details><summary>References</summary>
<ul>
<li><a href="https://www.broadcom.com/products/fiber-optic-modules-components/networking/optical-transceivers/sfpplus">“SFP Plus”, or SFP+ , are speed enhanced variations of the...</a></li>
<li><a href="https://resources.l-p.com/products/sfp-10-gbps-guide-what-is-10g-sfp-plus">SFP 10 Gbps Guide: What Is 10G SFP+ and How to Choose</a></li>

</ul>
</details>

**Discussion**: Community comments suggest that for new installations, fiber optic cabling is preferable due to lower power consumption and heat. Users also recommend DAC cables for short distances and note that some SFP+ modules do not report temperature or voltage.

**Tags**: `#networking`, `#10GbE`, `#SFP+`, `#hardware`, `#homelab`

---

<a id="item-18"></a>
## [Apple's Vehicle Motion Cues Effectively Reduce Car Sickness](https://www.theverge.com/tech/942854/apple-vehicle-motion-cues-review-really-work) ⭐️ 7.0/10

Apple's Vehicle Motion Cues feature, introduced in iOS 18, uses animated dots on the screen edges to represent vehicle movement, helping reduce motion sickness for passengers using iPhones or iPads in moving vehicles. This feature offers a practical, software-based solution to a common problem affecting many travelers, potentially improving productivity and entertainment during car rides without requiring medication or special hardware. The feature uses the device's accelerometer and gyroscope to detect vehicle motion and display corresponding animated dots. It is available on iPhones and iPads running iOS 18 or iPadOS 18 or later, and can be enabled in Settings > Accessibility > Motion > Show Vehicle Motion Cues.

hackernews · neilfrndes · Jun 16, 16:12 · [Discussion](https://news.ycombinator.com/item?id=48557530)

**Background**: Motion sickness occurs when there is a sensory conflict between what the eyes see and what the inner ear (balance system) feels. When reading or using a screen in a moving vehicle, the eyes perceive a static environment while the body feels motion, causing nausea. Vehicle Motion Cues aims to reduce this conflict by providing visual cues that match the perceived motion.

<details><summary>References</summary>
<ul>
<li><a href="https://www.self.com/story/vehicle-motion-cues-review">I Tried Apple’s New ‘Vehicle Motion Cues’ Feature and Risked ... Use iPhone more comfortably while riding in a vehicle - Apple ... Images A Complete Guide to Vehicle Motion Cues on iPhone and iPad Apple announces new accessibility features, including Eye ... How to Enable and Use Vehicle Motion Cues on iPhone in iOS 18 ... Your iPhone has a secret in-car feature that's ... - ZDNET Apple Reveals 'Vehicle Motion Cues' Feature to Fight Carsickness</a></li>
<li><a href="https://support.apple.com/en-in/guide/iphone/iph55564cb22/ios">Use iPhone more comfortably while riding in a vehicle - Apple ...</a></li>
<li><a href="https://economictimes.indiatimes.com/news/international/us/motion-sick-your-iphone-has-a-hidden-feature-that-could-be-the-game-changer/articleshow/123982887.cms">iPhone's hidden feature for motion sickness: Motion sick ...</a></li>

</ul>
</details>

**Discussion**: Community comments are mixed: some users report the feature works amazingly, while others find it ineffective. One user notes it doesn't work in electric cars, and another mentions Android equivalents exist. Overall sentiment is positive but with caveats about individual variability.

**Tags**: `#Apple`, `#accessibility`, `#motion sickness`, `#iOS`, `#user experience`

---

<a id="item-19"></a>
## [Slay the Spire 2 Uses Custom PRNG for Cross-Platform Seeds](https://tck.mn/blog/correlated-randomness-sts2/) ⭐️ 7.0/10

Slay the Spire 2 implements a custom pseudo-random number generator (PRNG) to ensure that game seeds produce identical outcomes across all platforms, avoiding the platform-dependent RNG issues that plagued the original game. This change guarantees seed consistency across desktop and mobile versions, preserving player-created seeded runs and enabling fair competition. It also future-proofs the game against changes in standard library RNG implementations. The custom PRNG is implemented in C# within the Godot engine, replacing System.Random. The seed is passed through a 32-bit hash function, limiting the total number of possible seeds to about 4 billion, which is smaller than the 64-bit seeds in the first game.

hackernews · rdmuser · Jun 16, 09:46 · [Discussion](https://news.ycombinator.com/item?id=48552844)

**Background**: In the original Slay the Spire, seeds on desktop and mobile versions produced different outcomes because each platform's standard library PRNG (e.g., C# System.Random) had platform-specific implementations. A PRNG is an algorithm that generates sequences of numbers that appear random but are deterministic given an initial seed. Using a custom PRNG ensures that the same seed always produces the same sequence regardless of platform or future library updates.

<details><summary>References</summary>
<ul>
<li><a href="https://tck.mn/blog/correlated-randomness-sts2/">Correlated randomness in Slay the Spire 2 - Andy Tockman</a></li>
<li><a href="https://en.wikipedia.org/wiki/Pseudorandom_number_generator">Pseudorandom number generator - Wikipedia</a></li>
<li><a href="https://codingtechroom.com/question/-consistent-cross-platform-pseudo-random-generator-java-net">How to Create a Consistent, Cross-Platform Pseudo-Random ...</a></li>

</ul>
</details>

**Discussion**: Commenters appreciated the technical depth and cross-platform consistency. Some noted that Godot's GDScript uses PCG32, which would have avoided the issue, while others discussed the implications of 32-bit seeds for brute-forcing unwinnable seeds. A user also shared a link to an unwinnable seed in the original game, sparking discussion about RNG hell.

**Tags**: `#game development`, `#PRNG`, `#randomness`, `#Slay the Spire`, `#software engineering`

---

<a id="item-20"></a>
## [Reflex.dev Speeds Up Python AST Walk 220x with Rust](https://reflex.dev/blog/why-ast-walk-when-you-can-ast-sprint/) ⭐️ 7.0/10

Reflex.dev published a blog post detailing how they achieved a 220x speedup of Python's ast.walk function by rewriting it in Rust as a custom implementation. This optimization demonstrates the significant performance gains possible by replacing slow Python code with Rust extensions, potentially benefiting many Python tools that rely on AST traversal, such as linters and code analyzers. The speedup was achieved by implementing a custom AST walker in Rust using the PyO3 crate, which allows seamless integration with Python. The original Python ast.walk is a generator function that recursively yields all descendant nodes, but its performance is limited by Python's overhead.

hackernews · palashawas · Jun 16, 16:25 · [Discussion](https://news.ycombinator.com/item?id=48557768)

**Background**: Python's ast module provides tools for parsing and walking Abstract Syntax Trees (ASTs), which represent the structure of Python code. The ast.walk function is commonly used in tools like linters and static analyzers, but its pure Python implementation can be slow for large codebases. Rust is a systems programming language known for its performance and safety, and can be used to create Python extensions via PyO3.

<details><summary>References</summary>
<ul>
<li><a href="https://pythonspeed.com/articles/intro-rust-python-extensions/">Let’s build and optimize a Rust extension for Python</a></li>
<li><a href="https://tedboy.github.io/python_stdlib/generated/generated/ast.walk.html">ast . walk () — Python Standard Library</a></li>

</ul>
</details>

**Discussion**: The community comments highlight Python's performance limitations when modularizing code, and question whether similar optimizations could benefit tools like libCST and bandit. One commenter humorously guessed that the improved version was written in Rust, which turned out to be correct.

**Tags**: `#Python`, `#AST`, `#performance`, `#Rust`, `#optimization`

---

<a id="item-21"></a>
## [Berlin court: Google AI Overviews are new search format, not original content](https://the-decoder.com/berlin-court-rules-googles-ai-overviews-are-just-a-new-search-format-not-original-content/) ⭐️ 7.0/10

A Berlin court ruled that Google's AI Overviews are a new search result format, not original content, and that Google has no decisive influence over the generated summaries. This ruling partly contradicts a recent Munich decision that held Google directly liable for false AI responses. This ruling reduces Google's liability for AI-generated summaries, setting a precedent that could affect how search engines and AI-generated content are regulated. It highlights legal uncertainty in the rapidly evolving AI landscape, impacting companies that deploy generative AI in search. The case was brought by a perfume company whose brand names appeared alongside cheaper knockoffs in AI Overviews. The Berlin court found that Google's AI Overviews are merely a new format for presenting search results, not independent content creation.

rss · The Decoder — AI新闻 · Jun 16, 18:19

**Background**: Google's AI Overviews automatically generate summaries from search results using AI. In Germany, two recent court rulings have reached opposite conclusions: a Munich court held Google directly liable for false AI statements, while the Berlin court classified AI Overviews as a search format with limited liability. These cases test the boundaries of intermediary liability protections for AI-generated content.

<details><summary>References</summary>
<ul>
<li><a href="https://the-decoder.com/landmark-german-ruling-declares-googles-ai-overviews-are-googles-own-words-and-makes-it-liable-for-false-answers/">Landmark German ruling declares Google's AI Overviews are ...</a></li>
<li><a href="https://byteiota.com/google-ai-overviews-liable-munich-court-ruling/">Google AI Overviews Lose Safe Harbor in Munich Ruling</a></li>

</ul>
</details>

**Tags**: `#AI`, `#legal`, `#search`, `#regulation`, `#Google`

---

<a id="item-22"></a>
## [New benchmark tests AI models' resistance to Russian propaganda](https://the-decoder.com/how-easily-can-russian-propaganda-fool-ai-models-a-new-benchmark-finds-out/) ⭐️ 7.0/10

The Institute of the Estonian Language has released a 'Propaganda Resistance' benchmark that evaluates how easily AI language models are fooled by Russian propaganda narratives. This benchmark addresses a critical gap in AI safety by measuring susceptibility to geopolitical misinformation, which could inform the development of more robust models and help counter disinformation campaigns. The benchmark was developed in cooperation with Propastop's disinformation experts, who helped define key narratives associated with Russian influence operations and ensured the reliability of results.

rss · The Decoder — AI新闻 · Jun 16, 11:28

**Background**: AI language models are increasingly used to generate and consume information, making them potential targets for propaganda. Russian propaganda often employs specific narratives to influence public opinion, and models that uncritically repeat such content could amplify disinformation. This benchmark systematically tests models' ability to resist these narratives.

<details><summary>References</summary>
<ul>
<li><a href="https://arstechnica.com/ai/2026/06/these-llms-are-the-best-at-resisting-russian-propaganda/">These LLMs are the best at resisting Russian propaganda</a></li>
<li><a href="https://news.err.ee/1610046565/estonian-study-finds-ai-models-still-vulnerable-to-propaganda-prompts">Estonian study finds AI models still vulnerable to propaganda ...</a></li>
<li><a href="https://www.propastop.org/en/2026/06/04/eki-and-propastop-studied-ai-resistance-to-propaganda/">EKI and Propastop Studied AI Resistance to Propaganda</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#misinformation`, `#benchmark`, `#propaganda`, `#NLP`

---

<a id="item-23"></a>
## [India Orders Temporary Telegram Ban Over Exam Fraud](https://techcrunch.com/2026/06/16/india-temporarily-blocks-access-to-telegram-over-exam-fraud-concerns/) ⭐️ 7.0/10

India has ordered a nationwide ban on Telegram until June 22, 2026, and demanded the platform disable its message-editing feature until June 30, citing concerns over exam fraud during the NEET (UG) 2026 re-examination. This action affects millions of Telegram users in India and sets a significant precedent for government intervention in messaging platforms over security concerns, impacting digital rights and the broader tech policy landscape. The ban includes two measures: a complete block on Telegram access in India until June 22, and a requirement to disable the message-editing feature—which allows altering sent messages while retaining timestamps—until June 30.

rss · TechCrunch — 科技创投 · Jun 16, 15:49

**Background**: India has a history of internet censorship, with both central and state governments able to impose bans during emergencies. The NEET (UG) exam is a highly competitive medical entrance test, and authorities have previously taken action against platforms used for cheating. Telegram's message-editing feature has been exploited to distribute altered exam materials after initial posts, making it a target for fraud prevention.

<details><summary>References</summary>
<ul>
<li><a href="https://in.mashable.com/tech/110979/telegram-banned-in-india-until-22-june-2026-for-neet-re-exams-several-bots-channels-deleted">Telegram Banned In India Until 22 June 2026 ... - Mashable India</a></li>
<li><a href="https://techstory.in/india-bans-telegram-till-june-22-and-disables-message-editing-till-june-30-to-secure-neet-ug-retest/">India Bans Telegram Till June 22 And Disables Message Editing ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Internet_censorship_in_India">Internet censorship in India - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#Telegram`, `#India`, `#ban`, `#exam fraud`, `#tech policy`

---

<a id="item-24"></a>
## [DOJ backs xAI's unpermitted gas turbines for national security](https://techcrunch.com/2026/06/16/doj-claims-xais-unpermitted-gas-turbines-are-a-matter-of-national-economic-and-energy-security/) ⭐️ 7.0/10

The U.S. Department of Justice filed a motion to dismiss a lawsuit by the NAACP, arguing that xAI must continue using unpermitted natural gas turbines to power its Memphis data centers for national, economic, and energy security reasons. This marks a significant escalation where the U.S. government invokes national security to defend a tech company's environmental violations, setting a precedent for AI infrastructure regulation and energy policy. The DOJ claims xAI's Grok chatbot is integral to military operations, including the Iran War, and that shutting down the turbines would undermine American security. The NAACP lawsuit alleges xAI built an illegal power plant with no permits, releasing pollutants like formaldehyde.

rss · TechCrunch — 科技创投 · Jun 16, 15:05

**Background**: xAI, Elon Musk's AI company, operates the Colossus 2 data center in Tennessee, powered by dozens of unpermitted methane gas turbines. The Southern Environmental Law Center and NAACP have challenged the legality of this setup, citing pollution and lack of public input. The DOJ's intervention elevates the dispute to a national security matter.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/06/16/doj-claims-xais-unpermitted-gas-turbines-are-a-matter-of-national-economic-and-energy-security/">DOJ claims xAI’s unpermitted gas turbines are a matter of ...</a></li>
<li><a href="https://www.theguardian.com/technology/2026/jan/15/elon-musk-xai-datacenter-memphis">Elon Musk’s xAI datacenter generating extra electricity ...</a></li>
<li><a href="https://www.wired.com/story/doj-lawyers-argue-xai-vital-national-security-naacp-lawsuit/">DOJ Lawyers Argue xAI Is ‘Vital’ for National Security in ...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#energy`, `#national security`, `#regulation`, `#infrastructure`

---

<a id="item-25"></a>
## [Cockroaches carry thousands of bacterial genome fragments](https://arstechnica.com/science/2026/06/cockroaches-scurry-around-with-thousands-of-pieces-of-bacterial-genomes/) ⭐️ 7.0/10

A new study reveals that cockroach genomes contain thousands of bacterial DNA fragments acquired through horizontal gene transfer, challenging the notion that such transfers are rare in animals. This discovery suggests horizontal gene transfer may be more common in multicellular animals than previously thought, with potential implications for evolution, adaptation, and even antibiotic resistance spread. The study identified thousands of horizontally transferred regions in cockroach genomes, many of which are intact and potentially functional, indicating ongoing gene flow from bacteria to these insects.

rss · ArsTechnica — 深度科技 · Jun 16, 21:54

**Background**: Horizontal gene transfer (HGT) is the movement of genetic material between organisms other than parent-to-offspring inheritance. While common in bacteria, HGT in animals has been considered rare. This study provides evidence that cockroaches, as a model organism, accumulate bacterial DNA on a large scale.

<details><summary>References</summary>
<ul>
<li><a href="https://arstechnica.com/science/2026/06/cockroaches-scurry-around-with-thousands-of-pieces-of-bacterial-genomes/">Cockroaches scurry around with thousands of pieces of ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Horizontal_gene_transfer">Horizontal gene transfer - Wikipedia</a></li>
<li><a href="https://farmaroc.net/public/news/cockroaches-scurry-around-with-thousands-of-pieces-of-bacterial-genomes">Cockroach Genomes Packed with Bacterial DNA Fragments ...</a></li>

</ul>
</details>

**Tags**: `#horizontal gene transfer`, `#cockroaches`, `#evolution`, `#genetics`, `#bacteria`

---

<a id="item-26"></a>
## [Anthropic Pauses Token-Based Billing for Claude Agent SDK](https://arstechnica.com/ai/2026/06/anthropic-pauses-token-based-billing-for-its-claude-agent-sdk/) ⭐️ 7.0/10

Anthropic has paused a planned token-based billing change for its Claude Agent SDK that was originally scheduled for Monday and would have significantly increased costs for power users. This decision provides temporary relief for developers and enterprises relying on the Claude Agent SDK, preventing sudden cost spikes and giving the community time to adapt or provide feedback on pricing. The token-based billing model would have charged users per token consumed by agent invocations, heavily impacting power users who run complex, multi-step workflows. The pause suggests Anthropic is reconsidering the pricing structure in response to community concerns.

rss · ArsTechnica — 深度科技 · Jun 16, 21:00

**Background**: The Claude Agent SDK allows developers to build AI agents that can autonomously read files, run commands, search the web, and edit code, using the same tools and agent loop that power Claude Code. Token-based billing is a common pricing model for AI APIs, where users pay for each unit of text processed (tokens). However, for agentic workflows that involve many back-and-forth calls, costs can escalate quickly.

<details><summary>References</summary>
<ul>
<li><a href="https://code.claude.com/docs/en/agent-sdk/overview">Agent SDK overview - Claude Code Docs</a></li>
<li><a href="https://github.com/anthropics/claude-agent-sdk-typescript">GitHub - anthropics/claude-agent-sdk-typescript</a></li>

</ul>
</details>

**Tags**: `#Anthropic`, `#Claude`, `#pricing`, `#AI SDK`, `#developer tools`

---

<a id="item-27"></a>
## [Pentagon Uses AI to Write Congressional Reports](https://arstechnica.com/ai/2026/06/pentagon-boasts-of-using-ai-to-write-reports-mandated-by-congress/) ⭐️ 7.0/10

The Pentagon announced it is using generative AI tools to write congressionally mandated reports, with 1.5 million personnel now using such tools. This marks a major shift in government AI adoption, raising concerns about accountability and accuracy in official reporting to Congress. The Pentagon's Chief Technology Officer Emil Michael highlighted AI-generated reports as a key example of AI use, though the specific AI tools were not named.

rss · ArsTechnica — 深度科技 · Jun 16, 18:11

**Background**: Congressional mandated reports are detailed documents that federal agencies must submit to Congress on various topics. The Pentagon previously spent months identifying and assigning these reports, but now uses generative AI to speed up the process.

<details><summary>References</summary>
<ul>
<li><a href="https://arstechnica.com/ai/2026/06/pentagon-boasts-of-using-ai-to-write-reports-mandated-by-congress/">Pentagon boasts of using AI to write reports mandated ... - Ars Technica</a></li>

</ul>
</details>

**Tags**: `#AI`, `#government`, `#generative AI`, `#policy`

---

<a id="item-28"></a>
## [Mobileye to Launch Standalone US Robotaxi Service by 2027](https://arstechnica.com/cars/2026/06/mobileye-is-entering-the-us-robotaxi-market-with-standalone-service/) ⭐️ 7.0/10

Mobileye announced plans to launch a standalone robotaxi service in a US city by 2027, leveraging its Moovit platform for ride-hailing and trip planning. This move positions Mobileye as a direct competitor to its own customers, such as Volkswagen and other automakers that use its self-driving systems, and signals a major shift in the robotaxi market landscape. The service will use Mobileye's self-driving technology and the Moovit app, which already serves over 1.7 billion riders in 3,500 cities. The specific US city has not been disclosed.

rss · ArsTechnica — 深度科技 · Jun 16, 14:20

**Background**: Mobileye is an Israeli company known for its advanced driver-assistance systems (ADAS) and autonomous driving technology. Moovit, acquired by Mobileye in 2020, is a popular mobility-as-a-service app that provides public transit directions and ride-hailing integration. Robotaxis are self-driving taxis that operate without a human driver, and several companies like Waymo and Cruise are already testing such services in the US.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mobileye">Mobileye - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Moovit">Moovit - Wikipedia</a></li>
<li><a href="https://www.mobileye.com/solutions/drive/">Mobileye Drive™ | Self-Driving System for Autonomous MaaS</a></li>

</ul>
</details>

**Tags**: `#autonomous vehicles`, `#robotaxi`, `#Mobileye`, `#mobility`, `#transportation`

---

<a id="item-29"></a>
## [llama.cpp b9670 Fixes NVFP4 Edge Cases for LORA and ModelOPT](https://github.com/ggml-org/llama.cpp/releases/tag/b9670) ⭐️ 6.0/10

llama.cpp release b9670 fixes and restricts NVFP4 edge-cases in llama-graph, ensuring correct dequantization order for LORA and bias-add for ModelOPT, and restricts build_ffn for NVFP4 to supported combinations. This fix improves correctness for users applying LORA adapters or NVIDIA ModelOPT quantization with NVFP4, preventing silent accuracy degradation in a widely-used open-source LLM inference engine. The patch moves post-GEMM multiplication required for dequantization before LORA and bias-add, aligning with LORA literature and NVIDIA ModelOPT reference. It also restricts build_ffn for NVFP4 to supported combinations to avoid unsupported configurations.

github · github-actions[bot] · Jun 16, 13:10

**Background**: NVFP4 is a 4-bit floating-point format introduced with NVIDIA Blackwell GPUs for efficient LLM inference. LORA (Low-Rank Adaptation) is a fine-tuning method that adds small adapters to pre-trained models, and ModelOPT is NVIDIA's model optimization toolkit. llama.cpp is a popular C/C++ library for running LLMs locally on various hardware.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/ggml-org/llama.cpp">GitHub - ggml-org/ llama . cpp : LLM inference in C/C++ · GitHub</a></li>
<li><a href="https://developer.nvidia.com/blog/introducing-nvfp4-for-efficient-and-accurate-low-precision-inference/">Introducing NVFP4 for Efficient and Accurate Low-Precision ...</a></li>
<li><a href="https://huggingface.co/docs/diffusers/quantization/modelopt">NVIDIA ModelOpt · Hugging Face</a></li>

</ul>
</details>

**Tags**: `#llama.cpp`, `#NVFP4`, `#LLM inference`, `#bug fix`

---

<a id="item-30"></a>
## [Bash /dev/tcp: HTTP Without curl](https://mareksuppa.com/til/bash-dev-tcp-http-without-curl/) ⭐️ 6.0/10

A blog post highlights that Bash's built-in /dev/tcp pseudo-device can be used to make raw HTTP requests without external tools like curl or wget. This technique involves opening a TCP connection and manually sending HTTP headers. This trick is valuable for debugging in constrained environments where curl or wget are unavailable, such as minimal Docker containers. It demonstrates Bash's versatility and can help developers quickly test HTTP endpoints without installing additional software. The /dev/tcp feature requires Bash to be compiled with --enable-net-redirections, which is common in most Linux distributions. The syntax is exec 3<>/dev/tcp/host/port followed by printf and cat to send and receive data.

hackernews · mrshu · Jun 16, 16:40 · [Discussion](https://news.ycombinator.com/item?id=48558018)

**Background**: Bash's /dev/tcp is a pseudo-device that allows TCP connections via file redirection. It is not a real device file but a feature of Bash itself. This capability is often used for port checking, file transfer, or creating reverse shells.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/fijimunkii/bash-dev-tcp">GitHub - fijimunkii/ bash - dev - tcp : collection of scripts using / dev / tcp</a></li>
<li><a href="https://www.linuxtopia.org/online_books/advanced_bash_scripting_guide/devref1.html">Advanced Bash Shell Scripting Guide - /dev</a></li>
<li><a href="https://linuxize.com/post/check-open-ports-linux/">Check Open Ports in Linux: nmap, netcat, and Bash | Linuxize</a></li>

</ul>
</details>

**Discussion**: Commenters note that while /dev/tcp is useful for quick tests, it is not a proper HTTP client and can break in production due to lack of proper HTTP parsing. Some share nostalgic memories of manually interacting with servers via telnet, and others mention using it in Docker containers where curl is absent.

**Tags**: `#bash`, `#http`, `#networking`, `#dev-tcp`

---

<a id="item-31"></a>
## [Has AI Already Killed Self-Help Nonfiction Books?](https://tim.blog/2026/06/12/has-ai-already-killed-nonfiction/) ⭐️ 6.0/10

A blog post by Tim Ferriss explores whether AI is killing the self-help nonfiction book industry through summarization, piracy, and format shifts to audio and video. This discussion highlights a potential existential threat to a major publishing category, affecting authors, publishers, and readers who rely on self-help books for personal development. The post notes that print book sales are declining while audiobooks and other formats are growing, and mentions tools like Gemini for summarizing YouTube videos and podcasts.

hackernews · imakwana · Jun 16, 17:11 · [Discussion](https://news.ycombinator.com/item?id=48558489)

**Background**: Self-help nonfiction books have long been a popular genre for personal improvement, but AI-powered summarization tools and piracy sites like Anna's Archive are making it easier to consume content without buying books. Meanwhile, formats like audiobooks and video are gaining traction, shifting reader habits.

**Discussion**: Commenters express skepticism about the self-help industry's value, calling it a 'self-help mafia' and noting that many prefer listening to audiobooks. Some mention using AI to summarize content, while others point to piracy as a factor in declining sales.

**Tags**: `#AI`, `#publishing`, `#self-help`, `#nonfiction`, `#industry trends`

---

<a id="item-32"></a>
## [Yak Shaving: The Joy of Distraction](https://parksb.github.io/en/article/32.html) ⭐️ 6.0/10

A 2019 blog post titled 'But yak shaving is fun' celebrates the unexpected productivity and enjoyment found in side projects that arise from yak shaving, with community comments sharing personal anecdotes of long-running tangents. This reframes yak shaving—often seen as a productivity pitfall—as a valuable and enjoyable creative process, resonating with many developers who find deep satisfaction in tangential exploration. The post highlights that yak shaving can lead to significant personal projects, such as a 30-year game engine development, and notes that AI tools have reduced the costs of such tangents, making them more feasible.

hackernews · parksb · Jun 16, 14:26 · [Discussion](https://news.ycombinator.com/item?id=48555838)

**Background**: Yak shaving is a programming term for the seemingly endless series of small tasks that must be completed before the next step in a project can move forward. It often involves going down rabbit holes that distract from the original goal, but can also lead to valuable discoveries or tools.

<details><summary>References</summary>
<ul>
<li><a href="https://softwareengineering.stackexchange.com/questions/388092/what-exactly-is-yak-shaving">agile - What exactly is Yak Shaving ? - Software Engineering Stack...</a></li>
<li><a href="https://medium.com/@firehoseproject/a-guide-to-yak-shaving-your-code-d30f98dc759">A Guide to Yak Shaving Your Code. How to Stay Focused... | Medium</a></li>
<li><a href="https://www.counterpart.biz/blog/yak-shaving/">Yak Shaving : When Tech Projects Get Weirdly Hairy | Counterpart</a></li>

</ul>
</details>

**Discussion**: Commenters shared their own yak shaving stories, including a 30-year game engine project and a macOS GIF generator built instead of writing a blog post. The sentiment is positive, with many finding joy and deep learning in these tangents, though some acknowledge the trade-offs.

**Tags**: `#yak shaving`, `#programming`, `#productivity`, `#side projects`

---

<a id="item-33"></a>
## [Snap Unveils Specs AR Glasses with 51° FOV and $2195 Price](https://newsroom.snap.com/introducing-specs-augmented-reality-glasses) ⭐️ 6.0/10

Snap announced Specs, its next-generation augmented reality glasses, featuring a 51-degree field of view, 4 hours of mixed-use battery life, and a price of $2195, with pre-orders starting at a $200 deposit and expected delivery in Fall 2026. This product marks Snap's entry into the standalone AR glasses market, competing with Meta and Apple, but the high price point raises questions about ecosystem adoption and developer interest. The glasses weigh 132-136 grams depending on size, support prescription lenses, and come with a charging case that provides an additional 20 hours of battery life. The 51-degree FOV is described as equivalent to viewing a 24-inch monitor at arm's length.

hackernews · haberdasher · Jun 16, 17:00 · [Discussion](https://news.ycombinator.com/item?id=48558337)

**Background**: Augmented reality glasses overlay digital content onto the real world through transparent lenses. Field of view (FOV) is a key metric; larger FOV provides a more immersive experience. Snap previously released Spectacles for developers, but Specs targets consumers and creators.

<details><summary>References</summary>
<ul>
<li><a href="https://www.forbes.com/sites/andrewwilliams/2025/06/11/snap-specs-6-key-facts-on-meta-ray-ban-smart-glasses-rivals/">Snap Specs : 6 Key Facts On Meta Ray-Ban Smart Glasses Rivals</a></li>
<li><a href="https://visionxo.com/articles/what-is-fov-in-smart-glasses-a-complete-beginner-s-guide-to-field-of-view">What Is FOV in Smart Glasses & AR Glasses? Field of View ...</a></li>

</ul>
</details>

**Discussion**: Community comments highlight concerns about the $2195 price hindering ecosystem growth, with one user noting that previous computing platforms were much cheaper. Another user joked about needing an ad blocker for real life, while a third pointed out inaccuracies in the demo video's location.

**Tags**: `#augmented reality`, `#hardware`, `#Snap`, `#AR glasses`

---

<a id="item-34"></a>
## [New York Bill Targets 'Ghost Jobs'](https://www.fastcompany.com/91558427/ghost-jobs-could-soon-be-illegal-in-new-york) ⭐️ 6.0/10

New York is considering legislation that would make it illegal for companies to post fake job listings, known as 'ghost jobs', which waste job seekers' time and effort. If passed, this law could set a precedent for other states and protect job seekers from deceptive practices, but enforcement remains a major challenge. The bill would require employers to prove that a job posting is for a real, open position, and violators could face fines. However, critics question how to distinguish ghost jobs from legitimate postings that are later filled or withdrawn.

hackernews · toomuchtodo · Jun 16, 17:01 · [Discussion](https://news.ycombinator.com/item?id=48558338)

**Background**: Ghost jobs are job postings that companies never intend to fill, often used to collect resumes, test the market, or create an illusion of growth. Job seekers spend hours applying to these positions, only to receive no response. The practice has drawn increasing scrutiny as the job market remains competitive.

**Discussion**: Commenters largely support the idea but express skepticism about enforcement. Some suggest requiring companies to send rejection notices, while others worry the practice will simply go underground. One user humorously compares it to unlicensed haunted houses.

**Tags**: `#policy`, `#labor`, `#job market`, `#regulation`

---

<a id="item-35"></a>
## [Qualcomm bets on AI wearables as next computing platform](https://techcrunch.com/2026/06/16/qualcomm-wants-to-be-the-chip-inside-whatever-replaces-your-smartphone-and-it-just-announced-two-products-toward-that-end/) ⭐️ 6.0/10

Qualcomm CEO Cristiano Amon announced that the company is developing over 40 AI-powered wearable devices, including jewelry, camera-equipped earbuds, pins, and watches, signaling a strategic pivot beyond smartphones. This move positions Qualcomm to lead the next computing paradigm, potentially replacing smartphones with always-on, AI-native wearables that offer personalized, on-device intelligence. The Snapdragon Wear Elite platform, announced in March 2026, features the industry's first NPU-powered wearable chip, delivering up to 12 TOPS of AI performance and supporting 2-billion-parameter models on-device.

rss · TechCrunch — 科技创投 · Jun 16, 18:22

**Background**: Qualcomm has long dominated the smartphone chip market, but as smartphone growth slows, the company is diversifying into wearables. The Snapdragon Wear Elite platform is designed to transform wearables from simple notification devices into active AI assistants, with support for 5G RedCap, Wi-Fi 6, and Bluetooth 6.0.

<details><summary>References</summary>
<ul>
<li><a href="https://www.qualcomm.com/news/releases/2026/03/qualcomm-powers-the-rise-of-personal-ai-with-new-snapdragon-wear">Qualcomm Powers the Rise of Personal AI with New Snapdragon ...</a></li>
<li><a href="https://www.qualcomm.com/wearables/products/snapdragon-wear-elite-platform">Snapdragon Wear Elite Platform | Qualcomm</a></li>
<li><a href="https://www.cnx-software.com/2026/03/03/qualcomm-snapdragon-wear-elite-wearable-platform-offers-5g-redcap-wifi-6-bluetooth-6-0-built-in-ai-accelerator/">Qualcomm Snapdragon Wear Elite wearable platform offers 5G ...</a></li>

</ul>
</details>

**Tags**: `#Qualcomm`, `#AI wearables`, `#hardware`, `#smartphone replacement`

---

<a id="item-36"></a>
## [60% of US consumers put off by 'AI' in brand messaging](https://techcrunch.com/2026/06/16/sixty-percent-of-u-s-consumers-say-ai-in-brand-messaging-is-a-turnoff-survey-finds/) ⭐️ 6.0/10

A survey by WordPress VIP found that 60% of US consumers are turned off by the use of 'AI' in brand messaging, even as companies increasingly rely on AI search as a referral channel. This highlights a significant disconnect between corporate enthusiasm for AI and consumer wariness, which could impact marketing strategies and AI adoption in customer-facing communications. The survey specifically measured consumer sentiment toward AI-generated answers and the term 'AI' in brand messaging, revealing a negative reaction despite growing industry use.

rss · TechCrunch — 科技创投 · Jun 16, 16:49

**Background**: Many companies are integrating AI into their products and marketing to appear innovative, but consumers may associate 'AI' with impersonal or untrustworthy experiences. This survey underscores the need for brands to communicate AI benefits without alienating their audience.

**Tags**: `#AI`, `#consumer sentiment`, `#branding`, `#survey`

---

<a id="item-37"></a>
## [Flutterwave hits $3.2B valuation with Ripple backing](https://techcrunch.com/2026/06/16/payments-startup-flutterwave-hits-3-2b-valuation-backed-by-ripple/) ⭐️ 6.0/10

African payments startup Flutterwave has reached a $3.2 billion valuation and secured blockchain company Ripple as both an investor and strategic partner. This deal signals growing convergence between traditional fintech and blockchain-based payments, and highlights Africa as a key market for cross-border payment innovation. Flutterwave became a unicorn in 2021 and has faced regulatory controversies in the past; Ripple is known for its XRP-based cross-border payment network and stablecoin solutions.

rss · TechCrunch — 科技创投 · Jun 16, 15:35

**Background**: Flutterwave is a fintech company founded in 2016 that provides payment infrastructure for merchants and payment service providers across Africa. Ripple is a blockchain company focused on enabling fast, low-cost cross-border payments using its XRP token and stablecoin technology. The partnership could combine Flutterwave's African reach with Ripple's blockchain expertise.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Flutterwave">Flutterwave - Wikipedia</a></li>
<li><a href="https://ripple.com/">Financial Infrastructure & Blockchain Technology Solutions | Ripple</a></li>

</ul>
</details>

**Tags**: `#fintech`, `#payments`, `#blockchain`, `#startup`, `#Africa`

---

<a id="item-38"></a>
## [Robinhood CEO Avoids AI Excuse for Layoffs](https://techcrunch.com/2026/06/16/robinhoods-note-on-10-layoffs-shows-blaming-ai-isnt-cutting-it/) ⭐️ 6.0/10

Robinhood CEO Vlad Tenev announced a 10% layoff without citing AI restructuring, unlike many tech peers who blame AI for job cuts. This highlights a growing skepticism toward using AI as a scapegoat for layoffs, potentially shifting how tech companies justify workforce reductions. The layoff note conspicuously omitted any mention of AI, contrasting with other tech leaders who have used AI restructuring as a rationale for mass layoffs.

rss · TechCrunch — 科技创投 · Jun 16, 14:50

**Background**: Many tech companies have recently laid off employees, often citing the need to restructure for AI efficiency. Robinhood's approach stands out by not following this trend.

**Tags**: `#layoffs`, `#AI`, `#tech industry`, `#Robinhood`

---

<a id="item-39"></a>
## [Probably raises $9M to build reliable AI](https://techcrunch.com/2026/06/16/probably-raises-9m-to-build-a-more-reliable-kind-of-ai/) ⭐️ 6.0/10

Probably, an AI startup, has raised $9 million in funding to develop AI systems that reduce hallucinations and achieve accuracy comparable to deterministic systems. This investment highlights the growing demand for trustworthy AI in critical applications, especially in regulated industries like finance and healthcare where errors are costly. Probably's initial product is a data science tool that provides answers from complex datasets with citations and an audit trail, ensuring transparency and verifiability.

rss · TechCrunch — 科技创投 · Jun 16, 13:15

**Background**: Most modern AI systems, like large language models, are probabilistic: they predict the most likely output based on training data, which can lead to hallucinations or factual errors. Deterministic AI, in contrast, follows explicit rules and always produces the same output for the same input, making it more reliable but less flexible. Probably aims to bridge this gap by building AI that combines the flexibility of probabilistic models with the reliability of deterministic systems.

<details><summary>References</summary>
<ul>
<li><a href="https://tech.yahoo.com/ai/deals/articles/probably-raises-9m-build-more-131509796.html">Probably raises $9M to build a more reliable kind of AI</a></li>
<li><a href="https://aichief.com/news/probably-secures-9m-to-build-dependable-ai/">Probably Secures $9M to Build Dependable AI</a></li>
<li><a href="https://www.linkedin.com/company/probably-ai">Probably - LinkedIn</a></li>

</ul>
</details>

**Tags**: `#AI`, `#funding`, `#reliability`, `#hallucination`

---

<a id="item-40"></a>
## [Foundation Alloy raises $22M for novel super metals](https://techcrunch.com/2026/06/16/this-startups-super-metals-could-soon-be-in-military-drones-luxury-watches-and-chefs-knives/) ⭐️ 6.0/10

Foundation Alloy has raised $22 million in Series A funding to scale production of its super metals made via a solid-state mechanical process called MetalsFIRST, which avoids traditional melting. This breakthrough could enable stronger, lighter metals for military drones, luxury watches, and chef's knives, potentially transforming industries that rely on high-performance alloys. The MetalsFIRST process combines composition design, mechanical alloying, shape forming, and sintering without melting, yielding alloys twice as strong as traditional metals with 10x faster development cycles.

rss · TechCrunch — 科技创投 · Jun 16, 11:25

**Background**: Traditional metal alloys are made by melting and mixing elements, which limits the combinations and properties achievable. Foundation Alloy's solid-state approach allows access to novel compositions and microstructures that cannot be made via melting, enabling ultra-high-performance materials for demanding applications.

<details><summary>References</summary>
<ul>
<li><a href="https://news.mit.edu/2025/new-platform-foundation-alloy-developing-advanced-metals-scale-0703">A new platform for developing advanced metals at scale</a></li>
<li><a href="https://foundationalloy.com/">Foundation Alloy</a></li>
<li><a href="https://foundationalloy.com/22m-series-a/">Foundation Alloy Industrializes New Metals Platform with $22M ...</a></li>

</ul>
</details>

**Tags**: `#materials science`, `#startup`, `#manufacturing`, `#alloys`

---

