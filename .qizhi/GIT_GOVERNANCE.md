# QiZhi Git governance

Git-only standard: **v1.3.0** at full commit **a07f432d5cf645a281f54ff35a219b85f0234667**. Public reusable executor pinned to **14757dec9aeaaa803105a027beb2abbb5e921139**. This supplements, never silently replaces, existing project-specific business/AI or module Standards Baseline.

Rules: new branches `type/scope-topic`; new non-merge commit subjects and PR titles `type(scope): description`; PR + passing CI before merging; default **Create a merge commit**; never rewrite production history, tags, or business results. Generated GitHub merge titles are exempt. Existing in-flight PRs may have naming-only exceptions recorded in `.qizhi/governance.lock.json`; project CI is never excepted.

Canonical source: https://github.com/qizhi-id/QiZhi_CostTools_Standards/blob/v1.3.0/standards/GIT_WORKFLOW_GOVERNANCE_STANDARD.md

Governance CI runs on PR, push and a weekly schedule. If branch protection cannot be enabled, a green check does not itself stop an administrator from merging; latest check results still require review.

## GitHub account rename — 2026-10-15

Current GitHub owner: `qizhi-id`; unchanged account ID: `277366790`.
Use `https://github.com/qizhi-id/<repository>` for current repository URLs,
clone commands, automation ownership checks, and online retrieval.

Fixed Standards declarations, schemas, vendored provenance and source hashes,
historical reports and source confirmations retain their original recorded
identity. Where those frozen records contain the former owner, resolve the
same repository and exact tag/commit under `qizhi-id`; this is an account
rename, not a Standards adoption or a business/version change. Do not rewrite
released tags, archived evidence, Android application IDs, or signed APKs.

