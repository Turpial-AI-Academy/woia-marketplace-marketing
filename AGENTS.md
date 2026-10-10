# AGENTS.md

- This repository is a generated WOIA department marketplace.
- Only authorized WOIA maintainers/developers may modify source.
- Never treat this repository as the canonical plugin registry.
- Plugin identity/release/lifecycle lives in `woia-ecosystem/registry/plugins.json`.
- Base membership lives in `woia-ecosystem/registry/marketplaces.json`; product additions and selections live in `registry/products.json`.
- Generate every catalog view through Ecosystem's deterministic `marketplace:generate` command. Preserve the exact source provenance in `GENERATED_FROM.json`.
- Do not add Plugin Factory logic or capability implementation here.
- Preserve historical tags and assets. Publish a verified draft only after the exact ZIP is uploaded and checked.
- Do not publish/merge marketplace changes without the required maintainer authorization.
