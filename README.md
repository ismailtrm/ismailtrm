# Ismail Tarim

Software engineer focused on distributed systems, Linux, backend infrastructure, and production reliability.

I build and operate systems with Go, Python, PostgreSQL, RabbitMQ, and Kubernetes. I am currently studying Computer Engineering at Izmir Katip Celebi University and working across production AI, open-source systems, and distributed systems research.

[LinkedIn](https://linkedin.com/in/ismailtarim) | [Email](mailto:me@ismailtarim.dev) | [ORCID](https://orcid.org/0009-0009-0503-8917)

## What I work on

* **HunerAI:** As a Founding Engineer, I design and operate backend and infrastructure for a production AI platform in the pharmacy domain. My work includes event-driven processing, cross-service consistency, observability, provider resilience, and production operations.
* **Linux kernel:** I contribute fixes and stable backport analysis, primarily around MediaTek Bluetooth and Wi-Fi drivers.
* **Evo-Sched:** I am researching Kubernetes scheduling through live workload replays and noise-aware multi-objective evaluation.
* **GDG on Campus IKCU:** I lead a 30-person chapter team and coordinate technical events, speakers, partnerships, and community operations.

## Open source

I authored two fixes for the MediaTek Bluetooth driver, correcting subsystem-reset paths that could report failed resets as successful. Both fixes were merged into mainline for Linux 7.3 and backported to multiple stable series.

* [`59c3ee19ca88`](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=59c3ee19ca88)
* [`21b50c24843b`](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=21b50c24843b)

I also identified and nominated an existing mt76 Wi-Fi NULL-dereference fix for stable backporting. It shipped in Linux 7.1.4 and was later tracked as CVE-2026-64325.

## Selected work

### Evo-Sched

A parameterized Kubernetes scheduler and noise-aware multi-objective evaluation pipeline implemented in Go. The system has been evaluated through 1,350 live workload replays covering 32,400 pods on a four-worker cluster.

### Can You Detect the Difference?

First-author research comparing diffusion- and autoregressive-model text across 3,000 samples, achieving 0.993 AUC for human-versus-AI detection. Presented at ICETAI 2026.

[Read the paper on arXiv](https://arxiv.org/abs/2507.10475)

### STOX

A gRPC-based microservice platform integrating Gemini and Google Cloud PostgreSQL. The project placed 2nd nationwide at the BTK Academy x Google x Turkish Entrepreneurship Foundation Hackathon 2025.

## Engineering focus

* **Languages:** Go, Python, C/C++, TypeScript, SQL
* **Backend and data:** PostgreSQL, MongoDB, RabbitMQ, REST, gRPC
* **Systems and cloud:** Linux, Docker, Kubernetes, Google Cloud, AWS, Cloudflare
* **Reliability:** Prometheus, Grafana, Alertmanager, profiling, load testing
* **Applied AI:** Gemini, provider integrations, structured retrieval, production AI workflows

## Collaboration

I am interested in collaborating on distributed systems, Linux, infrastructure, observability, Kubernetes scheduling, and production AI.
