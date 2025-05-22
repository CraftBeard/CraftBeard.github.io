Updated at 2025-05-22 17:09:20 (UTC+8)

### 1. Gemini Diffusion

 Score: 496 Comments: 119 [Link](https://simonwillison.net/2025/May/21/gemini-diffusion/)

 > Google's Gemini Diffusion is a fast new LLM using diffusion instead of autoregression, generating text by refining noise step-by-step. It achieves speeds like 857 tokens/second, comparable to Gemini 2.0 Flash-Lite but 5x faster. Unlike traditional models, it excels at tasks like editing code or math. It likely still uses transformers but without causal masking. Early tests show impressive performance, though benchmarks are lacking.

### 2. JEP 519: Compact Object Headers

 Score: 14 Comments: 1 comment [Link](https://openjdk.org/jeps/519)

 > JEP 519 proposes to promote compact object headers from an experimental feature to a product feature in JDK 25, citing proven stability, performance improvements (e.g., 22% less heap space in SPECjbb2015), and extensive testing. The change removes the need for `-XX:+UnlockExperimentalVMOptions` when enabling the feature.

### 3. Why does Debian change software?

 Score: 55 Comments: 34 [Link](https://blog.liw.fi/posts/2025/why-debian-changes/)

 > Debian changes software to comply with its policies, ensure compatibility, remove privacy/security risks, fix bugs, and adhere to licensing rules. These modifications aim to improve functionality and user experience while maintaining legal and security standards.

### 4. Decibels Are Ridiculous

 Score: 181 Comments: 99 [Link](https://lcamtuf.substack.com/p/decibels-are-ridiculous)

 > The article criticizes the decibel (dB) as a confusing and inconsistent unit, arguing it’s not a true unit but a logarithmic scale with arbitrary reference points and unclear applications across fields like acoustics and electronics. The author highlights its convoluted history, ambiguous suffixes, and lack of intuitive meaning, calling it a "madness" in scientific measurement.

### 5. Inigo Quilez: computer graphics, mathematics, shaders, fractals, demoscene

 Score: 98 Comments: 13 [Link](https://iquilezles.org/articles/)

 > This article is a collection of written tutorials on computer graphics, mathematics, shaders, fractals, and more by Inigo Quilez. It includes various indices of useful functions, procedural noises, raytracing techniques, and SDF/raymarching methods. The content is freely available under the MIT license, with options to support the author via Patreon or PayPal.

### 6. Kotlin-Lsp: Kotlin Language Server and Plugin for Visual Studio Code

 Score: 86 Comments: 46 [Link](https://github.com/Kotlin/kotlin-lsp)

 > The **Kotlin/kotlin-lsp** repository hosts a pre-alpha **Kotlin Language Server** and **Visual Studio Code plugin**, implementing the Language Server Protocol (LSP) for Kotlin. It supports features like project import, navigation, code actions, and diagnostics, but is experimental and not yet stable. Currently, it works best with VSC on macOS/Linux and requires Java 17+. The project is under active development by JetBrains.

### 7. Direct TLS can speed up your connections

 Score: 32 Comments: 7 [Link](https://marc-bowes.com/postgres-direct-tls.html)

 > A Cisco firewall on AWS corporate networks was causing 3-second delays by opening a second TLS connection to inspect certificates, conflicting with PostgreSQL's TLS protocol. PostgreSQL 17 introduced direct TLS support, allowing clients to skip initial negotiation steps, resolving the delay. This feature is now recommended for Aurora DSQL connections, improving speed without downsides.

### 8. Getting a paper accepted

 Score: 127 Comments: 51 [Link](https://maxwellforbes.com/posts/how-to-get-a-paper-accepted/)

 > Maxwell Forbes shares how minor revisions transformed his rejected paper into an accepted one by focusing on page 1 (title, abstract, Figure 1, introduction) to hook reviewers and ensuring the rest avoids rejection reasons (baselines, ablations, clarity). The changes improved both presentation and scientific value.

### 9. The Lost Decade of Small Data?

 Score: 82 Comments: 24 [Link](https://duckdb.org/2025/05/19/the-lost-decade-of-small-data.html)

 > The article benchmarks DuckDB on a 2012 MacBook Pro, showing it can handle complex analytical queries on large datasets, suggesting single-node solutions like DuckDB could have been viable a decade earlier. Modern hardware offers significant speedups (7–53×), but the qualitative capability was already present in 2012, raising questions about the need for distributed systems during that time.

### 10. For algorithms, a little memory outweighs a lot of time

 Score: 264 Comments: 67 [Link](https://www.quantamagazine.org/for-algorithms-a-little-memory-outweighs-a-lot-of-time-20250521/)

 > Ryan Williams proved a groundbreaking result in computational complexity, showing that a small amount of memory can be as powerful as a lot of time in algorithms—the first major progress in 50 years. His work challenges long-held assumptions and opens new paths to solving the P vs. PSPACE problem. The discovery stunned experts and highlights the surprising power of space in computation.

### 11. Devstral

 Score: 516 Comments: 114 [Link](https://mistral.ai/news/devstral)

 > Mistral AI introduces **Devstral**, an open-source agentic LLM for software engineering tasks, developed with All Hands AI. It outperforms other models on the SWE-Bench Verified benchmark (46.8%) and is lightweight enough for local deployment. Released under Apache 2.0, it’s available via Hugging Face, Ollama, and Mistral’s API. Future updates include a larger version.

### 12. Hotspot: Linux `perf` GUI for performance analysis

 Score: 7 Comments: 2 [Link](https://github.com/KDAB/hotspot)

 > Hotspot is a Linux perf GUI for performance analysis, developed by KDAB. It visualizes `perf.data` files with features like flame graphs, timeline filtering, and off-CPU profiling. Available as an AppImage or through various Linux distros, it supports embedded systems and data export. Licensed under GPL v2+.

### 13. CERN gears up to ship antimatter across Europe

 Score: 155 Comments: 85 [Link](https://arstechnica.com/science/2025/05/cern-gears-up-to-ship-antimatter-across-europe/)

 > CERN has developed a portable containment device to transport antimatter across Europe, enabling more precise measurements by moving it away from interference at its production site. The device, tested with protons, maintains extreme vacuum and superconducting conditions during transit. Successful trials suggest future shipments could reach labs like one in Germany, improving measurement accuracy by over 100 times. The main challenge is maintaining liquid helium levels for cooling.

### 14. ITXPlus: A ITX Sized Macintosh Plus Logicboard Reproduction

 Score: 86 Comments: 19 [Link](https://68kmla.org/bb/index.php?threads/itxplus-a-itx-sized-macintosh-plus-logicboard-reproduction.49715/)

 > The ITXPlus is a Mini-ITX-sized reproduction of the Macintosh Plus logic board, designed to work with modern components like ATX power supplies and VGA output. It uses no original parts, features 4MB of RAM, and will be open-source. The project aims to enable new builds in modern cases while preserving classic Mac functionality.

### 15. Rocky Linux 10 Will Support RISC-V

 Score: 142 Comments: 73 [Link](https://rockylinux.org/news/rockylinux-support-for-riscv)

 > Rocky Linux 10 will officially support RISC-V, including builds for platforms like StarFive VisionFive 2 and QEMU. This community-driven effort, in collaboration with Fedora, marks a step toward broader cross-architecture support. RISC-V is an alternative architecture, so build failures won’t block other releases. Hardware support varies, with some limitations on certain boards. Downloadable images and guides will be available soon.

### 16. Show HN: Display any CSV file as a searchable, filterable, pretty HTML table

 Score: 138 Comments: 26 [Link](https://github.com/derekeder/csv-to-html-table)

 > **Summary:**  
This GitHub project, *CSV to HTML Table*, converts CSV files into searchable, filterable HTML tables using JavaScript. It includes setup instructions, customization options, and dependencies like Bootstrap and jQuery. Users can deploy it via GitHub Pages or a web server and embed it using iframes. The tool is open-source under the MIT License.

### 17. Collaborative Text Editing Without CRDTs or OT

 Score: 228 Comments: 64 [Link](https://mattweidner.com/2025/05/21/text-without-crdts.html)

 > This article presents a simpler alternative to CRDTs and OT for collaborative text editing by using unique IDs for each character and "insert after" operations. It avoids complex algorithms, offers flexibility, and works with server reconciliation. The approach also extends to decentralized settings and includes a helper library, Articulated, for optimized implementation.

### 18. Gemini figured out my nephew’s name

 Score: 115 Comments: 59 [Link](https://blog.nawaz.org/posts/2025/May/gemini-figured-out-my-nephews-name/)

 > The author created an MCP server to let Gemini search his emails, which helped the AI deduce his nephew’s name (Monty) by analyzing email threads and context, despite no direct mention. The process involved iterative searches and tool usage.

### 19. Animated Factorization (2012)

 Score: 250 Comments: 55 [Link](http://www.datapointed.net/visualizations/math/factorization/animated-diagrams/)

 > The article showcases animated factorization diagrams that visually represent numbers as groups of dots, color-coded by their prime factors, offering an engaging way to understand mathematical concepts.

### 20. OpenAI to buy AI startup from Jony Ive

 Score: 728 Comments: 975 [Link](https://www.bloomberg.com/news/articles/2025-05-21/openai-to-buy-apple-veteran-jony-ive-s-ai-device-startup-in-6-5-billion-deal)

 > Bloomberg's page detected unusual network activity and requires CAPTCHA verification to confirm the user is not a robot. The error suggests access issues due to network restrictions or missing browser requirements.

### 21. LLM function calls don't scale; code orchestration is simpler, more effective

 Score: 226 Comments: 81 [Link](https://jngiam.bearblog.dev/mcp-large-data/)

 > Current LLM tool-calling methods struggle with large data due to high costs and inefficiency. Using structured output schemas and code orchestration simplifies processing, avoids hallucinations, and scales better. Code execution enables variables, tool chaining, and scalable transformations. MCP's new output schemas will unlock large-dataset use cases, though secure execution environments remain a challenge. This shift toward AI runtimes improves efficiency for complex tasks.

### 22. The curious tale of Bhutan's playable record postage stamps (2015)

 Score: 108 Comments: 14 [Link](https://thevinylfactory.com/features/the-curious-tale-of-bhutans-playable-record-postage-stamps/)

 > In 1972, Bhutan released playable vinyl record stamps featuring folk songs and national history, created by American adventurer Burt Todd. Initially dismissed as novelties, they’re now highly sought after by collectors, with prices rising sharply. Todd’s innovative stamp designs helped Bhutan gain global philatelic attention.

### 23. Possible new dwarf planet found in our solar system

 Score: 132 Comments: 87 [Link](https://www.minorplanetcenter.net/mpec/K25/K25K47.html)

 > The article is *MPEC 2025-K47*, published on May 21, 2025, providing observational data, orbital elements, and ephemeris for the minor planet *2017 OF201*. It includes details from telescopes like Canada-France-Hawaii and Cerro Tololo-DECam.

### 24. The Machine Stops (1909)

 Score: 91 Comments: 19 [Link](https://standardebooks.org/ebooks/e-m-forster/short-fiction/text/the-machine-stops)

 > In *The Machine Stops*, humanity lives underground, dependent on an omnipotent Machine for survival. Vashti, a devoted follower of the Machine, is visited by her rebellious son Kuno, who warns of its impending collapse. As the Machine fails, society crumbles, and Vashti finally understands Kuno’s warnings before they perish together, embracing human connection in their final moments.

### 25. An upgraded dev experience in Google AI Studio

 Score: 152 Comments: 90 [Link](https://developers.googleblog.com/en/google-ai-studio-native-code-generation-agentic-tools-upgrade/)

 > Google AI Studio now offers native code generation with Gemini 2.5 Pro, multimodal tools (Imagen, Veo, Lyria), and new features like URL Context and Model Context Protocol (MCP) support. Developers can build and deploy apps faster with streamlined workflows and one-click Cloud Run deployment. The platform also introduces enhanced audio capabilities for conversational AI. [Source](https://developers.googleblog.com/en/google-ai-studio-native-code-generation-agentic-tools-upgrade/)

### 26. Dijkstra on Ada

 Score: 42 Comments: 12 [Link](https://craftofcoding.wordpress.com/2014/04/16/dijkstra-on-ada/)

 > Dijkstra harshly criticized the Ada programming language proposals, calling them "technical incompetence" and "an unsalvageable mess." He even joked that Western security relying on Ada would make him feel safer if the Red Army adopted it too. His reviews of the four proposals (red, green, blue, yellow) were scathing, highlighting their flaws and complexity.

### 27. Sorcerer (YC S24) Is Hiring a Lead Hardware Design Engineer

 Score: None Comments: None [Link](https://jobs.ashbyhq.com/sorcerer/6beb70de-9956-49b7-8e28-f48ea39efac6)

 > Sorcerer is hiring a Lead Hardware Design Engineer in San Francisco to design avionics and sensing systems for high-altitude weather balloons. The role involves PCB design, testing, and collaboration with software and mechanical engineers. Candidates need 6+ years of hardware design experience and expertise in circuit design and PCB tools. The position offers $145K–$190K salary, equity, and benefits. Remote work may be considered for exceptional candidates.

### 28. Ancient reptile footprints are rewriting the history of when animals evolved

 Score: 15 Comments: 3 [Link](https://apnews.com/article/oldest-reptile-footprints-australia-963e3c38c8d5782e7ac20f5405f15f89)

 > The domain apnews.com is blocked until May 22, 2025, due to suspected DDoS abuse linked to a specific article. Access is restricted for security reasons.

### 29. Show HN: Confidential computing for high-assurance RISC-V embedded systems

 Score: 89 Comments: 5 [Link](https://github.com/IBM/ACE-RISCV)

 > IBM's ACE-RISCV is an open-source project providing a VM-based trusted execution environment (TEE) for RISC-V systems, focusing on formally verified firmware for secure confidential computing. It supports local attestation and post-quantum cryptography, targeting embedded systems with hardware requirements like RISC-V 64-bit with hypervisor extensions. The project includes a security monitor with formal verification proofs and tools for running confidential workloads. Licensed under Apache 2.0, it is an active research initiative.

### 30. Tales from Mainframe Modernization

 Score: 49 Comments: 20 [Link](https://oppi.li/posts/tales_from_mainframe_modernization/)

 > The author shares quirky experiences modernizing COBOL code, highlighting oddities like base-10 numerics, Spanish redefinitions, string parsing tricks, and an unexplained file with 800 number constants. The article offers a humorous look at legacy mainframe quirks.

