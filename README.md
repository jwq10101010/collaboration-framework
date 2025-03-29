# collaboration-framework (infrastructure)
This repository outlines a possible topological architecture for authentication, governance, and collaborating using Federated Wikis (established in containers) + Open Source Auth Protocols + Software version control + chat/voice messaging group.

### Government level
Each government entity has Internet Gateway -> Firewall -> Load Balancer -> Auto-Scaling Group -> Federated Wikis placed in cluster, spread, or partition placement groups. These Federated Wikis can also act as the government entity's source of truth on certain matters such as legislation, rules of living in that particular society, economic policies, etc.

### Local level
Several individuals could decide to band together and collaborate in a cluster of containers (local charter or club). They can establish rules and guidelines as needed.

### Individual level
Each individual can decide to self-host a Federated Wiki server and collaborate on other wiki pages from all over the world and even across civilizations and dimensions on any topic available. (let's all work together)

### Notes
- At the government level, could have multiple clustered department groups
- A group of people can share a server and discuss changes in-person (better for the environment and establishes a sense of local community).
- Each individual has their own key pair for authentication and to give credit where it is due
- alternative/augmentation to Federated Wikis: Kubernetes/Docker containers
- Also, could create Discord group for organizing beings together for a common purpose and use GitHub for software version control

**MVP:** Establish basic server architecture at government, local, and individual levels

**Additional features to implement:**
- High-level architecture diagrams

**Learn more**
https://wiki.archlinux.org/title/Docker
