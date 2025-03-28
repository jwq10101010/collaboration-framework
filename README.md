# collaboration-framework
This repository outlines a possible topological architecture for collaborating using Federated Wikis + Open Source Auth Protocols.

### Government level
Each government entity has Internet Gateway -> Firewall -> Load Balancer -> Auto-Scaling Group -> Federated Wikis placed in cluster, spread, or partition placement groups. These Federated Wikis can also act as the government entity's source of truth on certain matters such as legislation, rules of living in that particular society, economic policies, etc.

### Local level
Several individuals could decide to band together and collaborate in a cluster of Federated Wikis.

### Individual level
Each individual can decide to self-host a Federated Wiki server and collaborate on other wiki pages from all over the world on any topic available.
