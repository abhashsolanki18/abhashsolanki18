# Abhash Solanki

DevOps Engineer at [Spyne AI](https://www.spyne.ai) (Gurugram). I joined at the 0-to-1 stage and built the infrastructure it runs on today: a self-service Terraform platform across ~12 AWS accounts, 100+ services on EKS and ECS, and GPU model serving (NVIDIA Triton, KServe ModelMesh) for 40+ vision models.

I write Go and Python, and I contribute to the Kubernetes and ClickHouse ecosystems.

## Open source

- **[Kyverno](https://github.com/kyverno/kyverno)** (Kubernetes policy engine, Go), 4 merged PRs:
  [#12073](https://github.com/kyverno/kyverno/pull/12073) certificate renewer left stale CA certs in the secret ·
  [#11834](https://github.com/kyverno/kyverno/pull/11834) CLI crash on CEL scans of Namespace objects ·
  [#11584](https://github.com/kyverno/kyverno/pull/11584) Helm `mergeOverwrite` clobbering nested values ·
  [#11979](https://github.com/kyverno/kyverno/pull/11979) error handling and log noise
- **[PeerDB](https://github.com/PeerDB-io/peerdb)** (ClickHouse's CDC engine, Go):
  [#4844](https://github.com/PeerDB-io/peerdb/pull/4844) carry MongoDB change-stream pre-images on delete events (merged) ·
  [#4958](https://github.com/PeerDB-io/peerdb/pull/4958) validate pre-images for tables added to an existing mirror (open)

## Talk

**Simplifying CDC: Migrating from Debezium to ClickPipes**, ClickHouse Gurgaon Meetup, Jan 2026. A production migration of a 1.5TB+ Kafka/Debezium CDC warehouse to ClickHouse Cloud with zero downtime.

## Stack

AWS (EKS, ECS, Lambda, RDS, CloudFront, Secrets Manager, PrivateLink) · Kubernetes · Terraform · Ansible · Jenkins · Prometheus / Grafana / Loki · ClickHouse · Kafka / Debezium · Go · Python · Bash

RHCSA · RHCE · Microsoft Azure AI Engineer (AI-102)

[LinkedIn](https://www.linkedin.com/in/abhash-solanki-35b0a5288/) · abhashsolanki18@gmail.com
