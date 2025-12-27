<div align="center">

```
╔═══════════════════════════════════════════════════════════╗
║                                                           ║
║   ┌┬┐┌─┐┌┬┐┌┬┐  ┌─┐┬  ┬┌─┐┌┐┌┌─┐                          ║
║   │││├─┤ │  │   ├┤ └┐┌┘├─┤│││└─┐                          ║
║   ┴ ┴┴ ┴ ┴  ┴   └─┘ └┘ ┴ ┴┘└┘└─┘                          ║
║                                                           ║
║   DevOps · Security · AI Practitioner · Mentor            ║
║                                                           ║
╚═══════════════════════════════════════════════════════════╝
```

<img src="./assets/memoji.png" width="120" alt="matt" />

[![LinkedIn](https://img.shields.io/badge/linkedin-181717?style=flat-square&logo=linkedin&logoColor=0A66C2)](https://www.linkedin.com/in/mevanssecurity/)
[![GitHub](https://img.shields.io/badge/github-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/x86txt)

</div>

---

## `$ whoami`

```text
Principal Engineer with 25+ years building cloud infrastructure, automation,
and security systems. Equal parts architect and implementer. I build things
that are resilient, observable, and maintainable.
```

**Current runtime:**
- `AI_AUGMENTED_ENGINEERING=true` — LLMs in workflows, IP-safe
- `PLATFORM_SRE=active` — Golden paths, observability, toil reduction
- `SECURITY=default` — Policy as code, drift detection, hardening at scale

---

## `$ ls -la ~/projects/`

### Maintained

```
drwxr-xr-x  goWipeMe           Go        Privacy utility, DoD-grade wiping
drwxr-xr-x  aiTriage           Py/TS     SRE AI Agent and Daemon, plus universal SRE Skill
drwxr-xr-x  mattsblocklist     Go        UniFi region-blocking country blocklist updater
drwxr-xr-x  unifi_contrld      Shell     ControlD on UniFi, persists updates
drwxr-xr-x  argocd_2025        Shell     GitOps K8s, App-of-Apps pattern
```

<div align="center">

<table>
<tr>
<td>

### [`goWipeMe`](https://github.com/Secunit-Mercantile/goWipeMe)

Cross-platform privacy & data sanitization. GUI + TUI interfaces.

```
Features:
├── Browser history clearing
├── Secure disk wiping
│   ├── Single pass (zeros)
│   ├── DoD 5220.22-M (3-pass)
│   └── Gutmann (35-pass)
├── Backup & restore
└── Dry-run preview
```

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![MIT](https://img.shields.io/badge/license-MIT-green?style=flat-square)

</td>
<td>

### [`aiTriage`](https://github.com/x86txt/portfolio_sre_agent)

SRE AI Agent and Daemon, plus universal SRE Skill.

```
Pipeline:
├── Ingest (Prometheus, Datadog)
├── Correlate (signal analysis)
├── Generate (situation reports)
└── LLM narrative (optional)
```

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TS-3178C6?style=flat-square&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

</td>
</tr>
<tr>
<td>

### [`unifi_contrld`](https://github.com/x86txt/unifi_contrld)

ControlD daemon automation for UniFi OS.

```
Targets:
├── UCG Fiber
├── UDM / UDM-Pro
└── CloudKey

Features:
├── Persists in /data partition
├── Survives firmware updates
└── Healthchecks.io monitoring
```

![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)

</td>
<td>

### [`argocd_2025`](https://github.com/x86txt/argocd_2025)

GitOps Kubernetes platform.

```
Stack:
├── ArgoCD (App-of-Apps)
├── Infrastructure
│   ├── MetalLB, Traefik
│   └── cert-manager
├── Observability
│   ├── Prometheus, Grafana
│   └── Loki, Promtail
└── Secrets: Doppler
```

![K8s](https://img.shields.io/badge/K8s-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)

</td>
</tr>
<tr>
<td>

### [`mattsblocklist`](https://github.com/x86txt/mattsblocklist)

Keeps UniFi Region Blocking country lists updated (aggregate + apply).

```
Commands:
├── discover   (find the region-blocking API endpoint)
├── aggregate  (build blocked_countries.txt/json)
└── configure  (apply list to UniFi controller)
```

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![MIT](https://img.shields.io/badge/license-MIT-green?style=flat-square)

</td>
<td>

&nbsp;

</td>
</tr>
</table>

</div>

---

## `$ git log --oneline contributions/`

<div align="center">

```
a1b2c3d feat(GpgFrontend): Linux dark mode for Qt6    [C++]
d4e5f6g feat(Pangolin): sticky sessions support       [TS]
```

| PR | Project | Description |
|:---|:--------|:------------|
| [#209](https://github.com/saturneric/GpgFrontend/pull/209) | GpgFrontend | Linux dark mode for Qt6 Fusion theme |
| [#511](https://github.com/fosrl/pangolin/pull/511) | Pangolin | Sticky sessions for stateful apps |

[![Sponsor](https://img.shields.io/badge/♥_SPONSOR-Pangolin-ff69b4?style=flat-square)](https://github.com/fosrl/pangolin)

</div>

---

## `$ cat /proc/ai`

```go
package engineer

import _ "embed"

//go:embed inference.py
var ai string  // from anthropic import Claude

type Stack struct {
    Tools    []string  // {"OpenAI", "Anthropic", "LM Studio", "LocalAI"}
    Velocity int       // 10x
    IPSafe   bool      // true
}
```

<div align="center">

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-181717?style=flat-square&logoColor=white)
![LM Studio](https://img.shields.io/badge/LM_Studio-0D96F6?style=flat-square&logoColor=white)
![LocalAI](https://img.shields.io/badge/LocalAI-35B982?style=flat-square&logoColor=white)

<br/>

<picture>
  <img src="./assets/cursor-usage-2025.gif" alt="Cursor IDE usage metrics, 2025" width="75%" />
</picture>

<sub>`// AI-assisted development metrics, 2025`</sub>

</div>

---

## `$ pacman -Qi toolbox`

```
Languages......: bash, python, go
DevOps.........: terraform, ansible, puppet, github-actions, argocd
Containers.....: docker, kubernetes, firecracker, fargate
Observability..: prometheus, victoriametrics, grafana, loki, datadog
Security.......: snyk, sonarcloud, owasp-zap, veracode, gitguardian, nessus
Cloud..........: aws, cloudflare, azure, gcp, vultr, fly.io, hetzner
Platforms......: linux, proxmox, vmware, windows-server
```

<details>
<summary><code>$ cat ~/.config/skills.yml</code></summary>

<br/>

> Rating scale: 5★ = world-class mastery, 3★ = solid professional competence

### `development:`

| skill | level | notes |
|-------|-------|-------|
| `bash` | `★★★☆☆` | Extensive automation |
| `python` | `★★☆☆☆` | APIs, pipelines |
| `go` | `★☆☆☆☆` | Microservices, CLIs |

### `devops:`

| skill | level | notes |
|-------|-------|-------|
| `terraform` | `★★★☆☆` | Multi-cloud IaC |
| `puppet` | `★★★★☆` | Large-scale policy |
| `ansible` | `★★☆☆☆` | Config management |
| `github-actions` | `★★★☆☆` | CI/CD |

### `containers:`

| skill | level | notes |
|-------|-------|-------|
| `docker` | `★★★★☆` | Optimized builds |
| `kubernetes` | `★★★☆☆` | Orchestration |
| `argocd` | `★★★☆☆` | GitOps |

### `observability:`

| skill | level | notes |
|-------|-------|-------|
| `prometheus` | `★★★☆☆` | Metrics/alerting |
| `grafana` | `★★★☆☆` | Visualization |
| `datadog` | `★★★☆☆` | Cloud monitoring |

### `platforms:`

| skill | level | notes |
|-------|-------|-------|
| `linux` | `★★★★☆` | RHEL, Ubuntu |
| `aws` | `★★★★☆` | Full ecosystem |
| `cloudflare` | `★★★★☆` | Edge, zero-trust |
| `proxmox` | `★★★★☆` | Virtualization |

</details>

---

## `$ gpg --list-keys certs/`

<div align="center">

<a href="https://www.credly.com/badges/560a4d43-a9c9-43dd-8d2c-dc17b4c0f5e3/public_url">
<img src="https://images.credly.com/size/110x110/images/0e284c3f-5164-4b21-8660-0d84737941bc/image.png" width="80" />
</a>
&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://www.credly.com/badges/0e9019e7-545f-4243-9d8f-83c14c4dea7a/public_url">
<img src="https://images.credly.com/size/110x110/images/6eeb0a98-33cb-4f72-bfc3-f89d65a3286c/image.png" width="80" />
</a>

**AWS Solutions Architect** · **CISSP**

</div>

---

```
╔═══════════════════════════════════════════════════════════╗
║                                                           ║
║   $ echo "Interesting problems, collaboration welcome"    ║
║                                                           ║
╚═══════════════════════════════════════════════════════════╝
```

<div align="center">

[![Connect](https://img.shields.io/badge/ssh_mevans@linkedin-181717?style=for-the-badge&logo=linkedin&logoColor=0A66C2)](https://www.linkedin.com/in/mevanssecurity/)

</div>

---

## `$ gpg --export --armor matt@secunit.io`

<div align="center">

![GPG](https://img.shields.io/badge/GPG-0093DD?style=flat-square&logo=gnuprivacyguard&logoColor=white)
![KeyID](https://img.shields.io/badge/0x69D470703EAF7601-333?style=flat-square)

</div>

<details>
<summary><code>$ cat publickey.asc</code></summary>

<br/>

```
-----BEGIN PGP PUBLIC KEY BLOCK-----

xjMEZU9sQhYJKwYBBAHaRw8BAQdAX8i0gIEQHip34e5k2wJYH8CLov2j45jt
0M4e/CvOY3XNIW1hdHRAc2VjdW5pdC5pbyA8bWF0dEBzZWN1bml0LmlvPsKM
BBAWCgA+BYJlT2xCBAsJBwgJkGnUcHA+r3YBAxUICgQWAAIBAhkBApsDAh4B
FiEEfzYORnxnKhalUHqCadRwcD6vdgEAAAz1AP4tzQ+DRZ2hX+FhQwMEbsyV
RxWzgxkw8k6B4JLVPCMj5QEAgFvr13Xfn9kuA9hsd9gHE+77s9dK+qNwy2F0
po35Pg3OOARlT2xCEgorBgEEAZdVAQUBAQdAXkJ1xOP7qU65XrIOmv53lF4M
+twHsyB6QcAANW0gxkADAQgHwngEGBYIACoFgmVPbEIJkGnUcHA+r3YBApsM
FiEEfzYORnxnKhalUHqCadRwcD6vdgEAAAvWAQCIIUi3S6fshC6Rh8W5f6q0
A6Vd+LiN+d+cumz529tT+gEA3OeZ1fflS9NYuMEPzq49TvqkzoyukizhrAJ5
Jd9oXw8=
=0Qe6
-----END PGP PUBLIC KEY BLOCK-----
```

**[Download public key](./assets/publickey.matt@secunit.io-7f360e467c672a16a5507a8269d470703eaf7601.asc)**

</details>

---

<div align="center">

<sub>`exit 0` · [x86txt](https://github.com/x86txt)</sub>

</div>
