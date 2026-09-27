# AGBEVO Kodjo Honoré

Élève ingénieur en 5e année à l'ENSA Marrakech, spécialité Réseaux, Systèmes et Services Programmables (RSSP).

Je construis un profil Cloud & DevOps depuis un an à travers des projets personnels menés en autonomie (Kubernetes/GitOps, observabilité), en complément des projets académiques réseaux, systèmes et IoT. À la recherche d'un stage de fin d'études à partir de février 2027.

## Projets

**finops-platform: Plateforme FinOps Kubernetes multi-tenant (GitOps)**
Projet de fin d'année, en cours de développement.
- Gouvernance des coûts cloud sur Kubernetes (K3s/k3d)
- ArgoCD (App-of-Apps + ApplicationSet), politiques Kyverno (NetworkPolicy, ResourceQuota, LimitRange)
- Opérateur Kubernetes en Python/Kopf : détection de dérive budgétaire, actions correctives automatiques
- Observabilité des coûts via OpenCost, Prometheus, Grafana
- CI complète (GitHub Actions), 49 tests automatisés (pytest)

[Repo](https://github.com/Honore-M12/finops-platform)

**Ferme Connectée Intelligente**
Projet académique IoT, en équipe de 4.
- Supervision agricole en temps réel : 5 zones simulées (serre, plein champ, hydroponie)
- Capteurs ESP32 (Wokwi, PlatformIO)
- Chaîne de traitement MQTT vers Node-RED (règles agronomiques, anti-rebond)
- Diagnostic IA (API Groq, LLaMA 3.3 70B), historisation InfluxDB
- Dashboards ThingsBoard/Grafana, déploiement multi-conteneurs Docker Compose

[Repo](https://github.com/Honore-M12/Ferme_connectee)

**Application Multi-conteneurs avec Monitoring**
- Architecture Nginx / Flask / PostgreSQL orchestrée avec Docker Compose
- Métriques Prometheus personnalisées (Counter, Gauge, Histogram)
- Dashboards Grafana temps réel, Node Exporter
- Pipeline CI/CD GitHub Actions à deux jobs : tests (pytest, flake8) puis build et publication sur Docker Hub

[Repo](https://github.com/Honore-M12/containerized-guestbook)

**Infrastructure Réseaux Sécurisée Multi-site**
Projet académique.
- Architecture défense en profondeur : segmentation VLAN
- Pare-feu Cisco ASA (ACL, NAT), VPN IPsec site à site
- Routage BGP/OSPF inter-AS, authentification TACACS+
- Simulation de scénarios d'attaque et contre-mesures

**Réseau opérateur (GNS3)**
- 14 routeurs IOSv, 3 conteneurs Docker
- Routage BGP et MPLS, L3VPN
- Qualité de service et VoIP, supervision réseau
- Conception de topologie et débogage sous délai contraint

Documentation en cours de rédaction.

**Conception réseau campus**
- Conception d'une topologie réseau multi-bâtiments à grande échelle
- Découpage hiérarchique par zones, dimensionnement VLSM et agrégation de routes
- Plan d'adressage et de câblage pour un grand nombre d'utilisateurs répartis sur plusieurs sites

**Administration Windows Server**
- Active Directory, DNS, DHCP, GPO
- Délégation d'unités organisationnelles

## Compétences techniques

**Cloud / IaC**
AWS (EC2, S3, VPC), Terraform, GitHub Actions

**Conteneurs & Orchestration**
Docker, Docker Compose, Kubernetes (K3s/k3d), ArgoCD, GitOps, Kyverno

**Observabilité**
Prometheus, Grafana, Loki, Jaeger, Alertmanager, OpenCost, PromQL, Node Exporter

**IoT**
ESP32 (Wokwi, PlatformIO), MQTT, Node-RED, ThingsBoard, InfluxDB

**Réseaux**
OSPF, BGP, MPLS/L3VPN, VLAN, VPN IPsec, ACL, Cisco ASA, TACACS+, VoIP, QoS

**Systèmes**
Linux, Windows Server, Active Directory, DNS, DHCP, GPO

**Développement**
Python (Kopf), Bash, Java, SQL, HTML/CSS

**Outils**
Cisco Packet Tracer, GNS3, VMware, VirtualBox, Git

## Contact

[LinkedIn](https://www.linkedin.com/in/agbevo-kodjo-honor%C3%A9-6377133a2/) · agbevohonore06@gmail.com
