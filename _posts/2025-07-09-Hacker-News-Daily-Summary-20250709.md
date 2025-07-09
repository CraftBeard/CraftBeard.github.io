Updated at 2025-07-09 17:09:48 (UTC+8)

### 1. Helm local code execution via a malicious chart – CVE-2025-53547

 Score: 79 Comments: 25 [Link](https://github.com/helm/helm/security/advisories/GHSA-557j-xg8c-q2mm)

 > A vulnerability in Helm (CVE-2025-53547) allows malicious `Chart.yaml` content to execute code when updating dependencies if `Chart.lock` is symlinked to sensitive files. Fixed in Helm v3.18.4, it affects versions ≤3.18.3. Users should ensure `Chart.lock` isn't a symlink before updating dependencies. Severity: High (CVSS 8.5).

### 2. Is the doc bot docs, or not?

 Score: 21 Comments: 2 [Link](https://www.robinsloan.com/lab/what-are-we-even-doing-here/)

 > The author tried using Shopify's LLM-powered documentation bot to find Liquid syntax for detecting Shopify Collective orders, but the bot provided incorrect code. After testing, they discovered the bot's answer didn't work because the tag isn't available when needed. They question the value of a documentation bot that guesses instead of providing accurate information, arguing it undermines proper documentation efforts. The post ends with a working solution the author found themselves.

### 3. AI, Power and Sociolinguistics [pdf]

 Score: 14 Comments: 1 comment [Link](https://www.researchgate.net/profile/Ico-Maly-2/publication/385703534_AI_power_and_sociolinguistics/links/6813618cdf0e3f544f502f05/AI-power-and-sociolinguistics.pdf)

 > The domain www.researchgate.net is blocked until July 9, 2025, due to suspected DDoS abuse linked to excessive requests from a specific publication.

### 4. RapidRAW: A non-destructive and GPU-accelerated RAW image editor

 Score: 150 Comments: 55 [Link](https://github.com/CyberTimon/RapidRAW)

 > RapidRAW is a lightweight, GPU-accelerated RAW image editor built with Rust and React, offering non-destructive editing, AI-powered features, and cross-platform support. Developed by an 18-year-old, it aims to be a fast alternative to tools like Lightroom. The project is open-source under AGPL-3.0.

### 5. 7-Zip for Windows can now use more than 64 CPU threads for compression

 Score: 63 Comments: 10 [Link](https://www.7-zip.org/history.txt)

 > The article details the version history of 7-Zip, highlighting updates, bug fixes, and new features. Key improvements include support for more CPU threads, faster compression speeds, enhanced archive formats, and security fixes. The latest version (25.00) adds multi-threading for over 64 CPUs and boosts bzip2 and deflate compression speeds.

### 6. Most RESTful APIs Aren't RESTful

 Score: 26 Comments: 25 [Link](https://florian-kraemer.net//software-architecture/2025/07/07/Most-RESTful-APIs-are-not-really-RESTful.html)

 > Most RESTful APIs don't truly follow REST principles, as they often lack hypermedia (HATEOAS), a core requirement outlined by Roy Fielding. Many APIs simplify REST into CRUD-style HTTP operations, ignoring dynamic client-server interactions via embedded links. Fielding's rules emphasize protocol independence, media types, and discoverability, but practical trade-offs like tooling and tight coupling often lead to simpler, non-RESTful designs. The article suggests being pragmatic rather than dogmatic about REST compliance.

### 7. Bootstrapping a side project into a profitable seven-figure business

 Score: 508 Comments: 108 [Link](https://projectionlab.com/blog/we-reached-1m-arr-with-zero-funding)

 > ProjectionLab bootstrapped to $1M ARR in four years without funding, starting as a side project in 2021. Founder Kyle Nolan built it while working full-time, gradually scaling with community support and a small team. Key milestones included hitting $10K MRR in 2023 and quitting his job to focus fully. The company prioritizes sustainable growth and customer alignment over hype.

### 8. Breaking Git with a carriage return and cloning RCE

 Score: 314 Comments: 110 [Link](https://dgl.cx/2025/07/git-clone-submodule-cve-2025-48384)

 > A vulnerability (CVE-2025-48384) in Git allows remote code execution via a carriage return in `.gitmodules` during recursive cloning. The bug affects Unix-like systems, tricking Git into writing files to unintended paths. A patch fixes the issue by properly quoting CR characters. Users should update Git and related tools like GitHub Desktop.

### 9. Show HN: I rewrote an outdated React Native map clustering library

 Score: 9 Comments: 1 comment [Link](https://github.com/suwi-lanji/rn-maps-clustering)

 > **Summary:**  
`rn-maps-clustering` is a modern, performant map clustering library for React Native, built on `supercluster`. It offers a declarative API, TypeScript support, and customizable clusters. Features include high performance, spiderfier functionality, and easy integration with `react-native-maps`. Licensed under MIT.

### 10. Bug Stories

 Score: 6 Comments: 1 comment [Link](https://500mile.email/)

 > This article is a curated collection of bizarre and humorous tech-related bugs and incidents, such as emails not sending beyond 500 miles, microwaves interfering with radio telescopes, and software crashes tied to weather or user actions. Each story highlights unexpected and often absurd technical glitches with quirky explanations. The list serves as an entertaining archive of real-world tech troubleshooting gone awry.

### 11. I'm Building LLM for Satellite Data EarthGPT.app

 Score: 25 Comments: 3 [Link](https://www.earthgpt.app/)

 > EarthGPT is an AI-powered platform for analyzing multi-spectral satellite imagery, offering sample projects like Brazilian forests, Greenland ice sheets, and Pakistan flood monitoring. It leverages Sentinel-2 data and supports STAC Browser for dataset exploration.

### 12. Frame of preference A history of Mac settings, 1984–2004

 Score: 95 Comments: 15 [Link](https://aresluna.org/frame-of-preference/)

 > This article explores the evolution of Mac settings from 1984 to 2004, highlighting key design changes, nostalgic moments, and the shift from charming, bespoke interfaces to more uniform but less engaging modern layouts. It reflects on how early Mac control panels, like Susan Kare’s 1984 design, balanced functionality with personality, while later versions struggled with inconsistency and over-complexity. The piece also contrasts Mac OS with NeXTStep and laments the loss of creativity in today’s System Settings.

### 13. Supabase MCP can leak your entire SQL database

 Score: 700 Comments: 356 [Link](https://www.generalanalysis.com/blog/supabase-mcp-blog)

 > Supabase's Model Context Protocol (MCP) integration can be exploited to leak private SQL tables due to LLMs' inability to distinguish user instructions from data. Attackers can craft malicious messages that trick the system into executing unauthorized SQL queries using elevated `service_role` privileges, bypassing Row-Level Security. Mitigations include using read-only mode and filtering prompt injections. This highlights risks in combining overprivileged access with untrusted user input.

### 14. Smollm3: Smol, multilingual, long-context reasoner LLM

 Score: 289 Comments: 54 [Link](https://huggingface.co/blog/smollm3)

 > HuggingFace introduces **SmolLM3**, a fully open 3B multilingual model with long-context reasoning (up to 128k tokens). It outperforms similar-sized models like Llama-3.2-3B and Qwen2.5-3B while competing with larger 4B alternatives. The release includes detailed training recipes, datasets, and configurations for reproducibility. Available models: [Base](https://hf.co/HuggingFaceTB/SmolLM3-3B-Base) and [Instruct](https://hf.co/HuggingFaceTB/SmolLM3-3B).

### 15. US Court nullifies FTC requirement for click-to-cancel

 Score: 100 Comments: 117 [Link](https://arstechnica.com/tech-policy/2025/07/us-court-cancels-ftc-rule-that-would-have-made-canceling-subscriptions-easier/)

 > A federal court struck down the FTC's "click-to-cancel" rule, which aimed to make subscription cancellations as easy as sign-ups, citing procedural flaws in the rulemaking process. The 8th Circuit ruled the FTC failed to conduct a required preliminary regulatory analysis. Industry groups had challenged the rule, arguing it imposed excessive costs. The decision leaves companies free to maintain complex cancellation processes. The FTC had claimed the rule would protect consumers from deceptive subscription practices.

### 16. iPod Linux – Linux for Your iPod

 Score: 33 Comments: 8 [Link](http://www.ipodlinux.org/)

 > iPodLinux is an open-source project that ports Linux to iPods, featuring a custom uClinux kernel and the podzilla interface. It supports 1st-3rd generation iPods, with ongoing development for newer models. The project offers additional apps and modules beyond Apple's firmware. Installation guides and support are available, though newer iPods may lack full support.

### 17. Brut: A New Web Framework for Ruby

 Score: 174 Comments: 56 [Link](https://naildrivin5.com/blog/2025/07/08/brut-a-new-web-framework-for-ruby.html)

 > Brut is a new Ruby web framework focused on simplicity, using classes and objects instead of controllers. It emphasizes HTML generation, modern web practices, and avoids excessive abstractions. Built with tools like Phlex and RSpec, it offers built-in instrumentation and a Sequel-based data layer. Brut aims to make web development fun and straightforward.

### 18. Radium Music Editor

 Score: 199 Comments: 45 [Link](http://users.notam02.no/~kjetism/radium/)

 > Radium is an advanced, tracker-inspired music editor and DAW with a unique interface combining graphical and text-based editing. It supports MIDI, audio recording, plugins, and scripting, aiming to be user-friendly despite its complexity. Developed since 1999, it runs on Linux, Windows, and Mac.

### 19. SUSE launches new European digital sovereignty service to meet surging demand

 Score: 19 Comments: discuss [Link](https://www.zdnet.com/article/suse-launches-new-european-digital-sovereignty-support-service-to-meet-surging-demand/)

 > SUSE has launched a new Sovereign Premium Support service to help European businesses and governments maintain digital sovereignty by ensuring IT support, software, and data remain within the EU. The service addresses concerns over foreign data control by offering EU-based personnel, data storage, and encryption. This move aligns with growing European demand for secure, independent IT solutions amid geopolitical uncertainties.

### 20. Libpostal: C library for parsing/normalizing street addresses around the world

 Score: 42 Comments: 8 [Link](https://github.com/openvenues/libpostal)

 > **Summary:**  
Libpostal is a C library for parsing and normalizing street addresses globally using statistical NLP and open geo data. It supports multiple languages and helps convert human-readable addresses into machine-comparable formats. The project includes language bindings for Python, Ruby, Go, and others, and is open-source under the MIT License.

### 21. The Dangers of Stochastic Parrots: Can Language Models Be Too Big?

 Score: 4 Comments: 1 comment [Link](https://dl.acm.org/doi/10.1145/3442188.3445922)

 > The article "On the Dangers of Stochastic Parrots" examines the risks of increasingly large language models, highlighting environmental costs, biases, and ethical concerns. It recommends prioritizing curated datasets, evaluating stakeholder impacts, and exploring alternatives to ever-larger models.

### 22. Swahili on the Road

 Score: 25 Comments: 3 [Link](https://www.historytoday.com/archive/behind-times/swahili-road)

 > The article explores Swahili's rise as a key language in Tanzania's independence movement under Julius Nyerere, its standardization, and its role in postcolonial nation-building. It highlights Swahili's global influence today, its adoption by international organizations, and its cultural significance across Africa. Nyerere's promotion of Swahili helped unify Tanzania and support Pan-African solidarity.

### 23. Introduction to Indian English

 Score: 30 Comments: 15 [Link](https://www.oed.com/discover/introduction-to-indian-english/)

 > The Oxford English Dictionary (OED) is a comprehensive historical dictionary covering over 500,000 words and phrases in English. It provides detailed entries, word histories, and usage examples, along with resources like word lists and commentaries. The OED also features an AI search assistant for advanced queries and regularly updates its content with new and revised entries.

### 24. Springer Nature book on machine learning is full of made-up citations

 Score: 28 Comments: 6 [Link](https://retractionwatch.com/2025/06/30/springer-nature-book-on-machine-learning-is-full-of-made-up-citations/)

 > A Springer Nature book on machine learning, *Mastering Machine Learning: From Basics to Advanced*, contains numerous made-up citations, with two-thirds of checked references either nonexistent or containing major errors. The author, Govindakumar Madhavan, did not confirm or deny using AI but acknowledged challenges in detecting AI-generated content. Springer Nature stated it is investigating the issue but did not clarify editorial oversight. The case highlights growing concerns about AI-generated fake citations in academic publishing.

### 25. Taking over 60k spyware user accounts with SQL injection

 Score: 205 Comments: 61 [Link](https://ericdaigle.ca/posts/taking-over-60k-spyware-user-accounts/)

 > A researcher discovered a SQL injection vulnerability in the stalkerware service Catwatchful, exposing 62,000 user accounts with plaintext passwords. The flaw allowed full database access, revealing extensive surveillance capabilities. Despite reporting, the service briefly returned before being patched. The findings were published with journalist Zack Whittaker.

### 26. Show HN: OffChess – Offline chess puzzles app

 Score: 325 Comments: 143 [Link](https://offchess.com)

 > OffChess is an offline chess puzzle app with 100K+ rated puzzles, progress tracking, and customizable themes. Available on iOS and Android, it works without Wi-Fi. [Download links](https://offchess.com/) included.

### 27. Surfing on a Matchbox (1999)

 Score: 23 Comments: 8 [Link](http://news.bbc.co.uk/2/hi/science/nature/276762.stm)

 > Stanford University built the world's smallest web server, matchbox-sized, using standard components. It runs Linux and is part of a wearable computing project. Future versions may include voice recognition, and researchers are developing input methods like a digital sign language glove.

### 28. Dynamical origin of Theia, the last giant impactor on Earth

 Score: 87 Comments: 31 [Link](https://arxiv.org/abs/2507.01826)

 > This study explores the dynamical origin of Theia, the Moon-forming impactor on Earth, using simulations of terrestrial planet formation. It suggests that Theia likely originated from scattered carbonaceous material, matching cosmochemical constraints. The simulations indicate a 50% chance Theia was a carbonaceous object, validating previous theories. The findings align with Earth's late accretion of carbonaceous material and the Moon's formation timeline. The research supports a hybrid scenario where Theia could be either a pure carbonaceous embryo or a mixed object.

### 29. Where can I see Hokusai's Great Wave today?

 Score: 66 Comments: 53 [Link](https://greatwavetoday.com/)

 > Hokusai's *Great Wave* can currently be seen in Italy (Musei Civici, Treviso) and France (Musée d’histoire, Nantes) until 2025. Other locations include museums in Trieste, Verona, and the US. Many institutions temporarily store it for preservation. The site tracks its availability and welcomes updates.

### 30. PHP 8.5 alpha 1 is available for download

 Score: 7 Comments: 1 comment [Link](https://www.php.net/archive/2025.php)

 > The article summarizes PHP-related news from 2025, including the release of PHP 8.5.0 Alpha 1, security updates for PHP 8.3, 8.2, 8.1, and 8.4, and announcements for upcoming PHP conferences like CakeFest, Longhorn PHP, and PHP Tek. It also mentions a security audit of PHP Core and PHP's 30th-anniversary celebration at PHPverse.

