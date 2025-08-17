Updated at 2025-08-17 17:10:36 (UTC+8)

### 1. Lessons learned from building a sync-engine and reactivity system with SQLite

 Score: 35 Comments: 9 [Link](https://www.finkelstein.fr/sqlite-sync-engine-with-reactivity)

 > The author built a local-first, reactive app using SQLite in the browser with a custom sync engine and reactivity system. After trying PostgreSQL-based solutions like Electric and PGlite, they opted for a simpler approach with SQLite, polling for updates, and using triggers with the Broadcast Channel API for reactivity. This lightweight solution worked well for their single-player notes app, offering stability and real-time responsiveness.

### 2. SuperSight: A graphical enhancement mod for Brøderbund's "Stunts"

 Score: 51 Comments: 1 comment [Link](https://marnetto.net/2025/02/20/broderbund-stunts-1)

 > Alberto Marnetto details creating SuperSight, a mod for the 1990 racing game *Stunts*, aiming to enhance its 3D graphics. He reverse-engineers the game using community resources and tools like Ghidra, adjusting tile rendering and detail levels. The mod improves visual quality but reveals technical challenges like Z-ordering errors. The project continues in a second part.

### 3. Node.js can now execute TypeScript files

 Score: 105 Comments: 37 [Link](https://nodejs.org/en/blog/release/v22.18.0)

 > Node.js v22.18.0 (LTS) introduces experimental TypeScript support by default, allowing direct execution of `.ts` files without additional configuration. Key updates include new features like `import.meta.main`, improved fs-events handling, and permission model enhancements. This release also includes various bug fixes and performance improvements.

### 4. Dev Compass – Programming Philosophy Quiz

 Score: 149 Comments: 62 [Link](https://treeform.github.io/devcompas/)

 > The article introduces a quiz called "Dev Compass" that helps users discover their programming philosophy by answering 20 questions, mapping preferences along two dimensions: abstract vs. concrete style and human-friendly vs. computer-friendly coding.

### 5. LLMs tell bad jokes because they avoid surprises

 Score: 22 Comments: 25 [Link](https://danfabulich.medium.com/llms-tell-bad-jokes-because-they-avoid-surprises-7f111aac4f96)

 > The article argues that LLMs struggle with creativity (e.g., jokes, stories, journalism) because they are designed to minimize surprise, which is essential for humor and originality. Their predictive nature makes them generate bland, predictable content, limiting their ability to produce truly innovative or engaging work.

### 6. Visualising how close random GUIDs come to being the same

 Score: 124 Comments: 35 [Link](https://www.guidsmash.com)

 > The article could not be summarized because no content was available at the provided URL. The error indicates a failed assertion due to missing content.

### 7. An Argument for Increasing TCP's Initial Congestion Window Again

 Score: 72 Comments: 19 [Link](https://jeclark.net/articles/tcp-initcwnd/?tag=performance)

 > The article argues for increasing TCP's initial congestion window (initcwnd) from 10 to 20-40 to improve modern web performance, as current values are too low for today's larger assets. It suggests pairing this with Google's BBR congestion control algorithm to mitigate bufferbloat risks. While QUIC offers alternatives, TCP tuning remains crucial due to enterprise restrictions and legacy devices. The goal is to reduce latency and enhance web speed.

### 8. OpenAI Progress

 Score: 275 Comments: 236 [Link](https://progress.openai.com)

 > The article suggests potential conversation topics with future AI models, including advances in AI technology, AI alignment, ethical guidelines, societal impacts, and domain-specific applications. It notes that AI lacks emotions but provides ideas for meaningful discussions.

### 9. Dyna – Logic Programming for Machine Learning

 Score: 117 Comments: 9 [Link](https://dyna.org/)

 > Dyna is a logic programming language designed for machine learning, combining features from Datalog and Prolog with flexible execution orders and weighted rules. It simplifies expressing complex algorithms like matrix multiplication, Fibonacci sequences, and neural networks concisely. The project, started in 2004, evolved through versions 1.0 and 2.0 to address limitations and improve functionality. Ongoing research explores optimization techniques like reinforcement learning for execution strategies. Multiple implementations, including Dyna3 and Dyna-R, support its development.

### 10. Wan – Open-source alternative to VEO 3

 Score: 12 Comments: discuss [Link](https://github.com/Wan-Video/Wan2.2)

 > GitHub has blocked the domain github.com until August 17, 2025, due to suspected DDoS abuse from excessive requests linked to a specific repository. The error indicates a security compromise.

### 11. Hyundai wants loniq 5 customers to pay for cybersecurity patch in baffling move

 Score: 165 Comments: 110 [Link](https://www.neowin.net/news/hyundai-wants-ioniq-5-customers-to-pay-for-cybersecurity-patch-in-baffling-move/)

 > The domain www.neowin.net is blocked until August 17, 2025, due to suspected DDoS abuse linked to an article about Hyundai charging for a cybersecurity patch.

### 12. The Raft Consensus Algorithm (2015)

 Score: 137 Comments: 33 [Link](https://raft.github.io/)

 > Raft is an easy-to-understand consensus algorithm for fault-tolerant distributed systems, ensuring multiple servers agree on values. It's equivalent to Paxos in performance but simpler, making it accessible for practical implementations. Raft is widely used in replicated state machines and has many open-source implementations. The article provides resources, papers, talks, and courses related to Raft.

### 13. Dicing an Onion, the Mathematically Optimal Way

 Score: 272 Comments: 94 [Link](https://pudding.cool/2025/08/onions/)

 > This article explores the mathematically optimal way to dice an onion for uniform piece sizes, comparing vertical and radial cuts. It finds that radial cuts aimed ~96% below the onion's center yield the most consistent pieces (29.5% standard deviation) for a 10-layer onion. While optimal dicing improves uniformity, chef J. Kenji López-Alt notes it matters more for math than cooking. The analysis simplifies onion layers as concentric circles and evaluates various cutting techniques.

### 14. Pfeilstorch

 Score: 255 Comments: 66 [Link](https://en.wikipedia.org/wiki/Pfeilstorch)

 > A *Pfeilstorch* (German for "arrow stork") is a white stork injured by an arrow or spear in Africa that returns to Europe with the projectile embedded in its body. The most famous, found in 1822 near Klütz, Germany, proved birds migrate long distances, debunking earlier theories like hibernation or transformation. About 25 such cases have been documented in Germany. The 1822 specimen is preserved at the University of Rostock.

### 15. That 16B password story (a.k.a. "data troll")

 Score: 80 Comments: 8 [Link](https://www.troyhunt.com/that-16-billion-password-story-aka-data-troll/)

 > Troy Hunt debunks sensational headlines about a "16 billion password breach," revealing the data is mostly recycled from old infostealer logs. After analysis, only 109M unique email addresses were found, with 96% already in his database. The exaggerated claims stem from duplicated and repackaged data, not a new breach. Hunt emphasizes the need for accurate reporting on cybersecurity threats.

### 16. Counting Words at SIMD Speed

 Score: 18 Comments: 8 [Link](https://healeycodes.com/counting-words-at-simd-speed)

 > The article explores optimizing word counting in a text file, starting with a slow Python version (89.6s), improving it with regex (13.7s), then switching to C (1.2s), and finally using SIMD (249ms) and threads (181ms) for massive speed gains. The fastest version leverages ARM NEON SIMD and parallel processing to achieve ~5.52 GiB/s throughput. [Source code](https://github.com/healeycodes/counting-words-at-simd-speed).

### 17. Show HN: unsafehttp – tiny web server from scratch in C, running on an orange pi

 Score: 61 Comments: 39 [Link](http://unsafehttp.benren.au)

 > `unsafehttp` is a minimal HTTP server written in C for learning purposes, hosted on an Orange Pi without a proxy. It loads content into memory for security and ignores most HTTP RFC standards to keep the project simple and fun. The source code is available on GitHub.

### 18. Living with Williams Syndrome, the 'opposite of autism' (2014)

 Score: 81 Comments: 38 [Link](https://www.bbc.com/news/health-26888280)

 > Williams Syndrome (WS) is a rare genetic disorder causing extreme sociability, low IQ, and anxiety, often called the "opposite of autism." People with WS struggle with tasks like handling money but excel in empathy and acting. The disorder, affecting 1 in 18,000 in the UK, also brings heart issues and developmental delays. Families and charities advocate for more awareness and support.

### 19. Tversky Neural Networks

 Score: 95 Comments: 8 [Link](https://gonzoml.substack.com/p/tversky-neural-networks)

 > The article introduces Tversky Neural Networks, which replace traditional geometric similarity functions (like dot product) with a differentiable version of Tversky's asymmetric similarity model. This approach improves performance in tasks like image recognition and language modeling while offering built-in interpretability by aligning with human cognitive principles. The model learns common and distinctive features, outperforming standard layers in some cases.

### 20. Traps to Developers

 Score: 210 Comments: 91 [Link](https://qouteall.fun/qouteall-blog/2025/Traps%20to%20Developers)

 > This article summarizes common unintuitive traps developers may encounter across various domains like HTML/CSS, Unicode, floating-point, time handling, programming languages (Java, Go, C/C++, Python), databases, concurrency, Linux/bash, React, Git, networking, and YAML. These pitfalls often lead to bugs due to misunderstandings or overlooked behaviors.

### 21. A Lisp in 99LOC

 Score: 70 Comments: 11 [Link](https://github.com/Robert-van-Engelen/tinylisp)

 > GitHub.com is blocked until August 17, 2025, due to suspected DDoS abuse from a specific URL. The error indicates excessive requests triggered a security restriction.

### 22. For Iris Murdoch, morality is about love, not duties and rules

 Score: 37 Comments: 27 [Link](https://aeon.co/essays/for-iris-murdoch-morality-is-about-love-not-duties-and-rules)

 > Iris Murdoch argues that morality is fundamentally about love, not rules or duties. She believes attentive love—patient, just attention to others—helps us overcome self-centered fantasies and see people truthfully. This vision shapes our actions and is central to ethical life. Murdoch contrasts this with Kantian duty-based morality, emphasizing love’s power to draw us out of egoism. Cultivating such love requires practice, humility, and engagement with art or skills.

### 23. Passive Microwave Repeaters

 Score: 29 Comments: 8 [Link](https://computer.rip/2025-08-16-passive-microwave-repeaters.html)

 > Passive microwave repeaters, developed in the 1950s, used large aluminum panels to reflect signals around obstacles, offering a cost-effective alternative to active repeaters in rugged terrain. Pioneered by Microflect, they were widely adopted by utilities and telecoms but declined with fiber optics and improved active repeater technology. Many have since been abandoned or demolished.

### 24. Writing a competitive BZip2 encoder in Ada from scratch in a few days – part 2

 Score: 107 Comments: 7 [Link](https://gautiersblog.blogspot.com/2025/07/writing-bzip2-encoder-in-ada-from.html)

 > Gautier continues his series on creating a competitive BZip2 encoder in Ada, focusing on optimizing performance and refining the implementation in this second part. The post details technical challenges and solutions encountered during development.

### 25. Running Wayland Clients as Non-Root Users on Yocto

 Score: 18 Comments: 2 [Link](https://embeddeduse.com/2025/08/11/running-wayland-clients-as-non-root-users/)

 > The article explains how to run Wayland clients (like Qt apps) as non-root users for better security, addressing issues with socket permissions and environment variables. It provides a solution using Yocto to modify service units and environment files, ensuring Weston and clients communicate securely without root privileges.

### 26. GDPR meant nothing: chat control ends privacy for the EU [video]

 Score: 299 Comments: 209 [Link](https://www.youtube.com/watch?v=3NyUgv6dpJc)

 > The EU's proposed "chat control" law undermines GDPR by allowing mass surveillance of private messages under the guise of protecting children, raising concerns about privacy erosion and government overreach. Critics argue it exploits child safety as a pretext for invasive monitoring.

### 27. Do things that don't scale, and then don't scale

 Score: 431 Comments: 170 [Link](https://derwiki.medium.com/do-things-that-dont-scale-and-then-don-t-scale-9fd2cd7e2156)

 > The article argues that with AI-assisted coding, small-scale, personal projects don’t need to scale to be valuable. The author shares examples like a private Slack group and a custom postcard service, emphasizing that some tools work best when kept small and tailored. The freedom to build for a niche audience is now more accessible than ever.

### 28. A single lock of hair could rewrite what we know about Inca record-keeping

 Score: 69 Comments: 24 [Link](https://www.science.org/content/article/single-lock-hair-could-rewrite-what-we-know-about-inca-record-keeping)

 > The domain www.science.org is blocked until August 17, 2025, due to suspected DDoS abuse from excessive requests linked to a specific article. Access remains restricted for security reasons.

### 29. Toothpaste made with keratin may protect and repair damaged teeth: study

 Score: 373 Comments: 177 [Link](https://www.kcl.ac.uk/news/toothpaste-made-from-hair-provides-natural-root-to-repair-teeth)

 > Scientists at King’s College London developed a toothpaste using keratin from hair that repairs tooth enamel by forming a protective mineral layer, offering a sustainable alternative to fluoride treatments. The keratin-based solution could be available within 2-3 years.

### 30. "Mocha Dick," the White Whale of the Pacific

 Score: 7 Comments: discuss [Link](https://lithub.com/on-mocha-dick-the-white-whale-of-the-pacific-that-influenced-herman-melville/)

 > The domain lithub.com is blocked until August 17, 2025, due to suspected DDoS abuse linked to an article about Mocha Dick, a whale that inspired Herman Melville. The block resulted from excessive requests.

