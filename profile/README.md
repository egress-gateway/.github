<p align="center">
  <img src="https://raw.githubusercontent.com/egress-gateway/.github/main/profile/assets/logo.png" alt="Egress Gateway logo" width="144" height="144">
</p>

<h1 align="center">Egress Gateway</h1>

<p align="center"><strong>Controlled network access for untrusted workloads.</strong></p>

Egress Gateway is building network governance for AI agents and other untrusted workloads on Kubernetes.

Agents can write code, install packages, and reach external services. Our goal is to keep those connections under platform control: where a workload can connect, which credentials it can use, and how its traffic is handled and audited—without relying on the code inside the container to cooperate.

We are starting with AI agents, with a foundation designed to work across container runtimes and agent frameworks on Kubernetes.

## What we're building

The project is organized around three planned repositories:

| Component | Purpose |
| --- | --- |
| **Gateway** · `gateway` | Workload Proxy and Egress Gateway data planes for traffic handling, policy enforcement, and credential mediation. |
| **Controller** · `controller` | Label-driven Pod enrollment, sidecar injection, and the Kubernetes configuration needed to connect workloads to the data plane. |
| **CLI** · `cli` | Install and upgrade the system, inspect workloads, and diagnose connectivity and configuration. |

## Follow along

We're in early development. Use cases, design feedback, and contributions are welcome.

- [Explore the organization](https://github.com/orgs/egress-gateway/repositories)
- [Visit the project repository](https://github.com/egress-gateway/egress-gateway)
