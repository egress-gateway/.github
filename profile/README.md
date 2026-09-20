<p align="center">
  <img src="https://raw.githubusercontent.com/egress-gateway/.github/main/profile/assets/logo.png" alt="Egress Gateway logo" width="144" height="144">
</p>

<h1 align="center">Egress Gateway</h1>

<p align="center"><strong>Controlled network access for untrusted workloads.</strong></p>

Egress Gateway is building network governance for AI agents and other untrusted workloads on Kubernetes.

Agents can write code, install packages, and reach external services. Our goal is to keep those connections under platform control: where a workload can connect, which credentials it can use, and how its traffic is handled and audited—without relying on the code inside the container to cooperate.

**Credential Replacement** is a core capability we're building: workloads use placeholder credentials, and the gateway replaces them with the appropriate upstream credentials only after verifying the workload's identity, destination, and access permissions. Real API keys and other service credentials stay outside the workload.

We are starting with AI agents, with a foundation designed to work across container runtimes and agent frameworks on Kubernetes.

## Follow along

We're in early development. Use cases, design feedback, and contributions are welcome.

- [Explore the organization](https://github.com/orgs/egress-gateway/repositories)
- [Visit the project repository](https://github.com/egress-gateway/egress-gateway)
