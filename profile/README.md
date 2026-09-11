# DiamaneOS

**This is a read-only mirror. Development happens on [Codeberg](https://codeberg.org/diamaneos).**

Issues and pull requests are disabled here. Please use the Codeberg repositories.

---

DiamaneOS is a hardened, GrapheneOS-derived Android distribution for the Fairphone 6, maintained in the EU and distributed with a locked bootloader and its own verified-boot key.

It is an independent project. **Not affiliated with or endorsed by the GrapheneOS project**, and not affiliated with Fairphone.

## Status

Pre-release. Nothing here is ready for daily use, and no release has been published. Follow progress on Codeberg.

## What it is

- Built on GrapheneOS, with its hardening retained rather than reduced
- No microG and no signature spoofing — the app sandbox is not weakened for Google compatibility
- Vendor attack surface deliberately reduced
- Verified boot with a project-controlled key, and a relocked bootloader

## What it is not

- Not GrapheneOS, and not a substitute for it. GrapheneOS does not support this hardware, and the reasons are real: the Fairphone 6 has no discrete secure element and no memory tagging
- Not a phone that will do everything a stock device does. Some applications will not work

## Verifying what you run

The published verified-boot key fingerprint, per-release provenance records, and instructions for reproducing builds independently are on the project site.

Verify the key fingerprint from more than one independently operated source before relocking any device.

## Links

- **Development:** https://codeberg.org/diamaneos
<!--
- **Website:** https://diamaneos.de
- **Security contact:** security@diamaneos.de (PGP key on the site)
-->

## Licence

Apache-2.0 for project-authored components. Upstream components keep their own licences.
