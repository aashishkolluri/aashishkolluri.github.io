---
layout: about
title: About
permalink: /
description: AI Security | Distributed Machine Learning | Trustworthy Machine Learning

profile:
  align: right
  image: prof_pic.jpg
  # address: >
  #   # <p>AS06-04-25</p>
  #   # <p>Singapore, 117416</p>

news: true  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

<!-- Write your biography here. Tell the world about yourself. Link to your favorite [subreddit](http://reddit.com){:target="\_blank"}. You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder. -->

##### **Bio**
👋 Hi! I'm an AI security researcher at Microsoft Research, working in the Confidential Computing group in Cambridge, U.K. My current focus is on designing agents and agentic frameworks with strong, robust, and interpretable security guarantees.

Previously, I completed my Ph.D. under the guidance of [Prateek Saxena](https://www.comp.nus.edu.sg/~prateeks/){:target="\_blank"} at the National University of Singapore (NUS), where I built efficient and secure systems for distributed machine learning, with a particular emphasis on distributed graph learning.

##### Research Interests
My work spans multiple research areas with both theoretical and systems contributions. Please drop me a message if you are interested in any of them!

🧠 **AI Agent Security**
Most recently, I have been developing *formal* security foundations for autonomous AI agents. Our 2025 work introduces **FIDES**, a planner that tags every piece of data an agent ingests with confidentiality-and-integrity labels and then *deterministically* enforces information-flow policies before any tool call is executed. A formal model and task taxonomy show exactly which In benchmarks, FIDES blocks all prompt-injection attacks and completes up to 16% more tasks than a baseline planner when paired with OpenAI’s o-series model—offering auditable, proof-carrying security for multi-tool agent stacks. ([FIDES on arxiv](https://www.arxiv.org/pdf/2505.23643){:target="\_blank"})

🛡️ **Defending Poisoning Attacks**
**HiDRA** attack ([S\&P'24](https://arxiv.org/abs/2312.14461))  and **RandEigen** defense (CCS 2025, TBA) address the fundamental compuational limitations of desigining theoretically sound defenses for poisoning and backdoor attacks. 

HiDRA revealed a computational hardness barrier for any deterministic robust aggregator, like the classical iterative filtering, with dimension-independent guarantees. The attack breaks state-of-the-art defenses against targeted poisoning and backdoor attacks. RandEigen is a randomized aggregator that overcomes the computational vulnerabitlity of deterministic aggregators while matching their theoretical guarantees. RandEigen runs up to 300× faster than state-of-the-art theoretically sound defenses while preventing all existing poisoning and backdoor attacks in both centralized and federated settings---making bias-bounded defenses finally practical.

🌐 **Distributed Machine Learning**
My Ph.D. research laid the groundwork for designing efficient and privacy-preserving distributed graph learning. I built a system [**Retexo**](https://github.com/aashishkolluri/retexo-distributed), which optimizes GNN training efficiency across data centers and edge devices. **LPGNet** ([CCS 2022](https://arxiv.org/abs/2205.03105)) and **PrivaCT** ([CCS 2021](https://arxiv.org/abs/2105.09057)) are differentially private GNN and hierarchical clustering algorithms that protects graph data against leakage. These contributions have advanced the state of the art in scalable, privacy-aware learning over distributed graphs.

🌐 **Broader Interests:** I actively engage in solving algorithmic problems and enjoy building systems. My contributions extend to diverse areas such as program synthesis, translation, debugging, and the security of decentralized applications, with publications in top-tier venues.

##### **Academic History & Internships**
<!-- ![](/assets/img/iitk.png)
*B.Tech (2013-17)* -->
<figure style="display:inline-block;">
<img src="/assets/img/microsoft.png" alt="drawing" width="100" />
<figcaption style="text-align:center;">Researcher (Since Feb'25)</figcaption>
<figure style="display:inline-block;">
<img src="/assets/img/bell_labs.png" alt="drawing" width="100" />
<figcaption style="text-align:center;">Internship (Jun-Aug'23)</figcaption>
</figure>
<figure style="display:inline-block;">
<img src="/assets/img/aqilliz.png" alt="drawing" width="100" />
<figcaption style="text-align:center;">Internship (Jun-Jul'20)</figcaption>
</figure>
<figure style="display:inline-block;">
<img src="/assets/img/nus_logo.jpeg" alt="drawing" width="100" />
<figcaption style="text-align:center;">Ph.D. (2018-24)</figcaption>
</figure>
<figure style="display:inline-block;">
<img src="/assets/img/nus_logo.jpeg" alt="drawing" width="100" />
<figcaption style="text-align:center;">Internship (Aug'17-May'18)</figcaption>
</figure>
<figure style="display:inline-block;">
<img src="/assets/img/flipkart.png" alt="drawing" width="100" />
<figcaption style="text-align:center;">Internship (May-Jul'16)</figcaption>
</figure>
<figure style="display:inline-block;">
<img src="/assets/img/iitk.png" alt="drawing" width="75" />
<figcaption style="text-align:center;">B.Tech. (2013-17)</figcaption>
</figure>