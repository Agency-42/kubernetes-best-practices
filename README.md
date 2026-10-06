# Kubernetes Best Practices

Practical checklists and example manifests for running Kubernetes, OpenShift and
RKE2 in production. Maintained by [Agency 42](https://agency42.se), Kubernetes
specialists from Sweden.

> **Status: work in progress.** This repo is being rebuilt. Below is what's
> actually in here today, with no promises about folders that don't exist yet.

## What's in here

| Path | What it is |
|---|---|
| [`examples/network-policies/`](examples/network-policies/) | Default-deny NetworkPolicy **plus** the DNS exception it needs, for vanilla Kubernetes/RKE2 and OpenShift (which uses port 5353). |
| [`checklists/production-readiness.md`](checklists/production-readiness.md) | Production readiness checklist (being expanded). |
| [`checklists/cluster-hardening.md`](checklists/cluster-hardening.md) | Cluster hardening checklist (being expanded). |

## Coming next

- A full production readiness checklist, where every item says *why* and *how to verify* it
- Hardening notes (Pod Security Admission, RBAC, audit policy, etcd encryption) with Vanilla / OpenShift / RKE2 differences
- A namespace baseline and a "golden" Deployment example
- CI that validates every manifest

## Scope

This repo is about prevention: setting clusters up so they stay boring.
When something is already on fire, see our upcoming troubleshooting field guide,
`dont-panic`.

## Contributing

Issues and PRs are welcome. If you know a better way to do something, tell us.

Website: https://agency42.se · LinkedIn: https://www.linkedin.com/company/agency42ab
