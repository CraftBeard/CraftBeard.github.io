Updated at 2025-01-20 18:07:03 (UTC+8)

### 1. Reverse Engineering Bambu Connect

 Score: 303 Comments: 155 [Link](https://wiki.rossmanngroup.com/wiki/Reverse_Engineering_Bambu_Connect)

 > The article details the process of reverse engineering the Bambu Connect Electron app, which uses security through obscurity. It explains how to extract and decrypt the app's private key and certificates by analyzing the app's files, using tools like Ghidra and asarfix, and implementing RC4 decryption in Python. The goal is to reveal the obfuscated secrets stored in the app.

### 2. TypeScript enums: use cases and alternatives

 Score: 4 Comments: discuss [Link](https://2ality.com/2025/01/typescript-enum-patterns.html)

 > This article explores TypeScript enums, their use cases, and alternatives. It explains how enums work, their limitations, and scenarios where they are useful, such as namespaces for constants or custom types. The article also discusses alternatives like object literals, string literal unions, and enum classes, providing recommendations based on specific use cases and performance considerations.

### 3. UK's hardware talent is being wasted

 Score: 288 Comments: 422 [Link](https://josef.cn/blog/uk-talent)

 > The UK's elite hardware engineering talent from institutions like Imperial, Oxford, and Cambridge is being underutilized, with graduates often settling for low-paying jobs or switching to finance/consulting due to lack of opportunities and investment in hardware innovation. This misallocation of talent stifles national innovation, economic growth, and geopolitical competitiveness. The article argues for urgent investment in ambitious hardware startups to harness this untapped potential and position the UK as a global hardware leader.

### 4. TikTok says it is restoring service for U.S. users

 Score: 623 Comments: 1897 [Link](https://www.nbcnews.com/tech/tech-news/tiktok-says-restoring-service-us-users-rcna188320)

 > TikTok announced it is restoring service for U.S. users after President-elect Donald Trump provided assurances to its service providers, thanking him for clarity and support. The app had been blocked ahead of a ban, but Trump vowed to issue an executive order to extend the deadline and allow TikTok to remain operational. TikTok emphasized its commitment to working with Trump on a long-term solution to keep the platform in the U.S.

### 5. Bunkers in Albania

 Score: 116 Comments: 74 [Link](https://en.wikipedia.org/wiki/Bunkers_in_Albania)

 > During the Hoxhaist era (1967–1986), Albania built over 750,000 concrete military bunkers under Enver Hoxha's leadership to defend against perceived foreign threats. These bunkers, never used for their intended purpose, became a symbol of isolationism and drained Albania's resources. After the fall of communism, most were abandoned, though some have been repurposed for housing, cafés, or tourism. Today, they remain a prominent feature of Albania's landscape and a reminder of its Cold War history.

### 6. Byzantine-Sassanian War (602-628 CE): The Last Great War of Antiquity

 Score: 9 Comments: discuss [Link](https://www.thecollector.com/byzantine-sassanian-war/)

 > The Byzantine-Sassanian War (602-628 CE) was a devastating conflict between the Byzantine Empire and the Sassanian Empire, marked by initial Sassanian victories and the near-collapse of Byzantium. Emperor Heraclius' military and diplomatic efforts eventually led to a Byzantine resurgence, culminating in the decisive Battle of Nineveh. However, both empires were left exhausted, making them vulnerable to the rapid expansion of the Islamic Rashidun Caliphate. The war's legacy influenced religious dynamics, as persecuted minority groups became more receptive to Islam during the Arab Conquests.

### 7. It's time to make computing personal again

 Score: 498 Comments: 222 [Link](https://www.vintagecomputing.com/index.php/archives/3292/the-pc-is-dead-its-time-to-make-computing-personal-again)

 > The article argues that the personal computer era, once defined by user freedom and control, has been eroded by surveillance capitalism, DRM, and predatory tech practices. It critiques the shift from user-owned, repairable devices to locked-down, subscription-based models that prioritize corporate profits over individual liberty. The author calls for reforms, including privacy legislation, DRM reform, and right-to-repair laws, to reclaim personal computing and restore digital freedom.

### 8. Rhai: An embedded scripting language for Rust

 Score: 46 Comments: 15 [Link](https://github.com/rhaiscript/rhai)

 > Rhai is an embedded scripting language and evaluation engine for Rust, designed to safely and easily add scripting capabilities to applications. It features dynamic typing, efficient evaluation, tight integration with Rust, and support for various data types. Rhai is sandboxed, protected against malicious attacks, and offers customization options for language features and syntax. It is licensed under Apache 2.0 or MIT.

### 9. Blinkenlights

 Score: 12 Comments: 2 [Link](https://en.wikipedia.org/wiki/Blinkenlights)

 > Blinkenlights refer to diagnostic lights on the front panels of old mainframe computers, used to monitor internal processes. Originating from hacker humor, the term comes from a mock German warning sign. These lights became obsolete as computers became faster, but they remain as status indicators in modern hardware. The term has inspired various projects and retains nostalgic value in tech culture.

### 10. What does "supports DRM and may not be fully accessible" mean for SATA SDDs?

 Score: 100 Comments: 42 [Link](https://unix.stackexchange.com/questions/789838/what-does-supports-drm-functions-and-may-not-be-fully-accessible-mean-for-sata)

 > The article explains that the message "supports DRM functions and may not be fully accessible" in SATA SSDs refers to an ATA protocol extension allowing devices to respond differently based on requests signed by a trusted platform module, potentially limiting access. The "read cache: enabled, doesn't support DPO or FUA" message indicates the SSD has a read cache but lacks older techniques to bypass it, which are less relevant for SSDs. DRM here stands for Data Rights Management, not Digital Rights Management.

### 11. JTAG 'Hacking' the Original Xbox in 2023

 Score: 117 Comments: 6 [Link](https://blog.ret2.io/2023/08/09/jtag-hacking-the-original-xbox-2023/)

 > The article explores the process of hacking the original Xbox (2001) using Intel's x86 CPU JTAG interface, a method theorized but never fully realized in the past. By designing a custom CPU interposer PCB to access JTAG signals and using a vintage CodeTAP hardware debugger, the author successfully dumped the Xbox's secret bootrom and achieved full CPU debugging capabilities. This project, blending nostalgia and technical exploration, demonstrates the potential of hardware debugging for system introspection and preserves a piece of Xbox hacking history.

### 12. How do interruptions impact different software engineering activities

 Score: 87 Comments: 6 [Link](https://rdel.substack.com/p/rdel-75-how-do-interruptions-impact)

 > Interruptions significantly impact software engineers' productivity and stress, with effects varying by task type and interruption method. Research shows that in-person interruptions are less stressful physiologically but perceived as more stressful, while code writing is most affected by interruptions. Leaders should minimize high-dominance interruptions, protect focus time during code writing, and measure interruption impacts to improve team productivity.

### 13. Why is Git Autocorrect too fast for Formula One drivers?

 Score: 273 Comments: 155 [Link](https://blog.gitbutler.com/why-is-git-autocorrect-too-fast-for-formula-one-drivers/)

 > The article explains why Git's autocorrect feature, which waits 100ms before executing a corrected command, is too fast for even Formula One drivers to react. This behavior stems from a 2008 patch that introduced a decisecond-based delay, with `1` meaning 100ms. The author proposes a patch to interpret `1` as "immediate" instead, making it more user-friendly. The feature uses a modified Levenshtein distance algorithm to guess commands, and the article suggests setting `help.autocorrect` to "prompt" for better usability.

### 14. Chopstick sleeves as emissaries of Japanese typography and culture

 Score: 87 Comments: 11 [Link](https://letterformarchive.org/news/this-just-in-chopstick-sleeves-as-emissaries-of-japanese-typography-and-culture/)

 > This article explores the cultural and historical significance of Japanese chopstick sleeves, or *hashibukuro*, which originated in the Heian period and evolved into vernacular advertisements for shops and restaurants. The collection of over 500 sleeves, donated to the Letterform Archive, reflects Japanese typography, aesthetics, and national identity, including motifs like Mount Fuji and *origami*. The sleeves also highlight Japan's modernization, blending traditional and Western elements, and serve as ephemeral yet meaningful artifacts of Japanese culture.

### 15. Show HN: Terraform Provider for Inexpensive Switches

 Score: 10 Comments: discuss [Link](https://github.com/brennoo/terraform-provider-hrui)

 > The GitHub repository `terraform-provider-hrui` by brennoo is a Terraform provider for managing HRUI switches, including brands like Horaco, Sodola, and XikeStor. It uses the web UI of these switches and is compatible with firmware v1.9. The provider is licensed under MPL-2.0 and includes examples and documentation for getting started. Contributions are welcome, and the project has 8 stars and 0 forks as of the latest update.

### 16. CollectWise (YC F24) Is Hiring

 Score: None Comments: None [Link](https://www.ycombinator.com/companies/collectwise/jobs/miUmVns-founding-engineer)

 > CollectWise, a Y Combinator-backed startup, is seeking a Founding Engineer to help automate consumer debt collection using AI. The role offers $140K - $190K and 0.25% - 1.00% equity, with responsibilities including full-stack development, AI optimization, and shaping the company's future. Ideal candidates have experience with React JS, Node JS, Firebase, AWS, SQL, and GPT-4, and thrive in ambiguous, fast-paced environments. CollectWise aims to revolutionize debt recovery with AI agents that outperform human collectors.

### 17. I'll think twice before using GitHub Actions again

 Score: 28 Comments: 23 [Link](https://ninkovic.dev/blog/2025/think-twice-before-using-github-actions)

 > The author expresses dissatisfaction with GitHub Actions, particularly for large monorepo setups, citing issues with required checks, YAML complexity, lack of local development support, and GitHub's slow response to community feedback. They suggest exploring alternatives like GitLab, Jenkins, or Dagger for better CI/CD solutions.

### 18. Divers recover Phoenician shipwreck that sank 2.6k years ago off coast of Spain

 Score: 145 Comments: 55 [Link](https://www.smithsonianmag.com/smart-news/divers-recover-ancient-shipwreck-that-sank-2600-years-ago-off-the-coast-of-spain-180985778/)

 > Divers have recovered a 2,600-year-old Phoenician shipwreck, known as *Mazarrón II*, off the coast of Spain. Discovered in 1994, the 27-foot-long vessel was carrying lead ingots when it sank. After years of protection, shifting coastal conditions necessitated its removal. The ship will now undergo a four-year conservation process before being reassembled and displayed in a museum.

### 19. Using your Apple device as an access card in unsupported systems

 Score: 198 Comments: 79 [Link](https://github.com/kormax/apple-device-as-access-card)

 > This GitHub repository explains how to use an Apple device as an access card in systems that rely on UID-based authentication, which is typically unsupported. The solution involves using a specific Chinese transit card, "China T-Union," added to Apple Wallet, which stops UID randomization and allows the device to function like an access card. However, this method requires system owner approval and has limitations, such as the inability to control the UID. The guide also provides steps to acquire the T-Union card using AliPay.

### 20. FrontierMath was funded by OpenAI

 Score: 371 Comments: 117 [Link](https://www.lesswrong.com/posts/cu2E8wgmbdZbqeWqb/meemi-s-shortform)

 > The article discusses concerns about the lack of transparency regarding OpenAI's funding and involvement in the creation of the FrontierMath benchmark by Epoch AI. It highlights that many contributors were unaware of OpenAI's role, and there are worries about the potential misuse of the benchmark data for AI training, despite verbal agreements against it. The article calls for greater transparency and clearer communication about funding sources and data usage in future collaborations.

### 21. Two Hard Things (2009)

 Score: 42 Comments: 10 [Link](https://martinfowler.com/bliki/TwoHardThings.html)

 > The article humorously explores the adage, "There are only two hard things in Computer Science: cache invalidation and naming things," attributed to Phil Karlton. It includes various humorous riffs on the saying, such as adding "off-by-1 errors" or referencing distributed systems challenges. The author, Martin Fowler, traces the origin of the quote and acknowledges contributors who provided additional variations. The piece highlights the enduring relevance and humor of the original statement in the programming community.

### 22. Don't use Session – Round 2

 Score: 15 Comments: 3 [Link](https://soatok.blog/2025/01/20/session-round-2/)

 > The article is a follow-up to a previous blog post criticizing Session's cryptographic design. The author clarifies their earlier claims, provides a proof-of-concept for attacking Session's 128-bit Ed25519 seeds, and critiques Session's response to their original post. The author concludes that Session's design flaws, including insufficient entropy and lack of forward secrecy, make it an insecure alternative to Signal. They recommend using Signal instead.

### 23. A physicist's guide to ice cream

 Score: 39 Comments: 10 [Link](https://physicsworld.com/a/a-physicists-guide-to-ice-cream-the-complex-science-behind-one-of-the-worlds-most-popular-desserts/)

 > Ice cream is a complex multiphase material involving emulsions, foams, ice crystals, and solutes, requiring precise control of ingredients and processes. Food scientist Douglas Goff explains the science behind its structure, the challenges of making vegan ice cream, and techniques like electron microscopy to study it. Commercial ice cream differs from homemade in shelf life due to smaller ice crystals and stabilizers. Flavorings and ingredients like alcohol can alter freezing points and stability, requiring careful formulation. Goff remains passionate about ice cream, exploring global markets and sharing its science.

### 24. Build a Database in 3000 Lines with 0 Dependencies

 Score: 370 Comments: 40 [Link](https://build-your-own.org/blog/20251015_db_in_3000/)

 > The article describes building a minimalist database from scratch in 3000 lines of Go code, focusing on core concepts like power-loss atomicity, indexing with B+trees, and concurrency control. It emphasizes learning by simplifying complex systems, incrementally adding features like KV storage, SQL-like queries, and transactional interfaces. The author has also turned this project into a book for others to follow.

### 25. Build a tiny CA for your homelab with a Raspberry Pi

 Score: 195 Comments: 49 [Link](https://smallstep.com/blog/build-a-tiny-ca-with-raspberry-pi-yubikey/)

 > This tutorial guides you through building a tiny, standalone Certificate Authority (CA) using a Raspberry Pi and a YubiKey for secure key storage. It covers setting up the system, generating PKI, configuring the CA, and automating certificate renewal using the ACME protocol. The setup ensures secure TLS certificates for your homelab, with optional enhancements like a True Random Number Generator for improved entropy.

### 26. The Fuzzing Book

 Score: 211 Comments: 8 [Link](https://www.fuzzingbook.org/)

 > "The Fuzzing Book" is a comprehensive resource on automated software testing, focusing on techniques like random fuzzing, mutation-based fuzzing, and grammar-based test generation. Written by experts in the field, it serves as a textbook for software testing courses and a practical guide for developers, offering interactive Jupyter Notebooks, downloadable code, and slides for teaching. The book is freely available online and licensed under Creative Commons, encouraging contributions and adaptations.

### 27. Hacking the Yamaha DX9 to Turn It into a DX7 (2023)

 Score: 77 Comments: 15 [Link](https://ajxs.me/blog/Hacking_the_Yamaha_DX9_To_Turn_It_Into_a_DX7.html)

 > The author created a custom firmware ROM for the Yamaha DX9, enabling it to load and play DX7 patches, restore missing features like six-operator support, and add MIDI velocity sensitivity. The project involved reverse-engineering the DX9's firmware and porting DX7 functionality. The firmware's source code is available on GitHub, offering DX9 owners enhanced capabilities.

### 28. Why Twitter is such a big deal (2009)

 Score: 98 Comments: 142 [Link](https://paulgraham.com/twitter.html)

 > Twitter is a significant innovation because it functions as a new messaging protocol where recipients aren't specified, a rarity in the tech world. Unlike most protocols, it is owned by a private company, making its success even more notable. The founders' slow approach to monetization has allowed Twitter to feel like a public protocol, aiding its widespread adoption.

### 29. Robotics and ROS 2 Essentials

 Score: 108 Comments: 81 [Link](https://henkirobotics.com/robotics-and-ros-2-essentials-course-announcement/)

 > Henki Robotics, in collaboration with the University of Eastern Finland, has open-sourced their "Robotics & ROS 2 Essentials" course materials on GitHub. The course provides beginner-friendly, hands-on exercises using ROS 2 and Gazebo simulations, covering topics like SLAM, navigation, and path planning. No prior ROS 2 installation is needed, as Docker is used for a containerized environment. The course aims to equip learners with essential robotics skills and is freely available to support the growing demand for robotics expertise.

### 30. Physicists have shown that an idealized form of magnetism is heatproof

 Score: 73 Comments: 8 [Link](https://www.quantamagazine.org/heat-destroys-all-order-except-for-in-this-one-special-case-20250116/)

 > Physicists have discovered that an idealized form of magnetism can maintain order at any temperature, defying the typical expectation that heat destroys all patterns. This theoretical system involves two intermingled magnetic fields, where one stabilizes the other, allowing magnetic order to persist even at infinite temperatures. The findings, rigorously proven in recent studies, could influence cosmology and inspire new approaches to maintaining quantum phenomena like superconductivity at higher temperatures.

