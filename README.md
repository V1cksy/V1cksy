# Victoria Prado

**Cloud operations, cybersecurity, and Linux infrastructure · Madrid, Spain**

## Technical skills

- **Cloud operations labs** · Ubuntu deployment on AWS EC2, reboot verification, and resource teardown.
- **Cybersecurity labs** · Private access with Tailscale, restricted Linux service permissions, and encrypted backup and recovery.
- **Linux operations** · systemd services and timers, health monitoring, incident recovery, and continuous integration with GitHub Actions.
- **Networking and support** · Ethernet LANs, static IPv4, router DNS settings, and Windows and Linux workstation troubleshooting.

## Pink Party

![Original pixel-art farmhouse created for Pink Party](https://raw.githubusercontent.com/V1cksy/pink-party/main/public/farmhouse.svg)

[Pink Party](https://github.com/V1cksy/pink-party) is my personal project, a private voice room for up to four people on game night. It runs on TypeScript, Vite, Node.js 24, and LiveKit.

- A temporary Ubuntu deployment on AWS EC2 used encrypted storage, restricted SSH ingress, and private voice access through Tailscale. The service restarted after an EC2 reboot, and the lab resources were removed. [AWS deployment report](https://github.com/V1cksy/pink-party/blob/main/docs/cloud-report.md)
- The Ubuntu installation runs under a dedicated service account with restricted writable directories. A separate systemd timer detected a deliberate outage and recorded recovery. [Linux deployment](https://github.com/V1cksy/pink-party/blob/main/docs/linux-deployment.md) · [Incident report](https://github.com/V1cksy/pink-party/blob/main/docs/incident-linux-monitoring.md)
- Encrypted backups restored application data and configuration into a fresh Ubuntu VM. SFTP was tested against a local OpenSSH fixture. [Recovery report](https://github.com/V1cksy/pink-party/blob/main/docs/recovery-off-vm.md) · [SFTP exercise](https://github.com/V1cksy/pink-party/blob/main/docs/offsite-backup-report.md)
- GitHub Actions ran TypeScript and Python tests alongside browser tests with synthetic audio. [Hosted CI run](https://github.com/V1cksy/pink-party/actions/runs/44173546388)

Live off-device backup storage and a voice call between separate homes remain unverified.
