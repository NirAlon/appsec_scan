# AppSec Scanner Action

A composite GitHub Action that runs:

- ✅ Semgrep for Static Analysis (SAST)
- ✅ Terrascan for Infrastructure as Code (IaC) scanning
- ✅ Trivy for Software Composition Analysis (SCA)

## Requirements

- Ubuntu Runner
- Python pre-installed (for semgrep)

## Usage

```yaml
- name: AppSec Scanner
  uses: NirAlon/appsec_scan@latest
```
