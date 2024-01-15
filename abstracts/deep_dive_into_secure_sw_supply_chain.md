### Title

Deep dive into the secure software supply chain on IaC

### Short description

In this talk I’ll explain what is the Software Supply Chain, common threats and mitigations and how they apply to IAC ecosystem too. I’ll show off security threats using Terraform and its ecosystem and finally i’ll talk about OCI images talking about digital signatures and SBOM using Sigstore and Syft. I’ll do a live coding session showing off how to deploy secure OCI images on K8S cluster with security policies built with Kyverno, the session includes also security scanning using the generated SBOM.

### Long description

Background:

The security of the Software Supply Chain is a hot topic in the last years, the recent SolarWinds attack has shown how a compromised software supply chain can be a real threat for the security of the whole ecosystem. As developers or cloud engineers we should have a clear understanding of the threats to our infrastructure and how to mitigate them. By increasing awareness of supply chain security as a community, we will be able to provide safer code and software for the world.

Goal:

By the end of the talk, the audience will be educated about how to secure their infrastructure using some best practices and tools like Sigstore, Syft, Checkov, Snyk and others, ant to automate the dependency management with Dependabot or RenovateBot.

Target audiences:

DevOps, DevSecOps, software engineers.

Outline (40 mins):

- Intro to Software Supply Chain and common threats (5 mins)
- Deep Dive into IaC with Terraform/OpenTofu (15 mins)
- Deep Dive into OCI images and SBOM (10 mins)
- DEMO of Sigstore and Syft (10 mins)

### Suggested length

40 mins

### References

- [Have we reached a point of no return on managing software dependencies?](https://www.paolomainardi.com/posts/point-of-no-return-on-managing-software-dependencies/)
- [OpenTofu](https://opentofu.org/)
- [Sigstore](https://sigstore.dev/)
- [Syft](https://anchore.com/opensource/)
- [Checkov](https://www.checkov.io/)

### Slides

[slides url](https://www.slideshare.net/sparkfabrik/codemotion-2023-deep-dive-nella-supply-chain-della-nostra-infrastruttura-cloudpdf)
