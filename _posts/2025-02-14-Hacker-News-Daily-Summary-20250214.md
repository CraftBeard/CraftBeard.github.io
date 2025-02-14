Updated at 2025-02-14 18:29:31 (UTC+8)

### 1. The New York Stock Exchange to Launch NYSE Texas

 Score: 81 Comments: 30 [Link](https://ir.theice.com/press/news-details/2025/The-New-York-Stock-Exchange-to-Launch-NYSE-Texas/default.aspx)

 > The New York Stock Exchange (NYSE) plans to launch NYSE Texas, a fully electronic exchange headquartered in Dallas, pending regulatory approval. This move capitalizes on Texas’s status as the U.S. state with the most NYSE-listed companies (over $3.7 trillion in market value) and its pro-business environment. NYSE Texas will replace NYSE Chicago after reincorporation, offering global companies access to the southwestern U.S. economy. The exchange aims to leverage Texas’s growth, population, and business-friendly policies. NYSE Group President Lynn Martin highlighted Texas’s role in driving the U.S. economy.

### 2. Extensible WASM Applications with Go

 Score: 52 Comments: 19 [Link](https://go.dev/blog/wasmexport)

 > Go 1.24 introduces `go:wasmexport`, enabling Go functions to be exported as WebAssembly (Wasm) exports for integration with host applications, and supports building WASI reactors for persistent, reusable Wasm modules. Developers can now create long-running Go-based Wasm applications using `-buildmode=c-shared`, allowing multiple calls to exported functions without reinitialization. Enhanced type support simplifies data exchange between Go and Wasm hosts, though limitations like single-threaded execution and pointer constraints remain. These features expand Go's role in Wasm ecosystems, particularly for plugins and cloud services.

### 3. Zed now predicts your next edit with Zeta, our new open model

 Score: 65 Comments: 26 [Link](https://zed.dev/blog/edit-prediction)

 > Zed introduces edit prediction powered by Zeta, an open-source model fine-tuned from Qwen2.5-Coder-7B, enabling users to accept AI-suggested edits via the `tab` key while integrating seamlessly with existing features like language server completions. The model leverages speculative decoding and optimized serving via Baseten and Cloudflare to meet strict latency targets, trained using supervised fine-tuning and direct preference optimization on community-contributed datasets. Currently free during public beta, Zed aims to refine Zeta with user feedback and expand its capabilities.

### 4. Does X cause Y? An in-depth evidence review

 Score: 65 Comments: 12 [Link](https://www.cold-takes.com/does-x-cause-y-an-in-depth-evidence-review/)

 > The article critiques the evidence on whether X causes Y, noting most studies are observational and confounded by variables like wealth or education. A few rigorous studies (e.g., natural experiments, randomized trials) initially seem promising but face replication issues, conflicting results, or contextual limitations. Despite extensive analysis, the author concludes the relationship remains unclear, highlighting the fragility of social science research and advocating for randomized studies. Ultimately, ambiguity persists, leaving readers reliant on intuition or pre-existing beliefs. The piece reflects broader challenges in causal inference across fields like policy, economics, and public health.

### 5. Linux kernel cgroups writeback high CPU troubleshooting

 Score: 23 Comments: 2 [Link](https://dasl.cc/2025/01/01/debugging-our-new-linux-kernel/)

 > The article details debugging a Linux kernel performance issue causing listen overflows on Ubuntu web servers after upgrading from CentOS. Using network analysis, BPF, and system profiling, the team traced the problem to excessive system CPU spikes from kernel `inode_switch_wbs_work_fn` during cgroup transitions after systemd services terminated. By disabling cgroup controllers (`io`, `memory`) for affected services, they resolved the CPU spikes and listen overflows, attributing the issue to a kernel regression in cgroups v2 not present in CentOS’s older kernel.

### 6. Gemini beats everyone on new OCR benchmark

 Score: 29 Comments: 2 [Link](https://arxiv.org/abs/2502.06445)

 > This paper introduces a benchmark for evaluating Vision-Language Models (VLMs) on OCR tasks in dynamic video environments, testing models like Claude-3, Gemini-1.5, and GPT-4o against traditional OCR systems. Using a dataset of 1,477 annotated frames from diverse sources (news, YouTube, ads), results show VLMs often outperform traditional OCR but face challenges like hallucinations and handling stylized/occluded text. The dataset and framework are open-sourced to advance research.

### 7. Privacy Pass Authentication for Kagi Search

 Score: 757 Comments: 254 [Link](https://blog.kagi.com/kagi-privacy-pass)

 > Kagi Search has introduced Privacy Pass, a cryptographic authentication protocol allowing users to search anonymously by generating and redeeming tokens, ensuring Kagi cannot link searches to accounts. Available for paid plans (Professional, Ultimate, etc.), it integrates with browsers like Orion, Firefox, Chrome, and Android, while a new Tor service enhances IP anonymity. The system separates token generation (authenticated via session cookies) from redemption (anonymous searches), preventing user tracking. Customization features are disabled in Privacy Pass mode to preserve anonymity, and tokens expire monthly to avoid linkage. This update strengthens Kagi’s privacy-first approach by making user tracking technically impossible.

### 8. "Homotopical macrocosms for higher category theory" identified as woke DEI grant

 Score: 54 Comments: 21 [Link](https://mathstodon.xyz/@johncarlosbaez/114000054766059217)

 > John Carlos Baez critiques a U.S. Senate report led by Ted Cruz that labels over $2 billion in NSF grants as "woke DEI funding," targeting projects mentioning social justice, race, gender, or environmental justice. Highlighting mathematician Emily Riehl’s category theory grant, flagged for her DEI-related outreach efforts, Baez argues the investigation misrepresents legitimate research as political propaganda. He expresses concern over political interference in science, citing Trump’s executive order against DEI programs and potential threats to academic freedom, fearing a chilling effect on research and possible emigration of scholars.

### 9. Everything about Google Translate crashing React (and other web apps)

 Score: 28 Comments: 22 [Link](https://martijnhols.nl/blog/everything-about-google-translate-crashing-react)

 > Google Translate manipulates the DOM by replacing text nodes with translated content, disrupting React's Virtual DOM and causing crashes (e.g., `removeChild` errors) or stale data when dynamic content isn’t updated. Workarounds like wrapping text in spans or disabling translation exist but are imperfect, and the core conflict between DOM control by apps/extensions remains unresolved. The article urges developers to weigh accessibility against app stability and advocates addressing the issue via Chromium’s bug tracker.

### 10. OCR4all

 Score: 190 Comments: 45 [Link](https://www.ocr4all.org/)

 > OCR4all is a free, open-source tool for optical character recognition, offering flexible processing from manuscripts to mass printings. It includes the LAREX editor for layout/text annotation, integrates with the OCR-D ecosystem, and enables code-free workflow creation via a user-friendly interface. Deployment is simplified with Docker for cross-platform use.

### 11. What if Eye...?

 Score: 243 Comments: 43 [Link](https://eyes.mit.edu/)

 > MIT researchers developed a virtual simulation where digital creatures evolve eyes from scratch, mimicking natural evolutionary pressures like navigation and survival. The experiment showed how different eye types (e.g., compound or camera-like) emerge based on tasks, with solutions like lenses arising independently, mirroring biological evolution. The project includes a public simulator for users to evolve agents and outputs papers, a TEDx talk, and an MIT Museum exhibit exploring artificial vision design principles.

### 12. Yhangry (YC W22) Is Hiring

 Score: None Comments: None [Link](item?id=43045656)

 > The article describes a 422 error (AssertionFailureError) when accessing a URL, caused by "net::ERR_BLOCKED_BY_CLIENT," indicating the request was blocked by the client (e.g., ad blocker or browser settings).

### 13. Phind 2: AI search with visual answers and multi-step reasoning

 Score: 411 Comments: 144 [Link](https://www.phind.com/blog/phind-2)

 > The article cannot be accessed due to a 403 Forbidden error, indicating restricted access. The site *www.phind.com* is verifying the user's humanity and reviewing connection security before allowing entry, likely to prevent automated traffic or ensure safety protocols.

### 14. Evaluating RAG for large scale codebases

 Score: 7 Comments: 2 [Link](https://www.qodo.ai/blog/evaluating-rag-for-large-scale-codebases/)

 > The article discusses Qodo's approach to evaluating Retrieval Augmented Generation (RAG) systems for large-scale codebases, focusing on ensuring accuracy by combining human-curated ground-truth datasets, automated LLM-as-a-judge scoring, and regression testing. Key challenges include verifying correctness on private data and balancing expert input with scalability. They developed a custom LLM evaluator to address shortcomings in existing tools like RAGAS, prioritizing answer correctness and retrieval accuracy. The evaluation integrates into workflows via CLI tools and CI pipelines, streamlining quality assurance. This framework enhances confidence in RAG outputs while adapting to evolving codebases.

### 15. I built an AI company to save my open source project

 Score: 253 Comments: 49 [Link](https://timefold.ai/blog/how-i-built-an-ai-company-to-save-my-open-source-project)

 > The author's open-source project OptaPlanner, developed over a decade at Red Hat, faced discontinuation after IBM's acquisition. To save it, he co-founded Timefold AI, securing VC funding and adopting an open-core model with a SaaS platform. They forked OptaPlanner into Timefold Solver, expanded their team, and launched AI-driven scheduling solutions. Now thriving, Timefold combines open-source innovation with proprietary services to optimize global operations, aiming to eliminate wasteful scheduling.

### 16. Show HN: SQL Noir – Learn SQL by solving crimes

 Score: 280 Comments: 57 [Link](https://www.sqlnoir.com)

 > SQL Noir is an interactive detective game where players solve mysteries by writing and executing SQL queries. Combining storytelling with hands-on learning, it offers a practical way to practice SQL skills while unraveling engaging cases. The game is open-source and available on GitHub.

### 17. Rust: Doubling Throughput with Continuous Profiling and Optimization

 Score: 7 Comments: 2 [Link](https://www.polarsignals.com/blog/posts/2025/02/11/doubling-throughput-with-continuous-profiling-and-optimization)

 > S2, a serverless API for streaming data, leveraged Polar Signals Cloud's continuous profiling to optimize performance. By identifying CPU bottlenecks like SHA256 checksum computations (68.37% CPU usage), a one-line code change enabled hardware acceleration, reducing CPU usage to 31.82% and doubling throughput. Additional fixes addressed redundant CRC32C checksums and inefficient memory allocation. These optimizations enhanced efficiency, cut costs, and doubled capacity without increased compute spend. Polar Signals' profiling provided critical insights for targeted improvements.

### 18. Show HN: A unique generated maze to share with your valentine

 Score: 6 Comments: 3 [Link](https://love.berk.es/)

 > **Lost in Love** by Bèr Kessels is a generative art project that creates personalized mazes using two names as input, generating unique URLs for sharing. Inspired by Ricky Byrne's screenprints, it employs a recursive backtracking algorithm (via TypeScript/p5.js) to animate maze creation, emphasizing aesthetic design. The project, originally built with Rust/Nannou, is open-source on GitHub, allowing customization while prioritizing simplicity in user input.

### 19. Nvidia Security Team: “What if we just stopped using C?” (2022)

 Score: 199 Comments: 98 [Link](https://blog.adacore.com/nvidia-security-team-what-if-we-just-stopped-using-c)

 > NVIDIA's security team transitioned from C to SPARK, a formally verified language, to address cybersecurity challenges by mathematically proving code correctness instead of relying on testing. After a successful 2018 proof-of-concept converting security-sensitive apps to SPARK, they achieved improved security and efficiency, leading to widespread adoption across products. Over 50 developers were trained, with benefits including no performance loss compared to C, reduced audit focus on proven code, and initial skeptics becoming advocates.

### 20. Jooki – Taking Control of a Forgotten Device

 Score: 36 Comments: 5 [Link](https://nv1t.github.io/blog/reviving-jooki/)

 > The article details efforts to revive the defunct Jooki audio player, a device left unusable after its company's bankruptcy. By reverse-engineering its firmware, the author uncovered vulnerabilities like a root backdoor, insecure OTA update mechanisms, and multiple remote code execution (RCE) vectors via exposed HTTP endpoints. They demonstrate methods to regain control, modify configurations, and propose community-driven solutions, including urging the original creators to open-source the hardware. The analysis highlights security flaws and provides steps to bypass restrictions, enabling users to repurpose the device independently. The call to open-source aims to ensure Jooki's longevity through community support.

### 21. MapTCHA, the open-source CAPTCHA that improves OpenStreetMap [video]

 Score: 205 Comments: 31 [Link](https://fosdem.org/2025/schedule/event/fosdem-2025-5879-maptcha-the-open-source-captcha-that-improves-openstreetmap/)

 > MapTCHA is an open-source CAPTCHA that enhances OpenStreetMap (OSM) by using human verification of AI-generated object predictions (e.g., buildings) from aerial imagery. Unlike traditional CAPTCHAs, it avoids third-party data exposure and leverages crowdsourced validation to improve OSM accuracy. Users review mixed images of confirmed and AI-predicted objects, with aggregated votes determining valid additions to OSM. Developed by the Humanitarian OpenStreetMap Team (HOT) using their fAIr AI tool, it aims to expand to more objects and integrate into login systems. This approach combines bot prevention with community-driven mapping improvements.

### 22. Show HN: I made a tiny book using a pen-plotter and AI

 Score: 35 Comments: 9 [Link](https://muffinman.io/blog/the-tiny-book-of-great-joys/)

 > The author created a personalized, handcrafted tiny book for his wife using AI-generated illustrations (Midjourney), a pen plotter, and 3D-printed tools, overcoming challenges like smudged ink and bookbinding inexperience. After refining AI prompts, converting images to vector files via centerline tracing, and experimenting with technical pens, he bound the pages using pamphlet stitching and PVA glue. The book, filled with shared memories and inside jokes, delighted his wife despite minor imperfections. The project spanned AI, design, fabrication, and traditional crafts, highlighting the blend of technology and handmade effort. Ultimately, the heartfelt gift succeeded in breaking their routine and celebrating their relationship.

### 23. Rob Pike: On Bloat

 Score: 81 Comments: 46 [Link](https://docs.google.com/presentation/d/e/2PACX-1vSmIbSwh1_DXKEMU5YKgYpt5_b4yfOfpfEOKS5_cvtLdiHsX6zt-gNeisamRuCtDtCb2SbTafTI8V47/pub?start=false&loop=false&delayms=3000)

 > The article appears to be a Google Slides presentation titled "On Bloat," but the content fails to load properly, displaying error messages about incomplete slides. It includes keyboard shortcuts for presentation controls (e.g., laser pointer, full screen) and options like downloading as PDF/PPTX. The main content about "bloat" is inaccessible due to technical issues.

### 24. LM2: Large Memory Models

 Score: 81 Comments: 19 [Link](https://arxiv.org/abs/2502.06049)

 > LM2 is a decoder-only Transformer enhanced with an auxiliary memory module to improve multi-step reasoning, relational argumentation, and long-context information synthesis. It integrates a memory pathway via cross-attention and gating while preserving original Transformer capabilities. Experiments show LM2 outperforms memory-augmented RMT by 37.1% and Llama-3.2 by 86.3% on BABILong, with a 5.0% gain on MMLU, indicating no degradation in general tasks. The memory module enhances interpretability and effectiveness in tasks like multi-hop inference and numerical reasoning. The work highlights explicit memory's role in advancing Transformer architectures.

### 25. Doge.gov site has been hacked

 Score: 179 Comments: 84 [Link](https://www.404media.co/anyone-can-push-updates-to-the-doge-gov-website-2/)

 > The DOGE.gov website, created to track Elon Musk's government efficiency initiatives, has a security flaw allowing anyone to edit its publicly accessible database via Cloudflare Pages, with examples of unauthorized joke entries already visible. Despite claims of transparency, the site's insecure setup on non-government servers exposes vulnerabilities, as reported by experts to 404 Media.

### 26. NAT Is the Enemy of Low Power Devices

 Score: 53 Comments: 40 [Link](https://blog.golioth.io/nat-is-the-enemy-of-low-power-devices/)

 > NAT complicates communication for low-power devices by requiring frequent keep-alive messages or session reconnections to bypass aggressive timeouts, draining battery life. DTLS 1.2 Connection IDs allow devices to maintain sessions despite changing IP/port mappings, reducing overhead. The Golioth Firmware SDK can disable keep-alives and enable Connection IDs, enabling efficient data transmission with extended sleep intervals. This approach minimizes power consumption for devices sending infrequent data, avoiding costly reconnections. Optimizing these settings helps constrained devices operate longer without sacrificing connectivity.

### 27. Basis of the Kalman Filter [pdf]

 Score: 202 Comments: 30 [Link](https://github.com/tpn/pdfs/blob/master/Understanding%20the%20Basis%20of%20the%20Kalman%20Filter%20Via%20a%20Simple%20and%20Intuitive%20Derivation%20%282012%29.pdf)

 > The article provides an accessible derivation of the Kalman Filter, emphasizing its foundation in combining noisy sensor measurements with dynamic system predictions using probabilistic principles. It simplifies the mathematical underpinnings by leveraging concepts like recursive Bayesian estimation and linear algebra to derive the filter's update equations. The explanation focuses on minimizing estimation error covariance, highlighting the balance between prediction and correction steps. The approach avoids complex matrix manipulations, making the core ideas intuitive for readers new to state estimation. Overall, it demystifies the Kalman Filter by framing it as a weighted average of uncertain information sources.

### 28. Exposing concurrency bugs with a custom scheduler

 Score: 11 Comments: discuss [Link](https://lwn.net/Articles/1007689/)

 > Jake Hillion and Johannes Bechberger developed a custom Linux scheduler using the sched_ext framework to expose concurrency bugs by intentionally introducing delays and random thread scheduling, forcing rare race conditions to surface. This tool, concurrency-fuzz-scheduler, helps reproduce elusive bugs in applications (e.g., Java) by overwhelming threads or altering execution order, issues often masked by Linux’s efficient default scheduler. While effective for testing on developer workstations, it currently suffers from performance overhead and scalability challenges on large systems. Future improvements aim to reduce delays, enhance reliability, and integrate deterministic randomness. The project highlights sched_ext’s potential for innovative scheduling solutions beyond traditional approaches.

### 29. Fewer students are enrolling in doctoral degrees

 Score: 179 Comments: 334 [Link](https://www.nature.com/articles/d41586-025-00425-4)

 > Declining PhD enrollments in countries like Australia, Japan, Brazil, and the UK are attributed to high living costs, inadequate stipends, and limited academic job prospects, risking a talent drain. Experts urge reforms to improve financial support and diversify career pathways, with some nations increasing funding to address the crisis.

### 30. Computing Tricky Probabilities Using Model Counting

 Score: 12 Comments: 3 [Link](https://www.msoos.org/2025/02/computing-tricky-probabilities/)

 > The article explains how to compute complex probabilities using propositional model counting, exemplified by determining the probability of event Z (0.568) when events X (0.4) and Y (0.6) occur exclusively with a 0.8 constraint. By translating causal chains into conjunctive normal form (CNF) and using tools like ganak, intricate dependencies are resolved efficiently. This method scales to real-world scenarios like nuclear safety or financial risk modeling, where interdependent variables demand precise probability calculations. The approach leverages weighted model counting to handle intertwined causal chains and conditional probabilities, surpassing manual or brute-force methods. Applications span critical industries requiring accurate risk assessment.

