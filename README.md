<h2>Hi, I'm Ezgi Taştan <img src="https://raw.githubusercontent.com/ABSphreak/ABSphreak/master/gifs/Hi.gif" height="25px"></h2>

I am a Site Reliability Engineer working on GPU fleet reliability and cluster performance. My work spans rack-scale GPU systems, fault isolation, inference serving, and eBPF profiling.

I write at **[ezgitastan.systems](https://ezgitastan.systems/)**.

## Selected work

- **[bpftime: GB300 and CUDA 13 support](https://github.com/eunomia-bpf/bpftime/pull/647)** — added NVIDIA GB300 (`sm_103`) and CUDA 13 support for device-side eBPF. Merged August 2026.
- **[OpenTelemetry OBI: CUDA tracing fix](https://github.com/open-telemetry/opentelemetry-ebpf-instrumentation/pull/3814)** — fixed missing per-thread CUDA launch symbols. On an H200 test, OBI went from detecting 0 of 3,010 launches to all 3,010, while normal builds remained unchanged. Merged October 2026.
- **[MiniMax-H3 on GB300](https://github.com/EzgiTastan/minimax-h3-gb300-ebpf)** — published reproducible measurements of SGLang serving, GPU scaling, host eBPF traces, Grace–GPU fabric traffic, and energy. [Read the investigation](https://ezgitastan.systems/blog/minimax-h3-sglang-gb300-ebpf/).

## Other merged contributions

- [MiniMax-AI/awesome-minimax-h3-integration](https://github.com/MiniMax-AI/awesome-minimax-h3-integration/pull/12) — GB300 benchmarking and observability resource
- [vllm-project/production-stack](https://github.com/vllm-project/production-stack/pulls?q=author%3AEzgiTastan) — least-privilege RBAC for Kubernetes secrets
- [kubernetes-sigs/gateway-api-inference-extension](https://github.com/kubernetes-sigs/gateway-api-inference-extension/pulls?q=author%3AEzgiTastan) — release-process fix
- [eunomia-bpf/bpftime](https://github.com/eunomia-bpf/bpftime/pulls?q=author%3AEzgiTastan) — config rename across 36 files of the userspace eBPF runtime
- [dstackai/gpuhunt](https://github.com/dstackai/gpuhunt/pulls?q=author%3AEzgiTastan) — Azure H100 NVL and H200 support
- [aws-actions/amazon-ecs-deploy-task-definition](https://github.com/aws-actions/amazon-ecs-deploy-task-definition/pulls?q=author%3AEzgiTastan) — bounded exponential backoff in deployment waiters
- Also [agentgateway](https://github.com/agentgateway/agentgateway/pulls?q=author%3AEzgiTastan), [llm-d](https://github.com/llm-d/llm-d/pulls?q=author%3AEzgiTastan), [bifrost](https://github.com/maximhq/bifrost/pulls?q=author%3AEzgiTastan), [ratty](https://github.com/orhun/ratty/pulls?q=author%3AEzgiTastan), and [rustypaste](https://github.com/orhun/rustypaste/pulls?q=author%3AEzgiTastan).

[Browse my merged pull requests](https://github.com/search?q=author%3AEzgiTastan+is%3Apr+is%3Amerged&type=pullrequests).

## Writing

- [**Profiling MiniMax-H3 on GB300 with SGLang and eBPF**](https://ezgitastan.systems/blog/minimax-h3-sglang-gb300-ebpf/) — stage timing, Ulysses scaling, concurrency, fabric traffic, and energy measurements
- [**Profiling Voice AI on H100 with eBPF**](https://ezgitastan.systems/blog/gpu-observability-ebpf) — traced STT and TTS containers with bpftime: the GPU sat at 0% while the CPU ran 169K malloc/s
- [**Optimizing LLM Inference with Kubernetes and vLLM**](https://medium.com/@ezgitastan/optimizing-llm-inference-with-kubernetes-and-vllm-919ce4cd4491)

## What I'm working on

- Performance-regression detection for GPU fleets
- NVLink and NVSwitch fault isolation
- eBPF for GPU observability
- [bmclib: Redfish system selection on multi-system BMCs](https://github.com/bmc-toolbox/bmclib/pull/480) — open pull request

## Skills

**GPU & AI infrastructure**
GB300 NVL72 · B300 / B200 · H200 / H100 · NVLink / NVSwitch · InfiniBand · NVIDIA GPU Operator · MIG slicing · NFD · DCGM · NCCL · vLLM · CUDA · Redfish / IPMI

**Orchestration & platform**
Kubernetes · OpenShift (ROSA) · Helm · Kustomize · ArgoCD · Slurm

**Observability & reliability**
Prometheus · VictoriaMetrics · Grafana · eBPF / bpftime · Datadog · Sentry · Langfuse · K6 · PagerDuty

**Cloud, IaC & automation**
AWS · GCP · Terraform · Terragrunt · SaltStack · Packer · Vagrant · Python · Go · Bash

**Datacenter & storage**
Ceph · MAAS · NetBox · libvirt / KVM
