

---

# 🧠 **1. System Design & Architecture**

* Design a **multi-tenant Kubernetes/EKS cluster** with isolation across dev, QA, and prod environments, ensuring no noisy neighbor issues.
* How would you design infrastructure that **empowers developers while preventing misuse**?
* Describe a **hybrid cloud routing architecture** between AWS and GCP. Where do you enforce boundaries?
* Explain how you’d **secure cross-region S3 replication** and validate data integrity at scale.
* You’re moving from centralized logging to a **service mesh–based observability model** — what trade-offs do you consider?
* What trade-offs do you evaluate when redesigning an **observability architecture**?

---

# ⚙️ **2. Kubernetes & Platform Engineering**

* What’s your approach to managing **10+ Kustomize overlays** without drift or duplication?
* How do you perform **zero-downtime upgrades for stateful workloads using Helm 3**?
* How do you **prevent lateral movement between pods** inside a cluster?
* Walk through your strategy to **detect and mitigate pod-to-pod lateral movement**.
* What happens when **systemd encounters a failing unit** on a containerized node? How would you auto-recover?
* Kubernetes nodes are healthy, but `kubectl logs` returns nothing — what could be the cause?

---

# ☁️ **3. Terraform, AMIs & Infrastructure**

* Your **Terraform state got corrupted during backend migration** — what is your recovery strategy?
* What checks do you perform before **approving a custom AMI for production**?
* What’s your **Linux/system-level checklist** before promoting an AMI to production?
* Systemd journal logs disappear after reboot on some AMIs — what do you investigate in the image build and boot process?

---

# 🔍 **4. Troubleshooting & Incident Response**

### 🔐 Networking / Load Balancing

* TLS handshakes start failing after an **ALB config change** — walk through your RCA.
* Users see **504 errors but load balancer health checks are green** — how do you investigate?

---

### ⚙️ Kubernetes / Workloads

* A logging sidecar is deployed and **CPU throttling spikes** — what’s happening?
* Autoscaling isn’t triggering despite high CPU — is it **metrics, HPA, or API server**?
* A production pod is **OOMKilled but logs are missing** — how do you debug?
* Kernel panic on a node during deployment — how do you determine if it’s **infra, base image, or application-related**?

---

### 🖥️ System / Runtime

* What happens when **systemd hits a failing unit**? How do you recover automatically?
* System logs vanish after reboot — what’s your debugging approach?

---

# 🧪 **5. Practical / Hands-on**

* Bash one-liner:
  👉 Find all running containers using **more than 500MB RSS memory** on a node.
