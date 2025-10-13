Updated at 2025-10-13 17:08:46 (UTC+8)

### 1. Wireguard FPGA

 Score: 508 Comments: 125 [Link](https://github.com/chili-chips-ba/wireguard-fpga)

 > This is an open-source hardware implementation of WireGuard VPN on an Artix7 FPGA, designed to achieve wire-speed performance using low-cost hardware and open-source toolchains. The project implements both hardware data plane processing and software control plane management, with all code publicly available for security scrutiny. It aims to provide a fully transparent alternative to expensive proprietary VPN hardware solutions while maintaining high performance through FPGA acceleration.

### 2. Putting a Dumb Weather Station on the Internet

 Score: 26 Comments: 6 [Link](https://colincogle.name/blog/byo-weather-station/)

 > The author built a DIY internet-connected weather station using a cheap wireless thermometer from Temu. They used an RTL-SDR dongle and rtl_433 software to capture the temperature and humidity data transmitted over 433 MHz. A custom PowerShell script processes the data and uploads it to the APRS ham radio network via aprs-weather-submit. Additionally, the weather data is automatically posted to Mastodon approximately once per hour. This project demonstrates how to create an affordable, functional weather station that shares data through multiple platforms.

### 3. Tauri binding for Python through Pyo3

 Score: 91 Comments: 9 [Link](https://github.com/pytauri/pytauri)

 > PyTauri provides Python bindings for the Tauri framework using Pyo3, allowing developers to create cross-platform desktop applications with web technologies. It enables building GUI applications primarily in Python while leveraging Tauri's features, with minimal Rust coding required. The project supports integration with popular Python web frameworks and offers pre-compiled wheels to eliminate Rust compilation dependencies.

### 4. Ask HN: What are you working on? (October 2025)

 Score: 216 Comments: 580 [Link](item?id=45561428)

 > The system encountered a validation error when processing a URL parameter. The domain "item" could not be resolved, resulting in a 400 bad request error. This indicates the provided URL was invalid or inaccessible.

### 5. MicroPythonOS – An Android-like OS for microcontrollers

 Score: 90 Comments: 25 [Link](https://micropythonos.com)

 > MicroPythonOS is a lightweight operating system that runs on microcontrollers like ESP32 and desktop systems. It features an Android-like touch screen interface with an App Store and supports Over-The-Air updates. Built on MicroPython, it enables easy development for IoT devices, educational tools, and other interactive projects. The system is designed for fast performance and cross-platform compatibility.

### 6. Show HN: Baby's first international landline

 Score: 127 Comments: 28 [Link](https://wip.tf/posts/telefonefix-building-babys-first-international-landline/)

 > Téléfonefix is a kid-friendly telephone system that allows children to safely call relatives using a physical phone without screens. It uses a Raspberry Pi running Asterisk PBX software connected to a Grandstream HT801 analog telephone adapter and Twilio for international calling. The system includes parental controls like approved contact lists, timezone restrictions, and call scheduling. An open-source tool called allo-wed manages call permissions and translations between speed-dial numbers and actual phone numbers.

### 7. Emacs agent-shell (powered by ACP)

 Score: 168 Comments: 21 [Link](https://xenodium.com/introducing-agent-shell)

 > The author introduces agent-shell, a new Emacs package that provides native integration with AI agents using the Agent Client Protocol (ACP). This allows users to interact with different AI agents like Gemini and Claude Code directly within Emacs through a consistent shell interface. The package includes features like traffic inspection and fake agent replay for development. Both agent-shell and its underlying ACP library are now available on GitHub for users to try.

### 8. Three ways formally verified code can go wrong in practice

 Score: 128 Comments: 75 [Link](https://buttondown.com/hillelwayne/archive/three-ways-formally-verified-code-can-go-wrong-in/)

 > Formally verified code can still fail in practice for three main reasons: the proof itself might be invalid due to prover bugs or unchecked assumptions, the specification might be incorrect or incomplete (as with the Unicode handling in leftpad), or the underlying assumptions about the environment or dependencies may not hold. These issues highlight that "correctness" in formal verification is always relative to a specific specification and set of assumptions, not an absolute guarantee of bug-free operation.

### 9. HTTP3 Explained

 Score: 24 Comments: 5 [Link](https://http3-explained.haxx.se)

 > HTTP/3 is the next-generation HTTP protocol built on QUIC, which uses UDP instead of TCP to reduce latency and avoid head-of-line blocking. It provides reliable, multiplexed streams with built-in TLS 1.3 encryption for secure connections. This collaborative documentation project explains HTTP/3 and QUIC protocols in detail across multiple languages.

### 10. Bird photographer of the year gives a lesson in planning and patience

 Score: 127 Comments: 17 [Link](https://www.thisiscolossal.com/2025/09/2025-bird-photographer-of-the-year-contest/)

 > Canadian photographer Liron Gertsman won the 2025 Bird Photographer of the Year competition with a meticulously planned photo of a Magnificent frigatebird flying in front of a total solar eclipse. The contest received over 33,000 entries from around the world and featured various categories like Urban Birds and Best Portrait. The competition also supports conservation, donating funds to the charity Birds on the Brink.

### 11. Database Linting and Analysis for PostgreSQL

 Score: 86 Comments: 17 [Link](https://pglinter.readthedocs.io/en/latest/)

 > PGLinter is a PostgreSQL extension that analyzes databases for potential issues, performance problems, and best practice violations. It uses a rule-based approach to detect problems like missing indexes, security risks, and schema design flaws. The tool is designed for developers and CI/CD pipelines rather than traditional DBAs. It provides configurable rules and SARIF output for integration into modern development workflows.

### 12. A years-long Turkish alphabet bug in the Kotlin compiler

 Score: 109 Comments: 110 [Link](https://sam-cooper.medium.com/the-country-that-broke-kotlin-84bdd0afb237)

 > A Turkish locale bug in Kotlin's compiler caused years of issues by incorrectly converting the letter "I" to a dotless "ı" during case transformations. This led to build failures and runtime errors, such as generating calls to non-existent functions like `boxİnt()` instead of `boxInt()`. The problem affected multiple areas, including coroutines and array functions. It was fully resolved in Kotlin 1.5 and later versions by replacing locale-sensitive functions with invariant alternatives.

### 13. 3D-Printed Automatic Weather Station

 Score: 65 Comments: 15 [Link](https://3dpaws.comet.ucar.edu)

 > 3D-PAWS is an international initiative using 3D printing to create low-cost, reliable weather stations for remote and underserved areas. Developed by UCAR and partners, it aims to expand weather observations, reduce weather-related risks, and empower local communities through sustainable, locally-built infrastructure. Each station costs only $300-500 and measures multiple weather parameters. The project has been successfully deployed in over 17 countries, including major networks in Kenya and Barbados.

### 14. Keyboard Holders, Generation 1

 Score: 38 Comments: discuss [Link](https://cceckman.com/writing/keyboard-holders-gen1/)

 > The author created custom laser-cut plywood holders to store and display their collection of mechanical keyboards. Using parameterized designs in Cuttle software, they developed holders with back plates, bottom plates, and hook-shaped fins to securely hold different keyboard shapes. After multiple prototyping iterations at a library makerspace, they produced three functional holders mounted on the wall. The project demonstrates successful use of laser cutting for creating customized storage solutions.

### 15. Free software hasn't won

 Score: 233 Comments: 286 [Link](https://dorotac.eu/posts/fosswon/)

 > The article argues that while open source software has succeeded in certain areas like operating systems and development tools, it has largely failed in critical domains like consumer electronics, medical devices, and appliances where proprietary software dominates. The author demonstrates how everyday devices from printers to smartphones rely on closed firmware and software, undermining user freedom and control. They conclude that free software hasn't truly won because users remain dependent on closed systems in most aspects of modern life.

### 16. MAML – A new configuration language

 Score: 79 Comments: 111 [Link](https://maml.dev/)

 > MAML is a minimal configuration language designed to improve upon JSON for configuration files. It maintains JSON's simplicity while adding human-friendly features like comments, multiline strings, and optional commas/quotes. The language is both human-readable and machine-parsable, with implementations available in JavaScript, Python, and other languages. Created by Anton Medvedev, MAML aims to be a better configuration format than JSON.

### 17. For centuries massive meals amazed visitors to Korea (2019)

 Score: 102 Comments: 47 [Link](https://www.atlasobscura.com/articles/history-of-korean-food)

 > Access to the website www.atlasobscura.com has been blocked due to a suspected DDoS attack. The block is a security measure resulting from previous abuse detected on a specific article page. This restriction for anonymous users will remain in effect until October 13, 2025.

### 18. An initial investigation into WDDM on ReactOS

 Score: 53 Comments: 4 [Link](https://reactos.org/blogs/investigating-wddm/)

 > ReactOS is investigating WDDM (Windows Display Driver Model) support to improve modern hardware compatibility. The team successfully compiled and ran basic WDDM display drivers, including NVIDIA's Windows 7 driver, demonstrating 2D functionality. However, they emphasize that robust XDDM support remains essential since WDDM relies on XDDM components like CDD.dll. This initial progress marks an important step toward supporting Vista-era hardware and beyond in ReactOS.

### 19. Novelty Automation

 Score: 41 Comments: 9 [Link](https://www.novelty-automation.com/)

 > Novelty Automation is a London arcade featuring homemade satirical coin-operated machines. Located near Holborn station, it's twinned with The Under The Pier Show in Southwold. The venue offers daily operation except Mondays, corporate party hire, and sells token gift bags. It showcases various unique interactive machines with social commentary themes.

### 20. The Tiny Teams Playbook

 Score: 107 Comments: 31 [Link](https://www.latent.space/p/tiny)

 > The article introduces "Tiny Teams" as highly efficient organizations where small human teams, augmented by AI agents, achieve significant results. These teams prioritize speed, trust, and deliberate hiring of senior generalists over large headcounts. Key practices include minimal meetings, AI automation for support tasks, and maintaining a simple, focused product approach. The concept represents an evolution in organizational design for the AI era.

### 21. Completing a BASIC language interpreter in 2025

 Score: 83 Comments: 12 [Link](https://nanochess.org/ecs_basic_2.html)

 > The author developed a complete BASIC interpreter for the 1983 Mattel ECS add-on, adding string support with garbage collection and mathematical functions. They implemented cassette and printer support, successfully loading/saving programs and printing listings. The interpreter includes graphics commands and runs games, using 19 kilowords compared to the original's 24. The 7,370-line assembler source code is available on GitHub.

### 22. Show HN: I built a simple ambient sound app with no ads or subscriptions

 Score: 194 Comments: 76 [Link](https://ambisounds.app/)

 > AmbiURL is an iOS app that provides ambient soundscapes for relaxation, focus, and sleep. Users can mix multiple sounds together with individual volume controls. The app allows you to set a timer or play sounds continuously through the night. All sounds are available for offline use and play instantly without an internet connection.

### 23. A better SQL validator and comparison with existing SQL validators

 Score: 5 Comments: 1 comment [Link](https://app.sqlai.ai/posts/better-sql-validator/)

 > This article introduces an AI-powered SQL validator that addresses common limitations of existing tools. Unlike traditional validators that only report the first syntax error with vague messages, this new tool provides multiple error detection, inline annotations with precise locations, actionable explanations, and corrected queries with side-by-side diff views. It demonstrates superior performance compared to three popular SQL validators by successfully fixing a complex broken query that other tools couldn't fully resolve. The validator supports multiple SQL dialects and aims to eliminate whack-a-mole debugging.

### 24. John Searle has died

 Score: 102 Comments: 82 [Link](https://www.nytimes.com/2025/10/12/books/john-searle-dead.html)

 > I cannot access the specific article from the provided link due to an access error (403 Forbidden). The error message suggests the page may require JavaScript, an ad blocker to be disabled, or even a CAPTCHA to view. Therefore, I am unable to read the content and provide a summary.

### 25. Show HN: Aidlab – Health Data for Devs

 Score: 22 Comments: 6 [Link](item?id=45549392)

 > The system encountered a validation error when processing a URL parameter. The domain "item" could not be resolved, resulting in a 400 bad request error. This indicates the provided URL was invalid or inaccessible.

### 26. Countering Trusting Trust Through Diverse Double-Compiling (DDC)

 Score: 25 Comments: 3 [Link](https://dwheeler.com/trusting-trust/)

 > David A. Wheeler's work introduces "Diverse Double-Compiling" (DDC) as a practical method to counter the "trusting trust" attack, where compilers are subverted to insert malicious code. DDC involves compiling source code twice using different compilers to verify that the executable matches the source. This technique provides a way to independently verify that software executables correspond to their source code, effectively addressing a previously considered uncounterable threat.

### 27. A whirlwind introduction to dataflow graphs (2018)

 Score: 32 Comments: discuss [Link](https://fgiesen.wordpress.com/2018/03/05/a-whirlwind-introduction-to-dataflow-graphs/)

 > This article introduces dataflow graphs as a tool for analyzing performance in compute-bound loops. It explains how dependencies between instructions create critical paths that limit parallelism, using examples like array summation and linked list traversal. The author emphasizes that understanding these dependencies helps predict performance bottlenecks better than just profiling existing code. Dataflow graphs reveal both intra-iteration and inter-iteration dependencies, showing where latency impacts throughput. This approach provides a quantitative model for optimizing algorithms before implementation.

### 28. Constraint satisfaction to optimize item selection for bundles in Minecraft

 Score: 34 Comments: 11 [Link](https://www.robw.fyi/2025/10/12/using-constraint-satisfaction-to-optimize-item-selection-for-bundles-in-minecraft/)

 > The author created a constraint satisfaction solver using MiniZinc to optimize Minecraft inventory management with bundles. By modeling different item stack sizes as bundle slot costs and inventory selection as binary variables, the solver maximizes the number of items placed in bundles without exceeding capacity. This approach efficiently frees up inventory slots for collecting new items while handling various stack types (64-stack, 16-stack, and unstackable items). The solution demonstrates how constraint programming can solve complex game optimization problems declaratively.

### 29. Edge AI for Beginners

 Score: 154 Comments: 54 [Link](https://github.com/microsoft/edgeai-for-beginners)

 > Microsoft's EdgeAI for Beginners is a comprehensive course introducing Edge Artificial Intelligence, which runs AI models locally on devices rather than in the cloud. It covers fundamental concepts, popular small language models (SLMs), inference techniques, model optimization, and deployment strategies. The course includes hands-on projects and real-world applications across various industries. Designed for all skill levels, it provides a structured learning path from beginner to expert topics.

### 30. Loko Scheme: bare metal optimizing Scheme compiler

 Score: 162 Comments: 15 [Link](https://scheme.fail/)

 > Loko Scheme is an optimizing Scheme compiler that supports R6RS and R7RS Scheme standards. It features concurrency based on Concurrent ML and cross-compiles to Linux/amd64, NetBSD/amd64, and bare metal amd64. The compiler includes hardware support for networking, disk, video, and USB, and can run on real hardware. It's available through various package managers and is licensed under EUPL-1.2-or-later.

