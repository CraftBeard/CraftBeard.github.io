Updated at 2025-03-30 17:32:51 (UTC+8)

### 1. Everyone knows all the apps on your phone

 Score: 547 Comments: 240 [Link](https://peabee.substack.com/p/everyone-knows-what-apps-you-use)

 > Many Indian apps, including Swiggy, Zepto, and personal loan apps, exploit Android permissions to track users' installed apps, often for profiling despite Google's restrictions. Some use a loophole (ACTION_MAIN filter) to bypass policies, revealing widespread privacy violations. Sensitive data like SMS and app usage is collected without clear user consent.

### 2. Bringing Record and Replay debugging everywhere on Linux

 Score: 61 Comments: 5 [Link](https://github.com/sidkshatriya/me/blob/master/008-rr-everywhere.md)

 > The article introduces a modified version of the `rr` debugger that works without requiring CPU hardware performance counters, enabling its use in cloud VMs and containers. This "Software Counters mode" uses lightweight instrumentation to achieve record-and-replay functionality, expanding debugging possibilities. The author explains the benefits of record-and-replay debugging and highlights the limitations of the original `rr` tool. The modified version is available on GitHub for users to build and test.

### 3. Just Write a Test for It

 Score: 28 Comments: 10 [Link](https://kobzol.github.io/rust/2025/03/25/just-write-a-test-for-it.html)

 > The author describes how Rust encouraged them to write a test to prevent SQL migration issues in the `bors` project. They used the `sqlparser` crate to detect `NOT NULL` columns without defaults, showcasing Rust's ease of integrating powerful tools for robust testing. The test was quick to implement and effective.

### 4. Utah becomes first US state to ban fluoride in its water

 Score: 251 Comments: 587 [Link](https://www.bbc.com/news/articles/c4gmggp2y99o)

 > Utah has become the first U.S. state to ban fluoride in public water, citing health concerns raised by officials like Robert F. Kennedy. Critics, including dental experts, warn the move could harm oral health, especially for children. The ban takes effect on May 7. While some argue fluoride poses risks, most health organizations support its use for cavity prevention. Other states may follow Utah's lead.

### 5. Four Lectures on Standard ML (1989) [pdf]

 Score: 6 Comments: discuss [Link](https://www.cs.tufts.edu/~nr/cs257/archive/mads-tofte/four-lectures.pdf)

 > Mads Tofte's "Four Lectures on Standard ML" provides an overview of Standard ML, focusing on its module system. The lectures cover core language features, module programming methodology, static semantics of modules, and a practical project implementing an interpreter. The notes emphasize ML's functional nature, type system, and module constructs (structures, signatures, functors) for large-scale programming.

### 6. Show HN: Cloud-Ready Postgres MCP Server

 Score: 81 Comments: 21 [Link](https://github.com/stuzero/pg-mcp)

 > PG-MCP is a PostgreSQL Model Context Protocol server that helps AI agents interact with PostgreSQL databases. It offers features like multi-database support, schema discovery, query explanation, and connection management. Built with Python and FastMCP, it includes tools for secure, read-only database access and supports extensions like PostGIS and pgvector. Installation is available via Docker or manual setup.

### 7. Convert Linux to Windows

 Score: 187 Comments: 222 [Link](https://philipbohun.com/blog/0007.html)

 > The article proposes creating a Linux distro that runs Windows binaries by default via Wine, addressing Linux's binary compatibility issues while offering a familiar Windows-like environment. It highlights the stability of Win32 and criticizes the increasing restrictions and privacy concerns in macOS and Windows. The goal is to provide a seamless transition for users seeking freedom from commercial OS limitations.

### 8. C. Elegans: The Worm That No Computer Scientist Can Crack

 Score: 55 Comments: 11 [Link](https://www.wired.com/story/openworm-worm-simulator-biology-code/)

 > The article explores OpenWorm, an open-source project aiming to create a digital simulation of the microscopic nematode *C. elegans* to understand its biology. Despite over a decade of effort, the simulation remains incomplete, highlighting the challenges of replicating life computationally. Researchers hope advancements in technology and collaboration will eventually achieve this goal, offering insights into neuroscience and life itself. The project raises philosophical questions about the nature of simulation and existence.

### 9. Self-contained Python scripts with uv

 Score: 114 Comments: 17 [Link](http://blog.dusktreader.dev/2025/03/29/self-contained-python-scripts-with-uv/)

 > The article explains how to make self-contained Python scripts using `uv` by adding dependencies in script headers and using a special shebang line (`#!/usr/bin/env -S uv run script`). This avoids global installations or virtual environments, simplifying execution across systems with `uv` installed. The author demonstrates this with a script for testing API endpoints.

### 10. Towards fearless SIMD, 7 years later

 Score: 113 Comments: 35 [Link](https://linebender.org/blog/towards-fearless-simd/)

 > Raph Levien reflects on Rust's SIMD progress seven years after his initial "fearless SIMD" vision, noting current challenges like unsafe intrinsics and multiversioning. He highlights Linebender's growing need for SIMD in CPU/GPU hybrid rendering and proposes safer, more ergonomic approaches. While libraries like `std::simd` and `pulp` exist, he advocates for better language support and ecosystem collaboration to match C++'s Highway library. The goal is to make Rust a top choice for high-performance SIMD programming.

### 11. Certified randomness using a trapped-ion quantum processor

 Score: 6 Comments: discuss [Link](https://www.nature.com/articles/s41586-025-08737-1)

 > Researchers demonstrated a protocol for certified randomness using a trapped-ion quantum processor, combining quantum computing with classical verification to generate verifiably random bits. The experiment achieved a high-fidelity quantum computation and used exascale classical computing to verify the results, ensuring the randomness was not spoofed. This work represents a practical beyond-classical application of near-term quantum devices.

### 12. Atop 2.11 heap problems

 Score: 139 Comments: 55 [Link](https://openwall.com/lists/oss-security/2025/03/29/1)

 > Atop 2.11 has a heap vulnerability (CVE-2025-31160) where it connects to a TCP port during initialization, allowing malicious programs to send malformed strings, causing parsing failures and crashes. The issue exists since version 2.4.0. The fix disables the default connection and improves parsing when the `-k` flag is used.

### 13. Why Apple's Severance gets edited over remote desktop software

 Score: 442 Comments: 275 [Link](https://tedium.co/2025/03/29/severance-apple-remote-editing-weirdness/)

 > Apple’s *Severance* is edited using remote desktop software (Jump Desktop) on a Mac Mini, highlighting Apple’s lack of cloud-based professional solutions. The setup relies on offsite hardware, making the local Mac less essential. This reveals inefficiencies in Apple’s enterprise offerings compared to competitors like Microsoft. The article critiques Apple’s outdated approach to remote workflows.

### 14. Accessible open textbooks in math-heavy disciplines

 Score: 186 Comments: 58 [Link](https://richardzach.org/2025/03/accessible-open-textbooks-in-math-heavy-disciplines/)

 > The article discusses the challenges of creating accessible open textbooks in math-heavy disciplines, where LaTeX is the dominant authoring tool but produces inaccessible PDFs. It explores solutions like converting LaTeX to HTML using tools like LaTeXML and BookML, or using alternative platforms like PreTeXt and Markdown, while addressing accessibility issues for screen readers and visual presentation. A case study on converting a logic textbook highlights practical steps and pitfalls in making math content accessible.

### 15. Commercials that David Lynch directed (2018)

 Score: 124 Comments: 27 [Link](https://www.openculture.com/2018/07/watch-commercials-david-lynch-directed-big-30-minute-compilation.html)

 > The article highlights a 30-minute compilation of commercials directed by filmmaker David Lynch, known for his distinctive "Lynchian" style. After gaining fame with films like *Eraserhead* and *Blue Velvet*, Lynch brought his surreal, avant-garde vision to ads for brands like Calvin Klein, Georgia Coffee, and Parisienne cigarettes. The compilation showcases his unique approach to blending art and commerce.

### 16. Paged Out #6 [pdf]

 Score: 236 Comments: 30 [Link](https://pagedout.institute/download/PagedOut_006.pdf)

 > 

### 17. XAN: A Modern CSV-Centric Data Manipulation Toolkit for the Terminal

 Score: 86 Comments: 13 [Link](https://github.com/medialab/xan)

 > `xan` is a fast, memory-efficient command-line tool written in Rust for processing large CSV files. It offers features like filtering, sorting, joining, and visualizing CSV data, along with a custom expression language for complex tasks. Originally forked from `xsv`, it has been extensively rewritten for social sciences use cases, including lexicometry and graph theory. It supports terminal-based data exploration and basic visualizations.

### 18. The disappearance of Gaia, ESA spacecraft will be turned off on 27 March 2025

 Score: 90 Comments: 25 [Link](https://www.cosmos.esa.int/web/gaia/news)

 > The article summarizes updates on ESA's Gaia mission, including its final observations on 15 January 2025, upcoming data releases (DR4 in 2026 and DR5 in 2030), and technology tests before spacecraft passivation. It also highlights recent discoveries like exoplanet Gaia-4b and invites public observations of Gaia's brightness changes.

### 19. Matrix Calculus (For Machine Learning and Beyond)

 Score: 120 Comments: 20 [Link](https://arxiv.org/abs/2501.14787)

 > This paper introduces matrix calculus for undergraduates, extending differential calculus to functions on vector spaces like matrix operations and ODE solutions. It focuses on practical applications in optimization and machine learning, covering adjoint differentiation and automatic differentiation techniques. The notes are based on an MIT short course.

### 20. Kalua: An OpenWrt extension for building large mesh-networks

 Score: 3 Comments: discuss [Link](https://github.com/bittorf/kalua)

 > Kalua is a hardware-independent OpenWRT extension for setting up and managing large WiFi mesh networks. It includes features like billing, captive portals, QoS, and monitoring, using POSIX-shell as its main language. The project provides tools for building custom firmware and supports various router models.

### 21. Lvgl: Embedded graphics library to create beautiful UIs

 Score: 122 Comments: 24 [Link](https://github.com/lvgl/lvgl)

 > LVGL is a popular open-source embedded graphics library for creating beautiful UIs on MCUs and MPUs. It supports multiple display types, offers 30+ widgets, and requires minimal resources (32kB RAM, 128kB Flash). The library is portable, MIT-licensed, and backed by industry leaders. It also provides services like UI design and consulting.

### 22. Koto Programming Language

 Score: 170 Comments: 129 [Link](https://koto.dev/)

 > Koto is a lightweight scripting language designed for Rust applications, featuring documentation, installation guides, and an online playground.

### 23. Some Reflections After a Month of Tracking My Own Online Activity

 Score: 11 Comments: 6 [Link](https://mcwhittemore.com/posts/page-activity-report-2025-03-20.html)

 > Matthew Chase Whittemore tracked his web activity for a month using a custom tool, revealing he spent most time on Gmail, LinkedIn, and Feedbin—surprised by the gap between his perceived and actual usage. He reflects on identity and career choices, noting how data challenges self-perception. He also critiques Feedbin’s lack of unique URLs and shares insights from his tracking, including time spent on local projects. The data is limited to his personal laptop, excluding mobile and work browsing.

### 24. Electric power generation from Earth's rotation through its own magnetic field

 Score: 28 Comments: 32 [Link](https://arxiv.org/abs/2503.15790)

 > Researchers demonstrated a method to generate electricity from Earth's rotation using its magnetic field, overcoming previous theoretical limitations. They used a manganese-zinc ferrite cylindrical shell to produce a small but measurable DC current, validating predictions about orientation and material properties. The experiment was replicated at a second location, confirming the effect. Future work could explore scaling up the system for practical power generation.

### 25. The Mysterious Flow of Fluid in the Brain

 Score: 26 Comments: 4 [Link](https://www.quantamagazine.org/the-mysterious-flow-of-fluid-in-the-brain-20250326/)

 > Scientists debate how cerebrospinal fluid (CSF) clears brain waste, with some suggesting it flows actively during sleep to remove toxins. A recent study led by Maiken Nedergaard proposes that blood vessel movements, driven by norepinephrine, help pump CSF, potentially explaining sleep's restorative effects. Critics argue the evidence is inconclusive, and the exact mechanisms remain unclear. The debate highlights ongoing uncertainty about brain waste clearance.

### 26. Introduction to Open Source Laptop Project (2023)

 Score: 25 Comments: 8 [Link](https://resources.altium.com/p/open-source-laptop-part-one)

 > This article introduces an open-source laptop project aimed at making hidden engineering knowledge in consumer electronics accessible. The project focuses on sustainability, repairability, and upgradability while documenting the multidisciplinary design process. Future updates will include design details, simulation tools, and project files shared via Altium 365.

### 27. Vramfs: Vram Based Filesystem for Linux

 Score: 104 Comments: 36 [Link](https://github.com/Overv/vramfs)

 > vramfs is a Linux utility that creates a file system in GPU VRAM using FUSE, offering ~2.4 GB/s read and 2.0 GB/s write speeds. It requires OpenCL 1.2 support and is built for experimental use, not production. The project includes benchmarks and future ideas like RAID-0 support. Licensed under MIT.

### 28. Veloren – Voxel action-adventure role-playing

 Score: 296 Comments: 73 [Link](https://veloren.net/)

 > Veloren is an open-source, multiplayer action-adventure RPG set in a vast procedural fantasy world. Players can explore diverse environments, engage in dynamic combat, craft items, tame creatures, and delve into dungeons. The game supports multiplayer and community contributions.

### 29. 6502 as a Service

 Score: 31 Comments: 4 [Link](https://www.emulationonline.com/systems/chiplab/6502-lab-available/)

 > The article introduces a new online service called Chiplab that lets users run 6502 assembly programs on a real 6502 chip, providing cycle-by-cycle bus traces for accuracy. It explains how the system works, its purpose for emulation research, and invites contributors to help build a digital 6502 model. [Read more here](https://www.emulationonline.com/systems/chiplab/6502-lab-available/).

### 30. Spark AI (YC W24) is hiring a full-stack engineer in San Francisco

 Score: None Comments: None [Link](https://www.ycombinator.com/companies/spark/jobs/kDeJlPK-software-engineer-full-stack)

 > Spark is hiring a Full Stack Software Engineer in San Francisco to build AI-powered tools for clean energy developers. The role involves designing APIs, AI infrastructure, and data pipelines using Typescript, NextJS, and Postgres. Candidates need 3+ years of experience and must work in-person. The salary range is $150K–$200K. Spark is backed by top investors like AI Grant and Brex founders.

