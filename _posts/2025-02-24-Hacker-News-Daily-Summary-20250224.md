Updated at 2025-02-24 18:23:50 (UTC+8)

### 1. DeepSeek Open Source FlashMLA – MLA Decoding Kernel for Hopper GPUs

 Score: 239 Comments: 59 [Link](https://github.com/deepseek-ai/FlashMLA)

 > FlashMLA is an efficient Multi-Layer Attention (MLA) decoding kernel developed by DeepSeek-AI, optimized for variable-length sequences on Hopper GPUs. It features BF16 support, paged kvcache with 64-block size, and achieves up to 3000 GB/s memory bandwidth and 580 TFLOPS on H800 GPUs. The library requires CUDA 12.3+, PyTorch 2.0+, and offers easy integration via Python APIs for transformer-based models. Inspired by FlashAttention and Cutlass, it is released under the MIT license. The repository has garnered significant traction with 6k stars and 269 forks.

### 2. Cloudflare takes legal action over LaLiga's "disproportionate blocking efforts"

 Score: 74 Comments: 29 [Link](https://www.broadbandtvnews.com/2025/02/19/cloudflare-takes-legal-action-over-laligas-disproportionate-blocking-efforts/)

 > Cloudflare has filed a legal challenge against LaLiga, Spain's football league, over its aggressive IP-blocking measures targeting pirate streaming sites, which inadvertently restricted access to millions of unrelated websites. LaLiga accused Cloudflare of shielding illegal broadcasters, but Cloudflare argues the league’s actions—secured without notifying cloud providers—unlawfully prioritized commercial interests over public internet access. The dispute centers on shared IP addresses, where blocking one affects numerous sites, prompting Cloudflare to seek legal clarity against "disproportionate" practices threatening open internet principles.

### 3. Making any integer with four 2s

 Score: 236 Comments: 118 [Link](https://eli.thegreenplace.net/2025/making-any-integer-with-four-2s/)

 > This article describes a math puzzle where any natural number can be formed using exactly four instances of the digit 2 and various mathematical operations. Solutions range from basic arithmetic for simple numbers to advanced functions like factorials, Gamma functions, or nested square roots for complex targets. Paul Dirac devised a general solution using repeated square roots and logarithms, originally with three 2s, adjusted to four by exploiting \(2 - 2 = 0\) to meet the puzzle's rules. The approach demonstrates mathematical creativity, allowing endless solutions with increasing complexity. Dirac’s method highlights the puzzle’s flexibility and enduring appeal across skill levels.

### 4. Tokio and Prctl = Nasty Bug

 Score: 141 Comments: 44 [Link](https://kobzol.github.io/rust/2025/02/23/tokio-plus-prctl-equals-nasty-bug.html)

 > A bug in HyperQueue caused tasks to terminate after ~10 seconds due to using `prctl(PR_SET_PDEATHSIG)` in a Tokio `spawn_blocking` thread. Tokio's runtime reaped idle worker threads after 10 seconds, triggering `SIGTERM` on spawned processes when their parent thread exited. The issue stemmed from `PR_SET_PDEATHSIG` monitoring the worker thread (not the main process), leading to unintended task kills. Reverting the commit that moved process spawning to `spawn_blocking` resolved the bug. The fix preserved cleanup functionality while avoiding the thread-parent dependency pitfall.

### 5. Show HN: Jq-Like Tool for Markdown

 Score: 229 Comments: 53 [Link](https://github.com/yshavit/mdq)

 > mdq is a command-line tool inspired by jq, designed to query and extract specific elements from Markdown documents using syntax mirroring Markdown's structure (e.g., sections, lists, tasks). It supports filters like regex, quoted strings, and wildcards to target elements such as checkboxes, links, or tables. Use cases include validating checklist completion in GitHub PRs or extracting ticket URLs. Installation options include Cargo, pre-built binaries, and GitHub Actions workflows, with licensing under Apache 2.0 or MIT.

### 6. Partnering with the Shawnee Tribe for Civilization VII

 Score: 155 Comments: 143 [Link](https://civilization.2k.com/civ-vii/news/civilization-vii-shawnee-tribe-partnership/)

 > _Civilization VII_ partnered with the Shawnee Tribe to authentically represent their culture, collaborating with Chief Ben Barnes and cultural experts to ensure accurate depictions of the Shawnee civilization and leader Tecumseh, voiced by a Shawnee actor. The partnership included integrating the Shawnee language and historical research, while also supporting the Tribe's language preservation efforts through a new recording studio. This collaboration, part of the Tecumseh and Shawnee Pack DLC (available from April 2025), highlights mutual cultural respect and enriches both the game and the Shawnee Tribe's heritage initiatives.

### 7. Mere weeks after Starship's breakup, the vehicle may soon fly again

 Score: 14 Comments: 29 [Link](https://arstechnica.com/space/2025/02/starships-eighth-test-flight-may-take-place-next-week/)

 > SpaceX's Starship may launch its eighth test flight as early as February 26, just weeks after its seventh flight ended in an explosion over the Caribbean, scattering debris and disrupting air traffic. The FAA’s investigation into the January failure is ongoing but nearing resolution, allowing preparations for the next launch. The upcoming mission aims to replicate the previous flight’s objectives, including deploying dummy payloads and testing upgrades like larger propellant tanks. Success could advance SpaceX’s goals of deploying Starlink satellites and demonstrating in-space refueling. The FAA’s approval remains pending amid organizational scrutiny and logistical challenges.

### 8. European word translator: an interactive map

 Score: 194 Comments: 72 [Link](https://ukdataexplorer.com/european-translator/)

 > The European Word Translator is a tool that uses Google Translate to display translations of English words into various European languages, shown on a map. Users input lowercase words (e.g., "banana" or "she runs") and receive translations, though results may be inaccurate, use non-European variants, or lack coverage for some languages. Translations are based on 2014 data and are not updated. The project, inspired by Reddit etymology maps, relies on D3, Natural Earth, and Google’s API, with options to support hosting costs.

### 9. Ask HN: What are you working on? (February 2025)

 Score: 87 Comments: 275 [Link](item?id=43154065)

 > The article describes a 422 error (AssertionFailureError) when attempting to access the URL "http://item/?id=43154065," caused by "net::ERR_BLOCKED_BY_CLIENT," indicating the request was blocked by client-side security tools like ad blockers or browser settings.

### 10. Defragging my old Dell's UEFI NVRAM

 Score: 122 Comments: 24 [Link](https://artemis.sh/2025/02/22/uefi-nvram-defrag.html)

 > The author encountered a "No space left" error on an old Dell's UEFI NVRAM while setting up boot entries, despite minimal usage. Suspecting fragmentation, they used an EFI shell to dump, delete, and reload NVRAM variables via `dmpstore` commands, freeing up space without losing configurations. This resolved the issue, confirming NVRAM fragmentation as the cause.

### 11. Fast Cash vs. Slow Equity

 Score: 8 Comments: 3 [Link](https://blog.nateliason.com/p/fast-cash-slow-equity)

 > The article distinguishes between "cash businesses" (providing immediate, reliable income but limited scalability) and "equity businesses" (slow-growing but durable, with long-term value). The author, Nat Eliason, reflects on his mistake of treating his cash-focused marketing agency as an equity venture, while highlighting examples like Kit.com, which grew exponentially after years of minimal returns. He advises balancing both: using a cash business to fund living expenses while nurturing an equity business over 5-10 years. Misdiagnosing a business type risks wasted effort, such as scaling cash ventures beyond sustainability or abandoning equity projects prematurely. The key is maintaining cash flow to support long-term equity goals without immediate pressure.

### 12. Sublinear Time Algorithms

 Score: 91 Comments: 46 [Link](https://people.csail.mit.edu/ronitt/sublinear.html)

 > Sublinear time algorithms, which process only a tiny fraction of input, address challenges posed by massive datasets using randomization and approximation. They enable solutions for optimization problems, property testing, and distribution analysis, leveraging techniques like the Szemeredi Regularity lemma. The article highlights growing research, surveys, and resources, including the o(n) website and a 2024 Simons Institute program, while emphasizing the field's evolving nature and open questions.

### 13. It is not a compiler error (2017)

 Score: 62 Comments: 55 [Link](https://blog.plover.com/2017/11/12/)

 > The article argues that programming errors are almost always the programmer's fault, not compiler bugs, using anecdotes from Usenet, Perl, and JavaScript. However, the author shares a rare exception: discovering an actual bug in JavaScript's `sort()` function due to a flawed bubble sort implementation (incorrectly breaking on `changes ≤ 1` instead of `0`). Despite initial disbelief, the Code Studio team confirmed and fixed it, underscoring that while system errors are vanishingly rare, they *can* happen—but should only be considered after exhaustive self-checking.

### 14. WhiteSur: macOS-like theme for GTK desktops

 Score: 255 Comments: 157 [Link](https://github.com/vinceliuice/WhiteSur-gtk-theme)

 > The WhiteSur GTK Theme is a macOS-inspired customization for Linux GTK desktops, offering light/dark variants, adjustable opacity, accent colors, and Nautilus styles. Installation involves cloning the repository and running scripts, with options to tweak GNOME Shell, Firefox, GDM, and Flatpak themes. It addresses libadwaita compatibility in GNOME 43 via manual configuration overrides. Additional tools include icon themes, wallpapers, and detailed customization guides for panels, backgrounds, and fonts. The project supports donations and encourages community contributions.

### 15. Why Clojure?

 Score: 211 Comments: 166 [Link](https://gaiwan.co/blog/why-clojure/)

 > Clojure is chosen for its high developer productivity through interactive, REPL-driven development, enabling rapid feedback and functional programming with immutable data. Its ecosystem prioritizes long-term maintainability via stability and backward compatibility, minimizing upgrade costs. Additionally, Clojure fosters a culture of innovation, drawing from diverse ideas and promoting a community focused on thoughtful software design, while leveraging Java's ecosystem for broad interoperability.

### 16. Vietnamese Graphic Design

 Score: 311 Comments: 46 [Link](https://vietgd.com/)

 > Viet GD is an informal online platform dedicated to archiving, indexing, and celebrating Vietnamese graphic design, currently featuring 274 curated works. It offers navigation links to its homepage, about section, Instagram, a public spreadsheet of entries, and an issue-reporting form.

### 17. But good sir, what is electricity?

 Score: 358 Comments: 178 [Link](https://lcamtuf.substack.com/p/but-good-sir-what-is-electricity)

 > The article explains electricity through atomic structure and electron behavior, contrasting conductors (where valence electrons move freely as an electron gas) with insulators. It describes electricity as the movement of charges in conductors, driven by electrostatic fields propagating near light speed, though individual electrons drift slowly. The author avoids oversimplified analogies and advanced math, focusing on practical insights for hobbyists. Key topics include electron shells, conductivity mechanisms, and material properties, bridging basic concepts and deeper physics without relying on quantum mechanics.

### 18. The benefits of learning in public

 Score: 218 Comments: 61 [Link](https://www.gilesthomas.com/2025/02/20250223-til-deep-dive-posts)

 > Giles Thomas reflects on the benefits of documenting his learning process through blog posts, noting that writing detailed explanations ("TIL deep dives") helps solidify his own understanding and serves others seeking similar knowledge. These posts, often tutorials or summaries of technical topics, attract significant search traffic, indicating their value to external audiences. By sharing his learning publicly, he reinforces his expertise while creating resources he wished existed when he started. The author plans to prioritize such posts, blending personal growth with community contribution. This approach underscores the dual purpose of learning in public: enhancing retention and aiding others.

### 19. Orchid's nutrient theft from fungi shows photosynthesis-parasitism continuum

 Score: 66 Comments: 5 [Link](https://phys.org/news/2025-02-orchid-nutrient-theft-fungi-photosynthesis.html)

 > The orchid *Oreorchis patens* can photosynthesize but also parasitizes fungi, especially near rotting wood, switching to wood-decomposing fungi to boost nutrient uptake. This dual strategy enhances its growth and flower production, demonstrating a continuum between photosynthesis and parasitism. However, such behavior occurs in less than 10% of individuals, likely due to dependency on specific fungi found only near decomposing wood. The study highlights how environmental conditions influence parasitic adaptations, offering insights into evolutionary strategies in plant-fungi interactions.

### 20. We don't need startups, we need Digital-Mittelstand

 Score: 95 Comments: 113 [Link](https://mertbulan.com/2025/02/24/we-dont-need-startups-we-need-digital-mittelstand/)

 > The article argues that Germany's cultural values clash with Silicon Valley's startup ethos, making replication futile. Instead, it proposes a "Digital-Mittelstand" model, adapting Germany's traditional Mittelstand SMEs—known for niche expertise and quality—to digital products, prioritizing sustainability and work-life balance. This approach leverages Germany's decentralized economy and remote work to create scalable, low-cost digital solutions. The author suggests policy changes like salary grants, simplified regulations, VAT exemptions, and English support to foster this sector. Emphasizing alignment with German culture, Digital-Mittelstand aims to sustain economic resilience without mimicking Silicon Valley's growth-centric model.

### 21. Pollution from Big Tech's data centre boom costs US public health $5.4bn

 Score: 95 Comments: 72 [Link](https://www.ft.com/content/d595d5f6-79d1-47eb-b690-8597f09b39e7)

 > The rapid expansion of Big Tech's data centers in the U.S. has generated significant pollution, primarily from increased energy use and emissions, costing an estimated $5.4 billion annually in public health damages. These facilities, essential for cloud computing and AI, contribute to air quality degradation and associated health issues like respiratory illnesses. The analysis underscores the environmental and health trade-offs of tech infrastructure growth, urging stricter regulations and cleaner energy transitions.

### 22. Ultima VII: Revisited

 Score: 191 Comments: 43 [Link](https://www.u7revisited.com/)

 > Ultima VII: Revisited is a fan project by Anthony Salter that reimagines the classic 1992 RPG *Ultima VII* with a 3D engine, modernizing its visuals and addressing original flaws like clunky UI, poor performance, and tedious mechanics. Unlike the faithful 2D replication of the Exult engine, Revisited aims to enhance accessibility by introducing a 3D perspective, smoother combat, and improved inventory systems while preserving the game's innovative world design and depth. The goal is to bridge the gap for modern players, showcasing why *Ultima VII* remains a landmark RPG despite its dated technical execution.

### 23. Computer Simulation of Neural Networks Using Spreadsheets (2018)

 Score: 16 Comments: discuss [Link](https://arxiv.org/abs/1807.00018)

 > This article advocates for teaching neural network simulation using spreadsheets, reviewing methods like add-ins, macros, and optimization tools without external software. It highlights the historical role of the *Bulletin of Mathematical Biophysics*, Nicolas Rashevsky, and Walter Pitts in shaping computational neuroscience. The authors propose using historical models—Rashevsky’s continuous two-factor model, McCulloch-Pitts’ discrete model, and Householder-Landahl’s hybrid models—as educational foundations for spreadsheet-based neural network training.

### 24. Mascotbot: Real-Time, Engaging Avatar SDK for Al Agents

 Score: 20 Comments: 8 [Link](https://www.mascot.bot/)

 > Mascotbot offers a real-time avatar SDK for AI agents, featuring 120 fps vector characters, a TTS-agnostic lip-sync API, and multiplatform support via Rive’s technology. It provides customizable mascots designed by veteran animators, with plans starting at $2490 for custom designs and integration. Case studies highlight increased user engagement in education and nonprofit sectors through interactive, expressive avatars. The service includes React/NextJS SDKs and supports live voice interactions via Pipecat integration. Early adopters gain priority access to ensure competitive, dynamic user experiences.

### 25. JSON has become today's machine-readable output format (on Unix)

 Score: 29 Comments: 26 [Link](https://utcc.utoronto.ca/~cks/space/blog/sysadmin/JSONModernMachineReadableFormat)

 > The article advocates for JSON as the standard machine-readable output format on Unix systems due to its clarity, extensibility, and robust tooling (e.g., `jq`), citing its pragmatic advantages over custom formats. The author highlights a real-world example where JSON simplified processing Postfix mail queue data, emphasizing its role as a universal "narrow waist" for interoperability. While acknowledging JSON’s flaws, they argue its ecosystem and self-documenting structure outweigh alternatives, reducing the need for error-prone custom format design.

### 26. Show HN: Benchmarking VLMs vs. Traditional OCR

 Score: 98 Comments: 14 [Link](https://getomni.ai/ocr-benchmark)

 > The Omni AI OCR Benchmark evaluates Vision Language Models (VLMs) like Gemini 2.0 and GPT-4o against traditional OCR providers (Azure, AWS Textract) on 1,000 real-world documents, measuring JSON accuracy, cost, and latency. VLMs outperformed traditional models in handling complex layouts, handwriting, and low-quality scans, with OmniAI achieving 91.7% accuracy, though traditional OCR excelled in high-density text. The open-source benchmark uses GPT-4o to judge structured JSON extraction against ground truth data, avoiding text-similarity metrics for fairness. Costs and latency varied significantly, with VLMs generally pricier but more adaptable. The framework is publicly available for replication and future updates aim to expand document diversity.

### 27. How the UK Is Weakening Safety Worldwide

 Score: 192 Comments: 49 [Link](https://blog.thenewoil.org/how-the-uk-is-weakening-safety-worldwide)

 > The UK's Investigatory Powers Act compelled Apple to insert an encryption backdoor into iCloud, prompting Apple to remove its Advanced Data Protection (ADP) feature for UK users instead. This undermines global digital safety, as backdoors—like those exploited in the 2024 Salt Typhoon hack—are inherently vulnerable to abuse by malicious actors. The move reflects a broader pattern of governments, including the UK and US, pushing privacy-weakening measures under claims of combating crime or protecting children, echoing past "Crypto Wars." The article warns such actions threaten individual privacy and security worldwide, urging users to adopt alternative encrypted services and engage politically to resist erosion of digital rights.

### 28. Purely Functional Sliding Window Aggregation Algorithm

 Score: 31 Comments: 5 [Link](https://byorgey.github.io/blog/posts/2024/11/27/stacks-queues.html)

 > The article explains how to efficiently compute sliding window summaries (like sums or maximums) using monoidally-annotated queues built from two stacks. By annotating stacks with cumulative monoid measures (e.g., sums, max/min via custom monoids with infinity), queues enable O(1) amortized enqueue/dequeue and O(n) sliding window computations, leveraging functional programming techniques.

### 29. Augmenting NLQ with language knowledge bases like web search for ChatGPT

 Score: 7 Comments: discuss [Link](https://blog.hyperarc.com/p/ask-more-of-your-analytics)

 > The article discusses how integrating structured data (e.g., CRM, analytics) with unstructured knowledge (e.g., Slack, news) using LLMs and tools like graph RAG enables deeper business insights. While traditional BI tools address tabular data silos, combining them with linguistic knowledge from internal or public sources (e.g., layoff news, Slack conversations) allows answering complex questions that require both precise metrics and contextual understanding. Examples include analyzing H-1B data alongside layoff trends or calculating school replacement costs using institutional knowledge. Hyperarc’s beta feature demonstrates this unified approach, enabling queries that bridge data and knowledge silos for comprehensive answers. This integration unlocks new analytical possibilities, merging quantitative data with qualitative context.

### 30. War rooms vs. deep investigations

 Score: 214 Comments: 54 [Link](https://rachelbythebay.com/w/2025/02/22/war/)

 > The domain rachelbythebay.com has been blocked until December 31, 2039, due to suspected DDoS attacks originating from excessive requests to its feed URL. The security error cites abuse and enforces the block as a protective measure.

