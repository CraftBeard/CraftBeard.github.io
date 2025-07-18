Updated at 2025-07-18 17:10:33 (UTC+8)

### 1. Fully homomorphic encryption and the dawn of a private internet

 Score: 180 Comments: 51 [Link](https://bozmen.io/fhe)

 > Fully Homomorphic Encryption (FHE) enables computations on encrypted data without decryption, offering full privacy. Despite its high computational overhead, FHE is improving 8x yearly, making it increasingly practical for applications like encrypted cloud computing and AI. This could revolutionize internet privacy by keeping data encrypted at all times.

### 2. When Root Meets Immutable: OpenBSD Chflags vs. Log Tampering

 Score: 6 Comments: discuss [Link](https://rsadowski.de/posts/2025/openbsd-immutable-system-logs/)

 > The article explains how to use OpenBSD's `chflags` command with `sappnd` and `schg` flags to make system logs immutable, preventing tampering even by root users. This approach aligns with ISO 27001's requirement for log integrity without explicitly mandating immutability. The setup involves disabling automatic log rotation, creating an archive directory, and using `/etc/rc.securelevel` to manage flags during boot. This ensures forensic integrity while leveraging OpenBSD's built-in security features.

### 3. NIH is cheaper than the wrong dependency

 Score: 153 Comments: 79 [Link](https://lewiscampbell.tech/blog/250718.html)

 > Dependencies in coding aren't free—they come with costs like learning time, breaking changes, and deployment complexity. The article argues for evaluating dependencies based on ubiquity, stability, depth, ergonomics, and watertightness, using examples like POSIX and ECMA-48 as good dependencies. It warns against blindly relying on dependencies without considering their downsides.

### 4. Linux and Secure Boot certificate expiration

 Score: 65 Comments: 37 [Link](https://lwn.net/SubscriberLink/1029767/08f1d17c020e8292/)

 > Microsoft's Secure Boot certificate for Linux shim bootloaders expires in September 2025, potentially disrupting installations on systems without the new 2023 key. Firmware updates via LVFS/fwupd may help, but some older hardware might require manual intervention or disabling Secure Boot. The transition could be bumpy due to vendor-specific challenges.

### 5. ChatGPT agent: bridging research and action

 Score: 571 Comments: 386 [Link](https://openai.com/index/introducing-chatgpt-agent/)

 > OpenAI has introduced ChatGPT Agent, a unified system combining Operator's web interaction, deep research's synthesis, and ChatGPT's conversational skills to autonomously handle complex tasks like scheduling, research, and creating presentations. Available now for Pro, Plus, and Team users, it offers enhanced control and safety features while expanding real-world utility. The model sets new benchmarks in performance but remains in early stages with ongoing improvements planned.

### 6. Mistral Releases Deep Research, Voice, Projects in Le Chat

 Score: 529 Comments: 111 [Link](https://mistral.ai/news/le-chat-dives-deep)

 > Mistral AI has enhanced its Le Chat assistant with new features like Deep Research mode for structured reports, Voice mode for natural speech interaction, multilingual reasoning, Projects for organizing conversations, and advanced image editing. These updates aim to improve research, expression, and interaction efficiency. Users can try these features for free on chat.mistral.ai or via mobile apps.

### 7. The End of Windows 10: a toolkit for community repair groups

 Score: 29 Comments: 36 [Link](https://therestartproject.org/end-of-windows-10-toolkit-for-repair-groups/)

 > This article provides a toolkit for community repair groups to help users transition from Windows 10 as Microsoft ends support in 2025. It suggests integrating support into existing repair events, hosting dedicated "End of 10" parties, or collaborating with local organizations. Volunteers can guide users to alternatives like Linux or ChromeOS Flex, emphasizing data backups and tailored solutions. The goal is to extend device lifespans and reduce e-waste.

### 8. Arva AI (YC S24) Is Hiring an AI Research Engineer (London, UK)

 Score: None Comments: None [Link](https://www.arva.ai/careers/ai-research-engineer)

 > Arva AI is hiring an AI Research Engineer in Central London to develop LLM-based and agentic features for their AI-powered compliance platform. The role involves building AI systems, optimizing prompts, fine-tuning models, and collaborating with teams. Candidates need 3+ years of AI experience, technical expertise, and a product mindset. The company offers competitive pay, equity, and a flexible work culture.

### 9. My favorite use-case for AI is writing logs

 Score: 183 Comments: 119 [Link](https://newsletter.vickiboykis.com/archive/my-favorite-use-case-for-ai-is-writing-logs/)

 > The author highlights JetBrains' Full Line Code Completion in PyCharm as their favorite AI tool for writing logs, praising its efficiency and local inference model. It reduces repetitive logging tasks by auto-generating concise logs from context, improving debugging workflows. The feature uses a small, optimized model trained specifically for Python, demonstrating the value of specialized AI solutions over large general-purpose models.

### 10. My experience with Claude Code after two weeks of adventures

 Score: 253 Comments: 197 [Link](https://sankalp.bearblog.dev/my-claude-code-experience-after-2-weeks-of-usage/)

 > The author shares their experience using Claude Code (CC) for coding tasks over two weeks, comparing it to Cursor. They highlight CC's powerful features like subagents, context management, and CLI-based workflow, though it has a steeper learning curve. They prefer Sonnet 4 for most tasks but switch to Opus 4 for complex bugs. The post also includes tips, workflow insights, and feature requests for CC.

### 11. Claude Code Unleashed

 Score: 80 Comments: 42 [Link](https://ymichael.com/2025/07/15/claude-code-unleashed)

 > The article discusses the author's experience using Claude Code and background agents to enhance productivity, highlighting the benefits of running multiple agents simultaneously via Terragon. It covers workflow improvements, cost considerations, and practical examples of tasks suited for AI agents, concluding that this approach has transformed their development process.

### 12. Perfume reviews

 Score: 225 Comments: 119 [Link](https://gwern.net/blog/2025/perfume)

 > The author explores avant-garde perfumes after being intrigued by a Twitter thread, discovering scents like "Room 237" (inspired by *The Shining*) and ocean-themed fragrances. Sampling affordable options, they conclude perfumes can be art, settling on Acqua di Sale and Kyoto Incense as favorites. The experience broadened their appreciation for olfactory creativity.

### 13. Hand: open-source Robot Hand

 Score: 378 Comments: 100 [Link](https://github.com/pollen-robotics/AmazingHand)

 > GitHub.com is blocked until July 18, 2025, due to suspected DDoS abuse linked to a VMware Photon security update page. The domain was flagged for excessive requests.

### 14. Extending That XOR Trick to Billions of Rows

 Score: 54 Comments: 6 [Link](https://nochlin.com/blog/extending-that-xor-trick)

 > The article explains how the XOR trick for finding missing numbers can be extended to handle large datasets using Invertible Bloom Filters (IBFs). IBFs efficiently compare sets by focusing only on their differences, using partitioning and accumulators to detect and recover missing elements. The author provides a Python implementation and references for further reading.

### 15. TCP-in-UDP Solution (eBPF)

 Score: 17 Comments: 3 [Link](https://blog.mptcp.dev/2025/07/14/TCP-in-UDP.html)

 > The article introduces **TCP-in-UDP**, an eBPF-based solution to bypass middleboxes blocking MPTCP by converting TCP packets into UDP format without extra layers or VPNs. It explains header modifications, checksum handling, and optimizations while addressing challenges like GRO/TSO offloading and MTU adjustments. The tool simplifies deployment for improved MPTCP compatibility.

### 16. DIY Telescope Mods That Transformed My Astrophotography

 Score: 9 Comments: 1 comment [Link](https://www.youtube.com/watch?v=Efmzr_K4ApQ)

 > The video shows three budget-friendly DIY astrophotography upgrades costing under $20: flocking the telescope tube with felt to reduce reflections, installing a light shield to block stray light, and using a 3D-printed Bahtinov mask for precise focusing. These simple mods significantly improved image sharpness and contrast.

### 17. Self-taught engineers often outperform (2024)

 Score: 274 Comments: 224 [Link](https://michaelbastos.com/blog/why-self-taught-engineers-often-outperform)

 > The article argues that self-taught engineers often outperform formally trained ones because hands-on problem-solving and real-world experience ("purposeful tinkering") build deeper intuition and resilience than structured education alone. It highlights examples like Linus Torvalds and Margaret Hamilton, emphasizing that immediate feedback, creativity, and learning from failure drive mastery. Mentorship helps but cannot replace practical experimentation.

### 18. A look at IBM's short-lived "butterfly" ThinkPad 701 of 1995

 Score: 70 Comments: 20 [Link](https://www.fastcompany.com/91356463/ibm-thinkpad-701-butterfly-keyboard)

 > The 1995 IBM ThinkPad 701, known for its innovative "Butterfly" keyboard, expanded to provide a full-sized typing experience in a compact subnotebook. Despite its short lifespan due to outdated hardware and evolving laptop designs, its mechanical ingenuity remains iconic. Today, enthusiasts still celebrate its unique engineering, restoring and modding units to keep its legacy alive. The ThinkPad 701 stands as a testament to creative problem-solving in tech history.

### 19. RisingWave: An Open‑Source Stream‑Processing and Management Platform

 Score: 34 Comments: 4 [Link](https://github.com/risingwavelabs/risingwave)

 > GitHub.com is blocked until July 18, 2025, due to suspected DDoS abuse linked to a VMware Photon security update page. The domain was flagged for excessive requests.

### 20. Why is AI so slow to spread?

 Score: 42 Comments: 95 [Link](https://www.economist.com/finance-and-economics/2025/07/17/why-is-ai-so-slow-to-spread-economics-can-explain)

 > The article explains that despite widespread enthusiasm from executives about AI's potential, its adoption in businesses remains slow due to economic factors like high implementation costs, organizational inertia, and unclear returns on investment. Many companies struggle to integrate AI effectively, even as they tout its benefits.

### 21. All AI models might be the same

 Score: 197 Comments: 101 [Link](https://blog.jxmo.io/p/there-is-only-one-model)

 > The article argues that all AI models may converge to the same underlying representations as they scale, a concept called the Platonic Representation Hypothesis. It suggests that intelligence is compression, and better models learn similar features of the world. Evidence includes unsupervised mapping between embedding spaces and shared interpretable features across models. This could enable universal translation between languages or even decoding whale communication.

### 22. USB-C hubs and my slow descent into madness (2021)

 Score: 140 Comments: 96 [Link](https://overengineer.dev/blog/2021/04/25/usb-c-hub-madness/)

 > The author shares their frustrating experience with multiple USB-C hubs, all of which had reliability issues, overheating problems, and used the same unreliable Realtek RTL8153 chip. Despite paying premium prices for branded hubs, they discovered these were just rebranded cheap products from Chinese manufacturers. The article concludes with skepticism about USB-C hub quality and a switch to Thunderbolt alternatives.

### 23. Apple Intelligence Foundation Language Models Tech Report 2025

 Score: 214 Comments: 153 [Link](https://machinelearning.apple.com/research/apple-foundation-models-tech-report-2025)

 > Apple introduced two foundation models for Apple Intelligence: a 3B-parameter on-device model optimized for efficiency and a scalable server model using PT-MoE transformers. Both are trained on multilingual, multimodal data with privacy safeguards and outperform comparable models in benchmarks. Developers can integrate them via a new Swift framework.

### 24. Apple bans entire dev account, no reason given

 Score: 100 Comments: 60 [Link](https://twitter.com/rameerez/status/1945784476723810739)

 > A developer struggled with macOS app notarization delays in Xcode, contacted Apple Support, and unexpectedly had their entire Developer Account terminated. The incident sparked widespread discussion online.

### 25. Fixing a Direct3D9 bug in Far Cry (2018)

 Score: 12 Comments: discuss [Link](https://houssemnasri.github.io/2018/07/07/farcry-d3d9-bug/)

 > The article explains how a Direct3D9 bug in Far Cry caused broken water reflections on newer Windows versions. The issue stemmed from misapplied clip planes in the programmable pipeline. The author fixed it by saving and re-applying clip planes before each draw, restoring proper reflections without performance loss. The patch's source code is available on GitHub.

### 26. Astronomers Discover Rare Distant Object in Sync with Neptune

 Score: 34 Comments: 6 [Link](https://pweb.cfa.harvard.edu/news/astronomers-discover-rare-distant-object-sync-neptune)

 > Astronomers discovered a rare trans-Neptunian object, 2020 VN40, which orbits the Sun once for every ten orbits of Neptune. This finding, led by the Center for Astrophysics, provides insights into the dynamics of the outer solar system. The object's unusual orbit suggests new types of gravitational interactions with Neptune. The discovery was made using telescopes like the Canada-France-Hawaii Telescope and published in *The Planetary Science Journal*. Future surveys may reveal more such objects.

### 27. Anthropic tightens usage limits for Claude Code without telling users

 Score: 324 Comments: 200 [Link](https://techcrunch.com/2025/07/17/anthropic-tightens-usage-limits-for-claude-code-without-telling-users/)

 > TechCrunch.com is blocked until July 18, 2025, due to suspected DDoS abuse linked to an article about VivaTech 2025 startups. The domain was flagged for excessive requests.

### 28. Archaeologists discover tomb of first king of Caracol

 Score: 146 Comments: 35 [Link](https://uh.edu/news-events/stories/2025/july/07102025-caracol-chase-discovery-maya-ruler.php)

 > University of Houston archaeologists discovered the tomb of Te K’ab Chaak, the first ruler of the ancient Maya city Caracol in Belize, dating to 331 AD. The tomb contained artifacts like jadeite jewelry and pottery, revealing early connections between Maya rulers and Teotihuacan. The find, part of over 40 years of research, challenges previous assumptions about Maya-Teotihuacan interactions. The dynasty founded by Te K’ab Chaak lasted over 460 years. Further analysis of the tomb's contents is ongoing.

### 29. Run TypeScript code without worrying about configuration

 Score: 75 Comments: 45 [Link](https://tsx.is/)

 > **Summary:**  
_tsx_ (TypeScript Execute) is a Node.js tool that simplifies running TypeScript files with seamless ESM/CJS support, watch mode, and minimal configuration. It enhances Node.js for TypeScript users and relies on sponsorships for sustainability.

### 30. Modular Interpreters and Visitors in Rust with Extensible Variants and CGP

 Score: 15 Comments: discuss [Link](https://contextgeneric.dev/blog/extensible-datatypes-part-2/)

 > This article explores using Context-Generic Programming (CGP) in Rust to build modular interpreters and extensible visitors, addressing the expression problem. It demonstrates how CGP enables decoupled, type-safe evaluation and transformation of arithmetic expressions into Lisp-like syntax. The approach avoids rigid enum coupling and runtime errors, offering compile-time guarantees and extensibility. The full code is available on GitHub.

