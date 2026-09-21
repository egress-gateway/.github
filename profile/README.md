<p align="center">
  <img src="https://raw.githubusercontent.com/egress-gateway/.github/main/profile/assets/logo.png" alt="Egress Gateway logo" width="144" height="144">
</p>

<h1 align="center">Egress Gateway</h1>

<p align="center"><strong>Controlled network access for untrusted workloads.</strong></p>

Egress Gateway is building network traffic governance and credential replacement for AI agents and other untrusted workloads on Kubernetes.

Agents execute model-generated code and third-party tools. Our goal is to let them work with external services while keeping network access and real service credentials under platform control.

## Core capabilities

### Network traffic governance

**Control where workloads connect and how their traffic is handled.**

Scripts, dependencies, and tools can all initiate network requests. We are building a controlled egress path that applies access rules, request processing, and auditing outside the workload, without relying on application code to honor proxy settings or use a particular SDK.

### Credential replacement

**Let workloads use external services without exposing real credentials to their code.**

Placing real API keys inside a container lets code running there copy or leak them. Workloads instead use placeholder credentials. After verifying the workload's identity, destination, and permissions, the gateway replaces those placeholders with the appropriate service credentials before forwarding the request. Real credentials stay in trusted infrastructure.

## Follow along

We're in early development. Use cases, design feedback, and contributions are welcome.

- [Explore the organization](https://github.com/orgs/egress-gateway/repositories)
- [Visit the project repository](https://github.com/egress-gateway/egress-gateway)
