Updated at 2025-01-21 18:08:52 (UTC+8)

### 1. Kimi K1.5: Scaling Reinforcement Learning with LLMs

 Score: 37 Comments: 1 comment [Link](https://github.com/MoonshotAI/Kimi-k1.5)

 > Kimi k1.5 is a multi-modal large language model (LLM) developed by MoonshotAI, leveraging reinforcement learning (RL) to achieve state-of-the-art performance across various benchmarks. It excels in both short and long-chain-of-thought (CoT) reasoning, outperforming models like GPT-4o and Claude Sonnet 3.5 by significant margins. Key innovations include long context scaling, improved policy optimization, and a simplistic RL framework, enabling strong performance without complex techniques like Monte Carlo tree search. The model is trained on text and vision data, offering multi-modal reasoning capabilities.

### 2. Context should go away for Go 2

 Score: 37 Comments: 13 [Link](https://faiface.github.io/post/context-should-go-away-go2/)

 > The article criticizes Go's `context` package, arguing that it spreads like a "virus" by requiring context parameters in many functions, even when unnecessary. While useful for cancelation in server applications, it complicates code for general-purpose use and introduces inefficiencies. The author suggests that Go 2 should address cancelation directly in the language, offering a simpler, optional, and more elegant solution. The post highlights the need for a language-level fix to improve Go's usability.

### 3. Perl Weekly Issue #704 – Perl Podcast

 Score: 8 Comments: 1 comment [Link](https://perlweekly.com/archive/704.html)

 > The Perl Weekly Issue #704 highlights the revival of Perl podcasts with Philippe Bruhat's "The Underbar," announces the German Perl/Raku Workshop in Munich, and celebrates The Weekly Challenge's continued sponsorship. It also introduces new Perl modules, shares articles on MIDI music creation and geolocation data processing, and recaps recent Weekly Challenge tasks. The newsletter encourages participation in upcoming events and contributions to the Perl community.

### 4. Framework Fatigue: The Real Reason Developers Get Angry About New Tech

 Score: 13 Comments: 12 [Link](https://blog.raed.dev/posts/framework-fatigue-the-real-reason-developers-get-angry-about-new-tech)

 > The article discusses "framework fatigue," where developers feel overwhelmed by the constant influx of new JavaScript frameworks, each claiming to be faster and better. This leads to frustration, as developers worry about staying employable and keeping up with ever-changing job requirements. The emotional reactions stem from the fear that today's optional tech will become tomorrow's necessity, making employability a key concern. Understanding this perspective can lead to more productive discussions about industry evolution.

### 5. DeepSeek-R1

 Score: 1351 Comments: 484 [Link](https://github.com/deepseek-ai/DeepSeek-R1)

 > DeepSeek-R1 introduces advanced reasoning models, DeepSeek-R1-Zero and DeepSeek-R1, trained using large-scale reinforcement learning (RL) without supervised fine-tuning (SFT). DeepSeek-R1-Zero exhibits strong reasoning capabilities but faces issues like repetition and poor readability, which are addressed in DeepSeek-R1 by incorporating cold-start data. The models achieve state-of-the-art performance in math, code, and reasoning tasks, with open-sourced versions and distilled smaller models available for research. The project also provides a chat interface and API for interaction.

### 6. Reverse engineering Call of Duty anti-cheat

 Score: 310 Comments: 95 [Link](https://ssno.cc/posts/reversing-tac-1-4-2025/)

 > The article details a reverse engineering analysis of the Treyarch Anti-Cheat (TAC) system used in *Call of Duty: Black Ops Cold War*. It explores various anti-cheat mechanisms, including Arxan obfuscation, API hook detection, debug register monitoring, and custom syscall stubs. The author also discusses techniques to bypass these protections, such as exception handling and memory scanning, while highlighting TAC's advanced features like encrypted pointers and runtime API lookups. The research provides insights into the anti-cheat's detection methods and its reliance on user-mode protections without kernel components.

### 7. Mixxx: GPL DJ Software

 Score: 496 Comments: 99 [Link](https://mixxx.org/)

 > Mixxx is a free, open-source DJ software that offers powerful features for DJs of all levels, including BPM and key detection, DJ controller support, sound effects, and vinyl record control. It is community-driven, with no corporate backing, and is designed to support creative live mixing with digital music files. The software is regularly updated, with recent releases like Mixxx 2.5 and 2.4.2, and has received accolades such as being the #1 Top Free Mac App Worldwide in 2011.

### 8. 417-megapixel Andromeda galaxy panorama took over a decade to make

 Score: 166 Comments: 54 [Link](https://petapixel.com/2025/01/16/417-megapixel-andromeda-galaxy-panorama-took-over-a-decade-to-make/)

 > Astronomers have created a 417-megapixel panorama of the Andromeda Galaxy using over 600 images from the Hubble Space Telescope, a project that took over a decade to complete. The mosaic, featuring 200 million stars, provides unprecedented detail of Andromeda's structure and history, aiding in understanding galaxy evolution. This effort highlights Hubble's continued importance in astronomy, despite newer telescopes like James Webb. The project also sets the stage for future observations with the Nancy Grace Roman Space Telescope.

### 9. Regency Sex Ed: How did women in 19th C. Europe learn about the birds and bees?

 Score: 24 Comments: discuss [Link](https://www.historynewsnetwork.org/article/regency-sex-ed)

 > The article explores the portrayal of sexual education in Regency-era England, inspired by a scene from Netflix’s *Bridgerton*. It highlights the historical context of sexual knowledge among women, referencing real 18th- and 19th-century texts like *Aristotle’s Masterpiece* and *Every Woman’s Book*. The author, a historical romance novelist, emphasizes that women of the time were not as sexually ignorant as often depicted, and draws parallels between historical and modern struggles for sexual education and agency.

### 10. I'm Peter Roberts, immigration attorney, who does work for YC and startups. AMA

 Score: 291 Comments: 325 [Link](item?id=42770125)

 > The article is inaccessible due to a client-side blocking error (ERR_BLOCKED_BY_CLIENT) when attempting to access the URL http://item/?id=42770125, resulting in a 422 status code.

### 11. Official DeepSeek R1 Now on Ollama

 Score: 154 Comments: 46 [Link](https://ollama.com/library/deepseek-r1)

 > The article introduces DeepSeek's first-generation reasoning models, **deepseek-r1**, which offer performance comparable to OpenAI-o1 across math, code, and reasoning tasks. It provides various model sizes (1.5B to 671B parameters) and download links, along with instructions for running them using Ollama. The models are open-source under the MIT License.

### 12. Unlink vs. DEL – A deep dive into how it works internally in Redis

 Score: 5 Comments: 1 comment [Link](https://www.pankajtanwar.in/blog/unlink-vs-del-a-deep-dive-into-how-it-works-internally-in-redis)

 > The article explores the differences between Redis' `DEL` and `UNLINK` commands, focusing on their internal implementations. While `DEL` is synchronous and blocks operations, `UNLINK` is designed to be non-blocking by calculating the deallocation cost of an object. If the cost is low (below 64), it behaves like `DEL`; otherwise, it queues the object for background deletion. The article dives into Redis' source code to explain how these commands work under the hood, highlighting key mechanisms like two-phase linking and asynchronous deletion.

### 13. SRCL: Open-source React project to build web apps with terminal aesthetics

 Score: 128 Comments: 14 [Link](https://www.sacred.computer)

 > SRCL is an open-source React component and style repository designed for building web and desktop applications with a terminal-inspired aesthetic. It includes a variety of UI components like action bars, accordions, buttons, and data tables, all styled with a monospace font. The library also offers hosting options and studio services for application development.

### 14. Ancient Celtic tribe had women at its social center

 Score: 4 Comments: discuss [Link](https://www.npr.org/2025/01/15/nx-s1-5258236/ancient-celtic-tribe-had-women-at-its-social-center)

 > A study of ancient DNA from an Iron Age Celtic tribe in Britain reveals that women were central to their social networks, with communities organized around matrilocal practices where men moved to join their wives' families. This contrasts with earlier patrilocal societies and suggests women held significant social and political influence. The findings, published in *Nature*, highlight a rare pattern in European prehistory and challenge assumptions about gender roles in ancient societies.

### 15. Statement on planned protests during the upcoming FOSDEM 2025

 Score: 36 Comments: 14 [Link](https://fosdem.org/2025/news/2025-01-16-protests/)

 > FOSDEM 2025 organizers addressed planned protests over a controversial talk, clarifying that sponsorship does not influence talk selection. They emphasized their long-standing policy of allowing peaceful protests, provided they do not disrupt the event, and encouraged protest organizers to contact them in advance for safety coordination.

### 16. More than 40% of postdocs leave academia, study reveals

 Score: 56 Comments: 51 [Link](https://www.nature.com/articles/d41586-025-00142-y)

 > A study published in *Proceedings of the National Academy of Sciences* reveals that over 40% of postdoctoral researchers leave academia, often due to limited faculty positions. Those who secure faculty roles tend to have highly cited papers, change research topics between their PhD and postdoc, or move abroad. The study analyzed 45,500 researchers' careers over 25 years, highlighting the critical role of postdoctoral training in academic success.

### 17. The most viewed articles of 2024

 Score: 11 Comments: 3 [Link](https://en.wikipedia.org/wiki/Wikipedia:Wikipedia_Signpost/2025-01-15/Traffic_report)

 > The 2024 Wikipedia Traffic Report highlights the most-viewed articles of the year, dominated by the 2024 U.S. presidential election, which saw Donald Trump and JD Vance win, and Kamala Harris lose. Other top topics included the deaths of notable figures, popular films like *Deadpool & Wolverine* and *Dune: Part Two*, and global events such as the 2024 Summer Olympics and the Israel-Hamas war. Taylor Swift, ChatGPT, and Elon Musk also remained highly searched, reflecting ongoing cultural and technological trends.

### 18. Using eSIMs with devices that only have a physical SIM slot via a 9eSIM SIM car

 Score: 326 Comments: 191 [Link](https://neilzone.co.uk/2025/01/using-esims-with-devices-that-only-have-a-physical-sim-slot-via-a-9esim-sim-card-with-android-and-linux/)

 > The article explains how to use eSIMs on devices with only physical SIM slots by using a 9eSIM SIM card, which allows provisioning and switching between eSIM profiles. The author details the setup process on Android and Linux, including using a smartcard reader and software tools like `lpac` and EasyLPAC. Test eSIM profiles are used for experimentation, and the process is demonstrated with a LycaMobile eSIM on a Linux laptop. The solution enables eSIM functionality on devices without native eSIM support.

### 19. Guitar chord karaoke with Vamp, Chordino, and FFmpeg (2022)

 Score: 91 Comments: 22 [Link](https://dylanbeattie.net/2022/09/19/the-road-to-guitaraoke-part-1-vamp-chordino-imagesharp-ffmpeg.html)

 > The article describes the development of "Guitaraoke," a karaoke event where participants can play guitar or bass alongside singing. The author explores using tools like Vamp, Chordino, ImageSharp, and ffmpeg to automatically detect and overlay guitar chords onto karaoke videos. The process involves extracting chord data from audio, rendering it into video frames, and compositing it onto the original video. The goal is to automate the workflow for creating chord-accompanied karaoke tracks.

### 20. The QUIC API OpenSSL will not provide [2021]

 Score: 9 Comments: 2 [Link](https://daniel.haxx.se/blog/2021/10/25/the-quic-api-openssl-will-not-provide/)

 > OpenSSL has decided not to provide a QUIC API, despite the growing adoption of HTTP/3 over QUIC. Instead, OpenSSL plans to develop its own QUIC stack, which will take years to complete. This decision has disappointed the QUIC community, as existing QUIC libraries will have to rely on alternatives like quictls, an OpenSSL fork with QUIC support. The closure of the long-awaited PR8797 marks a setback for QUIC implementation progress.

### 21. Celestial Navigation for Drones

 Score: 174 Comments: 103 [Link](https://www.mdpi.com/2504-446X/8/11/652)

 > This study presents a low-cost, lightweight strapdown celestial navigation system for UAVs in GNSS-denied environments. By performing a full rotation of compass heading and averaging position estimates, the system reduces biases and achieves position accuracy within 4 km. The method is robust against initial conditions and does not require precise camera alignment, making it suitable for long-endurance UAVs operating in contested environments.

### 22. I am (not) a failure: Lessons learned from six failed startup attempts

 Score: 387 Comments: 244 [Link](http://blog.rongarret.info/2025/01/i-am-not-failure-lessons-learned-from.html)

 > The author reflects on six and a half failed startup attempts and an unsuccessful academic career, sharing lessons learned from each failure. Despite these setbacks, the author emphasizes personal growth and resilience, ultimately finding happiness and success in life. Key lessons include the importance of execution over ideas, the challenges of disrupting established industries, and the value of learning from repeated failures.

### 23. Where do those undergraduate divisibility problems come from?

 Score: 128 Comments: 40 [Link](https://grossack.site/2025/01/16/undergrad-divisibility-problems.html)

 > This blog post explores the origin of undergraduate divisibility problems, such as proving that a polynomial like \( n^6 + n^3 + 2n^2 + 2n \) is always divisible by 6. The author explains how Pólya-Redfield counting, a combinatorial method involving group actions, can be used to generate such polynomials by counting orbits of colorings under group actions. Examples, like counting bracelets or tic-tac-toe board configurations, illustrate how this method ensures divisibility. The post also poses a conjecture about whether all such polynomials arise from Pólya-Redfield counting.

### 24. Show HN: Personalized Duolingo (kind of) for vocabulary building

 Score: 114 Comments: 28 [Link](https://github.com/baturyilmaz/wordpecker-app)

 > WordPecker is a personalized language-learning app that combines Duolingo-style lessons with custom vocabulary lists. Users can add words from books, articles, or videos, and the app provides definitions and interactive quizzes. It aims to make language learning more efficient by tying vocabulary to real-world contexts. The app is built with React.js, Express.js, and Supabase, and contributions are welcome.

### 25. ROCm Device Support Wishlist

 Score: 158 Comments: 117 [Link](https://github.com/ROCm/ROCm/discussions/4276)

 > The discussion highlights user frustrations with AMD's ROCm support, particularly the lack of consistent and long-term support for consumer GPUs, APUs, and older hardware. Users emphasize the importance of broad device compatibility, especially for AI/ML tasks, and call for better Windows support, APU integration, and architecture-wide (e.g., RDNA2/3) rather than model-specific support. Many users compare AMD's approach unfavorably to NVIDIA's CUDA ecosystem, which offers extensive and stable support across a wide range of hardware.

### 26. Zork: The Great Inner Workings (2020)

 Score: 166 Comments: 60 [Link](https://medium.com/swlh/zork-the-great-inner-workings-b68012952bdc)

 > The article explores the inner workings of *Zork*, a classic text-based adventure game, delving into its design, programming, and the innovative techniques used to create its immersive world. It highlights how the game's parser and world-building set a foundation for future interactive fiction.

### 27. An astronomical view of Ancient Egyptian star clocks (2021)

 Score: 26 Comments: 8 [Link](https://storymaps.arcgis.com/stories/eea3fbc9c05b40948563ffd0ccfab59d)

 > The article "In Search of Lost Time" explores the concept of time through a narrative that intertwines personal reflections and historical events. It uses ArcGIS StoryMaps to visually and interactively present the journey of rediscovering lost moments and memories, blending geography with storytelling to create a unique experience.

### 28. YC X25, the spring 2025 batch

 Score: 49 Comments: 33 [Link](https://www.ycombinator.com/blog/announcing-yc-x25/)

 > Y Combinator has announced its first-ever Spring batch, YC X25, as part of its new four-batch-per-year schedule (Winter, Spring, Summer, Fall). The Spring batch, abbreviated as "X25," will run from April to June 2025, with applications open until February 11, 2025. This change aims to accommodate more founders and accelerate funding for startups, especially in the rapidly evolving AI landscape. The batch will conclude with an in-person demo day.

### 29. Flag drawing with Turtle

 Score: 23 Comments: 4 [Link](https://jtanx.github.io/2018/12/28/turtle-flag-drawing/)

 > The article discusses the author's experience with drawing flags using the Turtle graphics library in Python, inspired by a university programming task. Initially, the task involved drawing flags with limited commands, but the author later developed a parser to interpret SVG files as Turtle commands, enabling the drawing of complex flags like the Flag of Wales. The project evolved over time, with improvements to handle transformations, styling, and curve commands, though some issues remain unresolved. The author shares the code and results of various flags, highlighting challenges and modifications needed for accurate rendering.

### 30. Optical Fresnel zone plate flat lens: colored photoresist through I-line stepper

 Score: 53 Comments: 10 [Link](https://www.nature.com/articles/s41377-024-01725-6)

 > Researchers developed flat Fresnel zone plate (FZP) lenses using colored photoresist and an i-line stepper, enabling simple, large-area fabrication without complex post-processing. These lenses achieved sub-micrometer focusing and imaging, with a focusing efficiency of 7.2%, demonstrating potential for mass production and applications in visible light optics.

