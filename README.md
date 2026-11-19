# Victoria Prado

**Cloud operations, cybersecurity, and Linux infrastructure · Madrid, Spain**

## Technical skills

- **Cloud operations lab** · AWS EC2, Ubuntu deployment, and resource teardown
- **Cybersecurity lab** · Private access with Tailscale, restricted service permissions, and encrypted backups
- **Linux operations** · systemd services and timers, health monitoring, and incident recovery
- **Networking** · Ethernet LANs, static IPv4, router DNS settings, and Windows and Linux connectivity troubleshooting

## Pink Party

[Pink Party](https://github.com/V1cksy/pink-party) is my private voice room for game nights with up to four people. It uses TypeScript, Vite, Node.js 24, and LiveKit.

- **AWS deployment** · Used encrypted storage, restricted SSH ingress, and private Tailscale access. Verified startup after reboot and removed the temporary resources. [Deployment report](https://github.com/V1cksy/pink-party/blob/main/docs/cloud-report.md)
- **Service monitoring** · Ran the app under a dedicated Linux account. A separate systemd timer detected a deliberate outage and recorded recovery. [Linux setup](https://github.com/V1cksy/pink-party/blob/main/docs/linux-deployment.md) · [Incident report](https://github.com/V1cksy/pink-party/blob/main/docs/incident-linux-monitoring.md)
- **Backup recovery** · Restored encrypted data and configuration into a fresh Ubuntu VM. Tested SFTP against a local OpenSSH fixture. [Recovery report](https://github.com/V1cksy/pink-party/blob/main/docs/recovery-off-vm.md) · [SFTP exercise](https://github.com/V1cksy/pink-party/blob/main/docs/offsite-backup-report.md)
- **Continuous integration** · Ran TypeScript and Python tests in GitHub Actions, along with browser tests using synthetic audio. [CI run](https://github.com/V1cksy/pink-party/actions/runs/44173546388)

_Lab scope: live off-device backups and voice calls between separate homes remain unverified._

<img src="https://raw.githubusercontent.com/V1cksy/pink-party/main/public/farmhouse.svg" alt="Pink Party’s original pixel art farmhouse with a rose roof" width="144">
