Updated at 2025-02-20 18:24:48 (UTC+8)

### 1. Magma: A foundation model for multimodal AI agents

 Score: 182 Comments: 32 [Link](https://microsoft.github.io/Magma/)

 > Magma is a multimodal foundation model by Microsoft that integrates verbal, spatial, and temporal intelligence to enable AI agents to interpret, plan, and act in digital and physical environments. It uses Set-of-Mark (SoM) for action grounding and Trace-of-Mark (ToM) for temporal planning, trained on diverse datasets including UI navigation, robotics, and videos. Magma achieves state-of-the-art performance in tasks like UI navigation and robot manipulation, outperforming specialized models, while maintaining strong multimodal understanding with less training data than competitors.

### 2. 1972 Unix V2 "Beta" Resurrected

 Score: 309 Comments: 52 [Link](https://www.tuhs.org/pipermail/tuhs/2025-February/031420.html)

 > Yufeng Gao successfully resurrected a 1972 UNIX V2 "Beta" from DECtape archives (s1/s2), creating a functional system with a kernel bridging V1 and V2. This kernel supports V1/V2 binaries, has a 16 KiB core, and lacks V2 syscalls, suggesting it's transitional. Using emulators and manual disk image adjustments, he booted it on a specific PDP-11 emulator, overcoming compatibility issues. The restored system, including user directories and tools, highlights /usr stored on RF disk instead of RK. The work offers insights into early UNIX development between versions 1 and 2.

### 3. FAQ on Microsoft's topological qubit thing

 Score: 88 Comments: 12 [Link](https://scottaaronson.blog/?p=8669)

 > Microsoft announced the first topological qubit, Majorana-1, using nonabelian anyons for potential error resilience, though experts remain cautious due to a retracted 2018 claim. If validated, it marks a milestone in quantum computing, but practical utility remains distant. Traditional qubit approaches (superconducting, trapped-ion) still lead in scalability and control. Topological qubits must prove vastly superior to leapfrog existing methods, akin to transistors surpassing vacuum tubes. Microsoft’s long-term commitment stands out, but scaling to useful quantum systems remains speculative.

### 4. When imperfect systems are good: Bluesky's lossy timelines

 Score: 585 Comments: 217 [Link](https://jazco.dev/2025/02/19/imperfection/)

 > Bluesky addressed performance issues in their timeline system by introducing "Lossy Timelines," which probabilistically drop writes for users following excessive accounts, reducing database strain. This trade-off sacrifices perfect consistency for scalability, cutting P99 latencies by over 96% and eliminating hot shards. The approach balances user experience with system efficiency, demonstrating how strategic imperfection enhances large-scale system performance.

### 5. Softmax forever, or why I like softmax

 Score: 53 Comments: 18 [Link](https://kyunghyuncho.me/softmax-forever-or-why-i-like-softmax/)

 > The author advocates for softmax over alternatives like the harmonic formulation, highlighting its interpretable gradients (which push probabilities toward the target class) and connection to maximum entropy principles. They critique the harmonic method for unstable optimization dynamics, noting its gradients diverge near zero and vanish elsewhere, leading to unreliable learning signals. Softmax’s smooth, intuitive behavior contrasts with the harmonic approach’s sensitivity to initialization and parameter symmetry issues. Despite modern optimization tools, the author argues softmax’s robustness and theoretical grounding make it preferable. The post concludes by questioning whether modifications could salvage the harmonic method but remains skeptical.

### 6. The Plan 9 Foundation

 Score: 39 Comments: 17 [Link](https://plan9foundation.org/)

 > The Plan 9 Foundation is an Oregon nonprofit preserving and advancing the Plan 9 operating system, originally developed at Bell Labs. It maintains historical archives, hosts conferences, supports development via mentorship programs, Google Summer of Code participation, and hackathons, and provides access to source code and documentation for ongoing innovation.

### 7. Show HN: Subtrace – Wireshark for Docker Containers

 Score: 265 Comments: 57 [Link](https://github.com/subtrace/subtrace)

 > Subtrace is an open-source tool designed as "Wireshark for Docker containers," enabling developers to monitor network traffic (incoming/outgoing requests) in Docker environments without code changes. It supports all programming languages, provides full payload visibility, headers, status codes, and latency metrics with minimal performance overhead (under 100µs). Built on ClickHouse, it offers out-of-the-box functionality for debugging production issues. While open-source under BSD-3-Clause, it currently does not accept pull requests due to the team's limited resources.

### 8. Run structured extraction on documents/images locally with Ollama and Pydantic

 Score: 90 Comments: 22 [Link](https://github.com/vlm-run/vlmrun-hub)

 > The **VLM Run Hub** is a GitHub repository offering industry-specific Pydantic schemas for extracting structured data from images, videos, and documents using Vision Language Models (VLMs). It provides validated, type-safe schemas for domains like invoices, medical records, and retail, enabling seamless integration with models like GPT-4o and Claude. The hub simplifies visual ETL workflows, ensures data validation, and supports contributions for expanding its schema catalog.

### 9. Show HN: Mastra – Open-source JS agent framework, by the developers of Gatsby

 Score: 369 Comments: 125 [Link](https://github.com/mastra-ai/mastra)

 > Mastra is a TypeScript framework for building AI applications with features like agents, workflows, RAG, integrations, and evals. It supports LLM providers like OpenAI, Anthropic, and Google Gemini via the Vercel AI SDK, and includes tools for model routing, API integrations, and automated testing. Developers can quickly start projects using the `create-mastra` CLI and run a local playground with `npm run dev`. Currently in Alpha, Mastra has 2.3k GitHub stars and encourages community contributions. It offers serverless deployment options and detailed documentation for workflows, tools, and evaluations.

### 10. Obscura VPN – Privacy that's more than a promise

 Score: 102 Comments: 26 [Link](https://obscura.net/)

 > Obscura VPN emphasizes privacy by design, ensuring it cannot log user activity by separating identity (via randomized accounts) and traffic using a two-party protocol with independent exit nodes (e.g., Mullvad). It employs WireGuard-over-QUIC encryption to evade censorship and avoid traffic correlation, accepts Bitcoin for anonymous payments, and offers open-source verification for transparency. Unlike traditional VPNs, Obscura’s architecture prevents even internal access to user data, prioritizing provable privacy over trust-based claims.

### 11. The 8-Bit Era's Weird Uncle: The TI-99/4A

 Score: 106 Comments: 53 [Link](https://bumbershootsoft.wordpress.com/2025/02/15/the-8-bit-eras-weird-uncle-the-ti-99-4a/)

 > The article explores the Texas Instruments TI-99/4A, an 8-bit home computer from the early 1980s that failed commercially but left a lasting legacy through its innovative graphics (TMS9918A) and sound (SN76489) chips, which influenced consoles like the ColecoVision and Sega Genesis. It details the system's unique architecture, BASIC programming capabilities for tile-based graphics and sprites, and experiments with Extended BASIC for enhanced features. Despite its market struggles, the TI-99/4A's hardware became a foundational curiosity, blending minicomputer design with gaming console elements. The piece concludes by previewing a follow-up on developing cartridge software without relying on BASIC.

### 12. The Forecasting Company (YC S24) Is Hiring

 Score: None Comments: None [Link](https://www.ycombinator.com/companies/the-forecasting-company/jobs/yxUzVUm-founding-machine-learning-engineer)

 > The Forecasting Company, a Paris-based YC startup, seeks a Founding Machine Learning Engineer to develop time-series foundation models for enterprise forecasting (e.g., supply chain, finance). Responsibilities include architecting multimodal models, staying current with ML research, and deploying production systems. Candidates should excel in PyTorch/JAX, have high standards, and optionally possess ML infrastructure or time-series experience. The role offers equity, health insurance, and hybrid Silicon Valley/Paris culture, led by ML PhD founders with industry experience at Amazon, Google, and Bloomberg.

### 13. A tail calling interpreter for Python (already landed in CPython)

 Score: 96 Comments: 58 [Link](https://blog.reverberate.org/2025/02/10/tail-call-updates.html)

 > The article discusses advancements in using tail calls to optimize interpreters, highlighting Python's new tail-calling interpreter (merged for 3.14) achieving 9-15% speed gains, LuaJIT Remake's 31% performance boost via Deegen, and GCC/Clang compiler improvements like `musttail` and `preserve_none` attributes. It also notes a proposal to standardize tail calls in C via `return goto` syntax. These developments validate the author's earlier prediction that tail calls could significantly enhance interpreter performance across languages.

### 14. Requesting SDK for Meta Ray-Ban Smart Glasses for Visually Impaired Users

 Score: 20 Comments: discuss [Link](https://communityforums.atmeta.com/t5/General-VR-MR-Development/Suggestion-for-Developing-an-SDK-for-Meta-Ray-ban-Glasses/td-p/1196341/page/2)

 > A user suggests Meta develop an SDK for Ray-Ban smart glasses to enable third-party app integration, allowing custom voice commands (e.g., smart home control) and camera access for expanded functionalities. Community replies highlight interest in accessibility applications and existing workarounds, like streaming video for computer vision. Developers express frustration over the lack of an official SDK, urging Meta to release tools to unlock innovation and enhance the device's potential.

### 15. Speed matters (2021)

 Score: 29 Comments: 14 [Link](https://www.scattered-thoughts.net/writing/speed-matters/)

 > The article argues that improving coding speed significantly boosts productivity, using the author's projects (strucjure vs. rematch) to show a 5-30x efficiency gain over six years through better processes and decision-making. Increased speed enables more experimentation, faster learning, and tackling ambitious projects by reducing time costs, while small optimizations compound into major gains. It highlights that speed reduces mental strain, allows tool-building for further efficiency, and makes coding more enjoyable, with potential for another 10x improvement through deliberate practice.

### 16. Egg prices are soaring. Are backyard chickens the answer?

 Score: 76 Comments: 161 [Link](https://civileats.com/2025/02/18/op-ed-egg-prices-are-soaring-bring-out-the-backyard-hens/)

 > The article discusses soaring egg prices due to the avian flu outbreak, exacerbated by industry consolidation that leaves production vulnerable. It explores backyard chickens and small-scale poultry operations as resilient alternatives, noting their lower risk of mass infection and potential to diversify supply. While raising backyard hens involves costs, labor, and biosecurity measures, proponents argue it offers food security and reduces reliance on fragile industrial systems. Advocacy groups also allege egg producers may exploit the crisis for profit. Ultimately, the piece suggests decentralized poultry farming could strengthen food resilience amid ongoing outbreaks.

### 17. The Fall of FiveM

 Score: 29 Comments: 8 [Link](https://fivem.team/)

 > 

### 18. Grok 3: Another win for the bitter lesson

 Score: 57 Comments: 65 [Link](https://www.thealgorithmicbridge.com/p/grok-3-another-win-for-the-bitter)

 > Grok 3, developed by xAI, demonstrates state-of-the-art AI performance, attributed to massive compute scaling via a 100K+ GPU cluster, reinforcing the "Bitter Lesson" that prioritizing compute over heuristic optimizations drives progress. While DeepSeek achieved competitive results through engineering ingenuity under GPU constraints, Grok 3 highlights the advantage of scale in the post-training era, where test-time compute and infrastructure dominate. The paradigm shift from pre-training larger models to optimizing post-training compute enables faster advancements, benefiting latecomers like xAI. Despite exceptions, scaling remains critical, positioning well-resourced companies to lead as AI development increasingly hinges on compute access. Grok 3 underscores that raw computational power, not just algorithmic cleverness, remains pivotal in advancing AI capabilities.

### 19. Show HN: A Fast HTTP Request CLI Powered by HTTL

 Score: 24 Comments: 5 [Link](https://httl.dev/docs/cli)

 > HTTL CLI 0.1.7 enables running HTTL queries from the terminal with formatted, colorized output. Installed globally via npm (Node.js ≥16.14), it supports executing queries directly or from files, ideal for automation scripts and CI/CD pipelines. The tool integrates all HTTL language features.

### 20. DOGE has 'god mode' access to government data

 Score: 123 Comments: 139 [Link](https://www.theatlantic.com/technology/archive/2025/02/doge-god-mode-access/681719/)

 > Elon Musk’s Department of Government Efficiency (DOGE) has gained unprecedented "God mode" access to sensitive data across federal agencies like USAID, NASA, and the CDC, enabling control over financial systems, health records, and national-security information. Employees fear misuse of this access, including potential theft of classified data, manipulation of payrolls, and exposure of public-health information, while concerns grow over conflicts of interest with Musk’s private ventures. DOGE’s unchecked power threatens to undermine agency autonomy, compromise security, and enable political or corporate exploitation of Americans’ personal and governmental data. Federal workers report chaotic intrusions, resignations, and legal challenges as DOGE bypasses norms to expand control, risking irreversible harm to public trust and institutional integrity. The situation highlights unprecedented vulnerabilities in federal systems under Musk’s influence, with implications for democracy and national security.

### 21. A secret poker game you can play on the subway

 Score: 245 Comments: 90 [Link](https://experience.prfalken.dev/english/subway-poker/)

 > Subway Poker is a two-player game played during subway commutes where each player selects a row of seats, assigning passengers card values (e.g., child=10, elderly=Ace) to form poker hands. Players compete to create the highest-ranking hand by an agreed end station, using strategies like seat selection and predicting passenger turnover. Adaptable to various subway layouts, it transforms commutes into interactive fun by observing passenger patterns and urban dynamics.

### 22. Scented products cause indoor air pollution on par with car exhaust

 Score: 237 Comments: 99 [Link](https://newatlas.com/environment/indoor-air-pollution-scented-terpenes/)

 > Scented products like wax melts release terpenes that react with indoor ozone, forming nanoparticles comparable to car exhaust pollution, according to a Purdue University study. These ultrafine particles, when inhaled, pose respiratory risks and accumulate in high concentrations similar to those from gas stoves or diesel engines. The research highlights the need for improved ventilation and awareness of indoor air quality impacts from everyday fragranced items.

### 23. F8 – an 8 bit architecture designed for C and memory efficiency [video]

 Score: 27 Comments: 5 [Link](https://fosdem.org/2025/schedule/event/fosdem-2025-4902-f8-an-8-bit-architecture-designed-for-c-and-memory-efficiency/)

 > The f8 is an 8-bit architecture optimized for C programming and memory efficiency, addressing limitations of existing 8-bit processors like MCS-51 in devices such as Realtek WiFi chips. Designed using insights from the Small Device C Compiler (SDCC), it targets applications where RISC-V is overkill and every byte of code/data matters. Presented at FOSDEM 2025 by Philipp K. Krause, it includes Verilog code, documentation, and SDCC support for resource-constrained environments.

### 24. Animate Anyone 2: High-Fidelity Character Image Animation

 Score: 67 Comments: 12 [Link](https://humanaigc.github.io/animate-anyone-2/)

 > Animate Anyone 2 enhances character animation by integrating environmental context and object interactions, addressing prior limitations of isolated character motion. It captures environmental data from videos, uses a shape-agnostic mask strategy for character-environment coherence, and employs an object guider with spatial blending for realistic interactions. A pose modulation technique improves motion diversity. Results show superior fidelity and contextual coherence compared to methods like Viggle and MIMO.

### 25. Relaxed Radix Balanced Trees (2024)

 Score: 157 Comments: 13 [Link](https://peter.horne-khan.com/relaxed-radix-balanced-trees/)

 > Relaxed Radix Balanced (RRB) Trees enhance Clojure-style Persistent Vectors by enabling efficient merges and inserts while retaining near-constant-time operations. They use **size tables** to track cumulative element counts per node, allowing flexible node sizes and relaxed "leftwise dense" constraints. By enforcing invariants like **M..M-1** (nodes have 31–32 children for M=32) or **search step limits** (capping extra lookup steps), RRB Trees balance tree height and minimize rebalancing during merges. Merging splits and redistributes nodes only where necessary, reusing most subtrees to reduce overhead. This achieves O(log n) merge complexity with minimal node creation, improving on Persistent Vectors’ linear-time merging.

### 26. Build your own SQLite in Rust, Part 5: Evaluating queries

 Score: 160 Comments: 16 [Link](https://blog.sylver.dev/build-your-own-sqlite-part-5-evaluating-queries)

 > This article details building a basic SQL query evaluator for a SQLite-like database, focusing on simple `SELECT` statements. It covers modifying the Rust implementation's pager for concurrency, introducing an `OwnedValue` type for data handling, and creating a `SeqScan` operator to read table rows. The evaluator uses a `Planner` to convert parsed SQL into executable operations and integrates it into a REPL for testing, enabling queries like `SELECT * FROM table1` to return results. Future posts will expand features like filtering and sorting.

### 27. What Makes a Great Software Engineer (Dissertation) (2016) [pdf]

 Score: 65 Comments: 26 [Link](https://faculty.washington.edu/ajko/dissertations/Li2016Dissertation.pdf)

 > 

### 28. Broken legs and ankles heal better if you walk on them within weeks

 Score: 481 Comments: 265 [Link](https://www.scientificamerican.com/article/broken-legs-and-ankles-heal-better-if-you-walk-on-them-within-weeks/)

 > 

### 29. KubeVPN: Revolutionizing Kubernetes Local Development

 Score: 13 Comments: discuss [Link](https://github.com/kubenetworks/kubevpn)

 > 

### 30. Multiple Russia-aligned threat actors actively targeting Signal Messenger

 Score: 707 Comments: 258 [Link](https://cloud.google.com/blog/topics/threat-intelligence/russia-targeting-signal-messenger)

 > 

