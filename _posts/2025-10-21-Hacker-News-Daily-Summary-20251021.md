Updated at 2025-10-21 17:10:39 (UTC+8)

### 1. Language Support for Marginalia Search

 Score: 55 Comments: 6 [Link](https://www.marginalia.nu/log/a_126_multilingual/)

 > Marginalia Search has added experimental support for German, French, and Swedish, moving beyond its original English-only design. This required significant changes to its language processing pipeline, including new stemming and part-of-speech tagging logic for each language. The search engine now uses separate, language-specific indexes to maintain performance and accuracy. However, the current index for these new languages is very small, limiting search recall. The team is working to grow these indexes by improving its domain discovery process.

### 2. AWS multiple services outage in us-east-1

 Score: 1925 Comments: 1889 [Link](https://health.aws.amazon.com/health/status?ts=20251020)

 > On October 19-20, 2025, AWS experienced a major outage in its US-EAST-1 Region due to DNS resolution issues for DynamoDB endpoints. This triggered cascading failures affecting EC2 instance launches, network load balancers, and services like Lambda and SQS. AWS implemented throttling measures and worked through backlogs during recovery. Full service restoration was achieved by 3:01 PM PDT on October 20, though some backlogs continued processing.

### 3. Practical Scheme

 Score: 30 Comments: 18 [Link](https://practical-scheme.net/index.html#docs)

 > This website provides practical Scheme programming tools and libraries for systems engineers and programmers to handle daily tasks like file parsing, report generation, and GUI wrappers. It features the Gauche Scheme implementation, various applications like WiLiKi (a wiki engine), and extensions including OpenGL and GTK2 bindings. The site also contains technical documents and links to other Scheme resources. The author shares these tools to make their own work more efficient while hoping others find them useful.

### 4. Show HN: I'm rewriting a web server written in Rust for speed and ease of use

 Score: 11 Comments: 3 [Link](https://ferron.sh/)

 > Ferron is a modern web server designed for speed, security, and ease of use. It features automatic TLS certificate management, simple configuration, and memory-safe architecture. Ferron aims to solve issues with complex configurations and security vulnerabilities found in traditional servers like Apache and NGINX. It offers high performance and easy setup for sysadmins and developers.

### 5. A laser pointer at 2B FPS [video]

 Score: 408 Comments: 73 [Link](https://www.youtube.com/watch?v=o4TdHrMi6do)

 > This appears to be the footer section of the YouTube website. It contains various links to information about the company, its policies, and resources for creators and developers. The content includes sections for legal terms, privacy policies, and advertising. It also shows the copyright notice for Google LLC as of 2025.

### 6. Pasta/80 is a simple Pascal cross compiler targeting the Z80 microprocessor

 Score: 6 Comments: 2 [Link](https://github.com/pleumann/pasta80)

 > PASTA/80 is a Turbo Pascal 3.0-compatible cross compiler that generates machine code for Z80-based systems. It targets classic platforms including CP/M and various ZX Spectrum models (48K/128K/Next). The compiler uses a single-pass recursive-descent approach for fast compilation, though it prioritizes speed over code optimization efficiency. It supports most Turbo Pascal 3.0 language features while adding some modern enhancements.

### 7. Show HN: I'm making a detective game built on Wikipedia

 Score: 88 Comments: 17 [Link](https://detective.wiki/)

 > Detective Wiki is an online encyclopedia focused on detective-related topics. It appears to be a cached version of the original webpage. The content suggests it serves as a knowledge base for information pertaining to detectives and their work.

### 8. Bare Metal (The Emacs Essay)

 Score: 26 Comments: 3 [Link](https://waxbanks.wordpress.com/2025/08/01/bare-metal-the-emacs-essay/)

 > This essay presents Emacs as more than just a text editor, describing it as an "embodied philosophy" of freedom and user empowerment. It argues that Emacs's unique ability to be introspected and modified at runtime grants users unparalleled control over their tools, contrasting this with modern "walled garden" software. The author connects this to broader themes of magic, autonomy, and the liberatory potential of mastering complex systems. Ultimately, Emacs is framed as a tool for self-knowledge and imaginative transformation, representing a bet on a future of user freedom that never came to pass.

### 9. Alibaba Cloud says it cut Nvidia AI GPU use by 82% with new pooling system

 Score: 423 Comments: 265 [Link](https://www.tomshardware.com/tech-industry/semiconductors/alibaba-says-new-pooling-system-cut-nvidia-gpu-use-by-82-percent)

 > Access to Tom's Hardware has been blocked until October 21, 2025. This security measure was implemented due to suspected DDoS attack activity originating from the site's Intel Arc A380 review page. The block prevents anonymous access to protect the service from further abuse.

### 10. Production RAG: what I learned from processing 5M+ documents

 Score: 402 Comments: 95 [Link](https://blog.abdellatif.io/production-rag-processing-5m-documents)

 > The author processed over 5 million documents to build production RAG systems. Key improvements included using query generation to expand search context, implementing rerankers to significantly improve chunk selection, and developing custom chunking strategies. Other impactful changes were adding metadata to LLM context and routing non-RAG queries to different systems. These optimizations were compiled into an open-source project called agentset.

### 11. The Tyrrany of Literacy. On oral tradition and what is lost

 Score: 10 Comments: 5 [Link](https://languagelog.ldc.upenn.edu/nll/?p=71545)

 > This article critiques "the tyranny of literacy"—the misconception that literate societies are superior to oral ones. It argues that oral traditions can preserve complex knowledge across millennia, using examples like Indigenous stories accurately describing geological events from 7,700 years ago. The piece suggests modern technology may weaken memory skills that oral cultures cultivated, and highlights how pre-literate societies like ancient India maintained vast knowledge through meticulous oral transmission.

### 12. BERT is just a single text diffusion step

 Score: 393 Comments: 94 [Link](https://nathan.rs/posts/roberta-diffusion/)

 > This article demonstrates that BERT's masked language modeling is essentially a single step in a text diffusion process. By fine-tuning RoBERTa with variable masking rates and implementing iterative denoising, the author successfully repurposed the encoder model for text generation. The experiment shows surprisingly coherent outputs, proving that BERT-style models can function as basic diffusion models when trained with multiple masking probabilities rather than a fixed rate.

### 13. When Compiler Optimizations Hurt Performance

 Score: 40 Comments: 8 [Link](https://nemanjatrifunovic.substack.com/p/when-compiler-optimizations-hurt)

 > A developer discovered that compiler optimizations can sometimes hurt performance when benchmarking UTF-8 sequence length calculations. The "naive" branching approach processed over 2000 MB/s, while a hardware-assisted method using `std::countl_one` with a compiler-generated lookup table only achieved ~450 MB/s. Disabling jump tables with `-fno-jump-tables` in Clang restored performance by forcing branch instructions instead of table lookups. This shows that compiler optimizations like jump tables are not always beneficial and can introduce unexpected performance penalties.

### 14. My trick for getting consistent classification from LLMs

 Score: 191 Comments: 39 [Link](https://verdik.substack.com/p/how-to-get-consistent-classification)

 > This article addresses the problem of inconsistent classification labels generated by LLMs when working with unconstrained label sets. The author proposes using vector embeddings to cluster semantically similar but lexicographically different labels, then applying a disjoint union set algorithm to create consistent root labels. This approach becomes increasingly cost-effective and faster than pure LLM classification at scale, achieving 94% cache hits after processing 10,000 tweets. The method is implemented in an open-source Golang package called "consistent-classifier."

### 15. Claude Code on the web

 Score: 465 Comments: 287 [Link](https://www.anthropic.com/news/claude-code-on-the-web)

 > Anthropic has launched Claude Code on the web, a beta feature allowing users to delegate coding tasks directly from their browser. It enables parallel task execution on Anthropic's cloud infrastructure with isolated sandbox environments for security. Users can connect GitHub repositories, track progress in real-time, and automatically generate pull requests. This web interface complements existing workflows and is now available for Pro and Max users.

### 16. I made a small LED panel

 Score: 74 Comments: 18 [Link](https://www.stavros.io/posts/really-small-led-panel/)

 > The author created a small LED panel using an 8x8 WS2812 LED matrix and an ESP8266 microcontroller running WLED software. To diffuse the light, they 3D-printed a white PLA square and a box to hold it 10mm above the LEDs. The microcontroller was attached externally to the back of the box rather than housed inside it. The resulting compact LED panel successfully displays colorful patterns with good light diffusion.

### 17. Show HN: I created a cross-platform GUI for the JJ VCS (Git compatible)

 Score: 112 Comments: 28 [Link](https://judojj.com)

 > Judo is a full-featured GUI for the JJ version control system that also works with Git repositories. It enables users to restore repositories to any point in time using an operation log with undo/redo capabilities. The interface supports viewing combined diffs, applying or reverting code changes, and drag-and-drop rebasing. Additional features include custom commit selection queries, advanced operations like squashing, and bookmark management.

### 18. Today is when the Amazon brain drain sent AWS down the spout

 Score: 620 Comments: 273 [Link](https://www.theregister.com/2025/10/20/aws_outage_amazon_brain_drain_corey_quinn/)

 > A major AWS outage on October 20, 2025, caused widespread internet disruptions due to DNS resolution failures for the DynamoDB service in the US-EAST-1 region. The article argues this incident resulted from a "brain drain" of senior engineers who possessed critical institutional knowledge. Citing layoffs and high attrition rates at Amazon, the author contends that the loss of experienced staff has weakened AWS's ability to quickly diagnose and resolve complex system failures. This outage is presented as a tipping point demonstrating the consequences of depleted engineering expertise.

### 19. ChkTag: x86 Memory Safety

 Score: 241 Comments: 123 [Link](https://community.intel.com/t5/Blogs/Tech-Innovation/open-intel/ChkTag-x86-Memory-Safety/post/1721490)

 > Intel and AMD are collaborating to develop ChkTag, a unified x86 memory tagging instruction set architecture. This hardware-accelerated technology aims to detect memory safety violations like buffer overflows and use-after-free errors. It is designed to protect applications, operating systems, and firmware, complementing existing x86 security features.

### 20. Old Computer Challenge – Modern Web for the ZX Spectrum

 Score: 42 Comments: 8 [Link](https://0x00.cl/blog/2025/occ-2025/)

 > The author created a web browsing experience for the ZX Spectrum as part of the Old Computer Challenge. Using the Spectrum's limited 256x192 resolution and 8-color palette, they designed simplified versions of Google and Hacker News. Navigation was implemented through single-key commands due to hardware constraints. This project demonstrates how modern websites could function on 1980s computer hardware.

### 21. How to stop Linux threads cleanly

 Score: 207 Comments: 70 [Link](https://mazzo.li/posts/stopping-linux-threads.html)

 > This article explores methods to cleanly stop Linux threads while allowing proper cleanup. The simplest approach uses a flag-checking loop, but this requires cooperative code. Signals can interrupt blocking calls but risk resource leaks if not handled carefully. Thread cancellation via pthread_cancel is problematic due to potential unsafe unwinding. The article concludes that while there's no perfect solution, combining signal handling with atomic flag checks or using newer features like rseq can provide safer thread termination.

### 22. Results from blood test for 50 cancers

 Score: 99 Comments: 51 [Link](https://www.bbc.com/news/articles/c205g21n1zzo)

 > The Galleri blood test can detect over 50 types of cancer by identifying cancerous DNA fragments in the blood. In a trial of 25,000 people, it detected cancer in 62% of those who tested positive, with over half found at an early stage. Crucially, three-quarters of the cancers detected currently lack standard screening programs. While results are promising for earlier diagnosis, scientists say more evidence is needed to confirm if the test actually reduces cancer deaths.

### 23. Optical diffraction patterns made with a MOPA laser engraving machine [video]

 Score: 138 Comments: 27 [Link](https://www.youtube.com/watch?v=RsGHr7dXLuI)

 > This video demonstrates using a MOPA laser engraving machine to create optical diffraction patterns and hologram-like effects on stainless steel. The creator makes diffraction gratings and multi-color images by controlling laser parameters to produce different grating pitches and angles. These patterns are examined with an electron microscope and used to create images composed of diffraction grating "pixels." The technique produces colorful optical effects that resemble holograms through precise laser surface structuring.

### 24. Space Elevator

 Score: 1590 Comments: 368 [Link](https://neal.fun/space-elevator/)

 > This interactive article takes readers on a visual journey through Earth's atmosphere via a hypothetical space elevator. It describes various atmospheric layers and highlights altitude records of aircraft, animals, and natural phenomena encountered during the ascent. The content explains how temperature and air pressure change at different heights while showcasing historical aviation milestones. Ultimately, it presents space elevators as a potential future technology for space travel, despite current engineering challenges.

### 25. Code from MIT's 1986 SICP video lectures

 Score: 114 Comments: 14 [Link](https://github.com/felipap/sicp-code)

 > This GitHub repository contains digitized code from MIT's 1986 SICP (Structure and Interpretation of Computer Programs) video lectures. The project aims to make the code from these classic computer science lectures readable and accessible in digital format. It includes transcriptions of code shown on slides, boards, and terminals during the lectures. The repository is maintained under an MIT license and welcomes contributions for error corrections.

### 26. TernFS – an exabyte scale, multi-region distributed filesystem

 Score: 116 Comments: 21 [Link](https://www.xtxmarkets.com/tech/2025-ternfs/#posix-shaped)

 > XTX Markets developed TernFS, an exabyte-scale distributed filesystem, to meet their growing storage needs for algorithmic trading and machine learning workloads. After outgrowing existing solutions, they built a system that scales to trillions of files across multiple regions with no single point of failure. TernFS features immutable files, redundant storage using Reed-Solomon coding, and supports both custom APIs and a Linux kernel module. The company has open-sourced TernFS after successfully migrating their production storage to it.

### 27. 60k kids have avoided peanut allergies due to 2015 advice, study finds

 Score: 144 Comments: 126 [Link](https://www.cbsnews.com/news/peanut-allergies-60000-kids-avoided-2015-advice/)

 > A new study published in Pediatrics found that approximately 60,000 children in the U.S. have avoided developing peanut allergies due to landmark 2015 medical advice. This guidance, which reversed previous recommendations, urged parents to introduce peanut products to infants as early as 4 to 6 months old. The research showed peanut allergies in children aged 0-3 declined by more than 40% following the updated guidelines. This represents a significant public health success in preventing food allergies.

### 28. A magnetic field orientation that changes the fundamental design of motors

 Score: 41 Comments: 9 [Link](https://www.paranetics.com/copy-of-home)

 > ParaNetics has developed a novel ParaNetic electric motor using a unique magnetic field configuration. Unlike traditional magnets with single poles, their design creates a three-pole structure that enables simultaneous use of both sides of magnetic fields. This innovation reportedly increases torque and efficiency while reducing heat generation. Potential applications include drones, submersibles, and electric aircraft propulsion systems.

### 29. The scariest "user support" email I've received

 Score: 245 Comments: 186 [Link](https://www.devas.life/the-scariest-user-support-email-ive-ever-received/)

 > A developer received a phishing email disguised as a user support request about a cookie consent issue. The attacker sent a fake Google Drive link that appeared to contain a screenshot but actually led to a malicious site. This site prompted the developer to run a dangerous terminal command that would download and execute a harmful script. The incident highlights how AI-powered phishing attacks are becoming increasingly sophisticated and convincing.

### 30. x86-64 Playground – An online assembly editor and GDB-like debugger

 Score: 137 Comments: 16 [Link](https://x64.halb.it/)

 > X86-64 Playground is a web-based tool for writing, compiling, and debugging x86-64 assembly code directly in your browser. It supports multiple assemblers and allows step-by-step execution with GDB-like inspection of registers and memory. The app runs entirely client-side using the Blink Emulator, ensuring code never leaves your browser and works offline. It's designed for learning assembly and binary exploitation, with a responsive interface for both desktop and mobile use.

