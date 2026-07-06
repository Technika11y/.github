```
════════════════════════════════════════════════════════
   ▐▛▀▜▌   T E C H N I K A · 1 1 · Y
   ▐▙▄▟▌   root access for everyone · one discipline, two sides
════════════════════════════════════════════════════════
```

## TECHNIKA11Y

`Root access for everyone.`

Security, compliance, and accessibility are one discipline. A gate that's locked but unusable
has failed; so has one that's usable but open.

```js
const FULL = PERCEIVABLE | OPERABLE | ROBUST | SECURE;   // 0b1111
gate(profile) => (profile.conformance === FULL) ? "granted" : { denied, unmet };
```

🌐 **[technika11y.github.io](https://technika11y.github.io/)**

---

### The suite

Open, defensive tooling at the intersection of access and security. Every repo is honestly
`alpha` — pre-release, tested, and labeled for exactly what it does and doesn't do yet.

**Accessibility & assurance**
- [shadow-dom-auditor](https://github.com/technika11y/shadow-dom-auditor) — pierces shadow DOM for the accessibility defects *and* injection smells conventional scanners miss
- [pdf-ua-linter](https://github.com/technika11y/pdf-ua-linter) — PDF/UA (ISO 14289) conformance, every finding mapped to a Matterhorn Protocol checkpoint
- [vpat-generator](https://github.com/technika11y/vpat-generator) — WCAG 2.2 Accessibility Conformance Reports from the complete Level A + AA catalog
- [procurement-scanner](https://github.com/technika11y/procurement-scanner) — vendor intake → GO/NO-GO against a Section-508 + security + SBOM baseline
- [log-hardener](https://github.com/technika11y/log-hardener) — redacts PII and secrets from log streams before they reach a SIEM
- [incident-disclosure-toolkit](https://github.com/technika11y/incident-disclosure-toolkit) — turns incident facts into a dated notification checklist + advisory skeletons

**Food-service operations**
- [kitchen-microsegmenter](https://github.com/technika11y/kitchen-microsegmenter) — zero-trust nftables so a compromised sensor can't pivot to the POS
- [iot-firmware-auditor](https://github.com/technika11y/iot-firmware-auditor) — flags EOL/outdated firmware and default credentials on kitchen IoT
- [menu-a11y-engine](https://github.com/technika11y/menu-a11y-engine) — menu data → WCAG-compliant, allergen-aware, screen-reader-friendly menus
- [allergen-validator](https://github.com/technika11y/allergen-validator) — checks a dish's declared allergens actually match its ingredients
- [sous-vide-telemetry](https://github.com/technika11y/sous-vide-telemetry) — tamper-evident temperature ledger + HACCP proof-of-compliance

**Labs** — affectionate homages, built real
- [tron](https://github.com/technika11y/tron) — the Grid guardian: patrols observed traffic against the sanctioned-flow policy
- [cyberdyne](https://github.com/technika11y/cyberdyne) — the safety governor: the off switch Skynet never had

### Roadmap

Twenty-eight planned; status is honest. `planned` means planned, not hidden — the rest land as
they're built and tested.

---

**Contact / security:** technika11yspeakn@gmail.com — coordinated disclosure per each repo's `SECURITY.md`.

*Ship few, ship real, label honestly. Authority is earned, never staged.*
