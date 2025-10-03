Updated at 2025-10-03 17:10:08 (UTC+8)

### 1. Fp8 runs ~100 tflops faster when the kernel name has "cutlass" in it

 Score: 153 Comments: 48 [Link](https://github.com/triton-lang/triton/pull/7298)

 > This pull request rewrites the Triton attention kernel to use a persistent design, improving performance at low context lengths. While FP16 performance at large contexts decreased slightly due to a PTX assembly scheduling issue, FP8 performance gained about 100 TFLOPS when the kernel name contains "cutlass." The implementation includes performance benchmarks showing throughput improvements across various configurations and context lengths.

### 2. In Praise of RSS and Controlled Feeds of Information

 Score: 87 Comments: 27 [Link](https://blog.burkert.me/posts/in_praise_of_syndication/)

 > RSS offers a user-controlled alternative to algorithmic social media feeds by letting you subscribe directly to websites' content updates. Unlike platforms that prioritize engagement, RSS feeds deliver content in simple reverse chronological order without manipulation. This allows readers to curate their own information sources and consume content distraction-free. The author argues this restores personal agency over media consumption while avoiding the pitfalls of modern content distribution models.

### 3. Talent Is Alignment

 Score: 7 Comments: 3 [Link](https://xlii.space/thoughts/talent-is-alignment/)

 > The author argues that what people perceive as talent is actually alignment - a natural attraction to an activity that makes you want to spend time on it regularly. After one year of playing piano 1-3 hours daily, others call him talented, but he attributes this to consistent practice driven by genuine enjoyment. He suggests anyone can become "talented" by finding activities they naturally align with, making practice feel effortless rather than forced.

### 4. FyneDesk: A full desktop environment for Linux written in Go

 Score: 128 Comments: 53 [Link](https://github.com/FyshOS/fynedesk)

 > FyneDesk is a full desktop environment for Linux and Unix systems built using the Fyne toolkit. It follows material design principles and is written in Go. The project provides an easy-to-use interface and supports features like window management, virtual desktops, and theming. It can be installed as a selectable desktop option in login managers or tested in an embedded X window using Xephyr.

### 5. I spent the day teaching seniors how to use an iPhone

 Score: 157 Comments: 186 [Link](https://forums.macrumors.com/threads/i-spent-the-day-trying-to-teach-seniors-how-to-use-an-iphone-and-it-was-a-nightmare.2468117/)

 > A user describes their frustrating experience trying to teach seniors how to use iPhones, calling it a "nightmare." They found that seniors struggled with basic functions like unlocking the phone, entering passcodes, and navigating the interface. The author suggests Apple should create a simplified "senior mode" and concludes that flip phones might be more suitable for this demographic than complex smartphones.

### 6. Signal Protocol and Post-Quantum Ratchets

 Score: 553 Comments: 230 [Link](https://signal.org/blog/spqr/)

 > Signal has introduced the Sparse Post-Quantum Ratchet (SPQR) to enhance its protocol's security against future quantum computing threats. This new ratchet maintains existing security guarantees like forward secrecy and post-compromise security while adding quantum resistance. SPQR works alongside the current Double Ratchet in a hybrid approach called the Triple Ratchet, mixing both classical and quantum-safe keys. The update will roll out automatically to all users without requiring any action on their part. This ensures Signal communications remain protected even if cryptographically relevant quantum computers become a reality.

### 7. You Want Technology with Warts

 Score: 60 Comments: 19 [Link](https://entropicthoughts.com/you-want-technology-with-warts)

 > The article argues that technologies with visible "warts" (imperfections or quirks) are preferable for long-term projects because these flaws demonstrate strong backward compatibility. The author cites SQLite's default behaviors as examples of warts that preserve functionality for existing users. This backward compatibility reduces future maintenance by ensuring code continues working despite external changes. Therefore, choosing technologies with warts today can lead to more durable systems tomorrow.

### 8. The strangest letter of the alphabet: The rise and fall of yogh

 Score: 180 Comments: 133 [Link](https://www.deadlanguagesociety.com/p/history-of-letter-yogh)

 > The letter yogh (ȝ) was a Middle English character derived from the Old English insular 'g'. It represented two distinct sounds: the 'y' sound as in 'young' and the guttural 'gh' sound found in Scots 'loch'. Yogh fell out of use partly due to the printing press, as it was expensive to include in typefaces. It was replaced by 'y' for the 'y' sound and 'gh' for the guttural sound. The letter's disappearance contributed to English spelling complexity, though it survives in some Scottish names where it was replaced by 'z'.

### 9. Digital ID – The New Chains of Capitalist Surveillance

 Score: 103 Comments: 93 [Link](https://theslowburningfuse.wordpress.com/2025/09/26/digital-id-the-new-chains-of-capitalist-surveillance/)

 > Digital ID systems are presented as tools for convenience and efficiency, but they actually represent an expansion of capitalist surveillance and state control. These systems enable unprecedented monitoring, exclusion, and exploitation by tying access to essential services to digital verification. The article argues that digital ID deepens existing power structures and must be resisted through collective action and solidarity to protect freedom.

### 10. Google Workspace Updates: Send Gmail end-to-end encrypted emails to anyone

 Score: 40 Comments: 21 [Link](https://workspaceupdates.googleblog.com/2025/10/send-gmail-end-to-end-encrypted-emails-in-gmail.html)

 > Google now allows Gmail users with client-side encryption to send end-to-end encrypted emails to anyone, regardless of their email provider. Recipients can access these messages through a guest account without needing special software or key exchanges. This feature enhances data security and privacy while simplifying the user experience. It is available for Google Workspace Enterprise Plus customers with the Assured Controls add-on.

### 11. Stdlib: A library of frameworks, templates, and guides for technical leadership

 Score: 58 Comments: 5 [Link](https://debuggingleadership.com/stdlib)

 > Stdlib is a community-built library containing over 1,000 practical resources for technical leadership. It features frameworks, templates, guides, blog posts, and books covering topics like engineering management, team dynamics, and leadership strategies. The collection is curated to provide immediately applicable tools for technical leaders. New resources are continuously added based on community feedback and evolving best practices.

### 12. Blender 4.5 brings big changes

 Score: 124 Comments: 39 [Link](https://lwn.net/Articles/1036262/)

 > Blender 4.5 LTS was released on July 15, 2025, and will be supported through 2027. This final feature release of the 4.x series includes quality-of-life improvements and enhances the Vulkan backend to match the OpenGL backend. With 4.5 complete, developers are now focusing on Blender 5.0, which will introduce major changes, particularly to the Geometry Nodes system.

### 13. Constitent Hashing

 Score: 36 Comments: 8 [Link](https://eli.thegreenplace.net/2025/consistent-hashing/)

 > Consistent hashing is an algorithm that minimizes key redistribution when nodes are added or removed from a distributed system. It maps both nodes and items onto a circle, with each item assigned to the closest node in the clockwise direction. This approach ensures only about 1/N of keys need remapping when the number of nodes changes, unlike naive hashing which remaps all keys. Virtual nodes can be used to improve load balancing by distributing nodes more evenly around the circle.

### 14. Playball – Watch MLB games from a terminal

 Score: 287 Comments: 120 [Link](https://github.com/paaatrick/playball)

 > Playball is a terminal application that lets users watch MLB games directly from their command line. It provides real-time game updates, schedules, and standings in a text-based interface. The tool can be installed via npm or Docker and includes customizable color settings. This open-source project offers a discreet way to follow baseball games without graphical interfaces.

### 15. Potential issues in curl found using AI assisted tools

 Score: 424 Comments: 120 [Link](https://mastodon.social/@bagder/115241241075258997)

 > I cannot provide a summary of the article you've shared. The content appears to be the generic Mastodon social media interface and navigation elements, not an actual article or post with substantive content to summarize. There is no article text, news content, or meaningful information to extract for a summary.

### 16. The Beer Can

 Score: 27 Comments: 3 [Link](https://brr.fyi/posts/beer-can)

 > The Beer Can is a vertical tower at the South Pole Station that connects the modern elevated living area with the buried industrial infrastructure zone below. It contains 90 stairs and a freight elevator, spanning about 50 feet to bridge the elevation difference caused by accumulating snow. This structure serves as the transition point between comfortable living quarters and utilitarian work areas like the power plant and warehouses. Staff use it daily, and climbing it has become a fitness challenge due to the high altitude.

### 17. Microcomputers – The Second Wave: Toward a Mass Market

 Score: 38 Comments: 10 [Link](https://technicshistory.com/2025/10/03/microcomputers-the-second-wave-towards-a-mass-market/)

 > In 1977, three microcomputers—the Apple II, Commodore PET, and TRS-80—marked a shift from hobbyist gadgets to consumer appliances, making computing accessible without technical expertise. These "Trinity" machines required technical design, business vision, and capital to scale production. While established computer companies dismissed the market, these pioneers recognized the mass-market potential. Their success led to rapid growth and the decline of many earlier hobbyist-focused companies.

### 18. Babel is why I keep blogging with Emacs

 Score: 217 Comments: 59 [Link](https://entropicthoughts.com/why-stick-to-emacs-blog)

 > The author continues blogging with Emacs despite envying simpler static site generators because Org mode's Babel feature allows executing code blocks during export. This enables dynamic content generation like plots and tables directly within articles. While a custom 2,000-line solution would be simpler, replicating Babel's functionality would require months of work. The convenience of integrated code execution outweighs the complexity of the current setup.

### 19. Icebird: JavaScript Iceberg Reader

 Score: 10 Comments: 1 comment [Link](https://github.com/hyparam/icebird)

 > Icebird is a JavaScript library for reading Apache Iceberg tables. It supports reading both table data and metadata, works with Parquet and Avro storage formats, and includes features like time travel and authentication. Built on hyparquet for Parquet file reading, it currently supports Iceberg v1 and v2 tables but not v3. The project is open source under MIT license.

### 20. Researchers develop molecular qubits that communicate at telecom frequencies

 Score: 41 Comments: 5 [Link](https://chicagoquantum.org/news/researchers-develop-molecular-qubits-communicate-telecom-frequencies)

 > Researchers have developed molecular qubits using erbium that bridge light and magnetism while operating at telecom frequencies. This breakthrough enables compatibility with existing fiber-optic networks and silicon photonics. The technology could advance quantum networks, secure communications, and quantum sensors. These molecular qubits can integrate into chips and biological systems for various applications. The work represents a significant step toward scalable quantum technologies.

### 21. Why I chose Lua for this blog

 Score: 155 Comments: 98 [Link](https://andregarzia.com/2025/03/why-i-choose-lua-for-this-blog.html)

 > The author switched from a complex Racket-based blog system to Lua because JavaScript's ecosystem changes too rapidly, making long-term maintenance difficult. Lua evolves slowly and is simple enough to fully understand, allowing the author to implement features with minimal dependencies. This new system uses CGI scripts with SQLite and Mustache templates, prioritizing longevity over performance. The goal is a maintainable blog that can run unchanged for decades.

### 22. Dbos: Durable Workflow Orchestration with Go and PostgreSQL

 Score: 71 Comments: 36 [Link](https://github.com/dbos-inc/dbos-transact-golang)

 > DBOS Transact is a lightweight durable workflow orchestration library for Golang that uses Postgres as its backend. It enables developers to build fault-tolerant applications by automatically checkpointing workflow state in Postgres, allowing seamless recovery from failures. The library provides durable workflows, queues, scheduling, notifications, and exactly-once event processing capabilities. Unlike heavyweight orchestration systems, DBOS integrates directly with existing Golang applications through simple code annotations.

### 23. Highest bridge unveiled at more than 2,000ft above ground

 Score: 60 Comments: 91 [Link](https://www.independent.co.uk/tv/news/china-worlds-highest-bridge-video-b2835886.html)

 > Access to www.independent.co.uk is blocked until October 3, 2025. This security measure was implemented due to suspected DDoS attack abuse originating from a specific article URL on the site. The block prevents anonymous access to the entire domain.

### 24. Valuing Land: The Simplest Viable Method

 Score: 22 Comments: 6 [Link](https://progressandpoverty.substack.com/p/valuing-land-the-simplest-viable)

 > This article proposes a simple method for valuing land that can be implemented by property assessors. The approach involves dividing jurisdictions into neighborhoods with uniform land values and applying a local land rate based on a fixed percentage of typical property values. This method ensures land values don't increase due to building improvements while properly taxing underutilized land. The author argues this approach creates correct economic incentives for land use and can be easily explained and implemented using existing assessment frameworks.

### 25. Solveit – A course and platform for solving problems with code

 Score: 85 Comments: 77 [Link](https://www.answer.ai/posts/2025-10-01-solveit-full.html)

 > Answer.AI is launching "Solveit," a course and platform focused on iterative problem-solving with code. It teaches a method of breaking problems into small, understandable steps, using AI as an optional aid rather than a crutch. The platform provides a shared environment where humans and AI can collaborate with full context visibility. This approach aims to build deep understanding and avoid "vibe coding." The course opens for signups until October 20th.

### 26. How I block all 26M of your curl requests

 Score: 120 Comments: 32 [Link](https://foxmoss.com/blog/packet-filtering/)

 > The author developed a custom packet filtering system using XDP/eBPF to block unwanted bot traffic by implementing TLS fingerprinting. They created a new fingerprinting method called FST1 that uses a simplified hash function to identify clients like curl based on their cipher suites. This approach blocks requests at the network level before they reach the application, making it harder to bypass than traditional user-agent blocking. The solution can handle high traffic volumes while effectively identifying and blocking automated requests.

### 27. PyOCI – Publish and install private Python packages using OCI/Docker registries

 Score: 17 Comments: 8 [Link](https://github.com/AllexVeldman/pyoci)

 > PyOCI is a tool that enables publishing and installing private Python packages using OCI/docker registries like ghcr.io. It acts as a proxy between pip and OCI registries, allowing existing container registries to function as Python package indexes. This eliminates the need for separate package hosting services and leverages existing registry access controls. The project is open-source with an MIT license and can be self-hosted or used via the public instance at pyoci.com.

### 28. Self-supervised learning, JEPA, world models, and the future of AI [video]

 Score: 36 Comments: 17 [Link](https://www.youtube.com/watch?v=yUmDRxV0krg)

 > Yann LeCun's lecture discusses the future of AI through self-supervised learning approaches. He presents JEPA (Joint Embedding Predictive Architecture) as a method for learning world models by predicting abstract representations rather than detailed outputs. This architecture enables AI systems to develop common sense and understand how the world works. LeCun argues this approach is crucial for creating more capable, human-like artificial intelligence that can reason and plan effectively.

### 29. Some dogs can classify their toys by function

 Score: 67 Comments: 13 [Link](https://arstechnica.com/science/2025/09/some-dogs-can-classify-their-toys-by-function/)

 > A new study shows that some dogs can classify their toys by function, not just appearance. These "gifted word learner" dogs learned to associate toys with labels like "pull" or "fetch" through natural play. They could then correctly identify new toys based on function without formal training. This ability, known as label extension, was previously thought to require intensive training in animals.

### 30. OpenAI's H1 2025: $4.3B in income, $13.5B in loss

 Score: 448 Comments: 527 [Link](https://www.techinasia.com/news/openais-revenue-rises-16-to-4-3b-in-h1-2025)

 > OpenAI's revenue increased by 16% to reach $4.3 billion in the first half of 2025. This growth demonstrates the company's strong financial performance.

