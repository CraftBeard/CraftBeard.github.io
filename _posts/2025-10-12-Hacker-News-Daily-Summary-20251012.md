Updated at 2025-10-12 17:08:30 (UTC+8)

### 1. Meta Superintelligence's surprising first paper

 Score: 262 Comments: 133 [Link](https://paddedinputs.substack.com/p/meta-superintelligences-surprising)

 > Meta Superintelligence's first paper introduces REFRAG, a new RAG method that converts document chunks into compact embeddings. A lightweight policy selectively expands only the most relevant embeddings back into tokens under a budget. This approach achieves 30x faster response times and higher throughput while maintaining accuracy. The paper is surprising as it focuses on practical system-level efficiency rather than foundational model breakthroughs.

### 2. Pipelining in psql (PostgreSQL 18)

 Score: 62 Comments: 6 [Link](https://postgresql.verite.pro/blog/2025/10/01/psql-pipeline.html)

 > PostgreSQL 18 introduces pipelining commands in psql, allowing multiple queries to be sent without waiting for previous results, which improves throughput by enabling parallel client, network, and server processing. This feature utilizes the extended query protocol and is supported via libpq since PostgreSQL 14. Performance tests show significant speedups, especially over slower networks, with accelerations ranging from 1.5x on localhost to over 70x on WAN connections. The new psql commands include `\startpipeline`, `\endpipeline`, `\syncpipeline`, and `\getresults` for managing query batches efficiently.

### 3. Show HN: Rift – A tiling window manager for macOS

 Score: 120 Comments: 46 [Link](https://github.com/acsandmann/rift)

 > Rift is a tiling window manager for macOS written in Rust. It features multiple layout styles, mission control visualization, trackpad gestures, and window swapping via drag-and-drop. The project focuses on performance and usability while maintaining compatibility with macOS features like separate Spaces. Currently in active development, Rift is stable but has no official release yet.

### 4. The Flummoxagon

 Score: 14 Comments: 1 comment [Link](https://n-e-r-v-o-u-s.com/blog/?p=9827)

 > Flummoxagon is a new geometric puzzle game that combines block packing with logic constraints. Players must fit colored polyhex tiles into a hexagonal frame, ensuring pieces of the same color never touch. It includes 13 gameboards with varying difficulty levels, and new puzzles are added weekly. The game is available for purchase with a limited-time discount.

### 5. I/O Multiplexing (select vs. poll vs. epoll/kqueue)

 Score: 33 Comments: 4 [Link](https://nima101.github.io/io_multiplexing)

 > I/O multiplexing allows handling multiple I/O events from a single event loop. Select and poll are older mechanisms with O(n) performance that scale poorly for many connections. Epoll (Linux) and kqueue (macOS) are modern replacements offering O(1) performance for scalable I/O. These newer systems efficiently notify applications of I/O events without linear scanning, making them suitable for high-concurrency servers handling thousands of connections.

### 6. Coral Protocol: Open infrastructure connecting the internet of agents

 Score: 22 Comments: 1 comment [Link](https://arxiv.org/abs/2505.00749)

 > Coral Protocol is an open, decentralized infrastructure designed to connect AI agents in what's called the "Internet of Agents." It enables communication, coordination, and trust between different specialized AI agents from various domains and vendors. The protocol establishes standardized messaging formats and coordination mechanisms for complex multi-agent workflows. Its vendor-neutral approach ensures secure and efficient collaboration, positioning it as a foundational platform for automated agent ecosystems.

### 7. Vancouver Stock Exchange: Scam capital of the world (1989) [pdf]

 Score: 84 Comments: 39 [Link](https://scamcouver.wordpress.com/wp-content/uploads/2012/04/scam-capital.pdf)

 > The article identifies Vancouver as the "scam capital" of Canada, detailing various fraudulent schemes prevalent in the city. It highlights investment scams, real estate fraud, and other deceptive practices targeting residents. The piece serves as a warning to the public about these financial crimes.

### 8. Ask HN: Abandoned/dead projects you think died before their time and why?

 Score: 115 Comments: 323 [Link](item?id=45553132)

 > The system encountered a validation error when processing a URL parameter. The domain "item" could not be resolved, resulting in a 400 bad request error. This indicates the provided URL was invalid or inaccessible.

### 9. Spyware maker NSO Group confirms acquisition by US investors

 Score: 94 Comments: 55 [Link](https://techcrunch.com/2025/10/10/spyware-maker-nso-group-confirms-acquisition-by-us-investors/)

 > Israeli spyware maker NSO Group has been acquired by a group of U.S. investors who now hold controlling ownership. The deal, valued at tens of millions of dollars, was reportedly led by Hollywood producer Robert Simonds. NSO confirmed the acquisition but stated the company will maintain its headquarters and operations in Israel under Israeli regulatory oversight. This controversial company, known for its Pegasus spyware, has faced U.S. sanctions since 2021 due to its products being used to target journalists and government officials.

### 10. Anthropic's Prompt Engineering Tutorial

 Score: 126 Comments: 11 [Link](https://github.com/anthropics/prompt-eng-interactive-tutorial)

 > Anthropic's Interactive Prompt Engineering Tutorial is a comprehensive GitHub repository offering hands-on learning for crafting effective prompts for Claude AI models. The course is structured into 9 chapters covering beginner to advanced techniques, with practical exercises and examples. It teaches users to master prompt structure, address common failures, and build complex prompts for various use cases. The tutorial is available both on GitHub and as a more user-friendly Google Sheets version.

### 11. The World's 2.75B Buildings

 Score: 41 Comments: 14 [Link](https://tech.marksblogg.com/building-footprints-gba.html)

 > Researchers from the Technical University of Munich published the GlobalBuildingAtlas dataset, estimating Earth has 2.75 billion buildings. This contrasts with the UN's estimate of 4 billion buildings. The dataset combines multiple sources including Google's Open Buildings, OpenStreetMap, and AI-detected footprints from Planet Labs satellite imagery. The author processed 1.1 TB of GeoJSON files into 210 GB of Parquet format for easier access and analysis.

### 12. Show HN: Sober not Sorry – free iOS tracker to help you quit bad habits

 Score: 5 Comments: 1 comment [Link](https://sobernotsorry.app/)

 > Sober not Sorry is a free iOS app for tracking sobriety and quitting bad habits. It features a simple, clean design with counters, achievements, and health progress tracking. The app includes home and lock screen widgets to keep motivation visible. Its focus is on providing a calm, pressure-free tool for maintaining consistency in your journey.

### 13. Paper2Video: Automatic Video Generation from Scientific Papers

 Score: 43 Comments: 7 [Link](https://arxiv.org/abs/2510.05096)

 > Paper2Video introduces an automated system for generating academic presentation videos from research papers. It addresses challenges like multi-modal content coordination and proposes a benchmark dataset with evaluation metrics. The PaperTalker framework integrates slide generation, speech synthesis, and talking-head rendering. Experiments show it produces more faithful and informative videos than existing methods, advancing automated academic video creation.

### 14. Microsoft only lets you opt out of AI photo scanning 3x a year

 Score: 596 Comments: 207 [Link](https://hardware.slashdot.org/story/25/10/11/0238213/microsofts-onedrive-begins-testing-face-recognizing-ai-for-photos-for-some-preview-users)

 > Microsoft is testing a new AI feature in OneDrive that automatically recognizes faces in users' photos. The feature is currently rolling out to a limited number of preview users, though some report being enrolled without signing up. Users can supposedly disable the feature, but the article notes the toggle may not work and claims the setting can only be turned off three times per year. Privacy advocates have raised concerns about the opt-out approach rather than opt-in.

### 15. A Guide for WireGuard VPN Setup with Pi-Hole Adblock and Unbound DNS

 Score: 73 Comments: 7 [Link](https://psyonik.tech/posts/a-guide-for-wireguard-vpn-setup-with-pi-hole-adblock-and-unbound-dns/)

 > This comprehensive guide explains how to set up a WireGuard VPN server on a VPS, integrated with Pi-Hole for ad-blocking and Unbound for DNS resolution. It covers initial server configuration, firewall setup, WireGuard peer management, and connecting various devices. The setup enables secure remote access to home network resources while providing network-wide ad blocking through a custom DNS infrastructure. The guide includes detailed steps for server hardening, performance testing, and mobile client configuration.

### 16. The App Store was always authoritarian

 Score: 85 Comments: 48 [Link](https://infrequently.org/2025/10/the-app-store-was-always-authoritarian/)

 > Apple is censoring its App Store at the request of the Trump administration, removing apps that document ICE abuses. The article argues this authoritarian behavior stems from Apple's desire to protect its monopolistic App Store profits by suppressing web-based alternatives that could bypass its control. This demonstrates how Apple's centralized power easily capitulates to government pressure while undermining competition and free speech.

### 17. LineageOS 23

 Score: 214 Comments: 86 [Link](https://lineageos.org/Changelog-30/)

 > LineageOS 23.0 is now available, based on Android 16. This release arrives earlier than usual despite Google's new security patch cadence, which now primarily releases fixes quarterly rather than monthly. The update includes a rewritten camera app (Aperture), an updated music player (Twelve), and a new ad-free launcher for Android TV (Catapult). Support for legacy devices with older Linux kernels may be limited due to new Android requirements.

### 18. Show HN: A Lisp Interpreter for Shell Scripting

 Score: 43 Comments: 3 [Link](https://github.com/gue-ni/redstart)

 > Redstart is a lightweight Lisp interpreter written in C++ specifically designed for Linux shell scripting. It enables users to write shell scripts using Lisp syntax while maintaining full interoperability with standard Unix shell commands. The project allows command execution, output capture, piping between processes, and supports typical Lisp features like functions and closures. It can be installed via a provided script and includes both REPL and script execution capabilities.

### 19. Testing two 18 TB white label SATA hard drives from datablocks.dev

 Score: 175 Comments: 105 [Link](https://ounapuu.ee/posts/2025/10/06/datablocks-white-label-drives/)

 > The author purchased two 18 TB white label hard drives from datablocks.dev for a home server in Europe. These unbranded drives had minor cosmetic damage but were functional and offered significant cost savings over recertified models. After thorough testing, the drives performed as expected with typical noise and power consumption for HDDs. The author is satisfied with the purchase and now uses them for bulk storage alongside existing SSDs.

### 20. Floating Electrons on a Sea of Helium

 Score: 5 Comments: discuss [Link](https://arstechnica.com/science/2025/10/new-qubit-tech-traps-single-electrons-on-liquid-helium/)

 > A new quantum computing technology traps single electrons on the surface of liquid helium. These floating electrons can be manipulated using electromagnetic traps on a chip. The system offers potential advantages for creating stable qubits with long coherence times. This approach could enable scalable quantum processors using standard manufacturing techniques.

### 21. How Apple designs a virtual knob (2012)

 Score: 140 Comments: 86 [Link](https://jherrm.github.io/knobs/)

 > Apple designed virtual knobs for Garageband with three interaction methods: circular spinning, vertical sliding, and horizontal sliding. These gestures allow precise control and multitouch adjustments. The knobs use various visual techniques including static backgrounds with positioned indicators, repeating sprite sequences, and fully rendered 3D models with 120 frames. This attention to detail creates intuitive musical controls that leverage multitouch capabilities. The author recreated these interactions in Knob.js to demonstrate Apple's sophisticated approach.

### 22. CamoLeak: Critical GitHub Copilot Vulnerability Leaks Private Source Code

 Score: 32 Comments: 9 [Link](https://www.legitsecurity.com/blog/camoleak-critical-github-copilot-vulnerability-leaks-private-source-code)

 > A critical vulnerability called CamoLeak was discovered in GitHub Copilot Chat in June 2025, allowing attackers to silently exfiltrate secrets and source code from private repositories. The attack combined remote prompt injection with a novel Content Security Policy bypass using GitHub's own image proxy infrastructure. This enabled full control over Copilot's responses, including suggesting malicious code. The vulnerability was reported via HackerOne, and GitHub fixed it by completely disabling image rendering in Copilot Chat.

### 23. Google blocks Android hack that let Pixel users enable VoLTE anywhere

 Score: 149 Comments: 49 [Link](https://www.androidauthority.com/pixel-ims-broken-october-update-3606444/)

 > Access to AndroidAuthority.com is blocked until October 12, 2025. This security block was implemented due to suspected DDoS attack abuse originating from a specific page on their website. The error indicates the site was compromised by too many domains attempting access.

### 24. Windows Subsystem for FreeBSD

 Score: 254 Comments: 106 [Link](https://github.com/BalajeS/WSL-For-FreeBSD)

 > This is an experimental project called WSL-For-FreeBSD that adapts Microsoft's WSL2 open-source components to run FreeBSD on Windows. The project aims to enable FreeBSD to boot and run natively within WSL2's architecture with minimal modifications to the FreeBSD base system. Current status shows FreeBSD can successfully boot in WSL2 with basic functionality working, while networking and I/O features are still in progress. This is a personal project not affiliated with Microsoft or the FreeBSD Foundation.

### 25. The World Trade Center under construction through photos, 1966-1979

 Score: 213 Comments: 101 [Link](https://rarehistoricalphotos.com/twin-towers-construction-photographs/)

 > The World Trade Center was constructed from 1966-1979 as an urban renewal project in Lower Manhattan. Designed by architect Minoru Yamasaki, the twin towers featured innovative engineering including slurry wall foundations and reached 110 stories tall. The complex became a major business hub with over 10 million square feet of office space before being destroyed in the September 11, 2001 terrorist attacks.

### 26. Superpowers: How I'm using coding agents in October 2025

 Score: 350 Comments: 183 [Link](https://blog.fsck.com/2025/10/09/superpowers/)

 > The author has developed "Superpowers," a plugin system for Claude Code that enhances AI coding agents through reusable "skills" documented in markdown files. These skills systematize workflows like TDD development, git worktree management, and automated code review processes. The system uses persuasion principles to ensure agents consistently follow documented procedures. Users can install Superpowers via Claude's plugin marketplace to augment their coding agent capabilities with these structured workflows.

### 27. The <output> Tag

 Score: 761 Comments: 170 [Link](https://denodell.com/blog/html-best-kept-secret-output-tag)

 > The `<output>` HTML element is a semantic tag designed to display calculation results or dynamic content from user actions. It provides built-in accessibility by automatically announcing updates to screen readers through its default `role="status"` mapping. This eliminates the need for manual ARIA live regions when displaying dynamic results. The element has excellent browser support and can be used anywhere dynamic content updates based on user input.

### 28. Vibing a non-trivial Ghostty feature

 Score: 260 Comments: 121 [Link](https://mitchellh.com/writing/non-trivial-vibing)

 > The author developed a non-trivial macOS automatic update feature for Ghostty using AI assistance across 16 coding sessions costing $15.98. The process involved prototyping UI, implementing backend functionality with Sparkle framework, and extensive cleanup sessions. While AI handled much implementation work, the author maintained control through manual code review and restructuring. The feature was successfully shipped after approximately 8 hours of work spanning multiple days.

### 29. Beyond indexes: How open table formats optimize query performance

 Score: 54 Comments: 1 comment [Link](https://jack-vanlightly.com/blog/2025/10/8/beyond-indexes-how-open-table-formats-optimize-query-performance)

 > Open table formats like Apache Iceberg optimize query performance for analytical workloads through data skipping rather than traditional indexing. They rely on partitioning, sorting, and metadata like column statistics to prune irrelevant files and row groups during scans. Auxiliary structures such as Bloom filters and materialized views further enhance efficiency by reducing I/O. This approach is tailored for large-scale reads, contrasting with OLTP systems that use indexes for point lookups.

### 30. Heroin addicts often seem normal

 Score: 97 Comments: 120 [Link](https://justismills.substack.com/p/heroin-addicts-often-seem-normal)

 > Many heroin addicts appear normal and functional, not fitting the stereotypical image of visibly unstable individuals. The author lived with opiate addicts who maintained jobs, relationships, and responsible behavior while secretly using. Addiction affects diverse people randomly across communities, with recovery outcomes seeming unpredictable. Effective drug policy must address both visible public addiction issues and hidden functional addicts.

