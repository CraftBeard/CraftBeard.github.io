Updated at 2025-07-13 17:10:16 (UTC+8)

### 1. Reading Neuromancer for the first time in 2025

 Score: 17 Comments: 6 [Link](https://mbh4h.substack.com/p/neuromancer-2025-review-william-gibson)

 > The article reflects on reading *Neuromancer* for the first time in 2025, praising its lasting influence on cyberpunk despite its dense prose and dated tech assumptions. While Gibson’s vision feels eerily prescient in some areas (AI, VR), it misses others (mobile phones). The book remains a genre-defining classic, shaping sci-fi for decades.

### 2. Bypassing Google's big anti-adblock update

 Score: 671 Comments: 570 [Link](https://0x44.xyz/blog/web-request-blocking/)

 > The author found a bug in Chrome that allowed `webRequestBlocking` (used by adblockers) to work in MV3 by exploiting a legacy WebView ID parameter, bypassing Google's restrictions. They reported it in 2023, and Google patched it in Chrome 118 with no reward, as it wasn't deemed a security issue. The bug highlights how outdated code can undermine major updates.

### 3. Switching to Claude Code and VSCode Inside Docker

 Score: 112 Comments: 52 [Link](https://timsh.org/claude-inside-docker/)

 > The author switched from using ChatGPT and Cursor Pro to running Claude Code inside a Docker container with VSCode for better speed, cost efficiency, and security. They provide a simple guide to set this up, isolating Claude to prevent system-wide access while maintaining functionality. The setup uses GitHub fine-grained tokens for secure repository access. [Read more here](https://timsh.org/claude-inside-docker/).

### 4. Zig's New Async I/O

 Score: 174 Comments: 114 [Link](https://kristoff.it/blog/zig-new-async-io/)

 > Zig introduces a new `Io` interface for async I/O, allowing callers to inject their preferred implementation (blocking, thread pool, green threads, etc.). This design ensures code reusability and optimal performance while supporting concurrency and cancellation. The change decouples async/await from execution models, eliminating function coloring. Standard library implementations will include various event loop options.

### 5. Kimi K2 is a state-of-the-art mixture-of-experts (MoE) language model

 Score: 340 Comments: 81 [Link](https://github.com/MoonshotAI/Kimi-K2)

 > Kimi K2 is a large-scale Mixture-of-Experts (MoE) language model developed by Moonshot AI, featuring 1 trillion total parameters and optimized for agentic capabilities. It includes variants like Kimi-K2-Base and Kimi-K2-Instruct, excelling in coding, reasoning, and tool-use tasks. The model is available via API and supports deployment on inference engines like vLLM and TensorRT-LLM. Released under a Modified MIT License, it offers strong performance in benchmarks.

### 6. MacPaint Art from the Mid-80s Still Looks Great Today

 Score: 876 Comments: 181 [Link](https://blog.decryption.net.au/posts/macpaint.html)

 > The article explores nostalgic MacPaint art from the 1980s, showcasing creative works discovered on Discmaster. The author highlights the charm of early digital art and expresses interest in tracking down the original artists. Plans to explore Amiga-era art are also mentioned.

### 7. Chrome's hidden X-Browser-Validation header reverse engineered

 Score: 176 Comments: 37 [Link](https://github.com/dsekz/chrome-x-browser-validation-header)

 > This GitHub repository provides a toolkit for reverse engineering and generating Chrome's private `x-browser-validation` header, which is used for integrity verification. The header is created by hashing a platform-specific API key combined with the user agent string using SHA-1 and encoding it in Base64. The project includes a Python script to generate the header and details the reverse-engineering process.

### 8. Aeron: Efficient reliable UDP unicast, UDP multicast, and IPC message transport

 Score: 20 Comments: 6 [Link](https://github.com/aeron-io/aeron)

 > Aeron is an open-source project providing efficient, reliable UDP unicast, UDP multicast, and IPC message transport for high-performance applications. It supports Java, C, and C++ clients, focusing on low latency and high throughput. Features include message recording via Aeron Archive and fault-tolerant services with Aeron Cluster. Licensed under Apache-2.0, it’s widely used in financial and low-latency systems.

### 9. Hacking Coroutines into C

 Score: 81 Comments: 22 [Link](https://wiomoc.de/misc/posts/hacking_coroutines_into_c.html)

 > The article explores using coroutines in C to simplify state machine logic in embedded systems, demonstrating a macro-based approach to implement cooperative multitasking without an OS. It contrasts traditional state machines with coroutines, showing improved readability and linear control flow. The author acknowledges the hacky nature of the solution and recommends modern languages like Rust for better async support. A reference to Protothreads is also provided as an alternative approach.

### 10. Hill Space: Neural nets that do perfect arithmetic (to 10⁻¹⁶ precision)

 Score: 13 Comments: 1 comment [Link](https://hillspace.justindujardin.com/)

 > Hill Space introduces a constraint topology (W = tanh(Ŵ) ⊙ σ(M̂)) that enables neural networks to perform discrete selection tasks with machine-precision accuracy, extreme extrapolation, and deterministic convergence. By mapping unbounded weights to a bounded [-1,1] range, it guides optimization toward stable, discrete solutions. This approach allows calculating optimal weights rather than learning them, making neural arithmetic reliable and efficient. Interactive examples demonstrate its effectiveness for mathematical operations.

### 11. C++: Maps on Chains

 Score: 10 Comments: 4 [Link](http://bannalia.blogspot.com/2025/07/maps-on-chains.html)

 > The article explains how to implement a C++ `std::map` with disjoint integer intervals as keys by ensuring a strict weak ordering. It highlights the pitfalls of overlapping intervals and provides a workaround using exceptions. The solution also supports lookup by integers within intervals using heterogeneous lookup.

### 12. Parse, Don't Validate (For C)

 Score: 57 Comments: 16 [Link](https://www.lelanthran.com/chap13/content.html)

 > The article advocates for parsing input data into specific types (like `email_t`) instead of just validating it, ensuring type safety and reducing errors in C programs. By creating opaque types and handling parsing at system boundaries, it prevents misuse, minimizes attack surfaces, and leverages compiler checks to catch mistakes early. This approach enhances security and maintainability by structuring data correctly from the start.

### 13. Experimental imperative-style music sequence generator engine

 Score: 15 Comments: 1 comment [Link](https://github.com/renoise/pattrns)

 > **Summary:**  
Pattrns is an experimental imperative-style music sequence generator engine that works in Rust or Lua, supporting live coding and Tidal Cycles notation. It separates rhythm, gate, and emitter stages for flexible music generation. The project includes documentation, examples, and an online playground, licensed under AGPL-3.0.

### 14. Edward Burtynsky's monumental chronicle of the human impact on the planet

 Score: 40 Comments: 6 [Link](https://www.newyorker.com/culture/photo-booth/earths-poet-of-scale)

 > Edward Burtynsky's photography captures the vast scale of human impact on Earth, documenting industrial landscapes, agriculture, and urbanization. His work highlights the environmental and human costs of rapid economic growth, from mines to factories. While focusing on large-scale transformations, his images also reveal intimate details, creating a powerful visual chronicle of the Anthropocene. His latest work even touches on climate change, showing its growing effects. Burtynsky’s art serves as a profound reflection on humanity’s relationship with the planet.

### 15. Lost Chapter of Automate the Boring Stuff: Audio, Video, and Webcams in Python

 Score: 156 Comments: 9 [Link](https://inventwithpython.com/blog/lost-av-chapter.html)

 > This article presents a deleted chapter from *Automate the Boring Stuff with Python* on working with audio, video, and webcams using Python. It covers recording and playing multimedia content with libraries like OpenCV, Pygame, and ffmpeg, including tasks like taking photos, recording audio/video, and editing files. The chapter also provides practical code examples and explanations for automating multimedia tasks.

### 16. Bayeux Tapestry Will Return to the U.K. In 950 Years

 Score: 10 Comments: 8 [Link](https://news.artnet.com/art-world/bayeux-tapestry-british-museum-loan-2665313)

 > The Bayeux Tapestry, a 230-foot-long textile depicting the Norman Conquest of 1066, will return to the U.K. for the first time in 950 years as part of a historic loan deal between Britain and France. Likely made by English nuns, it will be displayed at the British Museum in a 2026 exhibition. The agreement includes reciprocal loans of treasures like the Sutton Hoo artifacts to France. The deal reflects strengthened cultural ties post-Brexit.

### 17. Programming Affordances That Invite Mistakes

 Score: 25 Comments: 12 [Link](https://thetechenabler.substack.com/p/programming-affordance-when-a-languages)

 > The article discusses how programming languages can unintentionally encourage mistakes due to their design patterns, using a real-world example where a PHP script's `or die()` pattern caused data loss in a psychology study. The author emphasizes that language affordances—natural tendencies in coding—can lead developers astray, advocating for better error handling and language choices to prevent such issues.

### 18. Light exposure at night predicts incidence of cardiovascular diseases

 Score: 108 Comments: 75 [Link](https://www.medrxiv.org/content/10.1101/2025.06.20.25329961v1)

 > A study of over 88,000 UK adults found that brighter nighttime light exposure significantly increased the risk of cardiovascular diseases like coronary artery disease, heart failure, and stroke. Those with the brightest nighttime light had 23-56% higher risks compared to those with darker nights. The findings remained robust after adjusting for lifestyle and genetic factors, suggesting avoiding nighttime light may help reduce cardiovascular risks. The study highlights potential health impacts of circadian disruption. (Preprint, not peer-reviewed.)

### 19. The fish kick may be the fastest subsurface swim stroke yet (2015)

 Score: 216 Comments: 143 [Link](https://nautil.us/is-this-new-swim-stroke-the-fastest-yet-235511/)

 > The article explores the "fish kick," a new underwater swimming technique inspired by fish movements, which may be faster than traditional strokes. Olympic swimmer Misty Hyman demonstrates its potential, though mastering it is challenging. Experts debate its efficiency, but vortices generated by the kick could make it superior to dolphin kicks in certain conditions.

### 20. Two-step system makes plastic from carbon dioxide, water and electricity

 Score: 60 Comments: 17 [Link](https://phys.org/news/2025-06-plastic-carbon-dioxide-electricity.html)

 > Scientists developed a two-step system that converts carbon dioxide, water, and electricity into polyketone plastics. The process first produces ethylene and carbon monoxide electrochemically, then polymerizes them using a palladium catalyst. This method offers a sustainable alternative to petroleum-based plastic production if powered by renewable energy.

### 21. ISRO successfully conducts hot tests of Gaganyaan propulsion system

 Score: 10 Comments: discuss [Link](https://www.thehindu.com/sci-tech/science/isro-successfully-conducts-hot-tests-of-gaganyaan-propulsion-system/article69790839.ece)

 > ISRO successfully conducted two hot tests of the Gaganyaan Service Module Propulsion System on July 3, 2025, validating its configuration. The tests lasted 30 and 100 seconds, demonstrating normal performance and simultaneous operation of thrusters. This marks progress toward India's crewed space mission.

### 22. A better Ghidra MCP server – GhidrAssistMCP

 Score: 81 Comments: 15 [Link](https://github.com/jtang613/GhidrAssistMCP)

 > GhidrAssistMCP is a Ghidra extension that implements the Model Context Protocol (MCP), enabling AI tools and scripts to interact with Ghidra's reverse engineering features via a standardized API. It offers 31 built-in analysis tools, real-time logging, and dynamic tool management. The extension supports HTTP/SSE communication and is compatible with Ghidra 11.4+. Installation is available via binary release or source build.

### 23. Show HN: I made a JSFiddle-style playground to test and share prompts fast

 Score: 32 Comments: 7 [Link](https://langfa.st/)

 > LangFast is a simple, no-signup prompt playground for testing and sharing Jinja2-based prompt templates with dynamic variables. It offers raw LLM results, customizable workspaces, and pay-as-you-go pricing. Created by Eugene to address challenges at Yola.com, it supports collaboration and welcomes feedback.

### 24. HNSW as abstract data structure: video intro to Redis vector sets

 Score: 28 Comments: discuss [Link](https://www.youtube.com/watch?v=kVApsFUeuEA)

 > This video introduces Redis's new Vector Set data type, explaining how it differs from traditional vector databases and demonstrating key commands like VADD and VSIM. The presenter, Salvatore Sanfilippo, also shares practical use cases and encourages viewers to watch at double speed for efficiency. The video has garnered over 4,200 views since its upload on July 8, 2025.

### 25. Malware found in official gravityforms plugin indicating supply chain breach

 Score: 216 Comments: 43 [Link](https://patchstack.com/articles/critical-malware-found-in-gravityforms-official-plugin-site/)

 > Malware was discovered in the official GravityForms plugin, indicating a supply chain attack. The malicious code sent sensitive site data to a suspicious domain (`gravityapi.org`) and allowed remote code execution. A patched version (2.9.13) was released, and the domain was suspended. Indicators of compromise include specific IPs, domains, and file hashes. Users should update immediately and check for infections.

### 26. New Date("wtf") – How well do you know JavaScript's Date class?

 Score: 325 Comments: 196 [Link](https://jsdate.wtf)

 > The article tests knowledge of JavaScript's Date class with verified examples using NodeJS 24.4.0 in the BST timezone (UTC+1).

### 27. Working through 'Writing A C Compiler'

 Score: 144 Comments: 34 [Link](https://jollygoodsw.wordpress.com/2025/03/13/working-through-writing-a-c-compiler/)

 > The author shares their experience working through *Writing a C Compiler*, praising its step-by-step approach, test suite, and practical focus on building a real C compiler. They highlight progress from basic functionality to advanced features and mention their Rust implementation. Future blog posts will detail each chapter.

### 28. Supreme Court's ruling practically wipes out free speech for sex writing online

 Score: 577 Comments: 767 [Link](https://ellsberg.substack.com/p/free-speech)

 > The Supreme Court's ruling allows conservative states to impose strict age-verification laws for online sexually explicit content, effectively nullifying First Amendment protections for writers and artists. These laws enable civil lawsuits and even felony charges for failing to implement invasive ID checks, chilling free speech. The author vows to resist, calling the laws a backdoor ban on adult content.

### 29. Second Variety, by Philip K. Dick (1953)

 Score: 65 Comments: 19 [Link](https://www.gutenberg.org/files/32032/32032-h/32032-h.htm)

 > In *Second Variety* by Philip K. Dick, during a post-apocalyptic war, autonomous killer robots called "claws" evolve into human-like forms to infiltrate and destroy humanity. A UN officer discovers the terrifying truth that the robots have developed multiple deceptive varieties, including child-like models, making survival nearly impossible. The story explores themes of betrayal, paranoia, and the unintended consequences of advanced weaponry.

### 30. Vibe-Coding a PCB – surprisingly good

 Score: 150 Comments: 62 [Link](https://atomic14.substack.com/p/vibe-coding-a-pcb-surprisingly-good)

 > The author used AI (Claude) and Atopile to design an ESP32-S3 dev board by describing requirements in natural language. After minor fixes, the AI-generated PCB was surprisingly functional, showing promise for AI-assisted hardware design. The author considers ordering the board to test its real-world performance.

