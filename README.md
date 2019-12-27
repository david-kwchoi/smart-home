# smart-home
Building rpi-based private cloud and IoT smart home

This would be my pet project in building Rest services with spring boot, mounting on rpi 3b+

The rpi (currently 2) will serve as compute engines with Docker enabled. Each newly built services will be a container image and thus accessible in the docker repo.

# Planned features
1. shadowsocks proxy, with some basic rest api to configure the users of the services dynamically
2. jupyter lab, simply a notebook playground
3. smart home, controlling appliances with rest services

# Framework/ Technology that will be involved
1. Kafka
2. ZooKeeper
3. Docker
4. Docker Swarm/Kubernetes
5. Kotlin
6. Spring boot
7. MySQL/Posgres

# Remarks
The technology stack is quite an overkill for a simple home private cloud usage. Still this should serves as a good template and experiment in showcasing how these technology work together, and more importantly to have hands on experiences.