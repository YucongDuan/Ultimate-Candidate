# DIKWP-ONE 6.0 Ultimate Candidate - Delivery Map

## System position

This is an integrated artificial-consciousness **ultimate candidate**, not a certificate of phenomenal consciousness. Semantic content is strictly limited to D / I / K / W / P. Repository outputs, model self-reports and prior certificates enter the runtime only as D and must be re-tested.

## Files

- `dikwp_one_6_0_ultimate_candidate_source.zip`: GitHub-ready clean source tree, tests, license, governance and CI.
- `dikwp_one_ultimate-6.0.1-py3-none-any.whl`: installable Python package.
- `dikwp_one_6_0_ultimate_candidate_standalone_studio.html`: offline single-file Studio.
- `dikwp_one_6_0_ultimate_candidate_report_cn.docx`: editable Chinese technical report.
- `dikwp_one_6_0_ultimate_candidate_report_cn.pdf`: fixed-layout report.
- `dikwp_one_6_0_ultimate_candidate_reference.zip`: full deterministic reference outputs.
- `dikwp_one_6_0_ultimate_candidate_validation.json`: machine-readable QA and evidence boundary.
- `dikwp_one_6_0_ultimate_candidate_sbom.spdx.json`: SPDX 2.3 SBOM.
- `interface_previews/`: validated interface screenshots.
- `SHA256SUMS.txt`: hashes for packaged components.

## Run

```bash
python -m pip install dikwp_one_ultimate-6.0.1-py3-none-any.whl
dikwp-one demo --out outputs/reference --steps 1800
dikwp-one verify outputs/reference
dikwp-one serve outputs/reference --port 8788
```

Open `http://127.0.0.1:8788/dashboard.html`.

## Boundary

The system provides an E2 author-side deterministic reference implementation. It does not prove subjective experience, moral status, legal personhood, unrestricted autonomy or first-person identity transfer.
