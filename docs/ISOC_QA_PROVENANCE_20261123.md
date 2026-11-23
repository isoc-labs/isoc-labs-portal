# Historical QA evidence provenance (ISOC Labs)

The historical XDR Labs GitHub Actions run URLs and PR numbers **cannot** be moved automatically into ISOC Labs by GitHub fork/snapshot. ISOC's repositories contain copied sources and assets, but historical CI run identifiers remain owned by the original organization.

## Historical original-run identifiers

| Historical subject | Original run ID | Status as described in the source documentation |
| --- | --- | --- |
| Suricata QA evidence (earlier) | `44895318676` | Historical source evidence for the earlier rule suite |
| Consolidated Suricata / TI QA | `44997698618` | Historical source reports 3/3 checks passing on its original revision |

The original run addresses for independent source verification (not recreated ISOC CI runs):

```text
https://github.com/xdr-labs/xdr-labs-portal/actions/runs/44895318676
https://github.com/xdr-labs/xdr-labs-portal/actions/runs/44997698618
```

**Provenance disclaimer:** This file is an index of previously reported results, **not a new or replayed CI run** and not proof that the copied ISOC GitHub workflow has passed. The old run records must be consulted on the original GitHub repository if historical verification is required.

The published ISOC files at `downloads/local-web-attack-ai-v1.0-333.rules`, `downloads/local-web-attack-ai-v1.0-333.zip`, `downloads/local-web-attack-ai-v1.2-383.zip`, and `downloads/local-web-attack-ai-v1.3-398-qa.rules` are source artifacts. The latter is an **unreleased QA candidate**, not a production-certified release.
