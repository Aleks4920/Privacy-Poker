# Privacy Poker, Project Submission

**Course:** Usable Security and Privacy  
**Deadline:** 16 June 2025  
**Project type:** Educational game (online, browser-based)  
**How to run:** Open `index.html` in any modern browser, no installation required.

---

## License

This work is licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

You are free to share and adapt this material for any purpose, even commercially, as long as appropriate credit is given, a link to the license is provided below.

Full license text: https://creativecommons.org/licenses/by/4.0/legalcode

---

## AI Tool Disclosure

**Claude (Anthropic, claude-sonnet-4-5)** was used during this project:

**Game implementation:** This the development of this game was drafted manually and improved with Cluade Code. The creation of multiple scenarios was assisted by Claude. The final code was reviewed and edited by the myself to ensure it met the project requirements and functioned correctly.

No AI tool was used to generate the scientific references or this report; citations were manually selected and found with the help of Google Scholar Lab search tool.

---

## Scientific Explanation

### Concept and Target Audience

Privacy Poker is a browser based educational game designed to teach **informed consent** and **data minimisation** as core principles of usable privacy. Informed consent in data collection requires that individuals knowingly and voluntarily agree to specific uses of their personal data; in practice, this is often undermined by a combonation of unreadable privacy policies, bundled consent, and the non-disclosure of downstream data uses such as resale to brokers or use in insurance scoring (Acquisti et al., 2015). Data minimisation, found in Article 5(1)(c) of the GDPR, holds that only data strictly necessary for a stated purpose should be collected. Users can rarely distinguish between genuinely required and merely requested data fields, resulting in acceptance due to status quo bias and the low perceived effort of clicking "agree" (Johnson & Goldstein, 2003). Another related concept, **data aggregation harm**, highlights the main mechanic of the game: individually innocuous attributes (location, date of birth, email address) combine into profiles enabling discrimination, de-anonymisation, and manipulation, a risk that is difficult to see or understand in isolation (Solove, 2006).

The target audience is **internet users and students**, who are regular users of the depicted services but may not have reflected on the privacy implications of everyday permissions. The game requires no technical background, making it accessible to all audiences such as psychology students interested in human-computer interaction.

### Game Development Process

The game was designed around a single idea: **personal data used as poker chips**. Players wager data for access to digital services across multiple rounds, each round representing a real-world service category such as weather, social network, e-commerce, navigation, fitness, news, dating app, smart home, etc. This framing makes the otherwise invisible data transaction explicit and introduces the vocabulary of *cost* and *risk* into what is typically a frictionless flow. Each service displays its data demands split into required and optional categories, reflecting the dark-pattern literature showing that most consent interfaces obscure this distinction (Nouwens et al., 2020; Mathur et al., 2019).

Play testing we conducted by myself and a few volunteers. Feedback was collected on the clarity of instructions, the perceived realism of the scenarios, and the emotional impact of the reveal panels. Improvements were made to the game flow, wording and colour scheme to enhance engagement and learning outcomes. The game was built using HTML, CSS, and JavaScript, with a simple state management system.

### Knowledge, Skills, and Attitudes

The game targets multiple learning dimensions. In terms of **knowledge**, players learn to distinguish required from optional data requests; that data is routinely resold to third-party brokers; and that individual data points combine into detailed profiles through aggregation. These facts are delivered immediately after each decision, leveraging the moment of highest relevance to maximise encoding (Cranor, 2012).

In terms of **skills**, repeated practice of the share or withhold decisions across eight rounds trains players to ask, "does this service actually need this data?", that can be applied during real app install and sign-up flows. Each data card displays a sensitivity score (1 to 10), training players to weightrisk across multiple data types.

In terms of **attitudes**, the game aims to shift users from passive acceptance to active evaluation. A persistent privacy score meter and a growing data-broker profile panel make the cumulative cost of sharing visible in real time.

### Limitations and Mitigations

Several limitations should be acknowledged. 

The game simplifies real consent interfaces, which may involve purpose-specific consents, retention periods, and multi-party sharing chains.

The reflective mindset induced by playing a game about privacy may not transfer to real-world conditions, where sign-up flows are completed quickly and under cognitive load. The game is intended as an exemplar educational tool rather than a comprehensive solution to the problem of informed consent.

The privacy facts presented are illustrative of documented industry-wide patterns and are not allegations against specific companies; all named services in the game are fictional.

---

## References

Acquisti, A., Brandimarte, L., & Loewenstein, G. (2015). Privacy and human behavior in the age of information. *Science*, *347*(6221), 509–514. https://doi.org/10.1126/science.aaa1465

Cranor, L. F. (2012). Necessary but not sufficient: Standardized mechanisms for privacy notice and choice. *Journal on Telecommunications and High Technology Law*, *10*(2), 273–308.

Johnson, E. J., & Goldstein, D. (2003). Do defaults save lives? *Science*, *302*(5649), 1338–1339. https://doi.org/10.1126/science.1091721

Mathur, A., Acar, G., Friedman, M. J., Lucherini, E., Mayer, J., Chetty, M., & Narayanan, A. (2019). Dark patterns at scale: Findings from a crawl of 11K shopping websites. *Proceedings of the ACM on Human-Computer Interaction*, *3*(CSCW), Article 81. https://doi.org/10.1145/3359183

Nouwens, M., Liccardi, I., Veale, M., Karger, D., & Kagal, L. (2020). Dark patterns after the GDPR: Scraping consent pop-ups and demonstrating their influence. In *Proceedings of the 2020 CHI Conference on Human Factors in Computing Systems* (pp. 1–13). ACM. https://doi.org/10.1145/3313831.3376321

Solove, D. J. (2006). A taxonomy of privacy. *University of Pennsylvania Law Review*, *154*(3), 477–564. https://doi.org/10.2307/40041279

---
