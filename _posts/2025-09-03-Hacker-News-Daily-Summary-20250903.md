Updated at 2025-09-03 17:10:56 (UTC+8)

### 1. Kernel-hack-drill and exploiting CVE-2024-50264 in the Linux kernel

 Score: 67 Comments: 1 comment [Link](https://a13xp0p0v.github.io/2025/09/02/kernel-hack-drill-and-CVE-2024-50264.html)

 > This article details the exploitation of CVE-2024-50264, a challenging race condition and use-after-free vulnerability in the Linux kernel's AF_VSOCK subsystem. The author introduces their personal project, kernel-hack-drill, as a testing environment to develop exploit primitives. They describe a novel cross-cache attack and a technique involving a controlled UAF write to corrupt a pipe_buffer, ultimately achieving arbitrary read/write and privilege escalation. The exploit overcomes numerous limitations, including the bug's instability and the need to bypass kernel hardening features like CONFIG_RANDOM_KMALLOC_CACHES.

### 2. Google can keep its Chrome browser but will be barred from exclusive contracts

 Score: 731 Comments: 473 [Link](https://www.cnbc.com/2025/09/02/google-antitrust-search-ruling.html)

 > Access to the CNBC website has been blocked for anonymous users until September 3, 2025. This security measure was taken because the system detected a suspected DDoS attack originating from too many requests to a specific page. The block is a response to previous abuse on the domain.

### 3. Lit: a library for building fast, lightweight web components

 Score: 66 Comments: 26 [Link](https://lit.dev)

 > Lit is a simple and fast library for building web components. It adds reactivity and declarative templates to the standard Web Components model, reducing boilerplate. Lit components are lightweight, interoperable with any framework, and natively supported by browsers. This makes them ideal for shareable components, design systems, and maintainable web apps.

### 4. Magic Lantern Is Back

 Score: 155 Comments: 27 [Link](https://www.magiclantern.fm/forum/index.php?topic=27315.0)

 > Magic Lantern has released its 2025 Midsummer Edition, marking the official return of the firmware project. This release introduces support for four new Canon cameras: the 200D (SL2), 6D Mark II, 750D (T6i), and 7D Mark II. The project has been modernized with a new build system, a Git repository, and a refreshed website. A new core development team is leading the effort, promising regular, tested releases and future expansion to more camera models.

### 5. Amazonq.nvim: Official AWS AI Assistant Plugin for Neovim

 Score: 12 Comments: 3 [Link](https://github.com/awslabs/amazonq.nvim)

 > This is a Neovim plugin that integrates Amazon Q Developer, an AI coding assistant, into the text editor. It provides chat functionality, inline code suggestions, and code refactoring/explanation commands. Users can authenticate for free using an AWS Builder ID or through their organization's SSO. The plugin requires NodeJS and a recent version of Neovim to function.

### 6. %CPU utilization is a lie

 Score: 269 Comments: 89 [Link](https://www.brendanlong.com/cpu-utilization-is-a-lie.html)

 > Reported CPU utilization is a misleading metric for actual performance capacity. Due to hyperthreading and turbo boosting, a system reporting 50% utilization may actually be performing 60-100% of its maximum possible work. This means you cannot linearly scale workload predictions based on the utilization percentage.

### 7. 10-20x Faster LLVM -O0 Back-End – Code Generation

 Score: 108 Comments: 8 [Link](https://discourse.llvm.org/t/tpde-llvm-10-20x-faster-llvm-o0-back-end/86664)

 > TPDE-LLVM is a new open-source back-end for LLVM that is 10-20x faster at code generation than the standard LLVM -O0 back-end. It achieves this significant speedup with similar runtime performance, though it produces code that is 10-30% larger. The project supports a subset of LLVM-IR and currently targets x86-64 and AArch64.

### 8. Comic Sans typeball designed to work with the IBM Selectric typewriters

 Score: 68 Comments: 8 [Link](https://www.printables.com/model/441233-comic-sans-typeball-for-the-ibm-selectric-typewrit)

 > This is a free, downloadable 3D model for a Comic Sans typeball designed for IBM Selectric typewriters that use 88-character elements. The creator, settinger, notes that the model is untested and advises users they "probably shouldn't print this." It is an original creation shared under a BSD license, allowing for remixing and commercial use.

### 9. This blog is running on a recycled Google Pixel 5 (2024)

 Score: 217 Comments: 97 [Link](https://blog.ctms.me/posts/2024-08-29-running-this-blog-on-a-pixel-5/)

 > The author successfully runs this blog on a recycled Google Pixel 5 using the Termux app to host a Hugo site. The phone is powered by a solar panel setup, aligning with the author's interest in permacomputing and reducing power consumption. The entire server setup is done on the Android device without needing a custom ROM.

### 10. Finnish City Inaugurates 1 MW/100 MWh Sand Battery

 Score: 108 Comments: 46 [Link](https://cleantechnica.com/2025/08/30/finnish-city-inaugurates-1-mw-100-mwh-sand-battery/)

 > Access to the website cleantechnica.com has been blocked for anonymous users until September 2025. This security measure was taken because the site was the target of a suspected DDoS attack originating from a specific article URL.

### 11. Lisp interpreter with GC in <750 lines of Odin (and <500 lines of C)

 Score: 52 Comments: 12 [Link](https://github.com/krig/LISP)

 > This repository contains two small LISP interpreters: `komplott` (written in C) and `komplodin` (a newer translation to Odin). They are minimal implementations inspired by the original LISP 1.5, featuring a semi-space garbage collector. The project includes build instructions and test cases.

### 12. The Middle Earth

 Score: 12 Comments: discuss [Link](https://www.historytoday.com/archive/out-margins/real-middle-earth)

 > The article explores the historical origins of the term "Middle Earth," tracing it back to its Anglo-Saxon roots. It argues that the concept, popularized by J.R.R. Tolkien's fantasy, is far from fictional and has a real history. The term's meaning has shifted over the centuries since its inception.

### 13. Making a Linux home server sleep on idle and wake on demand (2023)

 Score: 233 Comments: 84 [Link](https://dgross.ca/blog/linux-home-server-auto-sleep)

 > This article explains how to configure a Linux home server to automatically sleep when idle and wake up on demand. The solution requires an always-on device on the network, like a Raspberry Pi, to run a custom script (ARP Stand-in) that responds to ARP requests on behalf of the sleeping server. Key steps include enabling specific wake-on-LAN settings on the server, setting up a cron job to check for idle state, and disabling IPv6. The goal is to save energy while maintaining seamless access for services like SSH and Time Machine backups.

### 14. The staff ate it later

 Score: 304 Comments: 167 [Link](https://en.wikipedia.org/wiki/The_staff_ate_it_later)

 > "The staff ate it later" is a Japanese TV caption indicating that food used in a program was not wasted. It was introduced to preempt viewer complaints about food waste, as discarding food is socially unacceptable in Japan. There is debate over whether the staff actually eats the food, with some insiders confirming it and others calling it a lie. The practice is also criticized as an empty concession that lowers program quality.

### 15. A staff engineer's journey with Claude Code

 Score: 367 Comments: 247 [Link](https://www.sanity.io/blog/first-attempt-will-be-95-garbage)

 > A staff engineer describes his transition to using Claude Code for 80% of his initial code implementation. He details a workflow where the first AI-generated attempt is usually 95% garbage, requiring multiple iterations and reviews to refine. Key strategies include providing extensive context and managing AI like a team of junior developers. The result is a 2-3x increase in shipping speed, despite the significant cost of the AI tools.

### 16. The Little Book of Linear Algebra

 Score: 378 Comments: 98 [Link](https://github.com/the-litte-book-of/linear-algebra)

 > This GitHub repository hosts "The Little Book of Linear Algebra," a concise and beginner-friendly introduction to linear algebra. It covers core topics like vectors, matrices, systems of equations, vector spaces, and eigenvalues. The book is available in PDF, EPUB, and LaTeX formats, emphasizing clarity and simplicity over complex calculations.

### 17. Physically based rendering from first principles

 Score: 213 Comments: 49 [Link](https://imadr.me/pbr/)

 > This article explores the physics of light and its interaction with matter to create physically based rendering (PBR). It covers the nature of light, its generation, and how it interacts with surfaces. The core of PBR is explained through the rendering equation and the Bidirectional Reflectance Distribution Function (BRDF). The article uses interactive demos to illustrate concepts like reflection, refraction, and material properties.

### 18. Introduction to Ada: a project-based exploration with rosettas

 Score: 173 Comments: 42 [Link](https://blog.adacore.com/introduction-to-ada-a-project-based-exploration-with-rosettas)

 > This article introduces Ada through a project-based tutorial that generates animated rosetta patterns (hypotrochoid curves) as SVG files. It highlights Ada's readability, strong typing, and explicit design philosophy while demonstrating modern tooling like the Alire package manager. The tutorial walks through key code examples to show how Ada ensures safety and maintainability, making it suitable for both critical systems and general-purpose programming.

### 19. <template>: The Content Template element

 Score: 190 Comments: 64 [Link](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/template)

 > The `<template>` HTML element is a mechanism for holding HTML fragments that are not rendered immediately. Its content is stored as a DocumentFragment that can be accessed via JavaScript and cloned for later use. It also supports declarative shadow DOM when using the `shadowrootmode` attribute. This element allows for reusable client-side templates.

### 20. Static sites enable a good time travel experience

 Score: 169 Comments: 40 [Link](https://hamatti.org/posts/static-sites-enable-a-good-time-travel-experience/)

 > Static sites built with generators like Eleventy and stored in git enable easy "time travel" to view past versions. By checking out old commits, the author can rebuild their site exactly as it appeared at any point in history. This is a major advantage over database-driven sites where content isn't version-controlled.

### 21. AI is going great for the blind

 Score: 4 Comments: discuss [Link](https://robertkingett.com/posts/6230/)

 > Blind author Robert Kingett expresses skepticism about the AI hype within the blind community. While acknowledging that AI tools provide information sighted people often refuse to give, he is concerned about inaccuracies and the community's growing dependence on flawed technology. He predicts this will lead to new accessibility challenges and a decline in web accessibility as AI-generated code goes unchecked. Ultimately, he believes the community is embracing AI because humans have continuously failed to provide basic accessibility.

### 22. Acorn and the future of (AI?) theorem proving

 Score: 3 Comments: discuss [Link](https://lmao.bearblog.dev/acorn-ai-proving/)

 > The article contrasts Lean, a traditional interactive theorem prover that requires users to manually apply named theorems in a programming-like environment, with Acorn, a new AI-powered prover. Acorn allows users to write proofs in a more natural, declarative style, similar to human mathematical reasoning. It uses an underlying AI model to automatically find proofs for each step, engaging in a dialogue with the user only when it needs help. This approach makes theorem proving more accessible and intuitive.

### 23. 'World Models,' an old idea in AI, mount a comeback

 Score: 177 Comments: 64 [Link](https://www.quantamagazine.org/world-models-an-old-idea-in-ai-mount-a-comeback-20250902/)

 > AI researchers are reviving the concept of "world models"—internal representations of the environment that allow AI systems to simulate and evaluate decisions. While this idea is decades old, today's large language models appear to learn disconnected heuristics rather than a coherent world model. A robust world model would make AI systems more reliable, safe, and capable of reasoning. Major AI labs are now pursuing different strategies to build these models, though the best approach remains unknown.

### 24. Zig Software Foundation 2025 Financial Report and Fundraiser

 Score: 107 Comments: 31 [Link](https://ziglang.org/news/2025-financials/)

 > The Zig Software Foundation's 2024 financial report shows that 92% of its $520,748.91 in expenses went directly to compensating contributors. Despite a total income of $670,672.59, the report notes a concerning decline in recurring donations. The foundation is launching a 2025 fundraiser to secure more stable, recurring funding to maintain its current team and continue development.

### 25. Take something you don’t like and try to like it

 Score: 216 Comments: 164 [Link](https://dynomight.net/liking/)

 > The article explores the idea of trying to like things you currently dislike as a hobby and a tool for self-discovery. It uses personal anecdotes to show that our dislikes are often tied to our self-concept and past experiences, not the thing itself. While you can sometimes change your mind by reframing your perspective, the author also finds that some dislikes are too deeply ingrained to overcome. Ultimately, you have more power over your experience of a situation than you might think.

### 26. Launch HN: Datafruit (YC S25) – AI for DevOps

 Score: 58 Comments: 39 [Link](item?id=45104974)

 > The provided input is an error response, not an article. The error states that a domain named 'item' could not be resolved, resulting in a parameter validation failure.

### 27. Untangling the myths and mysteries of Dvorak and QWERTY (2023)

 Score: 62 Comments: 84 [Link](https://aresluna.org/the-primitive-tortureboard/)

 > This article explores the history and myths surrounding the QWERTY and Dvorak keyboard layouts. It debunks the common narrative that QWERTY was designed randomly or to slow typists down, revealing it was a deliberate solution to prevent typebar clashes on early typewriters. The piece also examines the development of August Dvorak's "Simplified Keyboard," its claimed ergonomic benefits, and the contentious studies that ultimately prevented its widespread adoption. The conclusion is that while Dvorak may offer some advantages, QWERTY's entrenched position and "good enough" performance have made it the enduring standard.

### 28. Triangle Grids (2022)

 Score: 64 Comments: 12 [Link](https://kvachev.com/blog/posts/triangular-grid/)

 > This article explores the use of triangular grids in turn-based games, comparing them to the more common square and hex grids. It highlights the visual and tactical advantages of triangle grids, such as their ability to represent both straight lines and curves, and their high number of adjacent tiles (12 with diagonals). The author also provides technical details on coordinate representation and distance calculations, concluding that triangular grids are a fantastic but underutilized option for game design.

### 29. Show HN: LightCycle, a FOSS game in Rust based on Tron

 Score: 33 Comments: 10 [Link](https://github.com/Tortured-Metaphor/LightCycle)

 > This is a classic TRON-inspired light cycle game built with Rust using the ggez framework. It features single-player and two-player modes, adjustable AI difficulty, and a strategic boost mechanic. The game includes visual effects like particle trails and has a retro, neon aesthetic. It is open source and available under the MIT license.

### 30. Still Asking: How Good Are Query Optimizers, Really? [pdf]

 Score: 44 Comments: 12 [Link](https://www.vldb.org/pvldb/vol18/p5531-viktor.pdf)

 > This retrospective revisits the influential 2015 paper "How Good Are Query Optimizers, Really?" and its Join Order Benchmark (JOB). The original work demonstrated that cardinality estimation errors are the dominant cause of poor query plans, not cost models or enumeration strategies. It spurred a decade of renewed research in query optimization, particularly in learned and AI-based approaches. The authors reflect on JOB's impact, survey key developments, and discuss future challenges around robustness and adaptive execution.

