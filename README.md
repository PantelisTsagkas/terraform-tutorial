# Terraform Mastery — From Zero to Infrastructure

A concise, hands-on guide to provisioning and managing cloud infrastructure with HashiCorp Terraform. The full, styled tutorial is available in the local HTML file: [terraform-tutorial.html](terraform-tutorial.html).

**Contents**

- **Overview**: What Infrastructure as Code (IaC) is and where Terraform fits.
- **Installation & Setup**: Installing Terraform on macOS, Linux, and Windows.
- **Core Concepts**: Providers, resources, variables, outputs, state, and modules.
- **Workflow**: The typical CLI workflow (init → plan → apply), remote state, and backends.
- **Production**: Best practices, troubleshooting, and further resources.

**Quick start — view the tutorial**

- Open the file directly in a browser: open the workspace file [terraform-tutorial.html](terraform-tutorial.html) with your browser.

- Serve it locally (recommended for full resource loading):

```bash
# from the project root
python3 -m http.server 8000
# then open http://localhost:8000/terraform-tutorial.html
```

**Try the examples**

- Many examples are shown in the HTML. To run CLI examples you will need Terraform installed.

macOS (Homebrew):

```bash
brew tap hashicorp/tap
brew install hashicorp/tap/terraform
terraform -version
```

Ubuntu/Debian (apt):

```bash
# follow HashiCorp instructions — add repo, then:
sudo apt update && sudo apt install terraform
terraform -version
```

**Project structure**

- [terraform-tutorial.html](terraform-tutorial.html) — the tutorial content and examples (single-file HTML).

**Contributing**

- Suggestions, corrections, or example improvements: open an issue or submit a pull request against this repository.

**Notes & license**

- This repository does not include an explicit license. Check with the repository owner before reusing or publishing the material.

---
