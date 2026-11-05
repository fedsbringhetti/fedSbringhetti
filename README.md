# Hi, I'm Federico Sbringhetti

Software Engineer Intern at **Tonic Minds** and MSc student in Computer Engineering at **Politecnico di Torino** (Networking and Cloud Computing, graduating Nov 2026).
I mostly write **Rust** backends with a security focus, and I'm drawn to low-level work: systems programming, embedded, kernels.

## Featured projects

| Project | What it is | Stack |
|---|---|---|
| [EuroTransit](https://github.com/g05-eurotransit/EuroTransit-application) | Cloud-native train-ticket marketplace, university capstone in a team of 5. My main area: the Orders checkout, with a Kafka workflow, transactional outbox, seat holds, dead-letter recovery and tracing | Kotlin, Spring WebFlux, Kafka, Kubernetes, Argo CD, Azure AKS |
| [InTime](https://github.com/fedsbringhetti/gtt-personal-api) | Real-time GTT departures for Turin: an API and an installable web app, self-hosted on an ARM64 home server | Rust, SQLite, Svelte, Docker |
| [PropFlow](https://github.com/fedsbringhetti/prop-flow) | Property-management backend shared by owners and tenants, with tenant isolation through PostgreSQL Row Level Security (in development) | Rust, Axum, SQLx, PostgreSQL |
| [Pac-Man on LandTiger](https://github.com/fedsbringhetti/landtiger-pacman) | Bare-metal game for an ARM Cortex-M3 board, with A* ghosts, DAC audio and CAN telemetry | C, LPC1768 |

## At work

**Sanitizer** (internship and MSc thesis, private): a Rust security gateway that fetches untrusted web content and returns a sanitized version of it. My work covers detection of indirect prompt injection hidden in PDFs, SSRF hardening, browser TLS fingerprinting and DNS-over-HTTPS.

## Running at home

- A Telegram bot that follows football matches live, in production since October 2026 (Python, FastAPI, Server-Sent Events)
- An ESP32 weather station feeding a self-hosted Orange Pi server, which also runs a NAS, InTime and the bot

## Contact

[LinkedIn](https://www.linkedin.com/in/fedesbringhetti) · [Email](mailto:federicosbringhetti@gmail.com)
