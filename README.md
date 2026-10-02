### Hi, I'm Innocent (Nkosiyethu) Mbatha

I'm changing careers into IT from Mbombela, South Africa. I learn by building networks in a home lab, breaking them on purpose, and writing up how I fixed them.

- **CCNA candidate.** Studying for the exam now.
- **Linux Essentials** (held).
- **Looking for:** helpdesk, network technician and junior NOC roles.

---

#### Featured project: [Bank Main Branch Network](https://github.com/Nkosiyethu95/bank-main-branch-network)

A three-tier bank branch in Cisco Packet Tracer, built with my partner Nondumiso Mbuyazi. She did Layer 2 plus the SVIs and the routed EtherChannel between the core switches. I did Layer 3 and the services:

- **HSRP** gateways for 10 VLANs (one virtual IP per VLAN, Active/Standby with preempt)
- **DHCP** on one edge router, relayed from the core switches with `ip helper-address`
- **Static routing** inside the branch and out to a Head-Quarters server
- **DNS** for the branch

The repo has a 27-page design document, per-device configs, a test plan, and write-ups of the two lab incidents I resolved: a Finance VLAN that lost its HSRP gateway, and a DHCP relay path that left clients on APIPA. It also lists the known issues and the tests I haven't run yet.

---

#### What I work with

| Area | Tools and topics |
|---|---|
| Networking | VLANs, 802.1Q trunks, subnetting, HSRP, DHCP and relay, static routing, DNS, inter-VLAN routing |
| Troubleshooting | Isolating L2 vs L3, `show` commands, ping/tracert, writing up tickets (fault → diagnose → fix → verify) |
| Linux | Command line, text tools (`grep`, `cut`, `sort`, pipes, redirection), basic Bash scripting, user management |
| Tools | Cisco Packet Tracer, Git and GitHub |

#### Currently learning

- **CCNA** exam prep. This is the main focus.
- **Longer term: cloud and DevOps.** Early hands-on labs with AWS EC2, Docker and Jenkins CI/CD. Still at the lab stage.

#### Elsewhere on my GitHub

- [user-creation-script](https://github.com/Nkosiyethu95/user-creation-script): a Bash script that creates a Linux user with checks and password confirmation
- [Linux-essential-](https://github.com/Nkosiyethu95/Linux-essential-): my Linux Essentials study notes

---

[LinkedIn](https://www.linkedin.com/in/innocent-mbatha-366446247/)
