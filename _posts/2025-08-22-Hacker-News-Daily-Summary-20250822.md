Updated at 2025-08-22 17:14:02 (UTC+8)

### 1. Io_uring, kTLS and Rust for zero syscall HTTPS server

 Score: 175 Comments: 26 [Link](https://blog.habets.se/2025/04/io-uring-ktls-and-rust-for-zero-syscall-https-server.html)

 > This article details the evolution of high-performance web servers, culminating in a project that combines io_uring, kTLS, and Rust to create an HTTPS server that aims for zero syscalls per request. The author built a server called `tarweb` to serve content from a tar file, overcoming integration challenges between these technologies. The goal is to handle requests without costly system calls by using asynchronous queues and kernel-offloaded TLS encryption.

### 2. DeepSeek-v3.1

 Score: 497 Comments: 119 [Link](https://api-docs.deepseek.com/news/news250821)

 > DeepSeek-V3.1 introduces a hybrid inference model with "Think" and "Non-Think" modes for faster reasoning and improved agent skills. The API now offers two endpoints: `deepseek-chat` for non-thinking and `deepseek-reasoner` for thinking, both with 128K context. The model features significant upgrades in tool use, multi-step reasoning, and thinking efficiency. New pricing will take effect on September 5th, 2025.

### 3. Control shopping cart wheels with your phone (2021)

 Score: 154 Comments: 37 [Link](https://www.begaydocrime.com/)

 > This article explains how to hack electronic shopping cart wheels by playing a specific 7.8 kHz audio signal from a phone's speaker. This frequency mimics the signal used by management remotes to lock and unlock the wheels. The method leverages parasitic EMF from the phone's speaker to transmit the code.

### 4. Everything Is Correlated

 Score: 84 Comments: 27 [Link](https://gwern.net/everything)

 > The article discusses the observation that in real-world datasets, all variables are correlated to some extent, often non-zero. This challenges null hypothesis significance testing, as large datasets will almost always reject the null hypothesis, making statistical significance uninformative. The implications include difficulties in model interpretation and the need to focus on effect sizes and practical significance rather than p-values.

### 5. 24,000-Watt Scooter Is Going for a 100 MPH Speed Record at Bonneville

 Score: 36 Comments: 28 [Link](https://www.thedrive.com/news/this-24000-watt-scooter-is-going-for-a-100-mph-speed-record-at-bonneville)

 > Access to the website www.thedrive.com has been blocked for anonymous users until August 22, 2025. This security measure was taken because the site was the target of a suspected DDoS attack, which involved too many requests. The block is a response to this previous abuse.

### 6. Code formatting comes to uv experimentally

 Score: 245 Comments: 146 [Link](https://pydevtools.com/blog/uv-format-code-formatting-comes-to-uv-experimentally/)

 > The uv tool has introduced an experimental `uv format` command in version 0.8.13. This new feature provides Python code formatting by calling Ruff's formatter under the hood. Users can format their code, check formatting, or see a diff of proposed changes. The feature is currently experimental and may evolve based on user feedback.

### 7. The Minecraft code no one has solved (2024) [video]

 Score: 6 Comments: 1 comment [Link](https://www.youtube.com/watch?v=nz2LeXwJOyI)

 > A mysterious encrypted file named "tominecon.7z" was discovered on Mojang's public servers in 2012. It was rumored to contain an early build of Minecraft 1.0, but its password has never been cracked. The video explores the file's discovery, the community's failed attempts to solve it, and the inconsistencies surrounding its origin and purpose.

### 8. It's Not Wrong that " ".length == 7

 Score: 67 Comments: 55 [Link](https://hsivonen.fi/string-length/)

 > This article explains that different programming languages report different string lengths for the same emoji ("🤦🏼‍♂️") because they measure different underlying units: UTF-8 code units (Rust: 17), UTF-16 code units (JavaScript: 7), Unicode scalar values (Python: 5), or extended grapheme clusters (Swift: 1). It argues that no single measure is universally "correct" and that UTF-8 is the best choice for new languages due to its efficiency and interoperability.

### 9. Is moderate drinking healthy? Scientists say the idea is outdated

 Score: 23 Comments: 37 [Link](https://news.stanford.edu/stories/2025/08/moderate-alcohol-consumption-drinking-health-benefits-impacts-research)

 > New research contradicts the long-held belief that moderate drinking is healthy. Recent studies link even low levels of alcohol consumption to an increased risk of cancer and other diseases. Stanford Medicine experts state that the idea of health benefits from moderate drinking is outdated and misleading. They emphasize that no amount of alcohol is truly safe for your health.

### 10. From GPT-4 to GPT-5: Measuring progress through MedHELM [pdf]

 Score: 95 Comments: 69 [Link](https://www.fertrevino.com/docs/gpt5_medhelm.pdf)

 > This paper evaluates GPT-5 on the MedHELM medical benchmark. Results show GPT-5 achieved new highs in factual recall and tied for the lead in quantitative calculations. However, it regressed significantly in structured query generation (EHRSQL) and fairness-sensitive reasoning (RaceBias), while also showing a slight shortfall in hallucination resistance.

### 11. VHS-C: when a lazy idea stumbles towards perfection [video]

 Score: 18 Comments: 4 [Link](https://www.youtube.com/watch?v=HFYWHeBhYbM)

 > VHS-C was a compact videotape format created by simply shrinking a standard VHS tape into a smaller cassette. Its key innovation was a clever adapter that allowed these smaller tapes to play in any standard VCR. This ensured perfect compatibility with the massive existing VHS ecosystem, which was a major factor in its success over more advanced but incompatible formats.

### 12. Crimes with Python's Pattern Matching (2022)

 Score: 188 Comments: 74 [Link](https://www.hillelwayne.com/post/python-abc/)

 > Python 3.10's pattern matching uses `isinstance()`, which checks Abstract Base Classes (ABCs) and their `__subclasshook__` method. This allows ABCs to hijack pattern matches by dynamically defining what counts as a subclass. The author demonstrates creating combinators like `Not` and `And` to match complex conditions, calling it "extremely dark magic" that should not be used in production.

### 13. An interactive guide to SVG paths

 Score: 305 Comments: 27 [Link](https://www.joshwcomeau.com/svg/interactive-guide-to-paths/)

 > This interactive guide by Josh W. Comeau demystifies the SVG `<path>` element, explaining its syntax and core drawing commands. It covers fundamental instructions like Move (M) and Line (L), explores Bézier curves (Q and C), and provides a detailed breakdown of the complex Arc (A) command. The article uses visual examples and interactive playgrounds to build intuition for creating custom, curved SVG shapes.

### 14. Weaponizing image scaling against production AI systems

 Score: 388 Comments: 106 [Link](https://blog.trailofbits.com/2025/08/21/weaponizing-image-scaling-against-production-ai-systems/)

 > Researchers have weaponized image scaling to hide malicious prompts within images that become visible only when downscaled by AI systems. This multi-modal prompt injection attack successfully exfiltrated user data from production systems like Google Gemini CLI and Vertex AI. They released an open-source tool called Anamorpher to generate these crafted images. The recommended defense is to avoid downscaling and provide users with a preview of the model's actual input.

### 15. Elegant mathematics bending the future of design

 Score: 107 Comments: 7 [Link](https://actu.epfl.ch/news/elegant-mathematics-bending-the-future-of-design/)

 > EPFL researchers have developed C-Tubes, a new computational algorithm that designs complex 3D tubular structures from flat materials like paper or metal. The method ensures the materials can bend without wrinkling or tearing, making production faster and more sustainable. This innovation allows designers to focus on aesthetics and function while creating strong, lightweight objects.

### 16. 1981 Sony Trinitron KV-3000R: The Most Luxurious Trinitron [video]

 Score: 53 Comments: 41 [Link](https://www.youtube.com/watch?v=jHG_I-9a7FY)

 > This error indicates a network connectivity issue between a client and an upstream server. The connection was terminated before the request could be completed and any response headers received. This is often caused by a timeout, a server crash, or a network interruption.

### 17. Building AI products in the probabilistic era

 Score: 136 Comments: 68 [Link](https://giansegato.com/essays/probabilistic-era)

 > AI is shifting software from a deterministic world of predictable inputs and outputs to a probabilistic one. Products now accept infinite inputs and produce stochastic, emergent outputs that are not fully knowable or controllable. This requires a new approach to building products, moving from engineering to empiricism and data-driven science. The entire tech industry's playbooks must adapt to this new reality.

### 18. Benchmarks for Golang SQLite Drivers

 Score: 69 Comments: 18 [Link](https://github.com/cvilsmeier/go-sqlite-bench)

 > Anonymous access to GitHub.com is blocked until August 22, 2025. This security measure was taken because a suspected DDoS attack originated from a specific page listing top GitHub users in Italy. The block is due to excessive requests from that source.

### 19. How does the US use water?

 Score: 156 Comments: 137 [Link](https://www.construction-physics.com/p/how-does-the-us-use-water)

 > The US uses about 322 billion gallons of water per day. The largest users are thermoelectric power plants (41% of total use, mostly non-consumptive cooling) and irrigation (37%, mostly consumptive). Public water supply for homes and businesses accounts for 12%, while industrial use is 4.5%. Overall water use has declined since its peak in 1980.

### 20. How Not to Buy a SSD

 Score: 67 Comments: 48 [Link](https://andrei.xyz/post/how-not-to-buy-a-ssd/)

 > The author bought a supposedly new SSD that exhibited extremely slow speeds. After investigation, they discovered it was a counterfeit drive, likely a genuine 128GB SSD with a modified firmware to report a larger, fake capacity. They were ultimately able to get a full refund from the retailer.

### 21. How well does the money laundering control system work?

 Score: 238 Comments: 257 [Link](https://www.journals.uchicago.edu/doi/10.1086/735665)

 > The global anti-money laundering (AML) system is widely regarded as ineffective despite its enormous cost. It fails to significantly reduce money laundering or its predicate crimes, with only a tiny fraction of illicit proceeds ever seized. The system relies heavily on private sector enforcement, which is costly and prone to over-reporting, while major banks frequently violate rules with minimal consequences for executives.

### 22. AWS CEO says using AI to replace junior staff is 'Dumbest thing I've ever heard'

 Score: 1333 Comments: 548 [Link](https://www.theregister.com/2025/08/21/aws_ceo_entry_level_jobs_opinion/)

 > AWS CEO Matt Garman called the idea of using AI to replace junior staff "the dumbest thing I've ever heard." He argued that junior employees are inexpensive, highly engaged with AI tools, and essential for learning and future leadership. Garman emphasized that companies should continue hiring and training new talent to ensure long-term growth and skill development.

### 23. Beyond sensor data: Foundation models of behavioral data from wearables

 Score: 208 Comments: 45 [Link](https://arxiv.org/abs/2507.00191)

 > This research develops a foundation model using behavioral data from wearables, not just raw sensor data. It was trained on over 2.5 billion hours of data from 162,000 individuals. The model demonstrated strong performance across 57 health-related tasks, particularly excelling in behavior-driven predictions like sleep. It shows that tailoring foundation models to behavioral data significantly improves health predictions.

### 24. AI tooling must be disclosed for contributions

 Score: 622 Comments: 355 [Link](https://github.com/ghostty-org/ghostty/pull/8289)

 > Anonymous access to GitHub.com is blocked until August 22, 2025. This security measure was taken because a suspected DDoS attack originated from a specific page listing top GitHub users in Italy. The block is due to excessive requests from that source.

### 25. Text.ai (YC X25) Is Hiring Founding Full-Stack Engineer

 Score: None Comments: None [Link](https://www.ycombinator.com/companies/text-ai/jobs/OJBr0v2-founding-full-stack-engineer)

 > Text.ai is a Y Combinator-backed startup building an AI-native communication platform for group chats. They are hiring a Founding Full Stack Engineer to lead the development of their React Native mobile app and backend integration. The role requires 4+ years of experience and offers a salary of $100K-$150K plus equity. The engineer will be responsible for building the product from the ground up.

### 26. My other email client is a daemon

 Score: 127 Comments: 22 [Link](https://feyor.sh/blog/my-other-email-client-is-a-mail-daemon/)

 > The author integrates NetHack's mail daemon feature with their mu4e email client in Emacs. They wrote a Python script that converts their maildir inbox to an mbox file, which NetHack checks for new mail. When new mail is detected, a script launches emacsclient to display the unread messages in mu4e, all without leaving their game or Emacs environment.

### 27. Show HN: OS X Mavericks Forever

 Score: 337 Comments: 136 [Link](https://mavericksforever.com/)

 > The author decided to downgrade from modern macOS to OS X 10.9 Mavericks, which they consider the peak of Apple's design and usability. They provide a guide for obtaining, installing, and customizing Mavericks on compatible hardware, including Macs from 2008–2014 or a custom-built Hackintosh. The guide covers essential post-install steps like security, web browsing, and app compatibility to make the old OS functional in 2025. The author acknowledges the inherent security risks but finds the experience worthwhile.

### 28. Using Podman, Compose and BuildKit

 Score: 268 Comments: 96 [Link](https://emersion.fr/blog/2025/using-podman-compose-and-buildkit/)

 > The author prefers Podman over Docker for its rootless, daemonless operation and better nftables support. They found that existing methods for using Docker Compose with Podman lacked full BuildKit support or other features. They detail a setup using the official Docker Compose CLI with a Podman socket and a custom BuildKit daemon. Finally, they introduce Bakah, their own tool that translates Docker Bake files to use Buildah for a truly daemonless build process.

### 29. Miles from the ocean, there's diving beneath the streets of Budapest

 Score: 125 Comments: 27 [Link](https://www.cnn.com/2025/08/18/travel/budapest-diving-molnar-janos-cave)

 > Access to CNN.com has been blocked for anonymous users until August 22, 2025. This security measure was implemented because the site was the target of a suspected DDoS attack, which involved too many requests.

### 30. Skill issues – Dialectical Behavior Therapy and its discontents (2024)

 Score: 48 Comments: 19 [Link](https://www.thedriftmag.com/skill-issues/)

 > Marsha Linehan developed Dialectical Behavior Therapy (DBT) based on her own traumatic experience in a psychiatric hospital. DBT treats emotional distress by teaching specific skills for emotional regulation, combining acceptance with behavioral change. It has become a gold standard for high-risk patients and has expanded into schools, workplaces, and popular culture. The article critiques DBT's focus on individual skill acquisition, linking it to a corporate ethos of self-management that risks depoliticizing suffering.

