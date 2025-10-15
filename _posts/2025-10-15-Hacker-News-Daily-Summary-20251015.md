Updated at 2025-10-15 17:09:04 (UTC+8)

### 1. FSF announces Librephone project

 Score: 854 Comments: 329 [Link](https://www.fsf.org/news/librephone-project)

 > The Free Software Foundation has launched the Librephone project to create a fully free mobile phone operating system. This initiative aims to reverse-engineer and replace proprietary components in existing Android-based systems. The project will build upon previous work by projects like LineageOS while eliminating remaining nonfree software. Developer Rob Savoye has been hired to lead the technical efforts, starting with identifying phones with the fewest freedom obstacles. The ultimate goal is to provide users with complete software freedom on their mobile devices.

### 2. Pixnapping Attack

 Score: 93 Comments: 9 [Link](https://www.pixnapping.com/)

 > Pixnapping is a new Android attack that allows malicious apps to stealthily steal information displayed by other apps or websites. It exploits Android APIs and a hardware side channel to recover sensitive data like 2FA codes from apps including Google Authenticator and Signal. The attack works without requiring any permissions and affects most modern Android devices. It is tracked under CVE-2025-48561, and Google plans to issue patches.

### 3. Show HN: Firm, a text-based work management system

 Score: 20 Comments: 12 [Link](https://github.com/42futures/firm)

 > Firm is a text-based work management system that lets technologists define business relationships in plain text files. It uses a custom DSL to model organizations, projects, and tasks as code, stored locally and version-controlled. The system builds a queryable graph of these entities, enabling powerful searches and relationship exploration. It includes a CLI for interaction and Rust libraries for programmatic use, promoting data ownership and AI integration.

### 4. Beliefs that are true for regular software but false when applied to AI

 Score: 381 Comments: 285 [Link](https://boydkane.com/essays/boss)

 > People mistakenly apply their understanding of regular software bugs to AI systems, assuming they can be similarly fixed. However, AI errors stem from massive training datasets that no human can fully comprehend or debug. Unlike traditional software where bugs can be pinpointed and permanently resolved, AI behaviors are unpredictable and can resurface unexpectedly. This fundamental difference means AI systems cannot be reliably patched or guaranteed safe through conventional software engineering approaches.

### 5. Nvidia DGX Spark: great hardware, early days for the ecosystem

 Score: 113 Comments: 47 [Link](https://simonwillison.net/2025/Oct/14/nvidia-dgx-spark/)

 > The NVIDIA DGX Spark is a compact $4,000 desktop "AI supercomputer" with impressive hardware, including an ARM64 CPU, 128GB of unified memory, and a powerful Blackwell GPU. However, the author found the software ecosystem challenging due to limited support for CUDA on ARM64 architecture. Recent improvements, including official NVIDIA guides and support from projects like Ollama and llama.cpp, are making the device more accessible. The reviewer concludes it's still early to give a confident recommendation, but the rapidly improving ecosystem is promising.

### 6. DOJ seizes $15B in Bitcoin from 'pig butchering' scam based in Cambodia

 Score: 134 Comments: 116 [Link](https://www.cnbc.com/2025/10/14/bitcoin-doj-chen-zhi-pig-butchering-scam.html)

 > The U.S. Department of Justice has seized $15 billion in bitcoin from a massive "pig butchering" scam based in Cambodia. This is the largest forfeiture in DOJ history. The alleged mastermind, Chen Zhi, remains at large and has been indicted for wire fraud and money laundering. The criminal operation used forced labor to run cryptocurrency investment scams that defrauded victims worldwide.

### 7. A modern approach to preventing CSRF in Go

 Score: 75 Comments: 20 [Link](https://www.alexedwards.net/blog/preventing-csrf-in-go)

 > Go 1.25 introduces a new `http.CrossOriginProtection` middleware that can prevent CSRF attacks without traditional token-based checks. This works by validating request headers to block cross-origin requests, but requires modern browser support. For comprehensive protection, the article recommends combining this middleware with HTTPS, TLS 1.3 enforcement, and SameSite cookies. This approach may eliminate the need for third-party CSRF packages under specific security conditions.

### 8. Interviewing Intel's Chief Architect of x86 Cores

 Score: 86 Comments: 9 [Link](https://chipsandcheese.com/p/interviewing-intels-chief-architect)

 > At Intel Tech Tour 2025, Stephen Robinson, Intel's Lead Architect for x86 Cores, discussed upcoming Panther Lake and Clearwater Forest CPUs. He detailed architectural improvements in the E-core Skymont, such as increased out-of-order depth and wider front-end design. The interview also covered memory disambiguation enhancements in the Darkmont and Cougar Cove cores and explained the rationale for removing SMT in client CPUs.

### 9. How bad can a $2.97 ADC be?

 Score: 229 Comments: 125 [Link](https://excamera.substack.com/p/how-bad-can-a-297-adc-be)

 > The author tested a $2.97 ADS1115 ADC module and found it mostly functional but with significant flaws. One unit had a wildly incorrect sample rate, and all showed a 0.5% voltage measurement error, far exceeding the datasheet specification. However, this error was correctable with software calibration. The author suspects these cheap modules may be clones or factory rejects.

### 10. Unpacking Cloudflare Workers CPU Performance Benchmarks

 Score: 227 Comments: 36 [Link](https://blog.cloudflare.com/unpacking-cloudflare-workers-cpu-performance-benchmarks/)

 > Cloudflare responded to independent benchmarks showing Workers performed worse than Vercel in CPU-intensive tasks. They identified and fixed several issues including inefficient scheduling algorithms and suboptimal V8 garbage collector tuning. These improvements have now closed most performance gaps, with Workers performing on par with Vercel in most benchmarks. The company continues optimizing OpenNext integration and upstream improvements to benefit the broader ecosystem.

### 11. How AI hears accents: An audible visualization of accent clusters

 Score: 216 Comments: 94 [Link](https://accent-explorer.boldvoice.com/)

 > BoldVoice used AI to analyze English accents from its large dataset of non-native speakers. The model clustered accents in a 3D visualization, revealing surprising patterns based on geography and cultural exchange rather than language families. For example, Australian and Vietnamese accents appeared close together, while Mongolian and Korean accents also clustered nearby. This shows how AI can detect phonetic similarities between accents that aren't linguistically related. The findings help improve accent training tools for English learners.

### 12. Hacking the Humane AI Pin

 Score: 132 Comments: 32 [Link](https://writings.agg.im/posts/hacking_ai_pin/)

 > After Humane announced it would shut down its Ai Pin services in February 2025, the author acquired several devices that were stuck in the onboarding process. By examining leaked APKs and using a mysterious ADB private key, they gained initial access but found the device heavily locked down. The author then exploited an Android vulnerability (CVE-2024-31317) to achieve privileged system access and developed a custom init system called pinitd. This allowed them to bypass restrictions and create a functional development environment, saving the devices from becoming e-waste.

### 13. Updating Desktop Rust

 Score: 13 Comments: 3 [Link](https://tritium.legal/blog/update)

 > Tritium's desktop software requires reliable updates while prioritizing privacy and user experience. Unlike approaches using background daemons or threads, Tritium implements a "speedbump" method that checks for updates on every application launch. If an update is available, it downloads it, exits, and uses a helper process to deploy the new version before restarting. This ensures users always have the latest version while keeping the update process simple and transparent across all platforms.

### 14. A 12,000-year-old obelisk with a human face was found in Karahan Tepe

 Score: 329 Comments: 142 [Link](https://www.trthaber.com/foto-galeri/karahantepede-12-bin-yil-oncesine-ait-insan-yuzlu-dikili-tas-bulundu/73912.html)

 > Archaeologists have discovered a 12,000-year-old human-faced standing stone at the Karahantepe site in Turkey. This T-shaped pillar is the first of its kind found with a carved human face, featuring sharp lines, deep eye sockets, and a blunt nose. The discovery marks a turning point in Neolithic research, providing direct evidence of human representation. It offers new insights into the symbolic thinking and artistic expression of early settled human societies.

### 15. How to turn liquid glass into a solid interface

 Score: 156 Comments: 101 [Link](https://tidbits.com/2025/10/09/how-to-turn-liquid-glass-into-a-solid-interface/)

 > Apple's new Liquid Glass interface design adds transparency and blur effects across its operating systems, which some users find distracting. The article explains how to reduce these effects using accessibility settings like "Reduce Transparency" and "Increase Contrast" on macOS, iOS, watchOS, and tvOS. It also mentions a hidden Terminal command to disable Liquid Glass entirely on macOS but advises against it due to interface issues. The author recommends using "Reduce Transparency" on macOS and iOS for better readability while keeping most settings default on watchOS and tvOS.

### 16. Can we know whether a profiler is accurate?

 Score: 37 Comments: 9 [Link](https://stefan-marr.de/2025/10/can-we-know-whether-a-profiler-is-accurate/)

 > This article proposes a novel method to evaluate the accuracy of Java profilers by accurately slowing down programs at the machine-code level. Since obtaining a true ground truth for profiling data is impractical, this slowdown technique approximates one by preserving execution behavior. The approach tests whether profilers correctly attribute time increases to the slowed-down methods, revealing significant accuracy differences among popular tools like async-profiler, JFR, JProfiler, and YourKit. This provides the first practical methodology to assess profiler accuracy for JIT-compiled systems.

### 17. Astronomers 'image' a mysterious dark object in the distant Universe

 Score: 222 Comments: 123 [Link](https://www.mpg.de/25518363/1007-asph-astronomers-image-a-mysterious-dark-object-in-the-distant-universe-155031-x)

 > Astronomers have discovered a mysterious dark object in the distant universe using gravitational lensing effects. The object has about one million solar masses and is located approximately 10 billion light-years away. It was detected through distortions in light from a background galaxy using a global network of radio telescopes. This represents the lowest mass dark object ever measured with this technique, potentially supporting cold dark matter theories.

### 18. SmolBSD – build your own minimal BSD system

 Score: 196 Comments: 18 [Link](https://smolbsd.org)

 > smolBSD is a minimal BSD system built on NetBSD that lets users create custom UNIX environments. It uses the netbsd-MICROVM kernel to build bootable images containing only selected services like sshd or bozohttpd. The system is composable, reproducible, and boots instantly in milliseconds. Users can quickly build their own minimal BSD systems using simple bmake commands.

### 19. Intel Announces Inference-Optimized Xe3P Graphics Card with 160GB VRAM

 Score: 100 Comments: 72 [Link](https://www.phoronix.com/review/intel-crescent-island)

 > Intel has announced its "Crescent Island" enterprise GPU, which is optimized for AI inference. The card features 160GB of LPDDR5x memory and is built on the Xe3P Celestial architecture. It is designed for power efficiency and cost-effectiveness, targeting large language models. Customer sampling is expected to begin in the second half of 2026.

### 20. Python's splitlines does more than just newlines

 Score: 16 Comments: 2 [Link](https://yossarian.net/til/post/python-s-splitlines-does-a-lot-more-than-just-newlines/)

 > Python's `str.splitlines()` method splits on many more characters than just the typical newline sequences. It handles various Unicode line separators and control codes including form feeds, vertical tabs, and paragraph separators. This means it splits on characters like `\v`, `\f`, `\x1c`, `\u2028`, and others beyond just `\n`, `\r`, and `\r\n`. The behavior can be surprising if you expect it to only split on universal newlines.

### 21. CSS for Styling a Markdown Post

 Score: 42 Comments: 10 [Link](https://webdev.bryanhogan.com/miscellaneous/styling-markdown/)

 > This article explains how to style markdown content on websites using custom CSS. It covers styling various HTML elements generated from markdown, including paragraphs, headings, images, lists, quotes, tables, code blocks, and thematic breaks. The author recommends writing custom CSS to maintain design consistency with the rest of the website rather than using pre-built frameworks. The guide provides specific CSS examples for each element type and emphasizes responsive design principles.

### 22. A Early History of Algebraic Data Types

 Score: 11 Comments: 1 comment [Link](https://www.hillelwayne.com/post/algdt-history/)

 > John McCarthy first proposed the concepts of sum and product types in 1961, calling them "direct union" and "Cartesian product." These ideas were later developed independently by Tony Hoare and Rod Burstall, with Burstall's work influencing functional programming languages. Robin Milner's ML implemented these types using + and × symbols, and Luca Cardelli later added tagged unions. The term "algebraic data types" first appeared in a 1985 paper about Miranda.

### 23. You Can't Mock Reality: Testing a 3D Rendering Pipeline in Blender

 Score: 3 Comments: discuss [Link](https://medium.com/@egorich42/you-cant-mock-reality-testing-a-3d-rendering-pipeline-in-blender-9c5b93e0076e)

 > This article explains why traditional unit testing approaches fail for 3D rendering pipelines in Blender. The author argues that in the 3D world, integration tests are essential because you cannot reliably mock Blender's complex behavior. Their solution involves using a large "Golden Dataset" of hundreds of real 3D models and testing on real hardware to catch unpredictable bugs and ensure rendering accuracy. The core message is that only real-world testing provides reliable results for such systems.

### 24. Printing Petscii Faster

 Score: 25 Comments: 6 [Link](https://retrogamecoders.com/printing-petscii-faster/)

 > This article explores methods to display PETSCII art faster on the Commodore 64 using BASIC. The author found that replacing POKE loops with direct PRINT statements significantly speeds up rendering. Other optimizations included removing unnecessary checks and simplifying loops. Ultimately, entering PETSCII symbols directly from the keyboard proved to be the fastest method in BASIC.

### 25. What Americans die from vs. what the news reports on

 Score: 544 Comments: 322 [Link](https://ourworldindata.org/does-the-news-reflect-what-we-die-from)

 > Major US news outlets disproportionately cover rare causes of death like homicide and terrorism while underreporting common killers. Heart disease and cancer account for 56% of deaths but receive only 7% of media coverage. This creates a significant disconnect between actual mortality risks and public perception. The bias exists because dramatic events generate more reader engagement than chronic health issues.

### 26. Europe's Digital Sovereignty Paradox – "Chat Control" Update

 Score: 9 Comments: 2 [Link](https://www.process-one.net/blog/chat-control-update-oct-2025/)

 > A European Council vote on "Chat Control," which would mandate scanning of all private communications including encrypted messages, was unexpectedly postponed in October 2025. Germany withdrew its support, creating a blocking minority against the proposal. The author argues the policy contradicts Europe's goal of digital sovereignty by forcing companies to undermine the secure encryption protocols that protect digital infrastructure. The postponement provides a two-month opportunity for engineers and policymakers to bridge the gap between political vision and technical reality before Denmark's next push in December.

### 27. Surveillance data challenges what we thought we knew about location tracking

 Score: 390 Comments: 93 [Link](https://www.lighthousereports.com/investigation/surveillance-secrets/)

 > An undercover investigation reveals how surveillance company First Wap sold its Altamides phone-tracking software to authoritarian governments and private clients, enabling them to monitor journalists, activists, and ordinary citizens worldwide. Despite company claims that its tools are only used for lawful law enforcement, the investigation uncovered tracking of over 14,000 people across 160+ countries. First Wap executives were recorded discussing how to circumvent sanctions and sell to questionable clients. The findings dismantle the surveillance industry's narrative that misuse of their technology is rare.

### 28. Why Is SQLite Coded In C

 Score: 217 Comments: 225 [Link](https://www.sqlite.org/whyc.html)

 > SQLite is coded in C because it provides optimal performance, universal compatibility across programming languages, minimal dependencies, and long-term stability. C allows SQLite to run efficiently on diverse systems while maintaining a small footprint. The language's maturity ensures reliability for this critical database engine. While newer "safe" languages exist, they lack C's proven track record and specific capabilities needed for SQLite's requirements.

### 29. Just Talk to It – The No-Bs Way of Agentic Engineering

 Score: 3 Comments: 2 [Link](https://steipete.me/posts/just-talk-to-it)

 > Peter Steinberger advocates for a straightforward approach to agentic engineering using GPT-5-Codex, which he finds more effective than complex workflows involving subagents or specialized tools. He emphasizes direct communication with the AI, using simple prompts and screenshots to guide development, and runs multiple agents in parallel for efficiency. The author has moved away from tools like Claude Code, preferring Codex for its speed, larger context, and reliable performance. His key advice is to avoid over-engineering and instead develop an intuitive working relationship with the AI.

### 30. GrapheneOS is ready to break free from Pixels

 Score: 303 Comments: 153 [Link](https://www.androidauthority.com/graphene-os-major-android-oem-partnership-3606853/)

 > Access to Android Authority's website is blocked until October 15, 2025. This security measure was implemented due to suspected DDoS attack abuse originating from the site's fingerprint scanner article. The block prevents anonymous access to protect the service.

