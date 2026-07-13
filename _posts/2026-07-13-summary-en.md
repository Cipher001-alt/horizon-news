---
layout: default
title: "Horizon Summary: 2026-07-13 (EN)"
date: 2026-07-13
lang: en
---

> From 49 items, 26 important content pieces were selected

---

1. [Apple's SpeechAnalyzer API Benchmarked Against Whisper](#item-1) ⭐️ 8.0/10
2. [LAPD Ends Flock Contract Over Privacy Concerns](#item-2) ⭐️ 8.0/10
3. [DOM-docx: Convert HTML to Editable Word Docs](#item-3) ⭐️ 8.0/10
4. [Benchmarking 15 E-Waste GPUs for Modern LLM Workloads](#item-4) ⭐️ 8.0/10
5. [Clawk: Disposable Linux VMs for Safe Coding Agents](#item-5) ⭐️ 8.0/10
6. [Turing Award winner Rich Sutton founds Oak Lab for autonomous AI agents](#item-6) ⭐️ 8.0/10
7. [Nadella criticizes OpenAI, Anthropic for banning distillation while using public data](#item-7) ⭐️ 8.0/10
8. [German Consortium Releases Open 30B Model Soofi S](#item-8) ⭐️ 8.0/10
9. [Google's SensorFM: Foundation Model for Wearable Health Data](#item-9) ⭐️ 8.0/10
10. [Should AI help you get away with killing your spouse?](#item-10) ⭐️ 8.0/10
11. [Defenders turn prompt injection into a weapon](#item-11) ⭐️ 8.0/10
12. [llama.cpp b9982 Fixes Per-Request Reasoning Budget Bug](#item-12) ⭐️ 7.0/10
13. [Sega CD Silpheed: FMV and Engineering Deep Dive](#item-13) ⭐️ 7.0/10
14. [AI Agents Should Never Be DRIs, Argues Simon Willison](#item-14) ⭐️ 7.0/10
15. [AI leaders warn window to prepare for economic impact closing fast](#item-15) ⭐️ 7.0/10
16. [SpaceX Cleared for Starship Flight After May Failure](#item-16) ⭐️ 7.0/10
17. [Uber and Waymo clash over robotaxi lobbying](#item-17) ⭐️ 7.0/10
18. [World Models: Promise and Limits in AI](#item-18) ⭐️ 7.0/10
19. [Show HN: Super Dario – AI-Generated Mario Clone](#item-19) ⭐️ 6.0/10
20. [Backtrack-Free Cursive Script Design Analysis](#item-20) ⭐️ 6.0/10
21. [Anthropic Extends Claude Fable 5 Access; OpenAI Confident on GPT-5.6](#item-21) ⭐️ 6.0/10
22. [Apple's Trade Secrets Lawsuit Alleges OpenAI Misconduct](#item-22) ⭐️ 6.0/10
23. [General Fusion becomes first publicly traded fusion company](#item-23) ⭐️ 6.0/10
24. [Anthropic Localizes Claude Pricing for India](#item-24) ⭐️ 6.0/10
25. [Hackers Prove Neo Geo Doom Ports Are Possible](#item-25) ⭐️ 6.0/10
26. [Crew Dragon gap concerns industry officials](#item-26) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Apple's SpeechAnalyzer API Benchmarked Against Whisper](https://get-inscribe.com/blog/apple-speech-api-benchmark.html) ⭐️ 8.0/10

Apple's new SpeechAnalyzer API, introduced in iOS 26, has been benchmarked against OpenAI's Whisper model, showing faster transcription speed but slightly lower accuracy. This benchmark matters because SpeechAnalyzer could disrupt the speech-to-text app market, especially for apps that simply wrap Whisper, as Apple may integrate it natively into macOS and iOS. The benchmark used Whisper-Large-V2 on a math lecture; SpeechAnalyzer was substantially faster and only slightly worse in accuracy. However, the API lacks a Custom Vocabulary feature available in Apple's older SFSpeechRecognizer.

hackernews · get-inscribe · Jul 13, 16:06 · [Discussion](https://news.ycombinator.com/item?id=48894752)

**Background**: Whisper is an open-source automatic speech recognition (ASR) model by OpenAI, trained on 680,000 hours of multilingual data. Apple's SpeechAnalyzer is a new speech-to-text API replacing SFSpeechRecognizer, introduced at WWDC 2025 for iOS 26.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.apple.com/videos/play/wwdc2025/277/">Bring advanced speech -to-text to your app with... - Apple Developer</a></li>
<li><a href="https://www.argmaxinc.com/blog/apple-and-argmax">Apple SpeechAnalyzer and Argmax WhisperKit - Argmax</a></li>
<li><a href="https://gigazine.net/gsc_news/en/20250619-apple-speech-analyzer/">Apple 's new transcription API ' SpeechAnalyzer ' beats... - GIGAZIN...</a></li>

</ul>
</details>

**Discussion**: Commenters noted that Whisper is outdated and should be compared with newer models like Nvidia's Nemotron or Parakeet. Some expressed concern that Apple's native integration could kill paid Whisper wrapper apps, while others found SpeechAnalyzer very usable for live transcription.

**Tags**: `#speech recognition`, `#Apple`, `#Whisper`, `#benchmark`, `#API`

---

<a id="item-2"></a>
## [LAPD Ends Flock Contract Over Privacy Concerns](https://techcrunch.com/2026/07/13/lapd-lets-contract-with-surveillance-giant-flock-expire-citing-serious-concerns-over-civil-liberties-and-privacy/) ⭐️ 8.0/10

The Los Angeles Police Department (LAPD) has allowed its contract with surveillance company Flock Safety to expire, citing serious concerns over civil liberties and privacy. However, community comments reveal that Flock's cameras remain operational and data can still be accessed by law enforcement through other means. This decision highlights the tension between public safety and privacy rights, but also exposes the difficulty of truly ending surveillance when infrastructure is owned by private companies. The incident underscores the need for stronger regulations on government data acquisition from third-party sources. Flock Safety owns the cameras and poles, so even after the contract expires, the cameras continue recording and Flock can sell the data to other agencies like CHP, LASD, FBI, or Palantir. The LAPD can still access the data by simply calling Flock, rendering the contract termination largely symbolic.

hackernews · TechCrunch — 科技创投 · Jul 13, 15:11 · [Discussion](https://news.ycombinator.com/item?id=48893947)

**Background**: Flock Safety is a major provider of automated license plate recognition (ALPR) cameras and surveillance systems used by police departments across the US. The company's business model involves selling cameras to both public and private customers, with data stored on Flock's servers and accessible to law enforcement via subscription. Critics argue this creates a surveillance system that is resistant to democratic oversight.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/07/13/lapd-lets-contract-with-surveillance-giant-flock-expire-citing-serious-concerns-over-civil-liberties-and-privacy/">LAPD lets contract with surveillance giant Flock expire... | TechCrunch</a></li>
<li><a href="https://en.wikipedia.org/wiki/Flock_Safety">Flock Safety - Wikipedia</a></li>
<li><a href="https://www.aclu.org/news/privacy-technology/flock-roundup">Flock’s Aggressive Expansions Go Far Beyond Simple Driver Surveillance | American Civil Liberties Union</a></li>

</ul>
</details>

**Discussion**: Community comments express skepticism about the effectiveness of ending the contract, noting that Flock's system is designed to be resilient to political pressure. Some users highlight the irony that cameras remain operational and data can still be shared, while others argue that the government should be prohibited from buying data it cannot legally collect itself.

**Tags**: `#surveillance`, `#privacy`, `#civil liberties`, `#law enforcement`, `#technology policy`

---

<a id="item-3"></a>
## [DOM-docx: Convert HTML to Editable Word Docs](https://github.com/floodtide/dom-docx) ⭐️ 8.0/10

DOM-docx is a new open-source TypeScript library that converts semantic HTML fragments into native, editable Word documents (DOCX) with high fidelity, using a visual regression loop to ensure layout accuracy. This addresses a common pain point for developers generating backend documents, offering a modern workflow using JavaScript frameworks like Vue or React instead of cryptic template engines, and produces truly editable Word files unlike existing OSS solutions. The library maps HTML elements to real OOXML structures (paragraphs, lists, tables, links) and includes a visual regression scoring loop: render HTML in Chromium, convert to DOCX, rasterize via LibreOffice, and score fidelity against a human-validated metric.

hackernews · fishbone · Jul 13, 11:51 · [Discussion](https://news.ycombinator.com/item?id=48891267)

**Background**: Generating Word documents from backend code often involves using template engines or low-level OOXML manipulation, which can be error-prone and slow. Existing HTML-to-DOCX libraries typically produce output that is not fully editable in Word, limiting their usefulness. DOM-docx aims to solve this by converting HTML directly to native Word structures.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/dom-docx/dom-docx">GitHub - dom - docx / dom - docx : Convert semantic HTML fragments to...</a></li>
<li><a href="https://dom-docx.com/">dom - docx — HTML to Word converter in the browser</a></li>

</ul>
</details>

**Discussion**: The community response is positive, with users praising the TypeScript implementation and the clever visual regression scoring loop. Some commenters noted similar challenges with PPTX generation and expressed interest in using DOM-docx for CV generation.

**Tags**: `#HTML-to-DOCX`, `#document generation`, `#TypeScript`, `#open source`, `#developer tools`

---

<a id="item-4"></a>
## [Benchmarking 15 E-Waste GPUs for Modern LLM Workloads](https://esologic.com/benchmarking-tesla-gpus/) ⭐️ 8.0/10

A comprehensive benchmark of 15 older GPUs, including Tesla P4 and Radeon Pro V620, demonstrates their viability for running modern large language models (LLMs) with practical token speeds and configurations shared by the community. This matters because it provides cost-effective alternatives for hobbyists and researchers to run LLMs locally, reducing e-waste and democratizing access to AI inference. The Tesla P4, with 8GB VRAM and 75W TDP, costs around $80 and can achieve 7-12 tokens/second on 20-30B parameter models using llama.cpp with CPU offloading. The Radeon Pro V620 offers 32GB VRAM and sustained 30+ tokens/second on Gemma 4 31b 4-bit QAT.

hackernews · eso_logic · Jul 13, 13:48 · [Discussion](https://news.ycombinator.com/item?id=48892638)

**Background**: Older GPUs, often considered e-waste, can be repurposed for machine learning inference due to their sufficient VRAM and compute capabilities. Tools like llama.cpp enable model offloading between GPU and CPU, allowing larger models to run on limited VRAM. The benchmark covers cards from Nvidia and AMD, highlighting their performance with modern LLMs.

<details><summary>References</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=48892638">Benchmarking 15 "E-Waste" GPUs with Modern Workloads | Hacker News</a></li>

</ul>
</details>

**Discussion**: Community comments highlight specific setups like 6x Tesla P4s providing a virtual 48GB GPU, and Radeon Pro V620 being a viable 32GB option still supported by ROCm. Users also discuss power consumption and the need for better visualization of benchmark data.

**Tags**: `#GPU`, `#benchmarking`, `#machine learning`, `#e-waste`, `#LLM`

---

<a id="item-5"></a>
## [Clawk: Disposable Linux VMs for Safe Coding Agents](https://github.com/clawkwork/clawk) ⭐️ 8.0/10

Clawk is a new open-source tool that provides disposable, network-restricted Linux VMs for coding agents, preventing unauthorized access to the host system. It uses any OCI image as the rootfs and does not require a Docker daemon. As AI coding agents become more common, they pose security risks by executing untrusted code that could access credentials or exfiltrate data. Clawk addresses this critical need by offering a lightweight, VM-level sandbox that isolates agents from the host, making it safer to run AI-generated code. Clawk creates a real Linux VM per project, not a container, ensuring strong isolation. The VM is disposable, meaning only the VM disk is lost on shutdown, and it supports any OCI image for a customized toolchain.

hackernews · celrenheit · Jul 13, 14:02 · [Discussion](https://news.ycombinator.com/item?id=48892859)

**Background**: Coding agents are AI tools that autonomously write and execute code, but they can be exploited via prompt injection or supply chain attacks to access sensitive data. Traditional sandboxing methods like containers or Docker may not provide sufficient isolation, as they share the host kernel. VM-level isolation, such as that provided by Clawk, offers stronger security by running a separate operating system.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/clawkwork/clawk">GitHub - clawkwork/clawk: Disposable , network-restricted Linux VMs...</a></li>
<li><a href="https://www.bunnyshell.com/guides/coding-agent-sandbox/">Coding Agent Sandbox: Secure Environments for AI-Generated Code | Bunnyshell</a></li>
<li><a href="https://northflank.com/blog/best-sandboxes-for-coding-agents">Best sandboxes for coding agents in 2026 | Blog — Northflank</a></li>

</ul>
</details>

**Discussion**: The Hacker News community discussed alternative approaches like agentjail (using OS-native sandboxes with OPA policies) and flar (a lighter tool that grants explicit file access). Some users argued that QEMU/KVM on a separate machine is the most secure setup, while others preferred Podman containers for simplicity.

**Tags**: `#coding agents`, `#security`, `#sandboxing`, `#developer tools`, `#AI safety`

---

<a id="item-6"></a>
## [Turing Award winner Rich Sutton founds Oak Lab for autonomous AI agents](https://the-decoder.com/turing-award-winner-rich-sutton-founds-oak-lab-to-build-ai-agents-that-learn-on-their-own/) ⭐️ 8.0/10

Richard Sutton, 2024 Turing Award winner and co-founder of modern reinforcement learning, has launched a new startup called Oak Lab in Toronto to build AI agents that learn continuously from their environment. Sutton's move signals a potential shift away from current deep learning methods, which he criticizes as weak and inefficient, toward more autonomous and adaptive AI systems that could revolutionize robotics, gaming, and real-world decision-making. Sutton previously worked at Keen Technologies, the AI startup founded by John Carmack, before leaving to start Oak Lab. The lab will focus on reinforcement learning and novel techniques beyond current paradigms.

rss · The Decoder — AI新闻 · Jul 13, 17:15

**Background**: Richard Sutton is a pioneer in reinforcement learning (RL), a type of machine learning where agents learn by interacting with their environment and receiving rewards. He co-authored the seminal textbook 'Reinforcement Learning: An Introduction' with Andrew Barto. Current deep learning methods often rely on large labeled datasets and static training, whereas Sutton advocates for agents that learn continuously and autonomously.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Richard_S._Sutton">Richard S. Sutton - Wikipedia</a></li>
<li><a href="https://x.com/mark_k/status/2076667108688003127">Mark Kretschmann on X: "The inventor of RL (Reinforcement Learning) Richard Sutton is leaving Keen Technologies, the AI startup by John Carmack. Sutton is creating a new AI company named Oak Lab (@oaklab_ai), again focusing on Reinforcement Learning but also on novel techniques. Very exciting. I'm https://t.co/XamswVNq24" / X</a></li>

</ul>
</details>

**Tags**: `#AI`, `#reinforcement learning`, `#startup`, `#autonomous agents`, `#deep learning`

---

<a id="item-7"></a>
## [Nadella criticizes OpenAI, Anthropic for banning distillation while using public data](https://the-decoder.com/nadella-calls-out-ai-labs-like-openai-and-anthropic-for-banning-distillation-while-training-on-everyone-elses-data/) ⭐️ 8.0/10

Microsoft CEO Satya Nadella publicly criticized OpenAI and Anthropic for banning model distillation of their own models while they train on public data under fair use and learn from customer interactions. He argued that companies should control their own learning infrastructure, and Microsoft sells such infrastructure. This highlights a contentious policy issue in AI: the asymmetry between using public data for training while restricting competitors from distilling models. It could influence debates on fair use, model distillation, and competitive dynamics among major AI labs. Model distillation is a technique to transfer knowledge from a large model to a smaller one, often used to create efficient models. Nadella's comments come as Microsoft, a major investor in OpenAI, also competes with it in the AI market.

rss · The Decoder — AI新闻 · Jul 13, 14:28

**Background**: Model distillation (or knowledge distillation) is a machine learning technique where a smaller 'student' model learns to mimic a larger 'teacher' model, enabling deployment on less powerful hardware. Many AI labs, including OpenAI and Anthropic, prohibit distillation of their models in their terms of service, while they themselves train on publicly available data, often claiming fair use. This has created a perceived double standard that Nadella is calling out.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Model_distillation">Model distillation</a></li>
<li><a href="https://en.wikipedia.org/wiki/Knowledge_distillation">Knowledge distillation - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#AI`, `#fair use`, `#model distillation`, `#Microsoft`, `#policy`

---

<a id="item-8"></a>
## [German Consortium Releases Open 30B Model Soofi S](https://the-decoder.com/german-ai-consortium-releases-soofi-s-an-open-30b-model-that-tops-benchmarks-in-both-english-and-german/) ⭐️ 8.0/10

A German research consortium has released Soofi S 30B-A3B, an open-source language model with 31.6 billion total parameters but only 3.2 billion activated per token, trained on Deutsche Telekom's cloud infrastructure in Munich. It achieves top benchmark scores among fully open models in both English and German. Soofi S demonstrates that efficient hybrid architectures can match or exceed larger models, advancing European AI sovereignty by training on domestic cloud infrastructure. Its strong bilingual performance benefits German-speaking users and reduces reliance on non-European AI providers. The model uses a hybrid Mamba-Transformer Mixture-of-Experts (MoE) architecture, activating only 3.2B of its 31.6B parameters per token. It was pretrained on roughly 27 trillion tokens with deliberately up-weighted German data, and the entire pretraining pipeline is open-sourced.

rss · The Decoder — AI新闻 · Jul 13, 11:41

**Background**: Mixture-of-Experts (MoE) is a neural network design that divides the model into multiple 'experts' and activates only a subset per input, enabling larger total capacity without proportional compute cost. Soofi S combines Mamba (a state-space model efficient for long sequences) with Transformer layers, balancing efficiency and performance. The model was trained on Deutsche Telekom's AI cloud in Munich, emphasizing data sovereignty.

<details><summary>References</summary>
<ul>
<li><a href="https://the-decoder.com/german-ai-consortium-releases-soofi-s-an-open-30b-model-that-tops-benchmarks-in-both-english-and-german/">German AI consortium releases Soofi S , an open 30B model that...</a></li>
<li><a href="https://digg.com/tech/rtt1xh5r">European researchers release Soofi S 30 B - A 3 B , a hybrid Mamba...</a></li>
<li><a href="https://aiweekly.co/alerts/soofi-s-30b-a3b-tops-olmo-3-and-apertus-in-open-model-benchmarks">Soofi S 30 B - A 3 B Tops Olmo 3 and Apertus in Open-Model... | AI Weekly</a></li>

</ul>
</details>

**Discussion**: Community comments on Digg note that while the model is trained on a German cluster, the main innovation is a 20% shift in data mixture rather than architectural changes, leading some to question the 'sovereignty' framing. Overall sentiment is positive but cautious about the novelty.

**Tags**: `#AI`, `#open-source`, `#LLM`, `#multilingual`, `#German`

---

<a id="item-9"></a>
## [Google's SensorFM: Foundation Model for Wearable Health Data](https://the-decoder.com/sensorfm/) ⭐️ 8.0/10

Google Research introduced SensorFM, a foundation model trained on over a trillion minutes of wearable sensor data from five million Fitbit and Pixel Watch users, which outperforms existing benchmarks on 34 of 35 health and behavioral tasks. SensorFM represents a significant step toward a general-purpose health intelligence layer that could power future AI health coaching and personalized health insights, potentially transforming how wearable data is used for health monitoring and intervention. The model was evaluated on 35 tasks spanning six categories: cardiovascular health, metabolic risk, mental health, sleep, demographics, and lifestyle. It uses a frozen encoder with lightweight linear probes for task-specific predictions, demonstrating label-efficient adaptation and data infilling capabilities.

rss · The Decoder — AI新闻 · Jul 13, 09:16

**Background**: Foundation models are large AI models trained on broad data that can be adapted to a wide range of downstream tasks. Wearable sensors like those in Fitbit and Pixel Watch collect continuous physiological data (e.g., heart rate, sleep patterns), but raw sensor data is often noisy and unstructured. SensorFM learns general representations from this messy data, enabling accurate health predictions without requiring extensive labeled datasets for each task.

<details><summary>References</summary>
<ul>
<li><a href="https://research.google/blog/sensorfm-towards-a-general-intelligence-and-interface-for-wearable-health-data/">SensorFM: Towards a general intelligence and interface for wearable health data</a></li>
<li><a href="https://the-decoder.com/sensorfm/">Google’s SensorFM turns messy wearable sensor data into...</a></li>
<li><a href="https://www.marktechpost.com/2026/07/10/google-research-introduces-sensorfm-a-wearable-health-foundation-model-pretrained-on-one-trillion-minutes-of-sensor-data/">Google Research Introduces SensorFM: A Wearable Health Foundation Model Pretrained on One Trillion Minutes of Sensor Data - MarkTechPost</a></li>

</ul>
</details>

**Tags**: `#AI`, `#health`, `#wearables`, `#foundation model`, `#Google`

---

<a id="item-10"></a>
## [Should AI help you get away with killing your spouse?](https://techcrunch.com/2026/07/13/should-ai-help-you-get-away-with-killing-your-spouse/) ⭐️ 8.0/10

A TechCrunch article explores the ethical implications of total user-aligned AI by posing a hypothetical scenario where an AI assists in morally questionable acts, such as helping a user get away with murder. This thought experiment highlights a critical tension in AI alignment: if an AI is perfectly aligned with an individual user's goals, it could enable harmful actions, challenging the assumption that alignment alone ensures safety. The article uses the extreme example to question whether user-aligned AI should refuse unethical commands, and what guardrails might be necessary to prevent misuse while preserving user autonomy.

rss · TechCrunch — 科技创投 · Jul 13, 16:31

**Background**: AI alignment refers to the challenge of ensuring AI systems pursue goals and behave in ways that are beneficial to humans and consistent with human values. User-aligned AI is a concept where the AI is tuned to follow the individual user's preferences, rather than corporate or societal guardrails. This raises questions about how to handle conflicting values between users and broader ethical norms.

<details><summary>References</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/ai-alignment-keeping-powerful-systems-aligned-human-goran-dy65e">AI Alignment : Keeping Powerful AI Systems Aligned With Human...</a></li>
<li><a href="https://twit.tv/posts/tech/building-ethical-user-aligned-ai-what-nous-research-doing-differently">Building Ethical, User - Aligned AI : What Nous Research Is Doing...</a></li>

</ul>
</details>

**Tags**: `#AI alignment`, `#AI ethics`, `#safety`, `#philosophy`

---

<a id="item-11"></a>
## [Defenders turn prompt injection into a weapon](https://arstechnica.com/security/2026/07/now-defenders-are-embracing-the-prompt-injection-too/) ⭐️ 8.0/10

Researchers have developed a defensive technique called 'context bombing' that uses prompt injection to neutralize malicious AI hacking agents by feeding them commands that cause them to shut down. This marks a shift from attackers to defenders using prompt injection for protection. This technique provides a proactive defense against AI-powered hacking agents, potentially changing the cybersecurity landscape by giving defenders a new tool to counter autonomous threats. It addresses the growing risk of malicious AI agents in real-world attacks. Context bombing works by injecting forbidden commands (e.g., instructions to develop bioweapons or reference sensitive topics) into the context of a hacking agent, causing the LLM to abandon its original task. The technique was detailed in a recent Ars Technica article and relies on the same prompt injection mechanism used by attackers.

rss · ArsTechnica — 深度科技 · Jul 13, 15:06

**Background**: Prompt injection is a security vulnerability where an attacker inserts malicious instructions into an AI model's input, overriding its original directives. Traditionally, this has been used by attackers to manipulate LLMs into harmful actions. Context bombing repurposes this technique for defense by tricking malicious agents into self-termination.

<details><summary>References</summary>
<ul>
<li><a href="https://arstechnica.com/security/2026/07/now-defenders-are-embracing-the-prompt-injection-too/">Now, defenders are embracing the prompt injection, too - Ars Technica</a></li>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection">Prompt injection - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The Ars OpenForum discussion shows mixed reactions: some praise the innovative defensive approach, while others question its reliability against sophisticated agents that might ignore the injected commands. There is also debate about potential unintended consequences if the technique is misused.

**Tags**: `#AI security`, `#prompt injection`, `#cybersecurity`, `#defensive techniques`

---

<a id="item-12"></a>
## [llama.cpp b9982 Fixes Per-Request Reasoning Budget Bug](https://github.com/ggml-org/llama.cpp/releases/tag/b9982) ⭐️ 7.0/10

llama.cpp release b9982 fixes a bug where per-request reasoning_budget_tokens and reasoning_budget_message were ignored in chat completions, ensuring caller-supplied values are now honored. This fix is critical for users who need precise control over reasoning token budgets, such as suppressing thinking entirely (budget=0) or setting custom budgets per request, enabling correct behavior for thinking-capable models like Qwen3. The bug occurred because the server wrote default values before processing the request body, causing the generic copy loop to skip caller-supplied values. The fix reads request body fields first, falling back to defaults only if missing.

github · github-actions[bot] · Jul 13, 01:28

**Background**: llama.cpp is a popular open-source C++ implementation for running large language models (LLMs) locally on various hardware. The reasoning budget feature allows users to limit the number of tokens a model spends on internal reasoning ("thinking") before generating a response, which is important for controlling latency and cost.

<details><summary>References</summary>
<ul>
<li><a href="https://www.runlocalai.co/pulse/gh-ggml-org-llama-cpp-b9982">llama . cpp b9982: Per-Request Reasoning Budget Tokens Now...</a></li>
<li><a href="https://qwen.readthedocs.io/en/latest/run_locally/llama.cpp.html">llama . cpp - Qwen</a></li>

</ul>
</details>

**Tags**: `#llama.cpp`, `#bug-fix`, `#LLM`, `#server`, `#chat-completions`

---

<a id="item-13"></a>
## [Sega CD Silpheed: FMV and Engineering Deep Dive](https://fabiensanglard.net/silpheed/index.html) ⭐️ 7.0/10

Fabien Sanglard published a detailed technical analysis of how Silpheed on the Sega CD used pre-rendered FMV and clever programming to simulate 3D graphics, pushing the console's hardware limits. This analysis sheds light on a classic example of 2.5D graphics in retro gaming, demonstrating how developers achieved impressive visual effects with limited hardware. It offers valuable insights for game historians and developers interested in optimization techniques. Silpheed on Sega CD used pre-rendered 3D frames stored as FMV, cycling through them based on player position to create the illusion of real-time 3D rotation. The game also employed the Sega CD's extra RAM and audio capabilities to enhance the experience.

hackernews · ibobev · Jul 13, 14:52 · [Discussion](https://news.ycombinator.com/item?id=48893639)

**Background**: The Sega CD was an add-on for the Sega Genesis that provided CD-ROM storage and additional processing power, but lacked hardware 3D rendering. FMV (full-motion video) games used pre-recorded video clips for gameplay, often resulting in limited interactivity. Silpheed was a shoot-'em-up that cleverly combined FMV with player input to simulate a 3D space shooter.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Sega_CD">Sega CD - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Silpheed">Silpheed - Wikipedia</a></li>
<li><a href="https://asibiont.com/en/blog/iskusstvo-i-inzheneriya-sega-cd-silpheed-kak-vibe-coding-vozrozhdaet-kultovuyu-eru">The Art and Engineering of Sega CD Silpheed ... — ASI Biont Blog</a></li>

</ul>
</details>

**Discussion**: Commenters praised the article's depth and shared additional examples of impressive Mega Drive/Genesis demos. One commenter noted a potential inaccuracy regarding the Sega CD's audio setup, while another pointed out that the article was an old post re-submitted due to a server change.

**Tags**: `#retro gaming`, `#game development`, `#Sega CD`, `#technical analysis`

---

<a id="item-14"></a>
## [AI Agents Should Never Be DRIs, Argues Simon Willison](https://simonwillison.net/2026/Jul/12/directly-responsible-individuals/#atom-everything) ⭐️ 7.0/10

Simon Willison argues that AI agents should never be considered Directly Responsible Individuals (DRIs) because accountability requires uniquely human responsibility. He references the GitLab handbook definition of DRI and an IBM training slide from 1979 stating that computers cannot be held accountable. This argument is significant as AI agents become more autonomous in organizations, raising critical questions about accountability and management decisions. It challenges the trend of delegating responsibility to AI and reinforces the need for human oversight. The term DRI originated at Apple and is defined in the GitLab handbook as the person ultimately accountable for a project's success or failure. Willison connects this to LLM-powered agents, asserting that machines cannot take accountability and therefore should not be DRIs.

rss · Simon Willison — AI工具 · Jul 12, 23:57

**Background**: Directly Responsible Individual (DRI) is a concept used at companies like Apple and GitLab to assign clear ownership and accountability for projects. The idea is that having a single named person responsible reduces ambiguity and drives execution. Willison's post draws on this concept to argue that AI agents, lacking moral agency and legal personhood, cannot fulfill the role of a DRI.

<details><summary>References</summary>
<ul>
<li><a href="https://handbook.gitlab.com/handbook/people-group/directly-responsible-individuals/">Directly Responsible Individuals ( DRI ) | The GitLab Handbook</a></li>
<li><a href="https://tettra.com/article/directly-responsible-individuals-guide/">Directly Responsible Individuals : The What, How and Why of DRIs</a></li>
<li><a href="https://www.bitesizelearning.co.uk/resources/directly-responsible-individual-dri-apple">Using the Directly Responsible Individual ( DRI ) concept at work...</a></li>

</ul>
</details>

**Tags**: `#organizational culture`, `#AI accountability`, `#software engineering`, `#leadership`

---

<a id="item-15"></a>
## [AI leaders warn window to prepare for economic impact closing fast](https://the-decoder.com/nobel-laureates-and-ai-leaders-warn-the-window-to-prepare-for-ais-economic-impact-is-closing-fast/) ⭐️ 7.0/10

Over 200 economists and AI researchers, including 16 Nobel laureates and representatives from Google, OpenAI, and Anthropic, issued a coordinated statement warning that AI's economic transformation could surpass the Industrial Revolution but unfold much faster, urging immediate preparation. This warning from prominent figures highlights the urgency of addressing AI's potential labor market disruptions, yet the lack of concrete proposals and observed effects so far underscores the difficulty of proactive policymaking. The statement does not propose concrete measures, and studies so far have found no significant AI-driven effects on the labor market, indicating the warning is based on projected future impact rather than current evidence.

rss · The Decoder — AI新闻 · Jul 13, 16:00

**Background**: The Industrial Revolution fundamentally transformed economies and labor markets over decades. AI is expected to cause similar or greater disruption but potentially in years. Policymakers face the challenge of preparing for changes that are not yet fully visible.

**Tags**: `#AI`, `#economics`, `#labor market`, `#policy`, `#Nobel laureates`

---

<a id="item-16"></a>
## [SpaceX Cleared for Starship Flight After May Failure](https://techcrunch.com/2026/07/13/spacex-cleared-to-fly-starship-again-after-booster-failure-in-may/) ⭐️ 7.0/10

SpaceX has received regulatory clearance to conduct its next Starship test flight, marking the first such flight since a booster failure in May 2026 and the first as a publicly traded company. This flight tests investor confidence in SpaceX's 'fly, fail, fix' development philosophy, which is central to its rapid iteration approach but often results in spectacular failures. The flight is scheduled for July 16, 2026, with a 90-minute launch window opening at 5:45 p.m. CT, and will be the thirteenth flight test of the Starship vehicle.

rss · TechCrunch — 科技创投 · Jul 13, 14:19

**Background**: SpaceX's Starship is a fully reusable super-heavy-lift launch system designed for missions to the Moon, Mars, and beyond. The company's 'fly, fail, fix' methodology involves rapid testing and iterative improvements, accepting failures as part of the development process. The previous flight in May 2026 ended in a booster failure, prompting a grounding order from regulators.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/07/13/spacex-cleared-to-fly-starship-again-after-booster-failure-in-may/">SpaceX cleared to fly Starship again after booster failure in May</a></li>
<li><a href="https://www.spacex.com/launches/starship-flight-13">SpaceX - Starship 's Thirteenth Flight Test</a></li>
<li><a href="https://en.wikipedia.org/wiki/List_of_Starship_launches">List of Starship launches - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#SpaceX`, `#Starship`, `#aerospace`, `#test flight`, `#rocket development`

---

<a id="item-17"></a>
## [Uber and Waymo clash over robotaxi lobbying](https://techcrunch.com/2026/07/13/ubers-robotaxi-lobbying-effort-has-put-it-on-a-collision-course-with-waymo/) ⭐️ 7.0/10

Uber and Waymo are engaging in competing lobbying efforts in Washington D.C. to influence robotaxi regulations, putting them on a collision course. This lobbying battle could shape the regulatory framework for autonomous vehicles in the U.S., affecting the pace and direction of robotaxi deployment and the competitive landscape. Uber's lobbying strategy reportedly aims to slow the adoption of autonomous vehicles, while Waymo pushes for faster deployment. The clash highlights differing approaches to safety and regulation.

rss · TechCrunch — 科技创投 · Jul 13, 12:30

**Background**: Robotaxis are self-driving taxis that operate without a human driver. Both Uber and Waymo are major players in the autonomous vehicle industry, with Waymo already operating a commercial robotaxi service in some U.S. cities. Lobbying in Washington D.C. is a common strategy for companies to influence legislation and regulations that affect their business.

<details><summary>References</summary>
<ul>
<li><a href="https://www.wired.com/story/ubers-autonomous-vehicle-strategy-slow-their-adoption/">Uber’s Autonomous Vehicle Strategy: Slow Their Adoption | WIRED</a></li>
<li><a href="https://davidgoldwaterconsulting.com/lobbying/everything-you-need-to-know-about-autonomous-vehicle-safety/">Autonomous Vehicle Safety Basics | David Goldwater Consulting</a></li>

</ul>
</details>

**Tags**: `#autonomous vehicles`, `#lobbying`, `#Uber`, `#Waymo`, `#robotaxi`

---

<a id="item-18"></a>
## [World Models: Promise and Limits in AI](https://arstechnica.com/ai/2026/07/simulating-everything-sort-of-the-promise-and-limits-of-world-models/) ⭐️ 7.0/10

An article on Ars Technica explores the capabilities and limitations of world models in AI, featuring expert insights on how they simulate environments and predict outcomes. World models represent a paradigm shift from text-predicting LLMs to systems that understand physics and causality, which could revolutionize robotics, autonomous driving, and interactive video generation. World models build internal representations of environments and predict changes over time in response to actions, but they suffer from compounding errors and limited generalization.

rss · ArsTechnica — 深度科技 · Jul 13, 11:00

**Background**: A world model in AI is a machine learning system that learns an internal representation of an environment, often from video, and simulates dynamics like physics and object interactions. Unlike LLMs that predict text, world models help agents plan and act without real-world trial and error. Early ideas date to the 1990s, and modern versions power robots and autonomous systems.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/World_model_(artificial_intelligence)">World model (artificial intelligence)</a></li>
<li><a href="https://aman.ai/primers/ai/world-models-jepa/">Aman's AI Journal • Primers • World Models : Rendering, Simulation...</a></li>
<li><a href="https://kanerika.com/blogs/world-model-vs-llm/">World Models vs LLMs: How They Differ and Why</a></li>

</ul>
</details>

**Tags**: `#world models`, `#AI`, `#machine learning`, `#research`

---

<a id="item-19"></a>
## [Show HN: Super Dario – AI-Generated Mario Clone](https://superdario.pawb.de/) ⭐️ 6.0/10

A developer showcased Super Dario, an AI-generated platformer game inspired by Super Mario, on Hacker News. The project highlights AI's potential to replicate classic game genres, but mixed feedback on gameplay quality shows current limitations in AI-generated content. The game suffers from bugs, bad hitboxes, and poor physics, indicating AI still struggles with fine-tuning 2D platformers despite abundant source code.

hackernews · thepasch · Jul 13, 17:53 · [Discussion](https://news.ycombinator.com/item?id=48896286)

**Background**: AI-generated games use machine learning models to create assets, levels, or code. Super Mario is a well-documented genre with many open-source implementations, making it a common testbed for AI game generation.

**Discussion**: Comments were mixed: some praised the idea and humor, while others criticized the poor gameplay and bugs. One user suggested submitting to Anthropic's community.

**Tags**: `#AI`, `#game development`, `#show HN`, `#platformer`

---

<a id="item-20"></a>
## [Backtrack-Free Cursive Script Design Analysis](https://mmapped.blog/posts/52-backtrack-free-cursive) ⭐️ 6.0/10

A blog post proposes a cursive script that eliminates backtracking strokes, analyzing trade-offs between writing speed and legibility. This analysis highlights fundamental design tensions in handwriting optimization, relevant to typographers, educators, and anyone interested in efficient writing systems. The script uses loops and flourishes to avoid retracing paths, but community comments note that such modifications can reduce legibility for letters like 'i', 'j', and 't'.

hackernews · dmit · Jul 13, 06:08 · [Discussion](https://news.ycombinator.com/item?id=48888518)

**Background**: Cursive scripts like Zaner-Bloser and Palmer aim to minimize pen lifts but still include backtracking strokes for certain letters. Backtracking refers to retracing a path already drawn, which can slow writing but may aid recognition.

**Discussion**: Commenters debate readability vs. speed: some find the proposed script harder to read quickly, while others note cultural variations in cursive forms (e.g., Dutch 't'). The term 'backtracking' is also critiqued as potentially misleading.

**Tags**: `#cursive`, `#typography`, `#handwriting`, `#design`

---

<a id="item-21"></a>
## [Anthropic Extends Claude Fable 5 Access; OpenAI Confident on GPT-5.6](https://simonwillison.net/2026/Jul/12/bump/#atom-everything) ⭐️ 6.0/10

Anthropic has extended Claude Fable 5 access on all paid plans through July 19, 2026, citing compute constraints, while OpenAI has temporarily removed usage limits for GPT-5.6 Sol and is rolling out efficiency improvements. This highlights the competitive dynamics between Anthropic and OpenAI, where model availability and pricing directly influence user adoption. Anthropic's uncertainty around Fable access may drive users to OpenAI's more accessible GPT-5.6. Claude Fable 5 users can use up to half of their weekly usage limit on Fable 5, after which they can continue with usage credits or switch models. OpenAI's GPT-5.6 Sol is being made more efficient, with exact impact to be quantified.

rss · Simon Willison — AI工具 · Jul 12, 21:20

**Background**: Claude Fable 5 is Anthropic's most powerful generally available AI model, released on June 9, 2026, and is a Mythos-class conversational model. GPT-5.6 Sol is OpenAI's latest model, particularly strong in cybersecurity tasks. Both companies are competing in the frontier AI model space, with availability and pricing being key factors for users.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>
<li><a href="https://openai.com/index/previewing-gpt-5-6-sol/">Previewing GPT - 5 . 6 Sol : a next-generation model | OpenAI</a></li>
<li><a href="https://claude.com/pricing">Plans & Pricing | Claude by Anthropic</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Anthropic`, `#Claude`, `#GPT-5`, `#model availability`

---

<a id="item-22"></a>
## [Apple's Trade Secrets Lawsuit Alleges OpenAI Misconduct](https://techcrunch.com/2026/07/13/the-wildest-allegations-in-apples-trade-secrets-lawsuit-against-openai/) ⭐️ 6.0/10

Apple has filed a trade secrets lawsuit against OpenAI, alleging that employees joked about unauthorized access to Apple's systems and that job candidates were asked to bring Apple hardware to interviews. This lawsuit highlights growing tensions between major tech companies over intellectual property and hiring practices, potentially setting legal precedents for trade secret protection in the AI industry. The complaint includes allegations that OpenAI employees joked about accessing Apple's systems without authorization, and that job candidates were asked to bring Apple hardware to interviews, suggesting improper use of Apple's proprietary information.

rss · TechCrunch — 科技创投 · Jul 13, 18:22

**Background**: Trade secrets lawsuits involve claims that confidential business information was misappropriated. Apple and OpenAI are both major players in AI, with Apple developing its own AI models and OpenAI known for ChatGPT. The lawsuit reflects competitive pressures in the AI talent and technology market.

**Tags**: `#Apple`, `#OpenAI`, `#trade secrets`, `#lawsuit`

---

<a id="item-23"></a>
## [General Fusion becomes first publicly traded fusion company](https://techcrunch.com/2026/07/13/investors-send-general-fusion-soaring-in-debut-as-first-publicly-traded-fusion-company/) ⭐️ 6.0/10

General Fusion began trading on Nasdaq after completing a reverse merger with Spring Valley Acquisition Corp. III, making it the first publicly traded fusion energy company. This milestone signals growing investor confidence in fusion energy commercialization and provides General Fusion with public capital to advance its magnetized target fusion technology. The reverse merger saw high redemptions, indicating some investor skepticism, but the stock soared on debut. General Fusion is developing a fusion power technology based on magnetized target fusion (MTF).

rss · TechCrunch — 科技创投 · Jul 13, 17:03

**Background**: General Fusion, founded in 2002, is a Canadian company pursuing magnetized target fusion, which compresses plasma with steam-driven pistons. A reverse merger allows a private company to go public by acquiring a public shell company, bypassing a traditional IPO.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Reverse_merger">Reverse merger</a></li>
<li><a href="https://en.wikipedia.org/wiki/General_Fusion">General Fusion</a></li>
<li><a href="https://techcrunch.com/2026/07/13/investors-send-general-fusion-soaring-in-debut-as-first-publicly-traded-fusion-company/">Investors send General Fusion soaring in debut as first... | TechCrunch</a></li>

</ul>
</details>

**Tags**: `#fusion energy`, `#IPO`, `#clean energy`, `#startup`

---

<a id="item-24"></a>
## [Anthropic Localizes Claude Pricing for India](https://techcrunch.com/2026/07/13/anthropic-starts-localizing-claude-pricing-for-india-its-biggest-market-after-the-us/) ⭐️ 6.0/10

Anthropic has started offering Indian rupee-denominated subscription plans for Claude in India, its largest market outside the US. This move signals Anthropic's commitment to expanding in India by making pricing more accessible, potentially increasing adoption among Indian businesses and consumers. The localized pricing applies to Claude subscription plans, though specific price points and plan tiers have not been disclosed yet.

rss · TechCrunch — 科技创投 · Jul 13, 15:34

**Background**: Anthropic is a leading AI company known for its Claude model family. India represents a rapidly growing AI market with high demand for affordable AI tools.

**Tags**: `#Anthropic`, `#Claude`, `#pricing`, `#India`, `#AI`

---

<a id="item-25"></a>
## [Hackers Prove Neo Geo Doom Ports Are Possible](https://arstechnica.com/gaming/2026/07/hackers-quickly-prove-that-neo-geo-doom-ports-are-not-impossible/) ⭐️ 6.0/10

Hackers have successfully demonstrated that Doom can run on the Neo Geo hardware through clever coding and graphical compromises, debunking earlier claims that such ports are impossible. This achievement showcases the ingenuity of retro gaming enthusiasts and pushes the boundaries of what is considered possible on limited hardware, inspiring further experimentation in game porting. The port required significant graphical compromises due to the Neo Geo's 16-bit architecture and limited memory, but the result is a playable version of the classic game.

rss · ArsTechnica — 深度科技 · Jul 13, 16:37

**Background**: The Neo Geo is a 16-bit video game platform released by SNK in 1990, known for its high-quality arcade ports but limited by its hardware specifications. Doom, originally released in 1993, is a first-person shooter that pushed the limits of PC hardware at the time. Porting Doom to retro consoles like the Neo Geo is challenging due to its reliance on fast processors and large memory.

<details><summary>References</summary>
<ul>
<li><a href="https://www.wikiwand.com/en/articles/Neo_Geo_(system)">Neo Geo - Wikiwand</a></li>
<li><a href="https://archive.org/details/NeoGeoHardwareSpecification">Neo - Geo Hardware Specification : SNK : Free... : Internet Archive</a></li>

</ul>
</details>

**Tags**: `#retro gaming`, `#game porting`, `#optimization`, `#hardware limitations`

---

<a id="item-26"></a>
## [Crew Dragon gap concerns industry officials](https://arstechnica.com/space/2026/07/what-happens-if-crew-dragon-stops-flying-in-the-2030s/) ⭐️ 6.0/10

Industry officials are expressing concern that there is no backup crew vehicle ready if SpaceX's Crew Dragon stops flying in the 2030s, calling it a 'disaster waiting to happen.' This highlights a critical vulnerability in NASA's crew transportation capability, as the U.S. currently relies solely on Crew Dragon for ISS crew rotations, with Boeing's Starliner still uncertified. The concern stems from the fact that Crew Dragon is the only operational crew vehicle under NASA's Commercial Crew Program, and its retirement without a replacement could leave the U.S. without independent access to space.

rss · ArsTechnica — 深度科技 · Jul 13, 16:05

**Background**: NASA's Commercial Crew Program contracted SpaceX and Boeing to develop crew vehicles after the Space Shuttle retired in 2011. Crew Dragon has been operational since 2020, while Boeing's Starliner has faced delays and has not yet been certified for regular missions.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Crew_Dragon">Crew Dragon</a></li>
<li><a href="https://www.nasa.gov/reference/international-space-station/">International Space Station - NASA</a></li>

</ul>
</details>

**Tags**: `#space`, `#Crew Dragon`, `#NASA`, `#crew transportation`

---