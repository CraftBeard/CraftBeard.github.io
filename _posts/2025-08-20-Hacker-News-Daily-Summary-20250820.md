Updated at 2025-08-20 17:11:54 (UTC+8)

### 1. AGENTS.md – Open format for guiding coding agents

 Score: 463 Comments: 209 [Link](https://agents.md/)

 > AGENTS.md is an open, standardized Markdown file that provides instructions and context specifically for AI coding agents. It complements a project's README by detailing setup commands, code style, testing procedures, and other technical guidelines. This format keeps human-focused documentation clean while giving AI agents a predictable place to find the information they need to work effectively on a codebase. It is used by over 20,000 open-source projects.

### 2. How to Think About GPUs

 Score: 84 Comments: 24 [Link](https://jax-ml.github.io/scaling-book/gpus/)

 > This article explains that modern ML GPUs like H100 and B200 are composed of many independent Streaming Multiprocessors (SMs), each containing specialized matrix multiplication units (Tensor Cores) and vector arithmetic units (CUDA cores), all connected to high-bandwidth memory (HBM). It details the memory hierarchy and compares GPU architecture and networking to TPUs, highlighting that GPUs offer more flexibility while TPUs can achieve higher peak performance with less effort. The article concludes with roofline analyses for different parallelism strategies in LLM training, showing how communication costs can become a bottleneck.

### 3. Ask HN: Why does the US Visa application website do a port-scan of my network?

 Score: 126 Comments: 48 [Link](item?id=44959073)

 > This is an error message, not an article. The system returned a "ParamValidationError" because it could not resolve the domain 'item' in the provided URL. The request failed with a 400 status code.

### 4. How to Draw a Space Invader

 Score: 288 Comments: 28 [Link](https://muffinman.io/blog/invaders/)

 > The author created a Space Invader Generator for a coding challenge. The tool generates random, pixelated alien invaders by first creating a vector polygon body, then adding mirrored limbs and horns. It uses a simple pixelization method to convert the vector shapes into a retro, grid-based look. The generator also includes color customization and simple two-frame animations.

### 5. Copilot broke audit logs, but Microsoft won't tell customers

 Score: 471 Comments: 158 [Link](https://pistachioapp.com/blog/copilot-broke-your-audit-log)

 > A security researcher discovered a vulnerability in Microsoft's M365 Copilot that allowed users to access files without generating an audit log entry, simply by asking the AI not to provide a link to the file. This creates a significant security and compliance risk. The researcher reported it to Microsoft, who fixed the issue but classified it as "important" and decided not to issue a CVE or notify customers that their audit logs were potentially incomplete.

### 6. Modern CI Is Too Complex and Misdirected

 Score: 56 Comments: 15 [Link](https://gregoryszorc.com/blog/2021/04/07/modern-ci-is-too-complex-and-misdirected/)

 > Gregory Szorc argues that modern CI systems like GitHub Actions and GitLab Pipelines have become overly complex, essentially reinventing build systems with their own intricate DAGs and configurations. He posits that CI functionality should instead be an extension of a sufficiently advanced build system, eliminating redundancy and fragmentation. His ideal solution is a unified, generic "remote code execution as a service" platform that handles both builds and CI, citing Mozilla's Taskcluster as a powerful but complex example of this approach. He is skeptical, however, that such a unified platform will become widely available soon due to a perceived small market and lack of incentive for major players.

### 7. How we exploited CodeRabbit: From simple PR to RCE and write access on 1M repos

 Score: 581 Comments: 196 [Link](https://research.kudelskisecurity.com/2025/08/19/how-we-exploited-coderabbit-from-a-simple-pr-to-rce-and-write-access-on-1m-repositories/)

 > Researchers exploited a vulnerability in CodeRabbit's AI code review tool by submitting a malicious pull request that leveraged Rubocop's extension feature to achieve remote code execution (RCE). This RCE allowed them to exfiltrate environment variables containing sensitive secrets, including CodeRabbit's GitHub App private key. With this key, they could have gained read and write access to over one million repositories, including private ones. CodeRabbit promptly fixed the issue upon disclosure.

### 8. Type-machine

 Score: 21 Comments: 4 [Link](https://arthi-chaud.github.io/posts/type-machine/)

 > Type-machine is a Haskell library that uses Template Haskell to derive record types and simulate structural subtyping. It provides type-transformers, inspired by TypeScript, to manipulate and generate record structures. The library also generates typeclasses for getters and setters to enable structural polymorphism. Benchmarks show it offers better performance than alternative approaches using heterogeneous lists.

### 9. The Value of Hitting the HN Front Page

 Score: 66 Comments: 30 [Link](https://www.mooreds.com/wordpress/archives/3530)

 > Based on his extensive experience, Dan Moore outlines the primary values of a high-ranking Hacker News post. These include significant traffic for brand awareness (though with low conversion), invaluable feedback from smart commenters, and potential follow-on traffic from other sources. He also cautions that it is not a reliable marketing plan and should not be expected to deliver direct sales or broad market feedback.

### 10. Tiny microbe challenges the definition of cellular life

 Score: 92 Comments: 17 [Link](https://nautil.us/a-rogue-new-life-form-1232095/)

 > Scientists have discovered a microbe, named *Sukunaarchaeum mirabile*, with an extremely small genome. It is completely dependent on its host organism for metabolism, lacking the genes to produce its own energy or cellular building blocks. This challenges the fundamental definition of cellular life, as it exists in a gray area between a living archaeon and a virus-like entity. The discovery suggests many more such "rogue" life forms may exist in nature.

### 11. D2 (text to diagram tool) now supports ASCII renders

 Score: 303 Comments: 50 [Link](https://d2lang.com/blog/ascii/)

 > D2 version 0.7.1 introduces ASCII output, allowing users to generate text-based diagrams by saving files with a `.txt` extension. This feature is particularly useful for embedding diagrams directly into source code comments. The renderer uses Unicode characters by default but supports standard ASCII for maximum portability. It is currently in an alpha stage with some limitations, including no style support and uneven spacing in certain cases.

### 12. How I Made Ruby Faster Than Ruby

 Score: 32 Comments: 7 [Link](https://noteflakes.com/articles/2025-08-18-how-to-make-ruby-faster)

 > The author improved the performance of the P2 HTML templating library for Ruby by optimizing its compilation process. Key changes included separating static and dynamic HTML parts to avoid string interpolation, removing rescue clauses to reduce overhead, using frozen string literals, and switching to a faster HTML escape method. These optimizations made P2's compiled templates as fast as compiled ERB and ERubi, significantly outperforming non-compiled alternatives like Papercraft and Phlex.

### 13. Gaussian Processes for Machine Learning [pdf]

 Score: 19 Comments: 4 [Link](https://gaussianprocess.org/gpml/chapters/RW.pdf)

 > 

### 14. Analysis of the GFW's Unconditional Port 443 Block on August 20, 2025

 Score: 128 Comments: 74 [Link](https://gfw.report/blog/gfw_unconditional_rst_20250820/en/)

 > On August 20, 2025, China's Great Firewall (GFW) disrupted all internet connections on TCP port 443 for approximately 74 minutes by injecting forged RST+ACK packets. This unconditional blocking affected both inbound and outbound traffic to and from China. Analysis of the injected packets revealed unique, incremental fingerprints that did not match any known GFW censorship devices, suggesting the incident was caused by either a new device or a known device in a misconfigured state.

### 15. Calling Their Bluff

 Score: 64 Comments: 31 [Link](https://anguscheng.com/post/2025-08-13-calling-their-bluff/)

 > The author was tricked into paying $79 USD to a third-party website (evisatravel.org) for a Canadian eVisa that officially costs only $7 CAD. After realizing the scam, they successfully obtained a real visa and initiated a chargeback for the fraudulent fee. The scam company threatened that a chargeback could lead to a government blacklist, but this was a bluff. The author entered Canada without any issues.

### 16. Emacs as your video-trimming tool

 Score: 238 Comments: 120 [Link](https://xenodium.com/emacs-as-your-video-trimming-tool)

 > The author created a video trimming tool for Emacs called `video-trimmer-mode`. It was inspired by another developer's post and uses ffmpeg to handle the actual video processing. The tool is about 300 lines of code and is available in the author's public Emacs configuration repository.

### 17. Fast and observable background job processing for .NET

 Score: 8 Comments: 2 [Link](https://github.com/mikasjp/BusyBee)

 > BusyBee is a lightweight, high-performance .NET library for in-memory background job processing. It uses .NET channels for efficiency and offers features like configurable queues, parallel processing, and built-in OpenTelemetry support for observability. It is designed to be simple to use and integrates fully with dependency injection.

### 18. Without the futex, it's futile

 Score: 263 Comments: 122 [Link](https://h4x0r.org/futex/)

 > The author criticizes "The Art of Multiprocessor Programming" for failing to cover the futex, a fundamental OS primitive for building efficient concurrency controls like mutexes. They argue the futex is crucial for modern performance, separating locking from waiting to minimize system calls. The article then provides a detailed, practical implementation of various mutex types using futexes to supplement the book's theoretical approach.

### 19. Rails Charts Using ECharts from Apache

 Score: 41 Comments: 4 [Link](https://github.com/railsjazz/rails_charts)

 > Rails Charts is a Ruby on Rails gem that simplifies the creation of charts using the Apache eCharts library. It provides a variety of chart types, including line, bar, pie, and area charts, with minimal code. The gem offers helpers for easy integration and customization options for styling and functionality.

### 20. Candle Flame Oscillations as a Clock

 Score: 286 Comments: 63 [Link](https://cpldcpu.com/2025/08/13/candle-flame-oscillations-as-a-clock/)

 > Bundling three candles together causes their flames to synchronize and oscillate at a stable frequency of approximately 9.9 Hz. This frequency is primarily dependent on gravity and the flame's diameter. The oscillation is detected using a wire suspended in the flame to sense capacitance changes from ionized gases. This signal is then processed and divided down to create a 1 Hz clock pulse.

### 21. Intel Foundry Demonstrates First Arm-Based Chip on 18A Node

 Score: 36 Comments: 15 [Link](https://hothardware.com/news/intel-foundry-demos-deer-creek-falls-reference-soc)

 > Intel Foundry has demonstrated its first Arm-based chip, a reference SoC named "Deer Creek Falls," fabricated on its advanced 18A process node. This chip features a three-tier CPU core configuration typical of modern Arm SoCs. The demonstration is a strategic move to attract external customers, as Intel's foundry business needs more clients to sustain future node development. This effort aims to showcase Intel's capability to manufacture competitive non-x86 processors for potential partners.

### 22. Show HN: Hanaco Weather – A poetic weather SNS from the OS Yamato project

 Score: 10 Comments: discuss [Link](https://github.com/osyamato/os-yamato)

 > OS Yamato is a minimalist, ephemeral operating system inspired by the wabi-sabi philosophy of impermanence. It runs as a virtual OS on AWS EC2 for mobile devices. Its core feature is that user data like notes, photos, and messages automatically delete after 365 days unless interacted with, promoting a clutter-free digital experience.

### 23. AnduinOS

 Score: 123 Comments: 146 [Link](https://www.anduinos.com/)

 > AnduinOS is a free, open-source Linux distribution based on Ubuntu. It offers a user-friendly GNOME desktop and is designed for ease of use, especially for those transitioning from Windows. The OS is available in both a stable LTS version and a Standard version with newer features. It is fully compatible with Ubuntu's software and focuses on user privacy and security.

### 24. Drunken Bishop (2023)

 Score: 65 Comments: 11 [Link](https://re.factorcode.org/2023/08/drunken-bishop.html)

 > This article explains the Drunken Bishop algorithm, a method used by OpenSSH to visualize public key fingerprints as ASCII art. It describes how the algorithm works by simulating a "drunken bishop" moving diagonally on a grid based on the key's bytes, incrementing counters in each cell it visits. The author then details their implementation of this algorithm in the Factor programming language, including code snippets for the movement logic and rendering. The result is a visual representation that helps users more easily verify if a key has changed.

### 25. CRDT: Text Buffer

 Score: 115 Comments: 5 [Link](https://madebyevan.com/algos/crdt-text-buffer/)

 > This article describes a CRDT algorithm for collaborative text editing. It assigns unique identifiers to each character and uses tree-based indexing to determine their order. The algorithm employs optimizations like storing text in contiguous blocks and using range-based deletion sets for efficiency. It includes an interactive demo to visualize the process.

### 26. How Figma’s multiplayer technology works (2019)

 Score: 146 Comments: 46 [Link](https://www.figma.com/blog/how-figmas-multiplayer-technology-works/)

 > Figma built a custom multiplayer system instead of using complex operational transforms (OTs). Their approach is inspired by conflict-free replicated data types (CRDTs) but simplified for their centralized client-server architecture. The system syncs changes to object properties and manages a tree structure for the document, using techniques like fractional indexing for ordering. This allows for real-time collaboration while handling conflicts and ensuring eventual consistency.

### 27. We’re Not So Special: A new book challenges human exceptionalism

 Score: 66 Comments: 112 [Link](https://democracyjournal.org/magazine/78/were-not-so-special/)

 > Christine Webb's book *The Arrogant Ape* challenges the concept of human exceptionalism. She argues that using human abilities as the baseline to measure other species is a biased and unscientific approach. Webb presents evidence of the unique and remarkable capabilities of various animals to advocate for humility and awe. Ultimately, she contends that this human superiority complex is harmful to science, the environment, and the animals themselves.

### 28. Databricks is raising a Series K Investment at >$100B valuation

 Score: 43 Comments: 45 [Link](https://www.databricks.com/company/newsroom/press-releases/databricks-raising-series-k-investment-100-billion-valuation)

 > Databricks is raising a Series K investment round that values the company at over $100 billion. The capital will be used to accelerate its AI strategy, including expanding its new Agent Bricks and Lakebase products. The funding will also support future AI acquisitions and deepen AI research. The company cites strong investor interest and unprecedented global demand for its AI products as the reason for the round.

### 29. Show HN: OpenAI/reflect – Physical AI Assistant that illuminates your life

 Score: 73 Comments: 28 [Link](https://github.com/openai/openai-reflect)

 > OpenAI Reflect is a physical AI assistant project created during a hackathon. It's a demo device built for Espressif microcontrollers that uses light and sound for interaction instead of screens. The device creates its own WiFi network for setup and is designed to be low-cost and easily modifiable. This is an experimental project provided as-is without guarantees.

### 30. Custom telescope mount using harmonic drives and ESP32

 Score: 286 Comments: 105 [Link](https://www.svendewaerhert.com/blog/telescope-mount/)

 > The author built a custom telescope mount for astrophotography using harmonic drives and an ESP32-S3 microcontroller. After learning PCB design and CAD modeling, they created a custom board and housing, integrating it with the open-source OnStepX firmware. The total project cost was approximately €1,700, and it successfully achieves tracking precision of 1-2 arcseconds.

