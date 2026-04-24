# AGI — Outline

Research-driven. Science book, same frame as *Déjà Vu*: one idea per page, chronological, with a gesture, a body, a citation, and a **plain-terms** walk-through at the bottom.

**Each theme holds 4–6 pages. Each page is one research paper or one landmark system.** No overflow, no filler.

**The thesis.** AGI-grade problem solving happens when fluent agents are forced to emit punch cards inside an organization that sustains the loop. Three spines co-evolved for eighty years and are now converging. The proof point is type-state: the compiler, not the evaluator, says yes.

**The spines.**

- **Fluent spine.** Neuron → transformer → agent. Output is language; language is negotiable.
- **Rigor spine.** Punch card → type system → noninterference. Output is a theorem; a theorem is not.
- **Organizational spine.** Bell Labs → DARPA → DeepMind → Anthropic. Two traditions on this spine: *space-mission engineering* (certainty first, humans expendable) and *agile* (humans first, certainty negotiated). AGI-scale work needs both, and nobody has figured out the blend.

**The convergence.** AlphaFold showed what the three spines do for biology. Gauger (2026) shows what they do for LLM tool authorization — a Rust type-state encoding that makes the compiler the authorization check and proves noninterference against unauthorized principals. The rigor spine, at its proof point, does not need the evaluator.

Sketched 2026-04-23. Revised to the braid.

---

## 01 — The Punch Card

*Rigor spine origin. Specification as artifact.*

- **01.01** The Loom — Jacquard, 1804.
- **01.02** The Census Engine — Hollerith, 1890.
- **01.03** On Computable Numbers — Turing, 1936.
- **01.04** Lambda Calculus — Church, 1936.
- **01.05** FORTRAN — Backus et al., IBM, 1957.

## 02 — The Neuron

*Fluent spine origin.*

- **02.01** A Logical Calculus — McCulloch & Pitts, 1943.
- **02.02** Information, Measured — Shannon, 1948.
- **02.03** Cells That Fire Together — Hebb, 1949.
- **02.04** The Imitation Game — Turing, 1950.
- **02.05** The Perceptron — Rosenblatt, 1958.

## 03 — Theory

*The shared substrate. Both spines point back here.*

- **03.01** Curry–Howard Correspondence — Howard, 1969; Curry, 1934. Propositions are types; proofs are programs.
- **03.02** An Axiomatic Basis — Hoare, 1969. Preconditions, postconditions, invariants.
- **03.03** System F — Girard, 1972; Reynolds, 1974. Polymorphism with proof content.
- **03.04** Martin-Löf Type Theory — Martin-Löf, 1972. Dependent types. The foundation of Coq, Agda, Lean.
- **03.05** ML and Type Inference — Milner, 1978. Let the compiler infer what a theorem prover would have demanded.

## 04 — The Winter

*Both spines stall. Differently.*

- **04.01** The XOR Wall — Minsky & Papert, 1969.
- **04.02** The Lighthill Report — UK SRC, 1973.
- **04.03** A Discipline of Programming — Dijkstra, 1976.
- **04.04** Temporal Logic of Programs — Pnueli, 1977.
- **04.05** Model Checking — Clarke, Emerson, 1981; Queille, Sifakis, 1982.
- **04.06** Backprop, Again — Rumelhart, Hinton, Williams, 1986.

## 05 — Types as Proof

*Rigor spine's production form. Where formal methods became something a working engineer could ship.*

- **05.01** A Lattice Model of Secure Information Flow — Denning, 1976.
- **05.02** Typestate — Strom & Yemini, 1986.
- **05.03** Sound Flow Types — Volpano, Smith, Irvine, 1996.
- **05.04** Language-Based Information Flow Security — Sabelfeld & Myers, 2003.
- **05.05** RustBelt — Jung, Jourdan, Krebbers, Dreyer, 2017. Safe Rust proved memory-safe in Iris.
- **05.06** Featherweight Typestate — Garcia et al., 2014. Nominal calculus with flow-sensitive permissions.

## 06 — The Long Thaw

*Fluent spine re-emerges.*

- **06.01** Convolutions on Digits — LeCun et al., 1989.
- **06.02** The Vanishing Gradient — Hochreiter, 1991.
- **06.03** LSTM — Hochreiter & Schmidhuber, 1997.
- **06.04** LeNet-5 — LeCun, Bottou, Bengio, Haffner, 1998.
- **06.05** Deep Belief Nets — Hinton, Salakhutdinov, 2006.

## 07 — The Substrate

*Organizational spine arrives: compute and data.*

- **07.01** CUDA — NVIDIA, 2007.
- **07.02** ImageNet — Deng et al., 2009.
- **07.03** AlexNet — Krizhevsky, Sutskever, Hinton, 2012.
- **07.04** Word2Vec — Mikolov et al., 2013.

## 08 — Attention

*Fluent spine reaches adulthood.*

- **08.01** Seq2Seq — Sutskever, Vinyals, Le, 2014.
- **08.02** Attention — Bahdanau, Cho, Bengio, 2014.
- **08.03** ResNet — He et al., 2015.
- **08.04** AlphaGo — Silver et al., 2016.
- **08.05** The Transformer — Vaswani et al., 2017.

## 09 — Scale

*Organizational spine compounds.*

- **09.01** GPT-1 / BERT — Radford; Devlin, 2018.
- **09.02** Scaling Laws — Kaplan et al., 2020.
- **09.03** GPT-3 — Brown et al., 2020.
- **09.04** Chinchilla — Hoffmann et al., 2022.
- **09.05** InstructGPT — Ouyang et al., 2022.
- **09.06** Constitutional AI — Bai et al., Anthropic, 2022.

## 10 — The Organization (AlphaFold)

*Brute force plus sustaining org solves a 50-year problem. The template.*

- **10.01** CASP — Moult et al., 1994. Twenty years of shared benchmark.
- **10.02** AlphaFold 1 — Senior, Jumper et al., 2018.
- **10.03** AlphaFold 2 — Jumper et al., 2021.
- **10.04** The Structure Release — EMBL-EBI, 2022. 200M structures.
- **10.05** The Nobel — Royal Swedish Academy, 2024. Hassabis, Jumper, Baker.

## 11 — Engineering for Humans

*Organizational spine, human-sustaining version. Why agile exists.*

- **11.01** The Mythical Man-Month — Brooks, 1975. Adding people to a late project makes it later.
- **11.02** The Psychology of Computer Programming — Weinberg, 1971. Programs are written by people, for people to read.
- **11.03** The Agile Manifesto — Beck, Fowler, Martin, Schwaber, Sutherland et al., 2001. Individuals and interactions over processes and tools.
- **11.04** Continuous Delivery — Humble & Farley, 2010. The deploy is the cadence.
- **11.05** Accelerate — Forsgren, Humble, Kim, 2018. DORA metrics. Evidence that high-throughput teams are also high-quality teams.

## 12 — Engineering for Certainty

*Organizational spine, certainty-first version. Space-mission software. Why it works when agile would fail.*

- **12.01** On the Criteria for Decomposing Systems — Parnas, 1972. Information hiding as a principle.
- **12.02** Safeware — Leveson, 1995. Why systems kill. The discipline of critical-systems engineering.
- **12.03** The Power of Ten — Holzmann, NASA JPL, 2006. Rules for safety-critical code.
- **12.04** DO-178C — RTCA, 2011. The avionics standard. No software flies without it.
- **12.05** seL4 — Klein et al., 2009. A formally verified microkernel in operating use.
- **12.06** SPARK Ada — Altran / AdaCore, ongoing. A verifiable subset of Ada shipping in aerospace and rail.

## 13 — The Drift

*Why fluent alone cannot be trusted.*

- **13.01** Stochastic Parrots — Bender, Gebru et al., 2021. Grammar is not truth.
- **13.02** Sycophancy — Perez et al., Anthropic, 2022. RLHF teaches agreement.
- **13.03** Jailbreaks — Zou et al., 2023.
- **13.04** Scheming — Apollo Research, 2024.
- **13.05** Agentic Misalignment — Anthropic, 2024. Drift compounds per step.

## 14 — The Braid

*Where rigor and fluency meet. Ordered by year; culminates in the proof point.*

- **14.01** ProVerif — Blanchet, 2001. Automated protocol verification.
- **14.02** AlphaCode — Li et al., DeepMind, 2022. Competitive programming at median contestant.
- **14.03** AlphaProof — DeepMind, 2024. Lean + transformer. IMO silver-medal performance.
- **14.04** MCP — Anthropic Model Context Protocol, 2024. A typed socket between model and tools.
- **14.05** P2FGPT — Li, Han, Yuan, Li, Wang, 2025. LLM → ProVerif. Generator / Checker / Modifier.
- **14.06** Type-State Authorization for LLM Tool Schemas — Gauger, 2026. Rust type-state + noninterference proof. The compiler is the evaluator. Zero runtime cost. The proof point.

## 15 — Cryptography and Its Quantum Successor

*The older tradition of the same proof style noninterference uses. And what's coming to break most of it.*

- **15.01** Communication Theory of Secrecy Systems — Shannon, 1949. Perfect secrecy defined. One-time pad proven optimal.
- **15.02** New Directions in Cryptography — Diffie & Hellman, 1976. Public-key. The paper that made the internet possible.
- **15.03** A Method for Obtaining Digital Signatures and Public-Key Cryptosystems — Rivest, Shamir, Adleman, 1978.
- **15.04** The Knowledge Complexity of Interactive Proof Systems — Goldwasser, Micali, Rackoff, 1985. Zero-knowledge.
- **15.05** Algorithms for Quantum Computation — Shor, 1994. Polynomial-time factoring. The threat.
- **15.06** Post-Quantum Cryptographic Standards — NIST, 2024. Kyber, Dilithium, Falcon, SPHINCS+.

## 16 — Governance and Ground Truth

*Who sustains the loop. On what terms.*

- **16.01** The EU AI Act — adopted 2024.
- **16.02** The Biden EO — 2023, rescinded 2025.
- **16.03** SB-1047 — California, 2024, vetoed.
- **16.04** NIST AI RMF — 2023.
- **16.05** Responsible Scaling Policies — Anthropic, OpenAI, DeepMind, 2023–2024.

## 17 — Information Architecture

*The older tradition than either spine. How hierarchical description enables everything downstream — including MCP's JSON Schema, your paper's capability lattice, and every database that ever held a fact.*

- **17.01** Systema Naturae — Linnaeus, 1735. Kingdom → Phylum → Class → Order → Family → Genus → Species. The founding hierarchical taxonomy.
- **17.02** Dewey Decimal Classification — Dewey, 1876. Knowledge as a numerical hierarchy. Every book a 3-digit address.
- **17.03** Five Laws of Library Science and Colon Classification — Ranganathan, 1931–1933. Faceted classification. Humans-first information architecture.
- **17.04** As We May Think — Bush, 1945. The Memex. Associative trails through information. Hypertext before the word.
- **17.05** Augmenting Human Intellect — Engelbart, 1962. NLS. Outlining, windowing, the mouse. The mother of all demos (1968).
- **17.06** Information Management: A Proposal — Berners-Lee, 1989. The memo that became the World Wide Web.

## 18 — Product Design

*How to project software in words. A car is built over years of people saying no to something projected. The specification is the projection; iteration is the no. Every rigor-spine artifact — a proof, a type, a schema — is also a design artifact that survived critique.*

- **18.01** The Sciences of the Artificial — Simon, 1969. Design as a science. Satisficing under constraint. The parable of the watchmakers: hierarchical decomposition is the only way complex systems get built.
- **18.02** A Pattern Language — Alexander, 1977. 253 architectural patterns as a shared vocabulary. Imported to software by Gamma, Helm, Johnson, Vlissides (*Design Patterns*, 1994).
- **18.03** No Silver Bullet — Brooks, 1987. Essential vs. accidental complexity. The hard part of software is the conceptual projection itself; no tool makes it an order of magnitude easier.
- **18.04** The Design of Everyday Things — Norman, 1988. Affordances and signifiers. The user in the loop, named.
- **18.05** The Inmates Are Running the Asylum — Cooper, 1999. Personas. Goal-directed design. The argument that programmers are not designers and the discipline needs its own practice.
- **18.06** Inspired — Cagan, 2008/2017. Discovery vs. delivery. Product-as-structured-no: the process that produces the artifact that survived every critique.

## 19 — The Living System

*Brain research: formation, repair, perishing. What the biological architecture does that the artificial one does not.*

- **19.01** The Neuron Doctrine — Cajal, 1894. The brain is discrete cells with synaptic gaps. Nobel 1906.
- **19.02** A Peculiar Disease of the Cerebral Cortex — Alzheimer, 1907. Neurodegeneration named and catalogued.
- **19.03** Critical Periods in Visual Cortex — Hubel & Wiesel, 1963. The brain's architecture forms through experience during developmental windows. Nobel 1981.
- **19.04** Cortical Remapping — Merzenich, 1984. Adult cortex reorganizes after sensory or motor change. The substrate of self-healing.
- **19.05** The Radial Unit Hypothesis — Rakic, 1988. How the cortex is built during development. Cortical columns as a product of radial migration.
- **19.06** Adult Human Neurogenesis — Spalding, Frisén et al., 2013. Adult humans make ~700 new hippocampal neurons per day. Lifelong renewal is real, and measurable.

## 20 — DevOps

*How software gets operated once deployed. The organizational-spine discipline of keeping systems alive under real load. Production as a sustained loop, not a finish line.*

- **20.01** How Complex Systems Fail — Cook, 1998. Eighteen propositions on the nature of failure in complex systems. The intellectual foundation of modern incident analysis.
- **20.02** The Field Guide to Understanding 'Human Error' — Dekker, 2002. Human error is a symptom of systems, not a cause. Safety-II.
- **20.03** 10+ Deploys Per Day: Dev and Ops Cooperation at Flickr — Allspaw & Hammond, Velocity 2009. The founding talk of the DevOps movement.
- **20.04** The DevOps Handbook — Kim, Humble, Debois, Willis, 2016. The canonical practitioner compendium.
- **20.05** Site Reliability Engineering — Beyer, Jones, Petoff, Murphy (Google), 2016. SLOs, error budgets, toil. The production discipline, formalized.
- **20.06** Observability Engineering — Majors, Fong-Jones, Miranda, 2022. High-cardinality telemetry. Knowing what happened in production, not just whether it broke.

## 21 — The Regulated Body

*How tissue sustains itself. Cancer as the failure mode. The biological proof of the book's thesis — a loop, an organization, a specification. When the spec goes, the tissue goes rogue.*

- **21.01** Apoptosis — Kerr, Wyllie, Currie, 1972. Programmed cell death named and catalogued. Removal as a regulated process, not a failure.
- **21.02** Cell Cycle Checkpoints — Hartwell, 1974; Hunt, Nurse — Nobel 2001. The regulator. Each division gated by a checkpoint that can say no.
- **21.03** Autophagy — Ohsumi, 1993 (Nobel 2016). Cells break down and rebuild their own components. The maintenance loop inside every cell.
- **21.04** Hallmarks of Cancer — Hanahan & Weinberg, 2000 (rev. 2011, 2022). Cancer named as the catalogue of failed regulations. Six (then eight, then ten) hallmarks, each a broken check.
- **21.05** Epithelial Stem Cell Renewal — Blanpain, Horsley, Fuchs, 2007. How skin, intestine, and other epithelia renew. The sustained loop, organ by organ.
- **21.06** Induced Pluripotent Stem Cells — Takahashi & Yamanaka, 2006 (Nobel 2012). Four factors reset an adult cell to an embryonic state. The biological punch-card rewrite: reprogramming the specification.

## 22 — The Fall of Nations

*Civilizational scale of the same argument. Nations are sustained loops. When they stop sustaining — elite overproduction, extractive institutions, declining marginal returns to complexity, institutional decay, inequality past the snap point — they collapse. Same shape as cancer at the tissue level and agentic drift at the protocol level.*

- **22.01** The Collapse of Complex Societies — Tainter, 1988. Declining marginal returns to complexity. Civilizations collapse when the cost of holding things together exceeds the benefit.
- **22.02** Collapse — Diamond, 2005. Five factors in case studies: environmental damage, climate change, hostile neighbors, lost trading partners, societal response.
- **22.03** Why Nations Fail — Acemoglu & Robinson, 2012. Inclusive vs. extractive institutions. The single most-cited contemporary theory of national divergence.
- **22.04** Political Order and Political Decay — Fukuyama, 2014. State capacity decays over time. Rule-of-law, accountable government, and state capacity each decay differently.
- **22.05** Ages of Discord — Turchin, 2016. Cliodynamics. Quantitative structural-demographic theory. Elite overproduction and immiseration as leading indicators.
- **22.06** The Great Leveler — Scheidel, 2017. Inequality accumulates between shocks; only catastrophes (war, revolution, state collapse, plague) reduce it. The mechanism that the other books don't want to be true.

## 23 — The Firm

*Corporate scale of the same argument. Companies are sustained loops too. GE gets too big, the synergy story stops being real, the conglomerate implodes. Startups invert the problem — designed to fail fast, cheaply, before too much is committed. Same mechanism, different posture toward failure.*

- **23.01** Creative Destruction — Schumpeter, 1942. Capitalism works by killing incumbents. The phrase that every subsequent founder has borrowed.
- **23.02** The Visible Hand — Chandler, 1977. Why big firms emerged in the 20th century. The managerial hierarchy as the replacement for the market.
- **23.03** The Innovator's Dilemma — Christensen, 1997. Why the very things that make incumbents successful prevent them from responding to disruptive entrants.
- **23.04** How the Mighty Fall — Collins, 2009. Five stages of corporate decline. The playbook you recognize too late from inside.
- **23.05** The Lean Startup — Ries, 2011. Startups as failure-driven experiments. Build-measure-learn. Pivot on evidence, not ego.
- **23.06** Lights Out — Gryta & Mann, 2020. The specific case study: how GE, the most valuable company in the world in 2000, became a warning by 2018.

## 24 — Evolution

*The original brute-force optimization. Four billion years of search over trillions of organisms, directed only by survival. AlphaFold trains on the output. Every protein it predicts is evolution’s finished work.*

- **24.01** On the Origin of Species — Darwin, 1859. Natural selection named. The mechanism by which variation plus differential reproduction plus time produces adaptation.
- **24.02** Experiments in Plant Hybridization — Mendel, 1866. Discrete inheritance. Traits are particulate, not blended. Rediscovered 1900.
- **24.03** Genetics and the Origin of Species — Dobzhansky, 1937. The Modern Synthesis begins. Mendel's genes meet Darwin's selection.
- **24.04** Molecular Structure of Nucleic Acids — Watson & Crick, 1953. The double helix. The physical carrier of the specification.
- **24.05** On the Origin of Mitosing Cells — Margulis, 1967. Endosymbiosis. Mitochondria and chloroplasts were once bacteria; eukaryotic cells are federations, not individuals.
- **24.06** Punctuated Equilibria — Eldredge & Gould, 1972. Evolution is not gradual. Long stasis punctuated by rapid change — the same pattern every complex system shows.

## 25 — Markets

*Distributed information-processing at civilizational scale. Prices aggregate what no single participant knows. Failure modes: asymmetry, irrationality, instability. The same organizational-spine argument, at the money layer.*

- **25.01** The Wealth of Nations — Smith, 1776. The invisible hand. Markets as coordination without central design.
- **25.02** The Use of Knowledge in Society — Hayek, 1945. The single sharpest article ever written on markets as distributed computation. Prices carry information no planner has.
- **25.03** The Market for Lemons — Akerlof, 1970. Information asymmetry. When the seller knows more than the buyer, the market can unravel. Nobel 2001.
- **25.04** Prospect Theory — Kahneman & Tversky, 1979. Humans do not maximize expected utility. Losses hurt twice as much as equivalent gains feel. Nobel 2002.
- **25.05** Stabilizing an Unstable Economy — Minsky, 1986. The financial instability hypothesis. Stability breeds instability. Long booms end in crisis because they must.
- **25.06** Irrational Exuberance — Shiller, 2000. Published weeks before the dot-com peak. Behavioral finance as the mechanism by which markets deviate from fundamentals. Nobel 2013.

## 26 — Empathy

*What it is, what it is not, and why the distinction matters for systems trained to sound like it. Therapy, theory of mind, mirror neurons, neural substrate, evolutionary substrate, and the critique. The fluent-spine failure mode of sycophancy is a counterfeit of this.*

- **26.01** The Necessary and Sufficient Conditions of Therapeutic Personality Change — Rogers, 1957. Empathy, congruence, unconditional positive regard. The founding paper of humanistic therapy. What a room with a witness actually does.
- **26.02** Does the Chimpanzee Have a Theory of Mind? — Premack & Woodruff, 1978. The phrase enters the literature. Representing what another being knows as a testable capacity.
- **26.03** Does the Autistic Child Have a Theory of Mind? — Baron-Cohen, Leslie, Frith, 1985. The Sally-Anne false-belief task. Theory of mind as a specific, selectively-impaired capacity.
- **26.04** Action Recognition in Premotor Cortex — Rizzolatti, Fadiga, Gallese, Fogassi, 1996. Mirror neurons in macaque F5. The proposed neural substrate of imitation and empathy.
- **26.05** Empathy for Pain Involves the Affective but Not Sensory Components of Pain — Singer et al., 2004. fMRI separates affective from cognitive empathy in the brain. Distinct systems.
- **26.06** Against Empathy — Bloom, 2016. The critique. Empathy is biased, innumerate, and parochial. Rational compassion is the proposed alternative.

## 27 — The Charter

*Corporate legal structure as specification of collective action. Each new form — joint stock, limited liability, nonprofit, LLC, benefit corporation, DAO — is an amendment to what a charter can commit an organization to. The specification of what an entity is *for* is the specification of which loops it must sustain.*

- **27.01** The Dutch East India Company (VOC) — 1602. The first publicly-traded joint-stock company. 21-year charter from the States General of the Netherlands. The first IPO. The template every subsequent corporate form extends.
- **27.02** Limited Liability Act — United Kingdom, 1855 (consolidated in Companies Act 1862). Investor personal wealth separated from corporate debt. Modern investment becomes possible.
- **27.03** 501(c)(3) Tax-Exempt Charitable Organizations — US Internal Revenue Code of 1954 (consolidating earlier provisions from 1913). The nonprofit corporation as a legal form with specified public-benefit constraints and tax-exempt status. Over 1.5 million in the US.
- **27.04** The Limited Liability Company — Wyoming LLC Act of 1977. Pass-through taxation plus limited liability. All 50 states adopted by 1996. Default form for small business today.
- **27.05** The Benefit Corporation — Maryland, 2010 (first state); Oregon Benefit Company, ORS 60.750–60.770, enacted 2013; Delaware Public Benefit Corporation, 2013. Legal accountability to a specified public benefit beyond shareholder return. Over 40 states have adopted.
- **27.06** Wyoming DAO LLC — 2021. Decentralized Autonomous Organizations given legal personhood as a variant of LLC. Crypto-native governance structures enter the legal system.

## 28 — The Brain's Networks

*The brain is not compartments. It is overlapping networks, some of which touch, some of which oppose each other, some of which are in active rivalry. The self, cognitive empathy, and autobiographical memory share the same hardware. The subconscious is a mode, not a location.*

- **28.01** In Search of the Engram — Lashley, 1929. Fifty years of lesion experiments looking for *the* memory location. There isn't one. Memory is distributed.
- **28.02** A Default Mode of Brain Function — Raichle et al., 2001. The Default Mode Network. The brain at rest is not idle — it is self-referencing, time-traveling, mentalizing.
- **28.03** An Information Integration Theory of Consciousness — Tononi, 2004. IIT. Consciousness is integrated information; quantitatively, Φ.
- **28.04** Anticorrelated Functional Networks — Fox, Snyder, Vincent, Corbetta, Van Essen, Raichle, 2005. The DMN and the task-positive network are in opposition. You cannot run both at full bore at once.
- **28.05** The Human Connectome — Sporns, Tononi, Kötter, 2005. The brain as a graph. The program that now maps every connection.
- **28.06** Consciousness and the Brain — Dehaene, 2014. Global Workspace Theory. Consciousness is what happens when information is broadcast across specific long-range networks.

## 29 — The Internet

*Engineered counterpart to the brain's resilience. Designed by DARPA during the Cold War to survive nuclear attack. Packet-switched, end-to-end, routes around damage. "Never die" is explicitly the second-highest design priority.*

- **29.01** Intergalactic Computer Network — Licklider, 1963. The DARPA memo that funded the research community that built ARPANET. Computing as communication.
- **29.02** On Distributed Communications — Baran, 1964. RAND. Packet switching. A network that routes around destroyed nodes. Built for the scenario nobody wanted.
- **29.03** ARPANET First Message — Kleinrock / UCLA, October 29, 1969. Two letters ("L", "O") reach Stanford before the remote system crashes. Packet switching, demonstrated.
- **29.04** A Protocol for Packet Network Intercommunication — Cerf & Kahn, 1974. TCP/IP. The protocol that lets networks of networks interoperate. The *internet*, named.
- **29.05** End-to-End Arguments in System Design — Saltzer, Reed, Clark, 1984. The architectural principle that kept the internet evolvable: keep the network simple; put the smarts at the edges.
- **29.06** The Design Philosophy of the DARPA Internet Protocols — Clark, 1988. Seven design goals, ranked. Survivability was #2. The paper that answers "why does the internet actually work."

## 30 — Applied

*Monday morning. What to carry.*

- **30.01** Reading a Model Card as a Specification.
- **30.02** Wrapping an Agent in a Type-Checked Tool Interface.
- **30.03** Writing a Noninterference Property for Your Domain.
- **30.04** Building the Loop Your Organization Can Sustain — agile and space-mission, blended.
- **30.05** When to Turn It Off.

---

## Design notes

- **One theme, 4–6 pages. No exceptions.** If a theme outgrows the cap, it splits.
- **One paper per page.** The page *is* the paper.
- **Three spines, braided.** Fluent (02, 06, 08, 09, 13). Rigor (01, 03, 05, 14). Organizational (04, 07, 10, 11, 12, 15). Themes are tags; the reading order is chronological.
- **Curry–Howard is the hinge of Theme 03.** Once types = propositions, every subsequent rigor-spine page is an application.
- **Gauger 2026 is the proof point.** Every theme points to 14.06. The compiler as the yes/no surface replaces the evaluator as the alignment tax. This is what the book is for.
- **AlphaFold is the organizational template.** Theme 10 is what an org can do when it sustains a loop long enough. 11 and 12 are *how* orgs sustain loops — with humans, with certainty.
- **Plain-terms at bottom.** Same `eli5` contract as *Déjà Vu*.
- **Gesture / body / citation / source link.** Every page. Quote and narrator optional.
- **The ending is Applied.** Chapter 16 is the Monday-morning protocol. You leave the book with a type interface to wrap your agent in.
