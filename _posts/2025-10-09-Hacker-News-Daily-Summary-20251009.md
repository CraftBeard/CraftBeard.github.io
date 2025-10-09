Updated at 2025-10-09 17:08:11 (UTC+8)

### 1. First-in-the-nation law to ban ultra-processed foods from school lunches

 Score: 10 Comments: 2 [Link](https://www.gov.ca.gov/2025/10/08/governor-newsom-signs-first-in-the-nation-law-to-ban-ultra-processed-foods-from-school-lunches/)

 > California Governor Gavin Newsom signed AB 1264, a first-in-the-nation law that phases out the most concerning ultra-processed foods from school meals. The law establishes a statutory definition for ultra-processed foods and aims to protect children's health. This action builds on California's previous initiatives to improve school nutrition and remove harmful additives from food.

### 2. The Unknotting Number Is Not Additive

 Score: 51 Comments: 11 [Link](https://divisbyzero.com/2025/10/08/the-unknotting-number-is-not-additive/)

 > Mathematicians Brittenham and Hermiller disproved a long-standing conjecture in knot theory by showing that the unknotting number is not additive under connected sum. Their counterexample demonstrates that the connected sum of a (2,7) torus knot with its mirror image has an unknotting number of 5, which is less than the sum of their individual unknotting numbers (3+3=6). This discovery was verified through a complex projection with 56 crossings, where changing five specific crossings yields the unknot.

### 3. The React Foundation: The New Home for React and React Native

 Score: 35 Comments: 10 [Link](https://engineering.fb.com/2025/10/07/open-source/introducing-the-react-foundation-the-new-home-for-react-react-native/)

 > Meta has announced the creation of the React Foundation, a new home for React and React Native. This foundation, part of the Linux Foundation, will manage the project's infrastructure and community initiatives. Technical governance will be handled independently by the project's maintainers. Meta is committing over $3 million in funding and engineering support for five years.

### 4. A History of Large Language Models

 Score: 78 Comments: 9 [Link](https://gregorygundersen.com/blog/2025/10/01/large-language-models/)

 > This article traces the evolution of large language models from foundational concepts to modern systems. It begins with early statistical language models and the introduction of distributed word representations (embeddings) by Bengio et al. (2003), which enabled neural networks to generalize across similar words. The narrative then covers sequence-to-sequence models with attention mechanisms, which improved handling of long-range dependencies, culminating in the transformer architecture (Vaswani et al., 2017) that relies solely on attention. Finally, it discusses modern training techniques like generative pre-training and reinforcement learning from human feedback that produce today's powerful LLMs.

### 5. Talk Python in Production

 Score: 37 Comments: 28 [Link](https://talkpython.fm/books/python-in-production)

 > "Talk Python in Production" is a practical guide for Python developers seeking to deploy applications using a "stack-native" approach. It teaches how to containerize apps with Docker, manage them on a single powerful server, and integrate tools like NGINX and CDNs. The book emphasizes reducing cloud dependency while maintaining reliability and cost efficiency. Based on real-world experience, it provides hands-on examples for scalable Python deployments.

### 6. We found a bug in Go's ARM64 compiler

 Score: 710 Comments: 114 [Link](https://blog.cloudflare.com/how-we-found-a-bug-in-gos-arm64-compiler/)

 > Cloudflare discovered a race condition bug in Go's arm64 compiler that caused sporadic crashes during stack unwinding. The bug occurred when async preemption happened between split stack pointer adjustment instructions, leaving the stack in an inconsistent state. This was triggered during garbage collection when the runtime attempted to unwind goroutine stacks. They created a minimal reproducer and reported the issue, which was fixed in Go versions 1.23.12, 1.24.6, and 1.25.0.

### 7. Thoughts on the Word Spec in Rust

 Score: 19 Comments: 8 [Link](https://tritium.legal/blog/word)

 > Tritium initially used the docx_rs crate for Word document processing but found it insufficient for their core legal tech product, which requires perfect round-trip preservation of documents. Since Microsoft Word's specification allows complex nested structures that are challenging to handle in Rust, Tritium decided to build their own custom docx module from scratch. This ensures complete control over document editing and prevents data loss during saves, which is critical for their business offering.

### 8. Designing a Low Latency 10G Ethernet Core (2023)

 Score: 91 Comments: 20 [Link](https://ttchisholm.github.io/ethernet/2023/05/01/designing-10g-eth-1.html)

 > This article introduces a series about developing a low-latency 10G Ethernet core for FPGAs. The author created this as a personal project to gain expertise in low-latency FPGA design and high-speed Ethernet. The design achieves under 60ns loopback latency, comparable to commercial products. The series will focus on unique aspects like verification tools and latency reduction techniques. It also provides recommended resources for readers unfamiliar with Ethernet fundamentals.

### 9. WinBoat: Windows apps on Linux with seamless integration

 Score: 225 Comments: 122 [Link](https://www.winboat.app/)

 > WinBoat is an open-source tool that enables running Windows applications on Linux with seamless integration. It automatically handles setup and provides a unified interface, unlike manual alternatives like WinApps. The software supports USB passthrough and can run applications that don't work well with Wine or CrossOver, including Microsoft Office. Currently in beta, it offers easier Windows app compatibility for Linux users.

### 10. The Forecasting Company (YC S24) Is Hiring a Machine Learning Engineer

 Score: None Comments: None [Link](https://www.ycombinator.com/companies/the-forecasting-company/jobs/cXJzAhA-founding-machine-learning-engineer)

 > The Forecasting Company is hiring a Founding Machine Learning Engineer to build time-series foundation models for business forecasting. The role involves architecting, training, and deploying large ML models using PyTorch/Jax, requiring 3+ years of experience and expertise in foundation models. This Paris-based position offers competitive compensation, equity, and benefits for someone passionate about creating state-of-the-art forecasting systems.

### 11. Discord says 70k users may have had their government IDs leaked in breach

 Score: 459 Comments: 237 [Link](https://www.theverge.com/news/797051/discord-government-ids-leaked-data-breach)

 > Access to The Verge website has been blocked until October 2025 due to a suspected DDoS attack. The security block was triggered by excessive domain requests linked to a specific article about Lumafield's CT scan of a lithium-ion battery. This is a security measure to prevent further abuse of the site.

### 12. Rejected announces from libtorrent clients proxying through SOCKS

 Score: 31 Comments: 19 [Link](https://catgirl.online/2025/10/01/libtorrent-socks-woes)

 > When using qBittorrent with SOCKS5 proxy for peer connections, the client unsets its listening port, making it appear unconnectable to trackers. This causes some trackers to reject announces with "port 1 is blacklisted" errors. The author found a pending libtorrent PR that fixes this issue and created custom patches for both libtorrent and qBittorrent to enable listening ports while using proxies. However, they ultimately decided not to use the modified client due to private tracker rules against development builds.

### 13. The RSS feed reader landscape

 Score: 249 Comments: 147 [Link](https://lighthouseapp.io/blog/feed-reader-deep-dive)

 > This article provides a comprehensive guide to choosing RSS feed readers by classifying them into four deployment models (on-device, browser extension, self-hosted, and hosted) and three business models (free, one-time payment, and SAAS). It explains the characteristics, advantages, and limitations of each category while listing popular products like NetNewsWire, FreshRSS, Feedly, and Lighthouse. The guide helps users select the best feed reader based on their needs for data control, functionality, and ease of use.

### 14. A competitor crippled a $23.5M bootcamp by becoming a Reddit moderator

 Score: 636 Comments: 393 [Link](https://larslofgren.com/codesmith-reddit-reputation-attack/)

 > Michael Novati, co-founder of competing coding bootcamp Formation, used his position as moderator of the r/codingbootcamp subreddit to launch a relentless reputation attack against Codesmith. He posted daily negative content, spread conspiracy theories, and deleted positive posts about Codesmith. This campaign severely damaged Codesmith's reputation, contributing to an 80% revenue drop and the CEO's departure. The story demonstrates how controlling a key industry subreddit can be weaponized to destroy competitors.

### 15. OpenAI, Nvidia fuel $1T AI market with web of circular deals

 Score: 231 Comments: 160 [Link](https://www.bloomberg.com/news/features/2025-10-07/openai-s-nvidia-amd-deals-boost-1-trillion-ai-boom-with-circular-deals)

 > OpenAI has made massive "circular" deals with Nvidia and AMD, where the chipmakers invest billions in OpenAI, which then commits to buying their processors. These interconnected transactions are artificially inflating the trillion-dollar AI market. Critics warn this creates an AI bubble, as spending far outpaces actual profitability. The complex web of deals binds the fates of multiple companies together, raising concerns about systemic risk if the bubble bursts.

### 16. SEC approves Texas Stock Exchange, first new US integrated exchange in decades

 Score: 573 Comments: 398 [Link](https://www.cbsnews.com/texas/news/sec-approves-texas-stock-exchange-txse/)

 > The SEC has approved the Texas Stock Exchange (TXSE), making it the first new fully integrated U.S. stock exchange in decades. Backed by major firms like BlackRock and Citadel Securities, the TXSE will be headquartered in Dallas. It is scheduled to launch trading services and corporate listings in 2026, aiming to compete with established exchanges like the NYSE and Nasdaq.

### 17. California enacts law enabling people to universally opt out of data sharing

 Score: 328 Comments: 56 [Link](https://therecord.media/california-signs-law-opt-out-browsers)

 > California has enacted a new law requiring web browsers to provide an easy, one-click mechanism for consumers to universally opt out of data sharing. This eliminates the need for users to opt out repeatedly on individual websites. The law builds upon the 2018 California Consumer Privacy Act and is the first of its kind in the United States. It aims to make privacy protections more accessible to millions of people.

### 18. Why we need SIMD

 Score: 136 Comments: 41 [Link](https://parallelprogrammer.substack.com/p/why-we-need-simd-the-real-reason)

 > SIMD (Single Instruction, Multiple Data) allows processors to perform the same operation on multiple data elements simultaneously, significantly increasing computational throughput. It became necessary after CPU designs exhausted other performance improvements like pipelining and superscalar execution. SIMD reuses existing CPU infrastructure, making it a cost-effective way to deliver more work per instruction. While adoption requires software updates, it provides major speedups for suitable workloads like media processing and scientific computing.

### 19. Man gets drunk, wakes up with a medical mystery that nearly kills him

 Score: 22 Comments: 4 [Link](https://arstechnica.com/health/2025/10/man-gets-drunk-wakes-up-with-a-medical-mystery-that-nearly-kills-him/)

 > A man nearly died from a mysterious illness after a night of heavy drinking. Doctors discovered he had accidentally swallowed a wooden toothpick while intoxicated, which pierced his intestine and caused a severe infection. The toothpick was found connecting his duodenum to his kidney during an endoscopic procedure. After its removal and antibiotic treatment, the man made a full recovery and stopped drinking.

### 20. One-man campaign ravages EU 'Chat Control' bill

 Score: 592 Comments: 197 [Link](https://www.politico.eu/article/one-man-spam-campaign-ravages-eu-chat-control-bill-fight-chat-control/)

 > A Danish software developer created a website called "Fight Chat Control" that enables mass email campaigns against the EU's proposed "chat control" bill. The legislation aims to combat child sexual abuse material but critics argue it threatens encryption and enables mass surveillance. The campaign has generated millions of emails to EU officials, overwhelming inboxes and influencing the political debate. This grassroots opposition has made some EU countries more hesitant to support the controversial proposal.

### 21. Birth of Prettier

 Score: 19 Comments: 2 [Link](https://blog.vjeux.com/2025/javascript/birth-of-prettier.html)

 > Prettier was created to end formatting debates like "tabs vs spaces" by automatically formatting code. The author was inspired by frustrating formatting experiences in school and at Facebook, then helped develop Prettier during a focused 6-month period. Using an elegant algorithm from an academic paper, Prettier formats code consistently while minimizing options. It achieved massive adoption, with over 80% of JavaScript developers using it by 2021, effectively solving code formatting disputes across the industry.

### 22. Meta launches Hyperscape, technology to turn real-world spaces into VR

 Score: 134 Comments: 183 [Link](https://techcrunch.com/2025/09/17/meta-launches-hyperscape-technology-to-turn-real-world-spaces-into-vr/)

 > Meta has launched Hyperscape, a technology that turns real-world spaces into photorealistic VR environments. Quest device owners can scan a room in minutes to create digital replicas. The feature is rolling out in early access for Quest 3 and Quest 3S users. Initially, users cannot invite others into these spaces, but that functionality is planned for the future.

### 23. Aerocart cargo gliders

 Score: 87 Comments: 53 [Link](https://www.aerolane.com/)

 > Aerolane develops Aerocart cargo gliders that fly behind existing aircraft to increase cargo capacity and reduce fuel consumption. These engineless gliders can double or triple payload capacity while achieving 65% fuel savings per cargo pound. The technology works with any aircraft as a "drop-in" upgrade and has been in flight testing since 2022. Aerolane claims this is the biggest aviation innovation since jet engines.

### 24. A few things to know before stealing my 914 (2022)

 Score: 301 Comments: 136 [Link](https://www.hagerty.com/media/advice/a-few-things-to-know-before-you-steal-my-914/)

 > This humorous article from a Porsche 914 owner details the numerous mechanical quirks that would frustrate any potential thief. The car has a disconnected battery, worn ignition switch requiring specific starting procedures, and extremely vague shift linkage. Additional challenges include malfunctioning brakes, oil leaks creating cabin fumes, and severe vibrations at higher speeds. The author suggests thieves would likely abandon the car after experiencing these issues.

### 25. Kurt Got Got

 Score: 256 Comments: 165 [Link](https://fly.io/blog/kurt-got-got/)

 > Fly.io's Twitter account was compromised after CEO Kurt Mackey fell for a targeted phishing email. The attack exploited psychological vulnerabilities by mimicking a Twitter alert about inappropriate content. The company had treated Twitter as a low-priority platform without phishing-resistant authentication. They regained control after approximately 15 hours through X.com's support. The incident highlights the importance of implementing phishing-resistant MFA for all systems.

### 26. Two things LLM coding agents are still bad at

 Score: 84 Comments: 114 [Link](https://kix.dev/two-things-llm-coding-agents-are-still-bad-at/)

 > LLM coding agents struggle with two key areas: they lack copy-paste functionality, instead rewriting code from memory which risks errors, and they fail to ask clarifying questions, making assumptions and brute-forcing solutions. These limitations make them feel like overconfident interns rather than replacements for human developers.

### 27. I played 1k hands of online poker and built a web app with Cursor AI

 Score: 87 Comments: 124 [Link](https://blog.rchase.com/i-played-1-000-hands-of-online-poker-and-built-a-web-app-with-cursor-ai/)

 > The author played 1,000 hands of online poker while studying the game extensively. Using Cursor AI, they built a fully functional Laravel web app for tracking poker statistics without writing any code themselves. The app includes features like hand history parsing, profit/loss charts, and automated data imports. This experience demonstrated how AI can rapidly build complex applications through conversational feedback.

### 28. X-ray scans reveal the hidden risks of cheap batteries

 Score: 158 Comments: 57 [Link](https://www.theverge.com/news/784966/lumafield-x-ray-ct-scan-lithium-ion-battery-risks-manufacturing-defect)

 > Access to The Verge website is blocked until October 2025 due to a suspected DDoS attack. The security block was triggered by abuse originating from a specific article about Lumafield's CT scans of lithium-ion batteries. This is a security measure to prevent further attacks.

### 29. Show HN: FleetCode – Open-source UI for running multiple coding agents

 Score: 81 Comments: 45 [Link](https://github.com/built-by-as/FleetCode)

 > FleetCode is a desktop application that enables running multiple CLI coding agents like Claude Code and Codex simultaneously. It creates isolated git worktrees for each session to keep work separate. The tool provides session persistence, terminal theming, and MCP server management. It's designed for developers who need to run parallel coding agent sessions efficiently.

### 30. Show HN: HyprMCP – Analytics, logs and auth for MCP servers

 Score: 46 Comments: 5 [Link](https://github.com/hyprmcp/jetski)

 > Jetski is an open-source platform that provides authentication, analytics, and prompt visibility for MCP servers without requiring code changes. It handles user onboarding, OAuth2.1 authentication, real-time logging, and analytics collection through a proxy gateway. The platform offers dashboards for monitoring server usage and automatically generates client setup instructions.

