# jbaez120 — Developer Portfolio

> **Focus areas:** Network Security · Systems Programming · Infrastructure Automation · AI-Assisted Tools

---

## Projects

### 🔒 [vpnai](https://github.com/JBaezDev25/vpnai) — Rust · Systems · Networking
**Custom UDP VPN Connection Manager**

Built a full VPN stack from scratch in Rust with no third-party VPN framework.

**Key capabilities:**
- Custom encrypted tunnel over UDP — ChaCha20-Poly1305 AEAD encryption, HMAC-SHA256 challenge-response auth
- TUN/TAP device management (vpn0) with full-tunnel routing and DNS leak protection
- WireGuard client mode — connects to NordVPN, Mullvad, ProtonVPN via standard `.conf` files (boringtun)
- SOCKS5 proxy — standalone (no root) and over-VPN (traffic bound to TUN IP)
- Multi-client server with IP pool, exponential backoff reconnect, keepalive heartbeat
- iptables + ip route automation for NAT masquerade and routing

**Skills:** Rust async (Tokio), TUN/TAP, Linux networking, iptables, WireGuard protocol, cryptography

---

### 🛡️ [WG_UFW-Server](https://github.com/JBaezDev25/WG-home-VPN) — Python · Automation · AI
**WireGuard VPN + UFW Firewall Manager with Claude AI Assistant**

Automated management platform for WireGuard VPN deployments on Ubuntu 24.04.

**Key capabilities:**
- Automated WireGuard peer provisioning and revocation
- UFW firewall rule management integrated with VPN lifecycle
- Claude AI assistant for natural-language VPN administration
- Deployment scripts using rsync over SSH

**Skills:** Python, WireGuard, UFW, Linux administration, Anthropic Claude API, shell scripting

---

### 📡 [netwatchm](https://github.com/JBaezDev25/netwatchm) — Python · Security · Monitoring
**Real-Time Network Threat Monitor**

Production-grade network monitoring tool with threat detection, dashboards, and alerting.

**Key capabilities:**
- Live packet analysis — port scan detection (SYN, NULL, XMAS), brute force, exfiltration, new device alerts
- Rich terminal dashboard + web UI for real-time visibility
- Email + ntfy push notifications on threat events
- Grafana dashboard integration with synthetic event seeding
- CLI subcommands: `inventory`, `deep-inspect`, `analytics`, `report`
- Hotdeploy pipeline via rsync over SSH

**Skills:** Python, libpcap/scapy, threat detection, Rich, FastAPI/web, Grafana, CI/CD scripting

---

### 🔍 [pk_sniffer](https://github.com/JBaezDev25/pk_sniffer) — C · Low-Level · Security
**Packet Sniffer & Threat Detection Tool**

Low-level network sniffer written in C for Linux environments.

**Key capabilities:**
- Real-time packet capture via libpcap
- Detects SYN/NULL/XMAS port scans, ICMP floods, oversized packets, malformed frames
- Monitors suspicious ports (FTP, Telnet, SMB, RDP, MySQL, VNC, known trojan ports)
- Color-coded terminal output with threat statistics

**Skills:** C, libpcap, TCP/IP, Linux sockets, network forensics

---

### 🎨 [uigen](https://github.com/JBaezDev25/uigen) — TypeScript · React · AI
**AI-Powered React Component Generator**

Conversational UI where users describe a component in chat and see it rendered live.

**Key capabilities:**
- Claude AI generates React components via tool calls (str_replace_editor, file_manager)
- Virtual in-memory file system — no disk writes, instant preview
- Live sandboxed iframe rendering with Babel JSX transformation
- Vercel AI SDK streaming responses

**Skills:** Next.js, React, TypeScript, Anthropic SDK, virtual FS, Vercel AI SDK

---

### 📁 [files_manager](https://github.com/JBaezDev25/files_manager) — Python · Automation
**File Transfer & Management Utility**

GUI and CLI tools for automated file transfer and management operations.

**Key capabilities:**
- GUI and headless file transfer modes
- Automated transfer logging and test coverage

**Skills:** Python, Tkinter/GUI, file I/O, test automation

---

## Skills Summary (Resume)

| Area | Technologies |
|------|-------------|
| **Systems & Networking** | Rust, C, TUN/TAP, WireGuard, iptables, UDP/TCP, libpcap |
| **Security & Monitoring** | Threat detection, packet analysis, port scan detection, SOCKS5, VPN protocols |
| **Infrastructure Automation** | Python, Shell scripting, rsync/SSH deploy, UFW, iptables automation |
| **AI Integration** | Anthropic Claude API, Vercel AI SDK, tool use, streaming |
| **Frontend** | React, Next.js, TypeScript, live preview, virtual FS |
| **DevOps** | Git, GitHub, Docker, deploy pipelines, Grafana |

---

## GitHub
[github.com/JBaezDev25](https://github.com/JBaezDev25)
