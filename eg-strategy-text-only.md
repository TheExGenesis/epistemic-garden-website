# Epistemic Garden \- Strategy

*Epistemic Garden runs the [Community Archive](https://www.community-archive.org/) and its discord server which serves as a Schelling point for [open memetics research](https://discord.gg/5mbWEfVrqw).*

## Executive Summary

**Online communities** are often rich sensemaking spots where people compare notes to figure out the truth, and decide on what to do together.

However, people lack awareness of the **narrative patterns** shaping the online information landscape, and are vulnerable to coordinated intentional spread of harmful narratives.

**Epistemic Garden** is a non-profit research and development lab that builds tools to map how ideas spread. We follow a living lab philosophy, iterating with online communities to improve their knowledge production and robustness.

We are building:

* A continuous stream of social media data via a crowd-sourced browser extension (the **Community Archive**),  
* The **Nooscope.** A tool we can point at the realm of ideas and track their origins and interactions over the social graph.  
* A portfolio of AI tool prototypes. See list [below](#shovel-ready-prototype-ideas).

Why we’re different

* **Open by default.** Code, data, and methods are public, enabling audit and downstream innovation.  
* **Community-oriented and supporting research.** Volunteer data donors are our main stakeholders; usage and research outputs drive our metrics.

**Traction to date**

* 17M tweets from 260 accounts [archived](https://www.community-archive.org/), MVP data streaming extension live on Chrome \+ Firefox, [6 prototypes](https://github.com/TheExGenesis/community-archive/blob/main/docs/apps.md) built   
  * [Keyword trends app](https://communityarchive.substack.com/p/exploring-historical-trends-in-the): like google trends, very important research primitive .  
  * [Birdseye](https://xiqo.substack.com/cp/163163201): a top down view of one’s body of work by topic and over time.  
  * [NYC Hackathon](https://xiqo.substack.com/cp/163163264): 30 participants, 15 submissions, including a genealogical analysis of viral terms.  
  * [NeurIPS submission](https://communityarchive.substack.com/p/were-submitting-a-paper-about-the): presenting the community archive dataset and finding a core of cultural producers in the network.  
* Core team assembled (1 ML engineer, 1 SWE, 1 community manager).  
* $175k angel funding from Vitalik Buterin, the Survival and Flourishing Fund, and Peter Wang.

**Ask**  
$1M would extend our runway to 2 years as 3-5 FTEs as we:

1. Scale the archive to 100k+ daily posts in real-time and multi-platform intake,  
2. Release the Nooscope and publish peer-reviewed validations,  
3. Consolidate our contributors by organising in-person focused-work events and online community calls.

With this backing, we’ll improve online communities’ situational awareness and robustness to memetic, and ability to protect their own interests and discourse. 

## Situation

1. **What’s the problem?**  
- **The internet is like a jungle**: chaotic and full of wonders, and threats. **People lack “jungle eyes”**, or an informed awareness of the hidden patterns, adversarial actors, and narrative forces shaping the online information landscape.  
- **Ads and psyops** **compete with legitimate information** for your attention and push an agenda that isn’t yours. AI manipulation is ramping up massively both individually (e.g. chatGPT sycophancy) and publicly (e.g. political twitter bots and more).  
- **Social media data is closed**. That makes it difficult to analyse.  
2. **Why are current methods not good enough?**  
- No open tools to track the spread of ideas quantitatively.  
- As AI bots become widespread and then the majority of nodes in the spread of ideas, runaway narrative risks increase.  
- There are no community-first approaches to mapping their own information environment.  
  - Community Notes is a step in the right direction but not sufficient because it’s per-tweet, and doesn't address wider patterns.  
  - Private companies and governments have visibility into wider information diffusion patterns but those aren’t public.  
3. **Why is it novel?**  
- AI uncovers lots of low-hanging fruit in the space of tools for interpreting the information environment.  
- Community focus, we crowd-source data, benefit data volunteers, and enable many people to contribute.  
4. **What happens if unaddressed?**  
- An example of a strictly memetic risk: Stories about rogue AGI making it to the training set of LLMs and directly causing those behaviors. ([source](https://nostalgebraist.tumblr.com/post/785766737747574784/the-void))  
- Without open social media data, we lose the historical record of intellectual production.  
- Confusion, Loneliness, Division, Radicalisation, Authoritarianism  
- It is hard for people to coordinate and defend their own interests from the whims of platforms and third actors, protect themselves, pursue their own flourishing.

## Mission

1. **Map how ideas spread to improve online knowledge production**. Help people to figure out what’s true together and to make better decisions together. AI reveals low hanging fruit, we pick it.   
   1. Gather **voluntary data** from twitter (other sources later).  
   2. Build **tools to interpret our information environment** in the open.  
   3. Cultivate a **scene of builders and researchers**.  
2. Move towards **a germ theory for memetics**, find public health interventions comparable to hand-washing.

## Approaches

See Appendix for high level strategy.

1. **🛠️ Technical: Build infra and tools**  
   1. What **capabilities** do we need?  
      1. Data science and ML  
      2. Human computer interface design  
      3. Software engineering  
      4. Product chops  
   2. What are the **risks**?  
      1. Open data and open memetics tools also empower smaller bad actors  
         * Can mitigate by clearly informing users of the risk and having multiple levels of access to tools.  
      2. Twitter may want to stop us (we can move to bluesky)  
         * We’re starting with Twitter (X) because we believe it’s still where the most consequential discourse is happening.  
         * There’s a world where the community persuades Elon we’re right.  
      3. Existing theory may not be good enough to be useful, and our own research may be too slow   
         * We can be a useful analytics layer even without breakthroughs.  
   3. What are the approach’s **limitations**?  
      1. On twitter: limited by the data we’re able to gather / users we convert.  
      2. On bluesky: limited by the quality of discourse, cohesion of social fabric, and our immersion in community there.  
      3. Our approach requires community trust, so they’re important stakeholders.  
         * We can maintain it by hosting regular events and communication.  
2. **🏡 Community development: Crowdsource data, provide value to those users, and cultivate a scene of builders and researchers**  
   1. What **capabilities** do we need?  
      1. Vision  
      2. Facilitation  
      3. Events (Memetics fellowship and conference)  
      4. Communication  
      5. Academic network  
      6. *Research taste / agenda*  
      7. Good documentation  
   2. What are the **risks**?  
      1. Scaling too early / trying to involve too many people.  
      2. Not faithfully syncing with the technical side on what is doable.  
   3. What are the approach’s **limitations**?  
      1. Impact capped by what we can accomplish technically.  
      2. Hype has cycles and can die down.

## Milestones {#milestones}

1. **High level strategy**  
   Two flywheels:  
- **Community trust \- Data volunteers \- Useful tools**: We seeded our database with existing trust, and keep it growing by providing value to the community via useful tools and insights.  
- **Useful tools \- Valuable research \- Prestige (or money)**: we build tools that enable research (done by others or us) that massively improve public health in the information sphere, which lets us ask for more donations. Alternatively, our prototypes can be spun out into products that make money.  
    
2. **Milestones**  
   1. **📈 Real time data**  
      1. 1000 users using our browser extension that streams tweets they see to the community archive.  
   2. **🌍 Whole-Earth moment for the noosphere**  
      1. When Stewart Brand campaigned for NASA to release a photo of the entire earth, it shifted how humanity saw itself. We’ll do the same to reveal the plane of ideas as an arena that can be understood.  
      2. V0 will require a pipeline to embed our real time stream of data and to plot them with [DataMapPlot](https://datamapplot.readthedocs.io/).  
   3. **🔬 The Nooscope**  
      1. A bi-weekly or monthly report of memetic trends, empowering a community with situational awareness of its information space  
      2. A visual dashboard of explorable real-time events, animating idea diffusion on a social graph.  
   4. **📚 A Portfolio of Prototypes**  
      1. First and foremost we want to provide value to the community volunteering its data. We don’t know what’s going to work ahead of time, but we are excited about a handful of directions that we can prototype quickly. See list [below](#shovel-ready-prototype-ideas).  
   5. **🏡 Iterate based on community feedback**  
      1. [Living lab](https://en.wikipedia.org/wiki/Living_lab) style.

    


3. **Metrics:**  
   1. Users: number of active users in apps  
   2. Data: number of tweets gathered  
   3. Active community members: builders and researchers  
      1. Number of 3rd party apps  
      2. Number of papers using our data or tools or methods or citing us  
   4. Stretch goal: Twitter/X opens up data

## Outcomes

1. **What does success mean for stakeholders?**  
   1. Community and individuals  
      1. **Memetic sovereignty on social media (twitter and bluesky)**: People can reference past events and what others they trust said about them, how they reacted, what positions they took, etc \- people can track where ideas came from. eg from “right wing cluster”, from the “lesswrong” cluster, from the “chinese ML” cluster  
         1. By “memetic sovereignty” we mean something like the state of having the awareness, tools, and community support to maintain agency over one's beliefs and information environment, resisting manipulation and exercising choice in how one engages with influential narratives.  
      2. **Resistance to AI manipulation on social media** and psyops by grounding their epistemics robustly in their community and direct social ties  
      3. **Better coordination on social media**: people are finding friends and collaborators faster, finding more common ground, figuring out the truth to their satisfaction faster, sourcing advice and knowledge faster (how do we measure this? Surveys? Just usage counts?)  
      4. **A cultural template** for an approach other communities can take to build their jungle eyes and protect themselves.  
   2. Builders  
      1. There is a layer of underlying technology and data that lets people build coordination and analysis tools easily.  
   3. Researchers  
      1. Tools enable studying cohesive communities with cultural heft \- ours or other communities who choose to follow the same cultural pattern  
   4. Funders  
      1. Prestige for hydrating a budding research scene that   
2. **What else is affected?**  
   1. The wider scene of sensemaking / coordination tech / memetics research.  
      1. Builders: [Cosmik](https://www.cosmik.network/), [Discourse graphs](https://discoursegraphs.com/#resources), [Nanopublications](https://nanopub.net/), [Community Notes](https://docs.google.com/document/d/17egAud513mGWyLjhG2U1HH7pdAJAlh5yG-hQ_9glG3c/edit#heading=h.gw7wns446fl0), [Bridging algorithms](https://bridging.systems/), [Collective intelligence project](https://www.cip.org/)  
      2. Funders: [SFF](https://survivalandflourishing.fund/), [OSV](https://www.osv.llc/oshaughnessy-fellowships), [Cosmos](https://cosmos-institute.org/), [Astera](https://astera.org/), [Renaissance](https://renaissancephilanthropy.org/), [Kanro](https://kanro.fi/), [d/acc Shift Grants](https://www.shiftgrants.org/), [Peter Wang](https://github.com/pzwang), [Convergent Research](https://www.essentialtechnology.blog/p/introducing-the-convergent-research), etc   
3. **What next?**  
   1. We gather an all-star team (such as leaders from the orgs above) to start a [Coordinated Research Programme](https://renaissancephilanthropy.org/playbooks/coordinated-research-programs/) or [Focused Research Organisation](https://www.convergentresearch.org/) with 8-figures in funding to take memetics, collective sensemaking, coordination tech field-building to the next level as a public good. E.g. expanding these tools to other data sources such as the AT Protocol. Academia dropped the ball, the private sector doesn’t have the right incentives, we do.

## Administration, Logistics, and Communications

**Who is the facilitator responsible for the project’s completion?**   
Xiq, [@exgenesis](https://x.com/exgenesis).

**Who, if anyone, is the team accountable to?**   
Community archive uploaders, users, Discord community members, our informal advisors.

**What resources and support elements are required?** 

- Next level: $1M to fund a team of 3-5 (AI and research, software engineer, community management and distribution) for 2 years at competitive low 6-figure salaries. 

**What resources are already available and how can they be accessed?** 

- Seed funding from SFF, Vitalik B and Peter Wang.  
- The [Community Archive](https://www.community-archive.org/), an open database and API with 17M tweets from the volunteered archives of \~260 accounts.  
- An [active discord of 300](https://discord.gg/5mbWEfVrqw) members, 40 of whom were present at our [NYC hackathon](https://xiqo.substack.com/p/the-community-archive-hackathon), with 16 submissions of tools and research.  
- A board of informal advisors  
  - [Ivan Vendrov](http://x.com/ivanvendrov) (leading collective intelligence at [Midjourney](https://www.midjourney.com/))  
  - [Brandon Duderstadt](https://scholar.google.com/citations?user=TIapXZQAAAAJ&hl=en) (CEO of [Nomic AI](https://www.nomic.ai/), AI product studio, top embeddings models)  
  - [Brent Baum](http://x.com/_brentbaum) (CEO of [Refract](https://refract.space/), AI Internal Family Systems)  
  - [Rich Bartlett](http://x.com/richdecibels) (CEO of [Microsolidarity](https://www.microsolidarity.cc/), a community-building practice)  
  - Beth Barnes (CEO of [METR](https://metr.org/), an AI Evaluations non-profit)  
  - Academic advisors incoming…

**What are the requirements for participation?**   
Being able to explain your contribution in terms of our coordination doc. A few areas we can use contributors in:

1. software development,   
2. build apps on our data and infra,   
3. research using our tools,   
4. communicate our work,   
5. help refine our frames,  
6. support community facilitation.

**How will the group communicate?**   
On the [Community Archive Discord server](https://discord.gg/5mbWEfVrqw).

**Where and how will the work be done?**   
We coordinate on the [Community Archive Discord server](https://discord.gg/5mbWEfVrqw). Software development on [github](https://github.com/TheExGenesis/community-archive), [modal](https://modal.com/), [supabase](http://supabase.com). Communication on twitter. Sometimes IRL events in NYC or Porto, Portugal.

**Under what circumstances will the project close and the group disintegrate?**   
If Xiq runs out of funding and no one else wants to take up leadership.

**Who are the current collaborators?**

- [Xiq](https://x.com/exgenesis): full-time Lead, ML, SWE, community building  
- [Defender](https://x.com/DefenderOfBasic): part-time communications, marketing  
- [Goat](https://x.com/iaimforgoat): part-time SWE, Product  
- [Emergent](http://x.com/emergentvibe): occasional volunteer, PM and community facilitation, data science   
- [Brandon](https://www.nomic.ai/): occasional volunteer, research contributions, partnership as NomicAI CEO

## Appendix	

### Glossary

**Collective sensemaking**: finding truth together, making decisions together, at multiple scales. (e.g. individual, team, Dunbar-scale, global)  
**Memetics**: the study of how ideas spread  
**Noosphere**: the plane of ideas  
**Nooscope**: a tool that enables looking into the noosphere, to potentially see ideas and ideologies competing, merging, splitting, engaging in parasitism or symbiosis.

### High-level strategy diagram

![][image1]  
**Figure 1**: The diagram illustrates our two core [flywheels](#milestones). 1\. Data: We began with trust in a specific community, solved the cold start by asking them to upload their twitter archive data to [community-archive.org](http://community-archive.org), which enabled us to build useful tools that delivered value back to the community. 2\. Research**:** The tools and data power research (we already have people at Johns Hopkins using our dataset) which we hope will result in a germ theory for ideas, and information hygiene interventions with global impact comparable to handwashing. 

### List of related orgs

1. Sensemaking  
   1. [Cosmik](https://www.cosmik.network/): AI tools for science social media  
   2. [Mosaic Labs](https://mosaic-labs.org/): R\&D for AI tools for collective sensemaking   
   3. [Discourse graphs](https://discoursegraphs.com/#resources): Mapping arguments.  
   4. [Nanopublications](https://nanopub.net/): Academic publishing for tweet-sized objects.  
   5. [Community Notes](https://docs.google.com/document/d/17egAud513mGWyLjhG2U1HH7pdAJAlh5yG-hQ_9glG3c/edit#heading=h.gw7wns446fl0): Crowdsourced twitter fact-checking  
   6. [Bridging Systems](https://bridging.systems/): Org developing the tech underlying Community Notes  
   7. [Collective intelligence project](https://www.cip.org/)  
2. Memetics   
   1. [The European Centre of Excellence for Countering Hybrid Threats](https://www.hybridcoe.fi/publications/hybrid-threats-a-comprehensive-resilience-ecosystem/)  
   2. [EU Disinfo Lab](https://www.disinfo.eu/publications/coordinated-inauthentic-behaviour-detection-tree/)  
   3. [Network Contagion, Research Institute](https://networkcontagion.us/reports/): They publish case reports on the spread of ideology online,   
   4. [Blackbird AI](https://blackbird.ai/): Narrative risk consultants  
   5. [Rook2root](https://rook2root.co/about): Index of dark UX patterns, growth tactics, and other exploits;   
3. Data sovereignty  
   1. [Surfer Protocol](https://surferprotocol.org/): Personal data wallet;   
   2. MiO data wallet  
   3. [AT Protocol](https://atproto.com/): An open data protocol for decentralized social-media  
   4. [Bluesky](http://bsky.app): A twitter clone built on the AT protocol.  
4. Twitter analytics  
   1. [Social database](https://www.socialdatabase.com/): Twitter analytics company

   

### List of aligned (potential) funders

1. [SFF](https://survivalandflourishing.fund/),   
2. [OSV](https://www.osv.llc/oshaughnessy-fellowships),   
3. [Cosmos](https://cosmos-institute.org/),   
4. [Astera](https://astera.org/),   
5. [Renaissance](https://renaissancephilanthropy.org/),   
6. [Kanro](https://kanro.fi/),   
7. [d/acc Shift Grants](https://www.shiftgrants.org/),   
8. [Peter Wang](https://github.com/pzwang),   
9. [Convergent Research](https://www.essentialtechnology.blog/p/introducing-the-convergent-research),   
10. etc   
  


### List of (potential) academic partners

1. Phillip Koralus \- Cosmos Institute, HAI Oxford:   
2. Carey Priebe \- Brendan’s prof, Johns Hopkins  
3. Jure Leskovec \- Andres’ prof Stanford  
4. Francisco C. Santos \- University of Lisbon  
5. Wout’s prof in Amsterdam

### Orgs we like 

- [Obsidian](https://obsidian.md/): bootstrapped, no VC, community-driven  
- [Midjourney](https://www.midjourney.com/): bootstrapped, no VC, space for creativity  
- [OpenStreetMap](https://www.openstreetmap.org/): open data, enables many other apps on top  
- [Qualia Research Institute](https://qri.org/): independent research seeding a new field  
- [Tldraw](https://www.tldraw.com/): playful innovation in AI interfaces  
- [Ink & Switch](https://www.inkandswitch.com/): innovation in human-computer interfaces, local-first, tools for though  
- [Dynamicland](https://dynamicland.org/): new paradigms of HCI, [living lab](https://en.wikipedia.org/wiki/Living_lab)  
- [Indiana U Observatory on Social Media](https://osome.iu.edu/): Our closest comparison in terms of research topic  
- 

### Relevant Literature

- Org philosophy  
  - [Gardening Platforms \- Alex Komoroske](https://docs.google.com/presentation/d/1cY95dRixFho0pMIlrEFcGL_XKVy9vnE4NGOD6TQMj50/view?slide=id.gf2764a25fd_0_0#slide=id.gf2764a25fd_0_0)  
- Easy to understand  
  - [Morphenius’ twitter thread overview of memetics](https://x.com/Morphenius/status/1874964994674295128). Key points:  
    - A pre-paradigmatic science (think zoology before dna, epidemiology before microbe theory, chemistry in the 1700s)  
    - It studies patterns of behavior that survive (in contrast to biology which studies patterns of matter that survive)  
    - Memes can be mutualists (e.g. hand-washing) or parasitic (e.g. caffeine addiction), among other things  
    - Successor to shamanic views about spirits and demons  
  - [CGP Grey video on how ideas spread](https://www.youtube.com/watch?v=rE3j_RHkqJc), cites [this paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=1528077).  
- Projects  
  - [Discourse Graphs](https://discoursegraphs.com/)  
  - [FAIR data principles](https://www.go-fair.org/fair-principles/)  
  - [OECD AI Incident Monitor](https://oecd.ai/en/incidents), many of which are misinformation attacks  
  - [500+ OSINT tools](https://start.me/p/0Pqbdg/osint-500-tools)  
- Academic  
  - [Did Memetics Fail?](http://ijbol.wikidot.com/user:thais:blog:did-memetics-fail)  
  - [Explorations in the Digital History of Ideas: New Methods and Computational Approaches](https://www.cambridge.org/core/books/explorations-in-the-digital-history-of-ideas/59DEBDB675A875ECDDCA3920E71F9CB3)  
  - [Hands-on Network Machine Learning](https://docs.neurodata.io/graph-stats-book/coverpage.html)  
- [Galip, I. (2024). Methodological and epistemological challenges in meme research and meme studies. Internet Histories, 8(4), 312–330.](%20https://doi.org/10.1080/24701475.2024.2359846)  
- [Munk, T. Digital Defiance. Memetic Warfare and Civic Resistance. Eur J Crim Policy Res (2025)](https://link.springer.com/article/10.1007/s10610-025-09613-4#citeas).   
  - [Detection and Characterization of Coordinated Online Behavior: A Survey (2024)](https://arxiv.org/abs/2408.01257v1)  
  - [Detecting coordinated and bot-like behavior in Twitter: the Jürgen Conings case (2024)](https://epjdatascience.springeropen.com/articles/10.1140/epjds/s13688-024-00477-y#:~:text=information%20online,analysis%20of%20text%2C%20but%20our)  
  - [A language framework for modeling social media account behavior (2023)](https://epjdatascience.springeropen.com/articles/10.1140/epjds/s13688-023-00410-9)  
  - [Prosocial Media (2025)](https://arxiv.org/abs/2502.10834)

Important links

- [Community Archive website](https://www.community-archive.org/).  
- See [API docs](https://github.com/TheExGenesis/community-archive/blob/main/docs/api-doc.md) for how to access the archive's supabase DB.  
- [Discord](https://discord.gg/5mbWEfVrqw) community.  
- For a detailed list of what data we use and why, see [archive\_data.md](https://github.com/TheExGenesis/community-archive/blob/main/docs/archive_data.md).  
- Want to donate? Use our [OpenCollective](https://opencollective.com/community-archive/donate).

### **Concrete stories of a world with higher memetic hygiene.** (our success case with the nooscope)

**Scenario 1: Spot a Psyop Early**

* A psyop emerges, e.g., Russia's undermining EU support for Ukraine.  
* Someone checks the nooscope, which flags it: "Likely intentional misinformation originating from X cluster."  
* You see a screenshot of its mapping and immediately recognize and ignore this type of content. Many others, similarly informed, take the same course, making the entire community more resilient.

**Scenario 2: Discourse maps to track an AI model release**

* Initial discourse reveals disagreement among voices trusted by you regarding the AI model's capabilities, the landscape is chaotic, lots of noise.  
* The nooscope's discourse mapping feature is used to quickly synthesize long threads or sets of discussions.  
* The analysis reveals three distinct camps, providing a one-sentence distillation of each's core argument.

**Scenario 3: Matchmaking powered by AI clones tuned on your writing**

* You’re a thinker / builder looking for your tribe  
* An AI-powered emissary, trained on your written work (e.g., tweets), acts as your proxy, discussing your preferred topics and reflecting your values, style, and tone.  
* Your emissary talks to other people’s emissaries to find who you would have most chemistry with  
* You reach out and find new friends, collaborators, funders, etc\!

**Most Ambitious Long-Term Scenario: A functional collective brain**

Feedback flows perfectly in human systems at all scales. Flowing bottom-up from each individual's experiences, being vetted, and aggregating into actionable tasks at the right levels: a fix in neighborhood infrastructure, a change in company policy, an amendment to a law, an update to a scientific model.

* Eg. You notice your neighborhood lacking trash bins so you tweet about it, it reaches city officials, who have ways to aggregate messages into prioritized actions, which are visible to anyone. Once a critical threshold is reached, the  
* Eg. Anyone can post about news that get treated, cross referenced, and aggregated into a coherent picture of real time events  
* Eg. Anyone can run scientific experiments and record their observations \- or review and critique existing science \- and these are treated as valid contributions, as nanopublications.

Communities have a bird’s eye view of their online information terrain (social graph) and weather (the contents of discussion). Where the winds (topics) are blowing from (eg. a Russian news cluster, or a Bay Area tech cluster, or a gamer furry cluster). Members of communities have common knowledge and can coordinate accordingly (eg. let’s unfollow the accounts that connect us to the misinformation-spawning cluster).

### Shovel-ready prototype ideas {#shovel-ready-prototype-ideas}

*Memetics*  
**Chat to archive and advanced search:** Ask an AI agent complex questions about the archive and have it query it for you. E.g. “What are the top 10 people that both A and B replied to in 2023?” This includes semantic search as one of the tools the agent has access to.

**(Bi-)Weekly Meme Report:** A newsletter summarizing the discourse within the community. New memes, ideas, or simply topics that took up a lot of attention. What they were, where they came from, what broad positions were taken. Easier situational awareness without scrolling every day.

**The Nooscope:** A dashboard to track historical topic diffusion. It’s a natural next step from the weekly meme report. More of an investigative tool. It gives users control to dive into topics, make complex queries, visualize the diffusion of topic in a social network, or their dynamics in semantic space.

*Coordination*  
**Frame Translator:** Translate a message from user A’s point of view to user B’s. Often people agree while using different language. The simplest version of this throws all (or a subset of) user A’s and B’s tweets \+ the message into an LLM context and shows the output. A more advanced version distills the relevant structure (assumptions, values, memories) from tweets and uses that to inform the translation. 

**Body-of-work Synthesiser**: People often post insights and notes on disparate topics. Over time, they return to them but these are hard to aggregate and distill into coherent positions. Many people have asked for ways to explore their body of work or even turn it into a book or explorable website. ([Birdseye](https://xiqo.substack.com/cp/163163201) is an early attempt)

**AI agent-mediated matchmaking:** Use people’s tweets to distill a personality with values, preferences. Have LLMs roleplay the users, and talk amongst themselves to find matches, resolve disputes, or create proposals for collaboration.

**Community Banger-Bot:** A viral twitter bot that consistently posts thoughtful and funny tweets.

### What looking through the nooscope should feel like

![][image2]  
**Figure 2:** This is particle Lenia, it illustrates our intuition for the plane of ideas as an arena where ideas compete as agents, fork, merge, and evolve. 

### Topic cluster proof of concept

![][image3]  
**Figure 3:** This is part of the community archive dataset animated over time in the Nomic Atlas. It illustrates the way different topics take over over time, like COVID first, then conflict in the Middle East. It has an organic quality, like mould blooms.
