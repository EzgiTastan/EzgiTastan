<h2>Hi, I'm Ezgi Taştan <img src="https://raw.githubusercontent.com/ABSphreak/ABSphreak/master/gifs/Hi.gif" height="25px"></h2>

I am a Site Reliability Engineer, working on rack-scale GPU fleet reliability, AI infrastructure and Kubernetes-based AI model serving.

I write at **[ezgitastan.systems](https://ezgitastan.systems/)**

## Skills

**GPU & AI infrastructure**
GB300 NVL72 · B300 / B200 · H200 / H100 · NVLink / NVSwitch · InfiniBand · NVIDIA GPU Operator · MIG slicing · NFD · DCGM · NCCL · vLLM · CUDA · Redfish / IPMI

**Orchestration & platform**
Kubernetes · OpenShift (ROSA) · Helm · Kustomize · ArgoCD · Slurm

**Observability & reliability**
Prometheus · VictoriaMetrics · Grafana · eBPF / bpftime · Datadog · Sentry · Langfuse · K6 · PagerDuty

**Cloud, IaC & automation**
AWS · GCP · Terraform · Terragrunt · SaltStack · Packer · Vagrant · Go · Bash

**Datacenter & storage**
Ceph · MAAS · NetBox · libvirt / KVM

## What I'm working on

- Performance-regression detection for GPU fleets
- NVLink and NVSwitch fault isolation
- eBPF for GPU observability

## Merged upstream

- [vllm-project/production-stack](https://github.com/vllm-project/production-stack/pulls?q=author%3AEzgiTastan) — least-privilege RBAC for Kubernetes secrets
- [kubernetes-sigs/gateway-api-inference-extension](https://github.com/kubernetes-sigs/gateway-api-inference-extension/pulls?q=author%3AEzgiTastan) — release-process fix
- [eunomia-bpf/bpftime](https://github.com/eunomia-bpf/bpftime/pulls?q=author%3AEzgiTastan) — config rename across 36 files of the userspace eBPF runtime
- [dstackai/gpuhunt](https://github.com/dstackai/gpuhunt/pulls?q=author%3AEzgiTastan) — Azure H100 NVL + H200 support
- [aws-actions/amazon-ecs-deploy-task-definition](https://github.com/aws-actions/amazon-ecs-deploy-task-definition/pulls?q=author%3AEzgiTastan) — bounded exponential backoff in deployment waiters
- Also [agentgateway](https://github.com/agentgateway/agentgateway/pulls?q=author%3AEzgiTastan), [llm-d](https://github.com/llm-d/llm-d/pulls?q=author%3AEzgiTastan), [bifrost](https://github.com/maximhq/bifrost/pulls?q=author%3AEzgiTastan), [ratty](https://github.com/orhun/ratty/pulls?q=author%3AEzgiTastan), [rustypaste](https://github.com/orhun/rustypaste/pulls?q=author%3AEzgiTastan) → [see all 13 merged](https://github.com/search?q=author%3AEzgiTastan+is%3Apr+is%3Amerged&type=pullrequests)

## Writing

- [**Profiling Voice AI on H100 with eBPF**](https://ezgitastan.systems/blog/gpu-observability-ebpf) — traced STT and TTS containers with bpftime: the GPU sat at 0% while the CPU ran 169K malloc/s
- [**Optimizing LLM Inference with Kubernetes and vLLM**](https://medium.com/@ezgitastan/optimizing-llm-inference-with-kubernetes-and-vllm-919ce4cd4491)
