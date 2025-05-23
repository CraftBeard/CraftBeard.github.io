Updated at 2025-05-23 17:11:06 (UTC+8)

### 1. John Carmack talk at Upper Bound 2025 – slides and notes

 Score: 147 Comments: 52 [Link](https://twitter.com/ID_AA_Carmack/status/1925710474366034326)

 > John Carmack shared his slides and detailed notes from his Upper Bound 2025 talk on research directions, mentioning the full video will be available later. This was his first time creating a slide deck for a presentation.

### 2. KumoRFM: A Foundation Model for In-Context Learning on Relational Data

 Score: 16 Comments: 2 [Link](https://kumo.ai/company/news/kumo-relational-foundation-model/)

 > KumoRFM is a Relational Foundation Model (RFM) designed for in-context learning on structured relational data, eliminating the need for task-specific training. It outperforms traditional methods by 2%–8% and improves by 10%–30% when fine-tuned, while being significantly faster. The model uses a table-invariant encoding scheme and a Relational Graph Transformer to handle multi-table data. It supports tasks like classification, regression, and link prediction with minimal code. KumoRFM enables real-time predictions, streamlining AI adoption for relational databases.

### 3. Tallest Wooden Wind Turbine

 Score: 38 Comments: 9 [Link](https://modvion.com/)

 > Modvion builds modular wooden wind turbine towers that are lighter, stronger, and more sustainable than steel. Their solution reduces transport costs, enables taller towers, and stores carbon, cutting emissions by 25%. Backed by partners like Vestas and Enel Green Power, they aim to scale globally.

### 4. Show HN: Defuddle, an HTML-to-Markdown alternative to Readability

 Score: 246 Comments: 48 [Link](https://github.com/kepano/defuddle)

 > Defuddle is a tool that extracts and cleans up the main content from web pages by removing clutter like headers, footers, and ads. It provides clean HTML output, supports metadata extraction, and works in both browser and Node.js environments. The project is open-source under the MIT license. [GitHub](https://github.com/kepano/defuddle).

### 5. Lockheed Martin and IBM combine quantum computing with HPC in new research

 Score: 27 Comments: discuss [Link](https://www.ibm.com/quantum/blog/lockheed-martin-sqd)

 > IBM and Lockheed Martin researchers demonstrated quantum computing's ability to model open-shell molecules like methylene (CH₂) using the sample-based quantum diagonalization (SQD) technique. This hybrid approach combines quantum and classical computing to accurately simulate complex electronic structures, achieving results comparable to high-accuracy classical methods. The study highlights quantum computing's potential for advancing chemistry, aerospace, and materials science by tackling challenging simulations beyond classical capabilities.

### 6. Claude 4

 Score: 1732 Comments: 971 [Link](https://www.anthropic.com/news/claude-4)

 > Anthropic has launched Claude 4, featuring two new models: **Claude Opus 4** (top-tier for coding and complex tasks) and **Claude Sonnet 4** (efficient upgrade). Both support extended reasoning, tool use, and improved memory. Claude Code is now generally available with IDE integrations. Pricing remains unchanged, and the models are accessible via Anthropic’s API and cloud platforms.

### 7. That fractal that's been up on my wall for years

 Score: 412 Comments: 31 [Link](https://chriskw.xyz/2025/05/21/Fractal/)

 > The author describes a fractal they doodled in middle school, later named "the wallflower," which they analyzed using linear algebra and matrix-based number systems. They explore its 2D properties, generalize it to 3D and 4D, and connect it to exotic number systems like balanced ternary and quaternions. The fractal's structure reveals unexpected mathematical relationships, blending geometry, algebra, and number theory.

### 8. Airport for DuckDB

 Score: 110 Comments: 15 [Link](https://airport.query.farm/)

 > The Airport extension adds Arrow Flight support to DuckDB, enabling remote data querying, modification, and storage via Arrow Flight servers. It allows DuckDB to access non-tabular data, add custom SQL functions, and provide fine-grained access control. The extension is installed via SQL commands and leverages Apache Arrow's high-performance RPC framework.

### 9. Does Earth have two high-tide bulges on opposite sides? (2014)

 Score: 204 Comments: 57 [Link](http://physics.stackexchange.com/questions/121830/does-earth-really-have-two-high-tide-bulges-on-opposite-sides)

 > The article is inaccessible due to a 403 error and requires CAPTCHA verification to confirm the user is human before proceeding.

### 10. 32 bits that changed microprocessor design

 Score: 83 Comments: 16 [Link](https://spectrum.ieee.org/bellmac-32-ieee-milestone)

 > Bell Labs' Bellmac-32, developed in the late 1970s, was the first commercially viable 32-bit microprocessor using CMOS technology. Though not widely adopted, its innovations in speed and energy efficiency paved the way for modern smartphone chips. The IEEE recently honored it as a Milestone for its lasting impact on microprocessor design.

### 11. Mozilla to shut down Pocket and Fakespot

 Score: 938 Comments: 587 [Link](https://support.mozilla.org/en-US/kb/future-of-pocket)

 > Pocket will shut down on July 8, 2025, with data export available until October 8, 2025. Premium users will receive prorated refunds, and the newsletter will transition to "Ten Tabs." Users are advised to export their saved content before the final deletion date.

### 12. How to cheat at settlers by loading the dice (2017)

 Score: 108 Comments: 91 [Link](https://izbicki.me/blog/how-to-cheat-at-settlers-of-catan-by-loading-the-dice-and-prove-it-with-p-values.html)

 > This article explains how to cheat in Settlers of Catan by loading dice to favor rolling sixes, supported by statistical analysis. The author demonstrates that biased dice provide a 5-15 card advantage per game and argues that standard p-value tests can't detect cheating within a single game. The post also critiques flaws in scientific significance testing and suggests alternatives like Bayes factors. Peer review feedback highlights minor calculation errors but doesn't change the main conclusions.

### 13. The Future of Flatpak

 Score: 232 Comments: 146 [Link](https://lwn.net/Articles/1020571/)

 > Flatpak is popular but development has stagnated due to a lack of reviewers, leaving many pull requests unmerged. Sebastian Wick suggests moving to OCI for better tooling and ecosystem support. Key issues include slow adoption of new features, outdated sandboxing, and networking security concerns. The project needs more contributors to address these challenges.

### 14. Fast Allocations in Ruby 3.5

 Score: 216 Comments: 53 [Link](https://railsatscale.com/2025-05-21-fast-allocations-in-ruby-3-5/)

 > Ruby 3.5 introduces a significant speedup in object allocations by inlining `Class#new`, making allocations up to 6.5x faster for keyword parameters. The optimization eliminates parameter copying and stack frames, improving performance for both positional and keyword arguments. Benchmarks show consistent speedups, with YJIT further enhancing gains. The change reduces overhead but removes the `Class#new` frame from stack traces.

### 15. Improving performance of rav1d video decoder

 Score: 273 Comments: 94 [Link](https://ohadravid.github.io/posts/2025-05-rav1d-faster/)

 > The author improved the performance of the `rav1d` AV1 decoder by 1% on an M3 Mac by avoiding unnecessary buffer zeroing with `MaybeUninit` and optimizing `PartialEq` implementations for small structs. These changes reduced runtime by 1.7% without introducing new unsafe code. The optimizations were identified by comparing profiler snapshots of `rav1d` and `dav1d`.

### 16. Sketchy Calendar

 Score: 60 Comments: 14 [Link](https://www.inkandswitch.com/ink/notes/sketchy-calendar/)

 > This article explores creating a hybrid calendar that blends the flexibility of paper planners with the convenience of digital apps, aiming to offer personalization and functionality beyond traditional rigid calendar tools.

### 17. A Formal Mathematical Investigation on the Validity of Kellogg's Glaze Claims

 Score: 10 Comments: discuss [Link](https://old.reddit.com/r/theydidthemath/comments/1iljmig/_/)

 > A Reddit user pointed out a mathematical error on Kellogg's Frosted Flakes packaging, which claimed spheres (donut holes) have more surface area for glaze than toruses (donuts). The user proved this wrong using surface area formulas and received a response from Kellogg's apologizing for the confusion and offering a coupon. The post sparked discussions about optimal shapes for maximum glaze.

### 18. We’ll be ending web hosting for your apps on Glitch

 Score: 110 Comments: 58 [Link](https://blog.glitch.com/post/changes-are-coming-to-glitch/)

 > Glitch is ending web hosting for apps on July 8, 2025, due to rising costs and competition from newer platforms. Users can download their code and set up redirects until the end of 2025. Glitch Pro subscriptions will be refunded, and the team will provide migration guides. The focus is now on supporting the community through this transition.

### 19. A South Korean grand master on the art of the perfect soy sauce

 Score: 163 Comments: 135 [Link](https://www.theguardian.com/world/2025/may/21/without-time-there-is-no-flavour-a-south-korean-grand-master-on-the-art-of-the-perfect-soy-sauce)

 > The Guardian's domain is blocked until May 23, 2025, due to suspected DDoS abuse linked to an article about Emma Thompson. The site received too many requests, triggering a security error.

### 20. I Built My Own Audio Player

 Score: 219 Comments: 120 [Link](https://nexo.sh/posts/why-i-built-a-native-mp3-player-in-swiftui/)

 > In 2025, Apple still makes it difficult to play personal MP3s without subscriptions, prompting the author to build their own SwiftUI-based music app with full-text search, iCloud support, and local-first functionality. Frustrated by Apple's paywalls and third-party app limitations, they explored React Native before switching to SwiftUI for better file access and performance. The app uses SQLite for storage and FTS5 for fast search, offering a seamless offline music experience. Despite technical hurdles, the project highlights Apple's restrictive ecosystem, where sideloading remains limited even after regulatory changes.  

[GitHub link](https://github.com/nexo-tech/music-app)

### 21. Ancient law requires a bale of straw to hang from Charing Cross rail bridge

 Score: 74 Comments: 82 [Link](https://www.ianvisits.co.uk/articles/ancient-law-requires-a-bale-of-hay-to-hang-from-charing-cross-rail-bridge-81318/)

 > An ancient law requires a bale of straw to hang from Charing Cross rail bridge when scaffolding reduces the height under its arches, as a warning to river traffic. This tradition, upheld by the Port of London Thames Byelaws, remains in place despite its unclear origins. Contractors working on the bridge recently added straw bales to comply with the rule. The bales will move along the bridge as maintenance progresses over the next few years.

### 22. Loading Pydantic models from JSON without running out of memory

 Score: 98 Comments: 34 [Link](https://pythonspeed.com/articles/pydantic-json-memory/)

 > The article explains how to reduce memory usage when loading large JSON files into Pydantic models by using `ijson` for incremental parsing and switching to dataclasses with slots. These optimizations cut peak memory from 2000MB to 450MB for a 100MB JSON file. The author suggests Pydantic could improve memory efficiency by adopting similar techniques.

### 23. Richard Garwin’s role in designing the hydrogen bomb was obscured

 Score: 51 Comments: 22 [Link](https://www.nytimes.com/2025/05/19/science/richard-garwin-hydrogen-bomb.html)

 > The article discusses Richard Garwin's contributions to the development of the hydrogen bomb, highlighting his scientific achievements and impact on nuclear weapons technology. (Note: The actual content is inaccessible due to a 403 error.)

### 24. America is in danger of experiencing an academic brain drain

 Score: 25 Comments: 26 [Link](https://www.economist.com/science-and-technology/2025/05/21/america-is-in-danger-of-experiencing-an-academic-brain-drain)

 > America risks losing top academic talent due to policy changes and funding cuts, potentially benefiting other countries while harming global scientific progress.

### 25. When a team is too big

 Score: 83 Comments: 79 [Link](https://blog.alexewerlof.com/p/when-a-team-is-too-big)

 > A large team of specialists struggled with inefficiency, miscommunication, and disengagement. After experimenting with splits and async standups, they shifted to a generalist model, fostering shared ownership and collaboration through mob programming. This improved productivity and resilience but required balancing learning depth with burnout risks. The key takeaway: continuous experimentation and cultural adaptability are essential for team success.

### 26. Show HN: SQLite JavaScript - extend your database with JavaScript

 Score: 162 Comments: 47 [Link](https://github.com/sqliteai/sqlite-js)

 > SQLite-JS is an extension that enables custom SQLite functions (scalars, aggregates, window functions, collations) using JavaScript. It allows dynamic data manipulation within SQLite by loading pre-built binaries or building from source. Functions can be synced across devices and evaluated directly in queries. The project is open-source under the MIT License.

### 27. Launch HN: WorkDone (YC X25) – AI Audit of Medical Charts

 Score: 63 Comments: 51 [Link](item?id=44063000)

 > The error indicates a validation issue where the domain "item" couldn't be resolved, resulting in a 400 status code. The system failed to process the request due to this unresolved domain.

### 28. When good pseudorandom numbers go bad

 Score: 58 Comments: 16 [Link](https://blog.djnavarro.net/posts/2025-05-18_multivariate-normal-sampling-floating-point/)

 > The article discusses how floating-point arithmetic errors can cause irreproducible results in multivariate normal sampling, even when using `set.seed()` in R. It compares `MASS::mvrnorm()` and `mvtnorm::rmvnorm()`, showing the latter is more robust due to its handling of matrix decompositions. The author recommends using `mvtnorm::rmvnorm()` with `method = "chol"` for better reproducibility.

### 29. 1,145 pull requests per day

 Score: 90 Comments: 64 [Link](https://saile.it/1145-pull-requests-per-day/)

 > The article is unavailable due to a 404 Not Found error, indicating the page does not exist. The server is running nginx/1.18.0 on Ubuntu.

### 30. Problems in AI alignment: A scale model

 Score: 42 Comments: 23 [Link](https://muldoon.cloud/2025/05/22/alignment.html)

 > The article critiques the narrow technical focus of AI alignment discussions, arguing that broader societal selection—like purchasing, regulation, and public discourse—plays a larger role in shaping AI's impact. It compares AI alignment to other industries (e.g., pharmaceuticals) where ethical outcomes depend on decentralized societal forces, not just lab work. The author urges prioritizing this "big work" of societal influence over purely technical solutions.

