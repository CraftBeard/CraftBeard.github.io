Updated at 2025-02-25 18:25:44 (UTC+8)

### 1. How Core Git Developers Configure Git

 Score: 98 Comments: 26 [Link](https://blog.gitbutler.com/how-git-core-devs-configure-git/)

 > The article outlines recommended Git configurations from core developers, including settings like `branch.sort = -committerdate`, `diff.algorithm = histogram`, and `push.autoSetupRemote = true` to enhance usability. It references a mailing list experiment where developers identified defaults like `merge.conflictstyle = zdiff3` and `rebase.autosquash = true` as improvements. These optimizations improve diff clarity, branch management, and conflict resolution but remain non-default despite consensus. The author argues these settings should be standard for a better Git experience.

### 2. Claude 3.7 Sonnet and Claude Code

 Score: 1680 Comments: 738 [Link](https://www.anthropic.com/news/claude-3-7-sonnet)

 > Anthropic launched Claude 3.7 Sonnet, its most advanced hybrid reasoning model, offering instant responses or visible extended thinking for complex tasks, with enhanced coding and web development capabilities. It introduces Claude Code, a command-line tool for agentic coding (limited preview), and maintains pricing at $3/$15 per million input/output tokens. The model excels in real-world applications, reduces unnecessary refusals by 45%, and is available across platforms including free tiers (excluding extended thinking).

### 3. DigiCert: Threat of legal action to stifle Bugzilla discourse

 Score: 315 Comments: 75 [Link](https://bugzilla.mozilla.org/show_bug.cgi?id=1950144)

 > DigiCert threatened legal action against Sectigo after Sectigo's Chief Compliance Officer, Tim Callan, criticized DigiCert's certificate practices on Mozilla's Bugzilla forum. Sectigo's General Counsel, Brian Holland, publicly denounced the legal threats, arguing they undermine transparent, open discourse vital for the WebPKI community's self-regulation. Holland emphasized that stifling such discussions harms industry accountability and security improvements, urging the community to address DigiCert's intimidation tactics. The incident highlights tensions over legal coercion in public technical debates critical to maintaining trust in certificate authority practices.

### 4. DeepSeek open source DeepEP – library for MoE training and Inference

 Score: 273 Comments: 36 [Link](https://github.com/deepseek-ai/DeepEP)

 > DeepEP is a high-performance communication library for Mixture-of-Experts (MoE) models, offering optimized GPU kernels for expert parallelism. It provides two modes: **high-throughput kernels** (for training/inference prefilling) leveraging NVLink/RDMA forwarding, and **low-latency kernels** (for inference decoding) using pure RDMA to minimize delays. The library supports FP8/BF16 precision and introduces a hook-based method for communication-computation overlap without GPU SM resource consumption. Tested on H800 GPUs, it achieves up to 158 GB/s intranode bandwidth and sub-200μs latency for small batches. DeepEP requires Hopper GPUs, CUDA 12.3+, and RDMA networks, with MIT licensing (excluding NVSHMEM components).

### 5. “The closer to the train station, the worse the kebab” – a “study”

 Score: 371 Comments: 265 [Link](https://www.jmspae.se/write-ups/kebabs-train-stations/)

 > A humorous "study" investigated the hypothesis that kebab quality decreases near Paris train stations, using GIS tools and Google Places data to analyze 400 restaurants' ratings against walking distances to stations. Results showed a weak positive correlation (0.091–0.098), suggesting slightly lower ratings closer to stations, but the link was statistically insignificant. Criticisms included subjective Google reviews, potential tourist bias, and data limitations. The author acknowledged flaws but found the exploration entertaining, hinting at a follow-up. Overall, the hypothesis remains unproven, highlighting the challenges of quantifying culinary quality through geospatial analysis.

### 6. Freelancing: How I found clients, part 1

 Score: 94 Comments: 27 [Link](https://crocspace.substack.com/p/freelancing-how-i-got-clients-part)

 > The article titled "Freelancing: How I Got Clients (Part...)" from Crocspace Substack is inaccessible due to a 403 Forbidden error, indicating restricted access. The content appears to be missing or improperly loaded, with only an error message and an image placeholder visible.

### 7. History of CAD – David Weisberg

 Score: 49 Comments: 9 [Link](https://www.shapr3d.com/blog/history-of-cad)

 > The article summarizes David E. Weisberg’s *The Engineering Design Revolution*, chronicling CAD's evolution from its 1950s origins at MIT through key milestones like AutoCAD’s rise. It highlights pivotal companies (e.g., IBM, Autodesk) and innovators, detailing how CAD transformed engineering design over 80+ years. Originally a 650-page book, it’s now digitized into blog chapters by Shapr3D, preserving insights from early pioneers. The work emphasizes interviews with industry founders, offering a comprehensive history up to the 2000s. Shapr3D hosts the content with approval from Weisberg’s family, providing free access to this technical legacy.

### 8. Clean Code vs. A Philosophy Of Software Design

 Score: 214 Comments: 137 [Link](https://github.com/johnousterhout/aposd-vs-clean-code/blob/main/README.md)

 > John Ousterhout and Robert Martin (Uncle Bob) debate key software design principles: **method length**, **comments**, and **TDD**. Ousterhout criticizes *Clean Code*'s extreme method decomposition, arguing it creates entanglement and shallow interfaces, while Martin defends small methods but acknowledges over-decomposition risks. On comments, Ousterhout emphasizes their necessity for abstraction and reducing cognitive load, whereas Martin views them as a "necessary evil," favoring self-documenting code. They clash on TDD—Ousterhout warns its tactical focus undermines design, while Martin tests its benefits for test coverage and refactoring. Their discussion highlights divergent priorities: Ousterhout prioritizes upfront design and clarity, while Martin values incremental refinement and code readability.

### 9. It's still worth blogging in the age of AI

 Score: 207 Comments: 128 [Link](https://www.gilesthomas.com/2025/02/blogging-in-the-age-of-ai)

 > The article argues that blogging remains valuable in the AI era because it aids personal learning, documents expertise for career opportunities, and occasionally connects with readers, even if AI tools repurpose content. While AI may reduce direct engagement, the intrinsic benefits of clarifying knowledge, building a portfolio, and rare validation outweigh concerns about diminished visibility.

### 10. Show HN: While the world builds AI Agents, I'm just building calculators

 Score: 81 Comments: 44 [Link](https://www.calcverse.live)

 > CalcVerse is a comprehensive platform offering fast, accurate calculators and unit converters for diverse needs, including financial planning (loans, investments, compound interest), health metrics (body fat), and scientific calculations. It also provides tools for converting units like length, temperature, volume, and area, emphasizing ease of use and precision.

### 11. What would happen if we didn't use TCP or UDP?

 Score: 42 Comments: 20 [Link](https://github.com/Hawzen/hdp)

 > The article details an experiment creating a custom transport protocol (HDP) using unused IP protocol numbers, bypassing TCP/UDP. Testing locally, the OS (macOS/Linux) allowed most protocols but blocked some (e.g., TCP/ICMP-related), revealing OS-specific filtering. Over the internet, routers/firewalls often dropped HDP packets, except within controlled environments like AWS VPCs. Results showed no latency benefits over UDP/TCP, with reliability issues due to NAT/firewalls. The author concludes that while possible, custom protocols face OS/infrastructure hurdles, making TCP/UDP more practical for real-world use.

### 12. Launch HN: SubImage (YC W25) – See your infra from an attacker's perspective

 Score: 114 Comments: 28 [Link](item?id=43161332)

 > The article describes a 422 AssertionFailureError when attempting to access the URL "http://item/?id=43161332," caused by a client-side blockage (net::ERR_BLOCKED_BY_CLIENT), likely due to browser settings, extensions, or security policies blocking the request.

### 13. Introduction to Stochastic Calculus

 Score: 379 Comments: 67 [Link](https://jiha-kim.github.io/posts/introduction-to-stochastic-calculus/)

 > The article introduces stochastic calculus by transitioning from discrete binomial models to continuous Brownian motion, which is non-differentiable and modeled via Itô calculus. Itô's lemma is highlighted for incorporating Brownian motion's variance into differentials, enabling solutions to stochastic differential equations (SDEs) like geometric Brownian motion in finance. Stratonovich calculus is contrasted as an alternative preserving classical chain rules via midpoint evaluation. Applications span physics, finance, and generative AI, with code examples provided for simulations. The approach emphasizes intuition over formalism, linking mathematical concepts to real-world phenomena.

### 14. Favicon Hasher – An Osint Tool

 Score: 4 Comments: 1 comment [Link](https://kriztalz.sh/favicon-hash/)

 > This free browser-based tool generates multiple favicon hashes (MMH3, MD5, SHA256) from website URLs, enabling OSINT researchers to identify related sites, subdomains, or hidden assets via security platforms like Shodan, VirusTotal, and Censys. It offers instant hash generation, visual previews, and direct search links for streamlined investigations.

### 15. Show HN: I made a site to tell the time in corporate

 Score: 277 Comments: 122 [Link](https://corporate.watch)

 > The article notes it's week 7 of Q1 2025 (13-week quarter ending March 31), with 34 days (38.2%) remaining, and promotes [objectivetrackr.com](https://objectivetrackr.com) as a tool to automate such progress tracking.

### 16. How to change your settings to make yourself less valuable to Meta

 Score: 166 Comments: 56 [Link](https://johnoliverwantsyourraterotica.com/)

 > This article provides step-by-step instructions to limit Meta’s data collection and ad targeting across Facebook and Instagram, including disabling ad personalization, unlinking off-platform activity, and using privacy tools like Firefox or Privacy Badger. It also advises disabling phone advertising IDs and credits the Electronic Frontier Foundation for guidance.

### 17. Breaking into apartment buildings in five minutes on my phone

 Score: 384 Comments: 213 [Link](https://www.ericdaigle.ca/posts/breaking-into-dozens-of-apartments-in-five-minutes/)

 > The article details how a security researcher discovered that numerous apartment buildings using the MESH by Viscount access control system were vulnerable due to unchanged default credentials (`freedom:viscount`), exposing personal data (names, unit numbers, access logs) and allowing remote unlocking of entrances. By scanning with tools like ZoomEye and Nuclei, the researcher found 89 vulnerable systems (14% of exposed instances), many in Canada, enabling unauthorized access and privacy breaches. Despite contacting vendors, the response emphasized user negligence rather than systemic fixes, highlighting critical IoT security flaws. A CVE (CVE-2025-26793) was assigned, but many systems remain at risk. The article underscores the dangers of poor IoT security practices.

### 18. Everyone at NSF overseeing the Platforms for Wireless Experimentation is gone

 Score: 338 Comments: 355 [Link](https://discuss.systems/@ricci/114059690609284323)

 > The article is a Mastodon discussion thread initiated by Rob Ricci on U.S. political debates around science funding, with contributions from John Regehr and Saagar Jha. The thread shows engagement via boosts and favorites but lacks visible detailed content beyond repeated mentions of "uspol science funding" and truncated "Show more" links. The discussion highlights community interest in the topic but offers limited substantive exchange due to platform formatting.

### 19. The HP-35: Consumer Electronics, an Origin Story

 Score: 37 Comments: 17 [Link](http://codex99.com/design/the-hp35.html)

 > The HP-35, launched in 1972, was the first handheld scientific calculator, born from Bill Hewlett's challenge to shrink HP's desktop model into a shirt-pocket device. Overcoming technical hurdles with custom chips and innovative design, HP marketed it directly to consumers via magazines and retail, defying skepticism. Priced at $395, it sold over 100,000 units in its first year, revolutionizing engineering by rendering slide rules obsolete and setting a blueprint for future consumer electronics. Its blend of advanced integrated circuits, user-centric design, and portability influenced devices from early handheld games to smartphones. The HP-35's success cemented HP's legacy in tech innovation and reshaped personal computing.

### 20. AI cracks superbug problem in two days that took scientists years

 Score: 226 Comments: 98 [Link](https://www.bbc.co.uk/news/articles/clyz6e9edy3o)

 > An AI tool developed by Google solved a decade-long superbug resistance mystery in two days, matching a hypothesis by Imperial College London researchers that antibiotic-resistant bacteria form viral "tails" to spread. The AI, not trained on the unpublished research, generated the same conclusion and additional viable hypotheses, shocking scientists. This breakthrough highlights AI's potential to accelerate scientific discovery.

### 21. Tuta Launches Post Quantum Cryptography for Email (2024)

 Score: 19 Comments: 2 [Link](https://tuta.com/blog/post-quantum-cryptography)

 > Tuta has launched TutaCrypt, a post-quantum encryption protocol combining CRYSTALS-Kyber (quantum-safe) with AES/ECC (traditional) algorithms, making it the first email provider to defend against quantum computer attacks. The hybrid protocol is enabled by default for new users, with gradual rollout to existing accounts. This upgrade addresses the "harvest now, decrypt later" threat, ensuring emails, calendars, and contacts remain secure. Tuta collaborates with academic partners for ongoing improvements and formal verification. The move aligns with global efforts to transition to quantum-resistant cryptography preemptively.

### 22. Xcode Constantly Phones Home

 Score: 86 Comments: 24 [Link](https://lapcatsoftware.com/articles/2025/2/5.html)

 > The article details how Xcode's frequent connections to Apple servers (e.g., `developerservices2.apple.com`) during builds slow development, particularly the "Gathering provisioning inputs" phase, and raise privacy concerns. By blocking these connections via Little Snitch, the author achieved faster builds without issues, criticizing Apple for unnecessary data collection despite privacy claims.

### 23. I ate and reviewed every snack in our office kitchen

 Score: 130 Comments: 91 [Link](https://www.getlago.com/blog/office-snacks)

 > The article humorously reviews office snacks using a rubric of taste, productivity, logistics, and social impact, with standout snacks like grapes (perfect scores) and bananas (mediocre logistics), while jokingly urging readers to support the billing software company by booking a demo. It balances absurdity (rating lemons, stealing lunches) with subtle product promotion.

### 24. Closing the "green gap": energy savings from the math of the landscape function

 Score: 86 Comments: 35 [Link](https://terrytao.wordpress.com/2025/02/23/closing-the-green-gap-from-the-mathematics-of-the-landscape-function-to-lower-electricity-costs-for-households/)

 > The article explains how advancements in mathematics, particularly the "landscape function," enabled more efficient LED designs by improving simulations of electron behavior in disordered semiconductors. This innovation helped close the "green gap," a challenge in producing efficient green LEDs, by optimizing quantum well structures through computational models. These improvements accelerated LED development, leading to significant energy savings and reduced household electricity costs, demonstrating the critical role of interdisciplinary research in practical technological advancements.

### 25. The best way to use text embeddings portably is with Parquet and Polars

 Score: 182 Comments: 49 [Link](https://minimaxir.com/2025/02/embeddings-parquet/)

 > The article advocates using Parquet files and the Polars library for efficiently storing and querying text embeddings, avoiding complex vector databases for small-to-medium projects. By embedding metadata alongside vectors in Parquet, users enable portable, fast similarity searches via numpy operations while maintaining compatibility across systems. The approach is demonstrated using Magic: The Gathering card embeddings, achieving quick results with filtering and numpy-based cosine similarity. Parquet’s columnar storage and Polars’ zero-copy numpy integration simplify workflows without proprietary tools. This method balances performance, portability, and ease of use for hobbyists or prototyping.

### 26. Larry Ellison's half-billion-dollar quest to change farming

 Score: 130 Comments: 242 [Link](https://www.wsj.com/tech/larry-ellison-hawaii-greenhouse-farm-food-2d260e1f)

 > Larry Ellison, Oracle co-founder, is developing a large greenhouse farm in Hawaii to address food sustainability and security. The project aims to utilize advanced agricultural technology to grow crops locally, reducing reliance on imports. It reflects Ellison's broader interest in innovative solutions for environmental and food challenges.

### 27. US Space Force reveals first look at secretive X-37B space plane in orbit

 Score: 87 Comments: 60 [Link](https://www.space.com/space-force-x-37b-1st-photo-from-orbit-earth)

 > The US Space Force released the first on-orbit photo of its secretive X-37B space plane, showcasing Earth in the background and parts of its structure during its seventh mission, which launched on a SpaceX Falcon Heavy rocket in December 2023. The mission tests new technologies, including aerobraking maneuvers and NASA radiation experiments, operating in higher orbits than previous flights. The X-37B, a reusable spacecraft for advancing space capabilities, follows China's similar reusable space plane, which launched its third mission shortly before this flight.

### 28. Writing a DSL in Lua (2015)

 Score: 77 Comments: 18 [Link](https://leafo.net/guides/dsl-in-lua.html)

 > The provided content appears to be a placeholder or loading message ("Please wait while your request is being verified...") rather than the actual article. Since the intended content about creating **Domain-Specific Languages (DSLs) in Lua** is unavailable here, a summary cannot be generated. Let me know if you can share the article text directly!

### 29. Show HN: I built an app to stop me doomscrolling by touching grass

 Score: 1079 Comments: 253 [Link](https://touchgrass.now/)

 > The article promotes reducing screen time through the app *Touch Grass*, which encourages users to disconnect from screens, "touch grass" (engage with the real world), and combat digital overuse. It directs readers to download the iOS app via the provided App Store link.

### 30. Student refines 100-year-old math problem, expanding wind energy possibilities

 Score: 126 Comments: 16 [Link](https://www.psu.edu/news/engineering/story/student-refines-100-year-old-math-problem-expanding-wind-energy-possibilities)

 > Divya Tyagi, a Penn State aerospace engineering student, simplified a 100-year-old mathematical problem by Hermann Glauert, enhancing its application to optimize wind turbine efficiency by accounting for forces and blade bending not originally considered. Her solution, published in *Wind Energy Science*, uses calculus of variations to maximize power output, potentially boosting energy production significantly with even minor efficiency gains. Recognized with the Anthony E. Wolk Award, her work could influence future turbine designs and educational curricula globally. Now pursuing a master’s, Tyagi researches helicopter rotor airflow dynamics for the U.S. Navy to improve pilot safety. Her adviser praised her persistence in refining a complex problem others had struggled with.

