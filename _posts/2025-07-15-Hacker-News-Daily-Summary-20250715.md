Updated at 2025-07-15 17:10:05 (UTC+8)

### 1. LLM Inevitabilism

 Score: 449 Comments: 413 [Link](https://tomrenner.com/posts/llm-inevitabilism/)

 > The article critiques "inevitabilism," the idea that AI's dominance is unavoidable, arguing it frames debates to dismiss alternatives. It warns against accepting this narrative and urges people to envision and fight for the future they want.

### 2. Apple's MLX adding CUDA support

 Score: 349 Comments: 141 [Link](https://github.com/ml-explore/mlx/pull/1983)

 > This pull request introduces a CUDA backend for MLX, enabling GPU acceleration on NVIDIA hardware with unified memory support. It includes initial implementations of key operations and optimizations to reduce overhead, though performance is still being improved. The work is sponsored by Apple and aims to provide a seamless developer experience across Mac and supercomputers. The PR was later split into smaller incremental updates.

### 3. LIGO detects most massive black hole merger to date

 Score: 258 Comments: 128 [Link](https://www.caltech.edu/about/news/ligo-detects-most-massive-black-hole-merger-to-date)

 > LIGO detected the most massive black hole merger to date, involving two black holes (100 and 140 solar masses) merging into a 225-solar-mass black hole. This event, named GW231123, challenges current astrophysical models and pushes the limits of gravitational-wave detection. The findings were presented at the GR24 conference in 2025.

### 4. Kiro: A new agentic IDE

 Score: 821 Comments: 348 [Link](https://kiro.dev/blog/introducing-kiro/)

 > Kiro is an AI-powered IDE designed to streamline development from concept to production using spec-driven workflows. It helps document assumptions, generate requirements, design technical specs, and automate tasks with hooks for consistency. Kiro ensures clarity and maintainability while integrating with existing tools. Currently free in preview, it supports multiple platforms and languages. [Download here](https://kiro.dev/downloads).

### 5. Dog Walk: Blender Studio's official game project

 Score: 222 Comments: 28 [Link](https://blenderstudio.itch.io/dogwalk)

 > **DOGWALK** is a short, casual game by Blender Studio where players control a dog exploring a wintery open world, helping a child decorate a snowman. Made with Blender and Godot, it features a charming, player-driven experience with no fail states. Available for free on Windows, macOS, and Linux.

### 6. RFC: PHP license update

 Score: 218 Comments: 50 [Link](https://wiki.php.net/rfc/php_license_update)

 > This RFC proposes updating PHP's custom license and the Zend Engine License to the Modified BSD License (BSD-3-Clause) to simplify licensing, maintain contributor rights, and ensure OSI/GPL compatibility. The change requires approval from the PHP Group and Perforce Software but doesn't alter user or contributor rights. Voting will follow a six-month discussion period.

### 7. Clashes between web and X11 colors in the CSS color scheme

 Score: 52 Comments: 9 [Link](https://en.wikipedia.org/wiki/X11_color_names)

 > X11 color names are text-based mappings to RGB values used in the X Window System. They originated in 1986 and were traditionally stored in `rgb.txt`. While not standardized, they became widely adopted, influencing web colors. Some names clash between X11 and W3C standards, like "Gray" and "Green." The list includes variants like "Dark" or "Light" but lacks systematic consistency.

### 8. C++ Coroutines Advanced: Converting std:future to asio:awaitable

 Score: 41 Comments: 6 [Link](https://www.ddhigh.com/en/2025/07/15/cpp-coroutine-future-to-awaitable/)

 > This article explains how to convert `std::future` to `asio::awaitable` in C++ coroutines using `asio::async_initiate` and a thread pool to avoid blocking IO threads. It covers core implementation, usage examples, exception handling, and performance benefits, making it ideal for integrating asynchronous libraries with coroutines.

### 9. Context Rot: How increasing input tokens impacts LLM performance

 Score: 155 Comments: 28 [Link](https://research.trychroma.com/context-rot)

 > The article examines how increasing input token lengths affect LLM performance, showing that even simple tasks like retrieval and repetition degrade as context grows. It highlights limitations of benchmarks like Needle in a Haystack and reveals non-uniform performance drops due to factors like semantic ambiguity, distractors, and haystack structure. The findings emphasize the need for better long-context evaluations and context engineering.

### 10. SQLite async connection pool for high-performance

 Score: 113 Comments: 38 [Link](https://github.com/slaily/aiosqlitepool)

 > `aiosqlitepool` is a high-performance async connection pool for SQLite, designed to boost efficiency by reusing connections, keeping caches hot, and maximizing throughput. It works with drivers like `aiosqlite` and is ideal for scalable applications under heavy load. Benchmarks show significant performance improvements in latency and queries per second.

### 11. VHS, VCDs, and Laserdiscs in Southeast Asia

 Score: 5 Comments: discuss [Link](https://rubenerd.com/vcds-and-laserdiscs-in-southeast-asia/)

 > The article explores why VCDs and Laserdiscs were more popular than VHS tapes in Southeast Asia, citing tropical humidity causing mould on tapes and economic factors like cheaper production and piracy. It also reflects on personal memories of media formats in Singapore.

### 12. I Solved the Century-Old Mystery of a Miraculous Shipwreck Survivor

 Score: 66 Comments: 19 [Link](https://thewalrus.ca/empress-of-ireland-survivor-mystery/)

 > The article explores the mystery of Gordon Charles Davidson, a survivor of the 1914 _Empress of Ireland_ shipwreck, whose alleged six-kilometer swim to shore was debunked by research. A reporter's exaggerated account became widely accepted, but Davidson's actual survival involved being rescued by a lifeboat. The tragedy faded from public memory due to the outbreak of World War I.

### 13. When Sigterm Does Nothing: A Postgres Mystery

 Score: 19 Comments: 3 [Link](https://clickhouse.com/blog/sigterm-postgres-mystery)

 > The ClickPipes team encountered a bug where Postgres read replicas would hang indefinitely when creating logical replication slots, ignoring termination signals. Investigation revealed a Postgres issue where standbys inefficiently polled for primary transactions without interrupt checks. A patch was submitted and accepted, fixing the problem in all supported Postgres versions. The team also worked with the community to improve visibility and efficiency for future releases.

### 14. Martin (YC S23) Is Hiring Founding Engineers to Build a Better Siri

 Score: None Comments: None [Link](https://www.ycombinator.com/companies/martin/jobs/)

 > Martin is an AI personal assistant that manages tasks like emails, calendars, and calls, outperforming Siri and Alexa. With rapid growth (500K tasks for 30K users in 5 months), it’s backed by top investors like YC and seeks ambitious engineers in San Francisco.

### 15. Show HN: Bedrock – An 8-bit computing system for running programs anywhere

 Score: 131 Comments: 34 [Link](https://benbridle.com/projects/bedrock.html)

 > Bedrock is a portable 8-bit computer system designed for longevity, allowing programs to run on any device with a Bedrock emulator. It features a simple 32-instruction set and supports platforms like Windows, Linux, and Nintendo DS. The system includes tutorials, documentation, and live demos showcasing its capabilities.

### 16. Show HN: CallFS – S3-style object store in one Go binary (MIT)

 Score: 63 Comments: 22 [Link](https://github.com/ebogdum/callfs)

 > CallFS is a lightweight, high-performance REST API filesystem that offers Linux filesystem semantics across multiple backends like local storage, Amazon S3, and peer networks. It features distributed architecture, secure links, and cross-server operations. Licensed under MIT, it supports Go and includes detailed documentation.

### 17. DEWLine Museum – The Distant Early Warning Radar Line

 Score: 51 Comments: 15 [Link](https://dewlinemuseum.com/)

 > The DEWLine Museum is a virtual resource dedicated to preserving the history of the Distant Early Warning Radar Line (1957-93), a Cold War surveillance system across the Arctic. It offers photos, videos, documents, and stories about construction, operations, and cleanup, while collaborating to establish a physical exhibit.

### 18. Show HN: VS Code extension to edit the filesystem like a text buffer

 Score: 21 Comments: 12 [Link](https://github.com/ahrm/voil)

 > Voil is a VS Code extension that lets you edit the file system like a text buffer, enabling keyboard-based file manipulation without mouse interaction. It supports creating, renaming, and moving files/directories via text commands, similar to oil.nvim. The tool includes features like recursive listing, sorting, filtering, and custom shell commands. It’s designed for efficiency, especially for users familiar with Vim keybindings. A demo video and donation options are available.

### 19. NeuralOS: An operating system powered by neural networks

 Score: 136 Comments: 42 [Link](https://neural-os.com/)

 > NeuralOS is a project that simulates operating systems using neural generative models, allowing users to interact via mouse and keyboard inputs. It offers adjustable sampling steps and modes (RNN/diffusion) for quality-speed tradeoffs, with an auto-input feature for automatic frame generation. [Project details here](https://anonymous.4open.science/r/neural-os).

### 20. Happy 20th Birthday, Django

 Score: 407 Comments: 125 [Link](https://www.djangoproject.com/weblog/2025/jul/13/happy-20th-birthday-django/)

 > Django celebrates its 20th anniversary on July 13, 2025, marking two decades since its first public commit. The Django community invites everyone to join global celebrations, including events and activities listed on a dedicated [20th birthday website](https://birthday20.djangoproject.com/). The post also encourages donations to support Django's future growth, aiming for 200 new donors in 20 days. The framework remains committed to evolving with the web while maintaining its inclusive community. Happy 20th birthday, Django! 🎉

### 21. Replicube: 3D shader puzzle game, online demo

 Score: 121 Comments: 20 [Link](https://replicube.xyz/staging/)

 > The article mentions a website called Replicube but notes that the page may not be fully loaded and lacks detailed content.

### 22. Cognition (Devin AI) to Acquire Windsurf

 Score: 412 Comments: 321 [Link](https://cognition.ai/blog/windsurf)

 > Cognition has acquired Windsurf, including its IP, product, and talented team. The Windsurf IDE and business will be integrated into Cognition’s offerings, enhancing their mission to advance software engineering. All Windsurf employees will benefit financially and join Cognition as equals. The deal combines Devin’s autonomous capabilities with Windsurf’s scalable GTM strategy. This marks a significant step in transforming software development.

### 23. Bringing Virtualization to the x86 Architecture with the Original VMware Workst [pdf]

 Score: 6 Comments: 1 comment [Link](https://www.cse.iitb.ac.in/~mythili/virtcc/papers/vmware.pdf)

 > The article describes how VMware Workstation brought virtualization to the x86 architecture in 1999 by combining a hosted architecture with a virtual machine monitor (VMM). It overcame challenges like x86's lack of virtualization support, complexity, and peripheral diversity through techniques like dynamic binary translation, segment truncation, and hardware-independent encapsulation. The solution enabled running unmodified guest operating systems efficiently while maintaining isolation and compatibility.

### 24. Cache Benchmarks

 Score: 18 Comments: 3 [Link](https://github.com/tidwall/cache-benchmarks)

 > This GitHub repository benchmarks the performance of five caching systems (Memcache, Redis, Valkey, Dragonfly, and Garnet) by measuring throughput, latency, and CPU cycles. Tests are conducted on an AWS ARM64 instance with persistence disabled, using local UNIX pipes and the `memtier_benchmark` tool. Results include median values from 31 runs across different pipeline configurations (1, 10, 25, 50). Graphs display logarithmic-scale metrics for comparison.

### 25. Building Modular Rails Applications: A Deep Dive into Rails Engines

 Score: 153 Comments: 33 [Link](https://www.panasiti.me/blog/modular-rails-applications-rails-engines-active-storage-dashboard/)

 > Giovanni Panasiti shares his experience building **Active Storage Dashboard**, a modular Rails engine that provides a visual interface for managing Active Storage data. The article explores Rails engines' benefits, best practices for development, and how they enable reusable, maintainable features without microservices complexity. The dashboard offers storage insights, file management, and maintenance tasks with zero external dependencies. [Read more](https://www.panasiti.me/blog/modular-rails-applications-rails-engines-active-storage-dashboard/).

### 26. Strategies for Fast Lexers

 Score: 154 Comments: 58 [Link](https://xnacly.me/posts/2025/fast-lexer-strategies/)

 > This article explains strategies for creating a fast lexer, focusing on techniques like computed gotos, zero-copy string handling, token interning, and on-demand parsing. The author shares benchmarks showing significant speed improvements, such as 1.58x faster performance with bump allocation and 35x faster file reading using `mmap`. The lexer achieves speeds of 580-848 MB/s on test inputs.

### 27. East Asian aerosol cleanup has likely contributed to global warming

 Score: 200 Comments: 224 [Link](https://www.nature.com/articles/s43247-025-02527-3)

 > The article suggests that East Asia's efforts to reduce aerosol pollution, particularly in China, have likely contributed to the recent acceleration in global warming. By cutting sulfate aerosol emissions, which previously masked greenhouse gas-driven warming, the region's cleanup has led to increased surface temperatures and radiative imbalance. The study estimates this contributed up to 0.05°C/decade to the post-2010 warming trend.

### 28. The Collapse of the FDA

 Score: 138 Comments: 76 [Link](https://www.nytimes.com/2025/07/08/magazine/fda-collapse-rfk-kennedy.html)

 > The article discusses concerns about the FDA's potential decline under Robert F. Kennedy Jr.'s influence, but access is restricted (Error 403).

### 29. Embedding user-defined indexes in Apache Parquet

 Score: 118 Comments: 16 [Link](https://datafusion.apache.org/blog/2025/07/14/user-defined-parquet-indexes/)

 > Apache Parquet files can embed user-defined indexes without breaking compatibility by storing them in the file body and recording their locations in the footer metadata. This approach avoids external indexes' complexity and sync issues while enabling advanced optimizations like distinct value pruning. The blog demonstrates embedding a distinct value index in Parquet using Apache DataFusion, showing improved query performance while maintaining compatibility with standard Parquet readers.

### 30. Japanese grandparents create life-size Totoro with bus stop for grandkids (2020)

 Score: 275 Comments: 72 [Link](https://mymodernmet.com/totoro-sculpture-bus-stop/)

 > A Japanese couple in their 70s built a life-size Totoro sculpture with a bus stop for their grandchildren, inspired by Studio Ghibli's *My Neighbor Totoro*. Using carpentry and plastering skills, they crafted the detailed statue, which has become a popular attraction for fans. The couple even provides a red umbrella for photos, recreating the iconic movie scene.

