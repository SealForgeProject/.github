<p align="center">
  <img src="https://raw.githubusercontent.com/SealForgeProject/.github/main/assets/sealforge-banner.png" alt="SealForge — Sign code, keep your keys." width="1128">
</p>

# SealForge

**Code signing on infrastructure you control.**

SealForge is a self-hosted code-signing platform for teams and build pipelines. It brings explicit permissions, a dedicated signing worker, and your own PKCS#11 provider together in one controlled workflow.

## A more deliberate way to sign

- **Keep your keys with your provider.** Private keys stay in your configured token, HSM, or software PKCS#11 provider.
- **Choose who can sign.** Grant each user or API client explicit permission to use a registered certificate.
- **Verify before delivery.** The signing worker timestamps and verifies each signed artifact before it is made available for download.
- **Follow the work.** Track signing jobs and record security-relevant operations for audit.

## Explore SealForge

[Website](https://getsealforge.com) · [Application source](https://github.com/SealForgeProject/sealforge) · [Website source](https://github.com/SealForgeProject/site)

[LinkedIn](https://www.linkedin.com/company/SealForgeProject) · [YouTube](https://www.youtube.com/@SealForgeProject)

## Security

Report suspected vulnerabilities privately to `security [at] getsealforge [dot] com`. Please do not open a public issue or include PINs, API keys, private keys, or production data in a report.
