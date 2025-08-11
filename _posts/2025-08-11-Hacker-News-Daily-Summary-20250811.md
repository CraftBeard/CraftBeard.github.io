Updated at 2025-08-11 17:10:30 (UTC+8)

### 1. Google paid a $250K reward for a bug

 Score: 225 Comments: 82 [Link](https://issues.chromium.org/issues/412578726)

 > This article describes a Chromium sandbox escape vulnerability (CVE-2024-3833) where a compromised renderer process can intercept and manipulate IPC messages to duplicate a browser process handle. The exploit involves intercepting `msg::AcceptIntroduction` messages, storing transport objects, and sending crafted `ReferNonBroker` messages with manipulated handles to escape the sandbox.

### 2. Basic Social Skills Guide

 Score: 105 Comments: 46 [Link](https://www.improveyoursocialskills.com/basic-social-skills-guide)

 > This free guide offers lessons on social skills, covering foundations, body language, conversation, supporting friends, and quick tips. It encourages sharing and includes an advanced guide for further learning.

### 3. Vanishing from Hyundai’s data network

 Score: 231 Comments: 84 [Link](http://techno-fandom.org/~hobbit/cars/ev/offnet.html)

 > The author disabled Hyundai's BlueLink telematics system in their Kona EV to prevent tracking and remote control, removing the cellular modem from the head unit and disabling the in-car microphone. This ensured privacy and eliminated unwanted connectivity.

### 4. Theft is not fair use

 Score: 30 Comments: 28 [Link](https://jskfellows.stanford.edu/theft-is-not-fair-use-474e11f0d063)

 > AI companies are accused of copyright infringement by scraping online content for training data without permission, claiming fair use. Lawsuits by publishers and creators challenge this practice, arguing it’s theft. Examples include AI replicating copyrighted photos and text. The article calls for fair compensation and stronger protections for creators.

### 5. Dropbox announces new gen server hardware for higher efficiency and scalability

 Score: 24 Comments: 11 [Link](https://dropbox.tech/infrastructure/seventh-generation-server-hardware)

 > Dropbox has launched its seventh-generation server hardware, featuring Crush, Dexter, and Sonic for compute, database, and storage workloads, along with new GPU tiers (Gumby and Godzilla) for AI. The upgrade boosts performance, doubles rack power, and improves thermal management while optimizing storage density and vibration control. This scalable architecture supports Dropbox's growing AI products like Dash. The design reflects close supplier collaboration and a product-first approach.

### 6. Going faster than memcpy

 Score: 65 Comments: 30 [Link](https://squadrick.dev/journal/going-faster-than-memcpy)

 > The article explores optimizing memory copying (`memcpy`) for large data transfers (>512kB) by testing various methods like `REP MOVSB`, aligned AVX, and streaming AVX with prefetching. Benchmarks show that while custom implementations can outperform `memcpy` in specific cases, `std::memcpy` remains the best general-purpose choice due to its adaptability and performance across different sizes. The author concludes that specialized methods are only worthwhile for very specific use cases.

### 7. Generic Containers in C: Safe Division Using Maybe

 Score: 32 Comments: 2 [Link](https://uecker.codeberg.page/2025-08-10.html)

 > Martin Uecker discusses implementing type-safe generic containers in C, focusing on a `maybe` type inspired by Haskell to handle potential errors like division by zero. He demonstrates its use in a safe division function, highlights an overlooked integer overflow case, and shows how compiler optimizations can statically verify safety. The approach is limited but useful for certain safety checks in C.

### 8. Try and

 Score: 528 Comments: 261 [Link](https://ygdp.yale.edu/phenomena/try-and)

 > The article explores the grammatical construction "try and" (e.g., "try and eat") in English, comparing it to "try to." It notes its historical usage since the 1500s, syntactic peculiarities (e.g., no inflection or reordering), and dialectal variations. While prescriptively discouraged, it remains common in both British and American English. Other pseudocoordination examples (e.g., "come and get") are also discussed.

### 9. Raised by Wolves Is Original Sci-Fi at Its Most Polarizing (2020)

 Score: 35 Comments: 30 [Link](https://www.rogerebert.com/streaming/hbo-maxs-raised-by-wolves-is-original-sci-fi-at-its-most-polarizing)

 > The domain www.rogerebert.com is blocked until August 11, 2025, due to suspected DDoS abuse linked to excessive requests on a specific article about HBO Max's "Raised by Wolves."

### 10. Graham: Synchronizing Clocks by Leveraging Local Clock Properties (2022) [pdf]

 Score: 30 Comments: 3 [Link](https://www.usenix.org/system/files/nsdi22-paper-najafi_1.pdf)

 > Graham is a system that improves clock synchronization in commodity servers by leveraging local clock properties and temperature sensors. It reduces clock drift by up to 2000×, achieving sub-microsecond accuracy without specialized hardware. By modeling clock stability and compensating for temperature-induced errors, Graham enables longer holdover times and tolerates synchronization failures. The paper debunks the myth of unstable commodity clocks and demonstrates Graham's effectiveness across various platforms.

### 11. Compiling a Lisp: Lambda lifting

 Score: 110 Comments: 9 [Link](https://bernsteinbear.com/blog/compiling-a-lisp-12/)

 > This article explains closure conversion in a Lisp compiler, detailing how to handle free variables in lambdas by transforming them into closures. It covers tracking bound and free variables, converting lambdas and `let` expressions, and compiling closures and function calls into assembly. The implementation is demonstrated in Python, with tests to ensure correctness.

### 12. GPT-OSS vs. Qwen3 and a detailed look how things evolved since GPT-2

 Score: 387 Comments: 80 [Link](https://magazine.sebastianraschka.com/p/from-gpt-2-to-gpt-oss-analyzing-the)

 > OpenAI released two open-weight LLMs, gpt-oss-20b and gpt-oss-120b, featuring architectural improvements like Mixture-of-Experts (MoE), sliding-window attention, and MXFP4 quantization for efficient local deployment. The models compare closely to Qwen3 but differ in depth-vs-width trade-offs and reasoning control. Benchmarks show competitive performance, though hallucinations remain a noted limitation.

### 13. The enduring puzzle of static electricity

 Score: 56 Comments: 4 [Link](https://pubs.aip.org/physicstoday/article/78/8/54/3355922/The-enduring-puzzle-of-static-electricityEven)

 > Unable to summarize—the article is behind a security check (403 error) and requires CAPTCHA verification.

### 14. Millau Viaduct

 Score: 6 Comments: discuss [Link](https://www.fosterandpartners.com/projects/millau-viaduct)

 > The Millau Viaduct, designed by Foster + Partners in collaboration with engineers, is a cable-stayed bridge in southern France that spans the Tarn River gorge. It features the world's tallest pylons and a sleek, minimal design to blend with the landscape. The bridge completes a key route from Paris to the Mediterranean, showcasing a balance of function, technology, and aesthetics.

### 15. Lists and Lists: Basics of Lisp through interactive fiction (1996)

 Score: 40 Comments: 6 [Link](https://eblong.com/zarf/zweb/lists/)

 > A mysterious door appears in a familiar place, introducing an interactive tutorial called "Lists And Lists" by Andrew Plotkin (1996). Players are instructed to type "about" for first-time guidance.

### 16. Show HN: Bolt – A super-fast, statically-typed scripting language written in C

 Score: 210 Comments: 62 [Link](https://github.com/Beariish/bolt)

 > GitHub.com is blocked until August 11, 2025, due to suspected DDoS abuse linked to a specific URL. The error cites excessive requests as the reason for the security restriction.

### 17. Fight Chat Control

 Score: 1058 Comments: 310 [Link](https://fightchatcontrol.eu/)

 > The EU's "Chat Control" proposal mandates mass scanning of private digital communications, including encrypted messages, threatening privacy and security. Critics argue it undermines fundamental rights, weakens encryption, and creates false positives, while failing to effectively protect children. Currently, 15 EU states support it, 3 oppose it, and 9 remain undecided. The proposal faces growing opposition over surveillance concerns.

### 18. Show HN: Engineering.fyi – Search across tech engineering blogs in one place

 Score: 372 Comments: 100 [Link](https://engineering.fyi/)

 > This article compiles the latest tech updates from top companies, covering topics like AI advancements (OpenAI's GPT-5, Google's Gemini), Kubernetes upgrades (Airbnb), and new tools (Meta's concrete AI, Shopify's FlashList). It includes insights on safety training, edge computing, and developer resources, with contributions from engineers and researchers.

### 19. Show HN: A Sinclair ZX81 retro web assembler+simulator

 Score: 41 Comments: 4 [Link](item?id=44859761)

 > The error indicates a validation issue with a URL parameter, stating the domain "item" couldn't be resolved (HTTP 400).

### 20. One Million Screenshots

 Score: 206 Comments: 73 [Link](https://onemillionscreenshots.com/?q=random)

 > "One Million Screenshots" is a website that displays a vast collection of screenshots from top web homepages, allowing users to explore and zoom into random sites. It offers a search function and supports random browsing, with images sourced via the Urlbox API. The site includes navigation tools and links to FAQs, terms, and privacy policies.

### 21. A ChatGPT Pro subscription costs 38.6 months of income in low-income countries

 Score: 4 Comments: discuss [Link](https://policykahani.substack.com/p/a-chatgpt-pro-subscription-costs)

 > A ChatGPT Pro subscription costs 38.6 months of income for people in low-income countries, highlighting a significant AI access gap. High-income countries benefit more from these advanced tools, while affordability remains a major barrier in developing nations. The article suggests companies like Google and OpenAI should consider pricing adjustments or university partnerships to improve accessibility. The disparity raises concerns about global productivity inequality.

### 22. Creating the Longest Possible Ski Jump in “The Games: Winter Challenge”

 Score: 168 Comments: 9 [Link](https://mrwint.github.io/winter/writeup/writeup2.html)

 > The article details reverse-engineering *The Games: Winter Challenge* to optimize ski jumps by analyzing the game's physics, replay files, and input handling. The author created a simulation to find the longest possible jump (113.8m) by exploiting mechanics like strafing and drag manipulation. The process involved disassembling the game, reconstructing its logic, and validating results through memory dumps.

### 23. Bouncing on trampolines to run eBPF programs

 Score: 7 Comments: discuss [Link](https://bootlin.com/blog/bouncing-on-trampolines-to-run-ebpf-programs/)

 > This article explains how eBPF trampolines improve performance for tracing programs by dynamically generating low-overhead call mechanisms instead of using exception-based kprobes. It covers trampoline implementation details, advanced use cases like fentry/fexit programs, and Bootlin's contributions to ARM64 support. The trampoline approach reduces overhead significantly for high-frequency tracing scenarios.

### 24. 1910: The year the modern world lost its mind

 Score: 275 Comments: 222 [Link](https://www.derekthompson.org/p/1910-the-year-the-modern-world-lost)

 > The article explores how the rapid technological advancements of the early 20th century—like cars, planes, and cameras—triggered widespread anxiety, mental health crises, and artistic revolutions, mirroring today's challenges with modern innovation. It highlights parallels between past and present societal upheavals, emphasizing how history's themes persistently "rhyme."

### 25. Diffusion language models are super data learners

 Score: 176 Comments: 13 [Link](https://jinjieni.notion.site/Diffusion-Language-Models-are-Super-Data-Learners-239d8f03a866800ab196e49928c019ac)

 > The article discusses how diffusion language models excel as data learners, highlighting their superior performance in processing and learning from data. (Cached snapshot from August 11, 2025.)

### 26. PHP compile time generics: yay or nay?

 Score: 76 Comments: 42 [Link](https://thephp.foundation/blog/2025/08/05/compile-generics/)

 > The PHP Foundation explores implementing compile-time generics for interfaces and abstract classes, offering significant benefits with simpler implementation. This approach avoids runtime complexities while enabling type safety for common use cases like collections. The team seeks community feedback before investing further in this partial solution.

### 27. Booting 5000 Erlangs on Ampere One 192-core

 Score: 198 Comments: 36 [Link](https://underjord.io/booting-5000-erlangs-on-ampere-one.html)

 > The article details running 5,000 Erlang virtual machines on an Ampere One 192-core server using KVM acceleration. Key improvements include a custom bootloader (`little_loader`) and memory optimizations, achieving stable performance with 110MB RAM per VM. This setup enables large-scale testing for IoT devices using the Nerves framework.

### 28. TCP Client Self-Connect (2013)

 Score: 35 Comments: 4 [Link](http://sgros.blogspot.com/2013/08/tcp-client-self-connect.html)

 > A TCP client can accidentally connect to itself when the kernel assigns the same ephemeral port as the destination port, causing a self-connection. This occurs due to sequential port allocation and TCP's simultaneous open feature, leading to an established connection without a server. The article explains the technical details and warns against using ephemeral ports for servers.

### 29. Writing simple tab-completions for Bash and Zsh

 Score: 236 Comments: 79 [Link](https://mill-build.org/blog/14-bash-zsh-completion.html)

 > This article explains how to create custom tab-completions for both Bash and Zsh, including descriptions for each completion option. It provides code examples for basic completion, adding descriptions in Zsh, and even hacking Bash to show descriptions. The final solution ensures a consistent user experience across both shells.

### 30. How I code with AI on a budget/free

 Score: 616 Comments: 208 [Link](https://wuu73.org/blog/aiguide1.html)

 > The article explains a budget-friendly AI coding workflow using multiple free AI models (like GLM 4.5, Kimi K2, Gemini, and Claude) in browser tabs for debugging and coding tasks. It highlights the AI Code Prep GUI tool, which curates project code for better AI context, avoiding excessive or insufficient input common in coding agents like Cline or Copilot. The workflow prioritizes free web-based AI chats for problem-solving while reserving paid models for specific tasks.

