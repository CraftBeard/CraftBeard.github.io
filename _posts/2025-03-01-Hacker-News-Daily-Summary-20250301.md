Updated at 2025-03-01 17:34:50 (UTC+8)

### 1. How to gain code execution on hundreds of millions of people and popular apps

 Score: 641 Comments: 171 [Link](https://kibty.town/blog/todesktop/)

 > Eva discovered a critical vulnerability in ToDesktop, a service used by apps like Cursor and ClickUp, by exploiting insecure Firebase configurations and a build container with hardcoded admin credentials. This allowed her to hijack deployments and execute remote code (RCE) on millions of users' devices. After responsibly disclosing the issue, ToDesktop swiftly patched the flaw and compensated her $5k, while Cursor awarded her $50k post-fix. The exploit highlighted risks in third-party app-build services but praised ToDesktop's responsive resolution.

### 2. Self-Hosting a Firefox Sync Server

 Score: 163 Comments: 30 [Link](https://blog.diego.dev/posts/firefox-sync-server/)

 > The article details the author's experience self-hosting a Firefox Sync server using the Rust-based `syncstorage-rs` project after Mozilla's original Python solution was deprecated. Facing confusing Docker documentation, they opted for a community-driven Docker setup (`syncstorage-rs-docker`) and configured MariaDB, Docker Compose, and a Caddy reverse proxy. Challenges included database persistence, server storage limits, and unclear setup steps. Despite hurdles, the server was successfully deployed in two hours, highlighting reliance on community tools over official guides. The process is feasible but requires Docker and database familiarity.

### 3. 400 reasons to not use Microsoft Azure

 Score: 386 Comments: 210 [Link](https://azsh.it)

 > The article compiles daily critiques from "Daily Azure Shit," a Mastodon account documenting recurring issues with Microsoft Azure, including broken documentation links, unreliable APIs (e.g., Carbon Optimization API errors), internal server errors with no logs, and inconsistent UI/resource management. It highlights Microsoft's shift toward AI tools like Copilot over functional solutions, causing user frustration. The account, unaffiliated with Microsoft, emphasizes persistent platform flaws affecting usability and sustainability efforts.

### 4. Zen 5's AVX-512 Frequency Behavior

 Score: 59 Comments: 12 [Link](https://chipsandcheese.com/p/zen-5s-avx-512-frequency-behavior)

 > AMD's Zen 5 architecture efficiently handles AVX-512 workloads without fixed frequency offsets, maintaining peak clock speeds (e.g., 5.7 GHz) for register-based operations, unlike Intel's Skylake-X, which suffered significant frequency drops. However, Zen 5 experiences brief transition periods with reduced IPC during heavy AVX-512 memory workloads, adapting via fine-grained throttling rather than drastic clock reductions. This adaptive approach, leveraging per-core sensors and gradual frequency adjustments, minimizes performance penalties and outperforms Intel's older methods, showcasing Zen 5's advanced power and thermal management on a 4nm process.

### 5. 3,200% CPU Utilization

 Score: 379 Comments: 162 [Link](https://josephmate.github.io/2025-02-26-3200p-cpu-util/)

 > A Java application experienced 3200% CPU usage due to concurrent threads corrupting an unsynchronized TreeMap, causing infinite loops during insertions. The corruption occurred when concurrent modifications created cyclic references in the underlying red-black tree, exacerbated by swallowed NullPointerExceptions in thread pools. The author reproduced the issue in Java, C++, and Go, challenging assumptions that only languages allowing caught NPEs were vulnerable. Fixes involved using thread-safe structures like ConcurrentHashMap or synchronizing access. The incident underscores the importance of layered safeguards like CPU monitoring, uncaught exception handlers, and static analysis to detect concurrency bugs.

### 6. Certificate Transparency in Firefox: A Big Step for Web Security

 Score: 17 Comments: 3 [Link](https://blog.transparency.dev/ct-in-firefox)

 > Firefox now enforces Certificate Transparency (CT) starting with desktop version 135, rejecting non-compliant certificates to combat fraud and man-in-the-middle attacks. This aligns Firefox with other major browsers, requiring certificates to be logged in public CT logs for validation. Website owners must ensure their Certificate Authorities support CT and monitor for unauthorized certificates. Firefox uses Chrome’s CT log list, updated weekly, and may adopt tile-based logs as industry standards evolve. This move enhances web security by increasing transparency and reducing risks of undetected malicious certificates.

### 7. OlmOCR: Open-source tool to extract plain text from PDFs

 Score: 172 Comments: 25 [Link](https://olmocr.allenai.org/)

 > olmOCR is an open-source OCR tool by AllenAI for converting PDFs, images, and documents into text while preserving structure, supporting tables, equations, and handwriting. Trained on academic and technical content, it uses prompting techniques to enhance accuracy and reduce errors, optimized for English. The toolkit offers scalable processing at ~$190 per million pages via GPU deployment, with a demo available for testing.

### 8. Affixes: The Building Blocks of English

 Score: 41 Comments: 5 [Link](https://www.affixes.org/index.html)

 > The Dictionary of Affixes, created by Michael Quinion, is a free online resource derived from his 2002 Oxford University Press book, offering over 1,250 entries and 10,000 examples of prefixes, suffixes, and combining forms. After the book went out of print in 2008, it was made freely available online, with ongoing updates and revisions. The site includes an introduction, author details, and a contact page, last updated in July 2020.

### 9. Why it's so hard to build a jet engine

 Score: 158 Comments: 37 [Link](https://www.construction-physics.com/p/why-its-so-hard-to-build-a-jet-engine)

 > Building jet engines is exceptionally challenging due to extreme performance demands, requiring advanced materials to handle high temperatures and pressures while optimizing efficiency and durability. Development involves balancing innovation with cost-effective manufacturing, leading to multi-billion-dollar investments and prolonged R&D. Only a few companies like GE, Rolls-Royce, and Pratt & Whitney possess the technical and financial capacity, as seen in projects like Rolls-Royce's RB211, which faced bankruptcy from technical challenges. Continuous advancements in turbine cooling, compression ratios, and materials are critical to meet aviation's stringent safety and efficiency standards.

### 10. When eBPF pt_regs reads return garbage on the latest Linux kernels, blame Fred

 Score: 67 Comments: 4 [Link](https://tanelpoder.com/posts/ebpf-pt-regs-error-on-linux-blame-fred/)

 > Starting with Linux kernel 6.9, the `CONFIG_X86_FRED` feature adds 16 bytes of padding to the kernel stack, shifting the `pt_regs` structure's location. eBPF programs accessing `task->stack->pt_regs` directly must adjust their address calculations to avoid reading garbage values. The author resolved this by dynamically detecting FRED's presence and modifying the offset in their eBPF code. This change impacts x86_64 systems (Intel/AMD) and requires manual handling in raw memory access scenarios.

### 11. Troubleshooting: A skill that never goes obsolete

 Score: 205 Comments: 69 [Link](https://www.autodidacts.io/troubleshooting/)

 > The article emphasizes troubleshooting as a vital, timeless skill involving systematic problem-solving across domains. It advocates stepping back to understand systems, isolating issues through hypothesis testing, and gathering data to shorten feedback loops. Key strategies include balancing fixes with information gathering, understanding risks, and maintaining patience. The author highlights improvisation, reducing noise, and learning from experts to enhance effectiveness. Ultimately, troubleshooting is portrayed as a mindset requiring both analytical and adaptive thinking.

### 12. Harnessing orbital Hall effect in spin-orbit torque MRAM

 Score: 9 Comments: discuss [Link](https://www.nature.com/articles/s41467-024-55437-x)

 > This article explores using the Orbital Hall Effect (OHE) to enhance Spin-Orbit Torque Magnetic RAM (SOT-MRAM) for energy-efficient data storage. Traditional SOT-MRAM relies on high-resistance materials like platinum or beta-tungsten, which increase power consumption. By integrating OHE with ruthenium, niobium, or chromium layered with platinum, the study achieves a 30% boost in torque efficiency and 20% lower switching current compared to pure platinum, reducing power use by 60%. Testing over 250 devices confirmed these improvements while maintaining industrial-grade thermal stability. This approach offers a promising path for next-generation, high-density memory with lower energy demands.

### 13. Show HN: Torii – a framework agnostic authentication library for Rust

 Score: 44 Comments: 9 [Link](https://github.com/cmackenzie1/torii-rs)

 > Torii-rs is a Rust authentication framework offering full control over user data through a plugin system, supporting features like passwords, OAuth, and passkeys. It allows storing data in SQLite or PostgreSQL (with MySQL planned) and is MIT-licensed. Currently in early development, it is not production-ready and lacks security audits.

### 14. Write to Escape Your Default Setting

 Score: 295 Comments: 73 [Link](https://kupajo.com/write-to-escape-your-default-setting/)

 > The article argues that writing helps escape the mind's default state of distraction and superficial thinking by structuring thoughts, expanding memory, and revealing biases. It forces clarity, connects ideas, and uncovers hidden assumptions, allowing self-interrogation to disentangle mental clutter and gain insight. Writing exposes flawed ideas and emotional projections, creating mental space for deeper understanding.

### 15. Merlion: A Machine Learning Framework for Time Series Intelligence

 Score: 132 Comments: 19 [Link](https://github.com/salesforce/Merlion)

 > Merlion, developed by Salesforce, is a Python machine learning library for time series intelligence, offering tools for forecasting, anomaly detection, and change point detection. It provides an end-to-end framework with AutoML, benchmarking, diverse models (statistical to deep learning), and visualization, supporting both univariate and multivariate data. Compared to libraries like Prophet or darts, Merlion excels in features like post-processing, exogenous regressors, and distributed computation via PySpark. Installation is via PyPI, and it includes a GUI dashboard for interactive analysis. A technical report details its architecture and performance benchmarks.

### 16. An update on Mozilla's terms of use for Firefox

 Score: 314 Comments: 182 [Link](https://blog.mozilla.org/en/products/firefox/update-on-terms-of-use/)

 > Mozilla updated its Firefox Terms of Use (TOU) and Privacy Notice, clarifying that user data is only licensed to Mozilla for operating Firefox, not granting ownership, and removed a confusing Acceptable Use Policy reference. They adjusted Privacy FAQ language around "selling data" to address evolving legal definitions (e.g., CCPA), emphasizing they don’t sell personal data traditionally but share limited, anonymized data with partners for features like sponsored search suggestions. Mozilla highlighted user control over privacy settings and reaffirmed its commitment to data protection through safeguards like OHTTP. The changes aim to align with legal standards while maintaining transparency.

### 17. The Dino, the Llama, and the Whale (Deno and Jupyter for Local AI Experiments)

 Score: 32 Comments: 8 [Link](https://deno.com/blog/the-dino-llama-and-whale)

 > The article details using Deno, Jupyter Notebooks, and Ollama to experiment with local AI models like DeepSeek R1, leveraging TypeScript/JavaScript tools (LangChain.js, Zod) for workflows and validation. It outlines setup steps for local LLMs, demonstrates creating chains for structured outputs, and highlights Deno's seamless integration with Jupyter for iterative AI prototyping. The author concludes that this setup offers a low-friction, productive environment for learning and testing AI locally.

### 18. Boris Spassky: 1937–2025

 Score: 274 Comments: 49 [Link](https://en.chessbase.com/post/boris-spassky-1937-2025)

 > Boris Spassky (1937–2025), the 10th World Chess Champion, renowned for his 1969 title win and 1972 "Match of the Century" loss to Bobby Fischer, passed away at 88. A chess prodigy turned grandmaster at 18, he later faced health struggles after a 2012 stroke. Frederic Friedel, a longtime friend, shared personal memories of their encounters, highlighting Spassky's charisma and contributions to chess. FIDE president Arkady Dvorkovich praised him as a gentleman and legend. The article reflects on his legacy and directs readers to broader tributes.

### 19. Japanese Toshiba Typewriter Model BW-2112 (2020) [video]

 Score: 69 Comments: 13 [Link](https://www.youtube.com/watch?v=JZcui85b4EE)

 > The video showcases a rare Toshiba BW-2112 typewriter designed for Japanese, Chinese, and English text, utilizing a grid-based mechanical system with knobs and levers to select characters. Uploaded in 2020 by Typewriter Collector, it highlights the machine's intricate engineering to handle thousands of kanji and kana symbols. Viewers express awe at its complexity, comparing it to simpler Latin keyboards and praising Japanese ingenuity. The typewriter's slow, deliberate operation contrasts sharply with modern digital input methods, emphasizing its historical significance. Comments also note its nostalgic value and the skill required to operate such a device efficiently.

### 20. AI is killing some companies, yet others are thriving – let's look at the data

 Score: 163 Comments: 159 [Link](https://www.elenaverna.com/p/ai-is-killing-some-companies-yet)

 > AI is disrupting companies like WebMD, Chegg, and G2, which rely on SEO and ad revenue, as AI-powered tools (e.g., ChatGPT, Google AI Overviews) deliver instant answers, reducing user visits. Platforms such as Quora and Stack Overflow also face traffic declines, while Reddit, Substack, and Wikipedia thrive by emphasizing authentic community content and user-generated material. The shift, termed "Product-Market Fit Collapse," aligns with AI advancements post-2022, though external factors may contribute. Struggling firms risk obsolescence without adapting to AI, while resilient platforms leverage human-driven engagement. Traffic data highlights this divergence, with some sites losing millions of visits and others growing.

### 21. Surgery implants tooth material in eye as scaffolding for lens

 Score: 115 Comments: 50 [Link](https://www.cbc.ca/radio/asithappens/tooth-in-eye-surgery-canada-1.7470626)

 > Canadian surgeons performed the country's first osteo-odonto keratoprosthesis (OOKP), or "tooth-in-eye" surgery, embedding a patient's tooth with a lens into the eye to restore vision for those with severe corneal blindness. The procedure, used as a last resort, involves implanting a modified tooth into the eye to support a prosthetic lens, leveraging the body’s own tissue to avoid rejection. Three patients, including Brent Chapman, who lost his sight due to a rare autoimmune reaction, underwent the complex two-stage surgery in B.C., aiming to permanently restore vision after previous treatments failed. The surgery, successful in other countries for decades, could lead to Canada’s first dedicated OOKP clinic, improving access for patients who previously needed to seek care abroad. Chapman hopes the groundbreaking procedure will allow him to regain independence and inspire future treatments.

### 22. Violence alters human genes for generations, researchers discover

 Score: 387 Comments: 224 [Link](https://news.ufl.edu/2025/02/syrian-violence-epigenetics/)

 > A University of Florida-led study reveals that Syrian women who endured the 1982 Hama siege passed epigenetic changes—chemical modifications affecting gene expression—to their grandchildren, marking the first human evidence of multigenerational stress transmission previously seen in animals. Researchers found 14 epigenetic markers in grandchildren linked to grandmothers' trauma and noted accelerated biological aging in those exposed prenatally to violence. The findings, drawn from three generations of Syrian refugees, suggest such genetic imprints may contribute to intergenerational cycles of trauma and health risks, emphasizing the need to address systemic violence and its enduring impacts.

### 23. Calendar.txt

 Score: 292 Comments: 121 [Link](https://terokarvinen.com/2021/calendar-txt/)

 > Calendar.txt is a plain text-based calendar system using ISO-8601 dates and week numbers, designed for simplicity, cross-platform compatibility, and version control. It allows easy editing with any text editor, supports grep-based searches for events/tags, and syncs via tools like Syncthing. The format includes daily, weekly, monthly, and yearly goals, with optional context tags (@Work) and timezone flexibility. A downloadable template extends to 2033, and it integrates with todo.txt for task management. Benefits include future-proofing, Unix philosophy adherence, and mobile-friendly synchronization.

### 24. Zelensky leaves White House after angry meeting

 Score: 2382 Comments: 3569 [Link](https://www.bbc.com/news/live/c625ex282zzt)

 > Ukrainian President Volodymyr Zelensky was reportedly asked to leave the White House following a heated exchange with U.S. President Donald Trump and Vice President JD Vance during a visit in February 2025. The clash, centered on U.S. support for Ukraine and perceived ingratitude, drew condemnation from Democrats, who accused Trump and Vance of undermining Ukraine and aiding Russian President Vladimir Putin. Zelensky later addressed the incident in a Fox News interview, defending Ukraine’s stance and expressing hope for continued U.S. support, while acknowledging the strained relations. The confrontation, captured in a viral photo of Ukraine’s ambassador reacting in dismay, left the Ukrainian delegation reeling and raised concerns about future bilateral ties. Zelensky proceeded to London to meet UK Prime Minister Keir Starmer amid efforts to salvage international alliances.

### 25. Failure Theory for Materials Science and Engineering – Richard M. Christensen

 Score: 33 Comments: 5 [Link](https://www.failurecriteria.com/)

 > This article outlines comprehensive failure criteria for isotropic and anisotropic materials, addressing ductile vs. brittle failure, fatigue, creep, and composite-specific behaviors. It integrates theoretical frameworks with experimental validation, covering micromechanics, probabilistic failure, and nanomaterials like graphene. The criteria are calibrated using uniaxial tension/compression properties and emphasize transitions between failure modes. Applications span fiber composites, laminates, and nanoscale materials, with a focus on rigorous validation through critical data comparisons. The approach unifies elasticity, fracture mechanics, and strain energy principles to predict failure across diverse conditions.

### 26. Stone Soup AI (2024)

 Score: 108 Comments: 48 [Link](https://simons.berkeley.edu/news/stone-soup-ai)

 > The article "Stone Soup AI" by Alison Gopnik critiques the view of AI systems as autonomous intelligent agents, likening them instead to "cultural technologies" that aggregate human knowledge, akin to the folktale where villagers collectively create a soup from stones and shared ingredients. Gopnik argues that AI’s effectiveness stems from combining algorithms with vast human-generated data, feedback, and user prompts, emphasizing collaboration over individual intelligence. While debunking claims of AI’s inherent "magic," she highlights the genuine value of collective human contributions in advancing these systems.

### 27. Hot take: GPT 4.5 is a nothing burger

 Score: 181 Comments: 197 [Link](https://garymarcus.substack.com/p/hot-take-gpt-45-is-a-nothing-burger)

 > The article titled "Hot Take: GPT-4.5 is a Nothing Burger" by Gary Marcus appears inaccessible due to a 403 Forbidden error, suggesting restricted access or technical issues. Based on the title, Marcus likely critiques GPT-4.5 as an underwhelming or insignificant update, though the full content cannot be retrieved for confirmation. The error message and image placeholder imply the piece may not load properly.

### 28. Netboot Windows 11 with iSCSI and iPXE

 Score: 178 Comments: 46 [Link](https://terinstock.com/post/2025/02/Netboot-Windows-11-with-iSCSI-and-iPXE/)

 > The author details their process of netbooting Windows 11 via iSCSI and iPXE to avoid local installation, driven by a game that bans Linux and VMs. Using a NAS-hosted iSCSI target and a custom Windows PE image with network drivers, they configured iPXE to boot from the network, overcoming installer issues and automating the boot process via EFI. This setup allows running Windows solely over the network, preserving local storage for Linux while complying with the game’s restrictions.

### 29. Show HN: Globstar – Open-source static analysis toolkit

 Score: 87 Comments: 20 [Link](item?id=43207942)

 > The error indicates a failed attempt to access the URL "http://item/?id=43207942" due to being blocked by the client (likely a browser extension, ad blocker, or security setting). The server returned a 422 status code, signaling an unprocessable request.

### 30. A Path to Scalable Quantum Computers

 Score: 11 Comments: discuss [Link](https://physics.aps.org/articles/v18/40)

 > Researchers at ETH Zurich developed a scalable trapped-ion quantum computing architecture using integrated photonics to control ions in a quantum charge-coupled device (QCCD). They overcame distortions from dielectric materials by stabilizing ion transport with tailored voltage protocols, reducing coherent excitation from 58 to 8 quanta and achieving over 99% fidelity in single-qubit operations. Their system enabled coherent qubit manipulation across multiple zones and parallel operations, addressing key challenges for scaling. This work demonstrates a critical step toward large-scale quantum processors by integrating photonics while maintaining high fidelity, paving the way for practical, scalable quantum computers.

