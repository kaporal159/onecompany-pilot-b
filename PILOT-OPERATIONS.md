# Pilot B — independently owned A4 execution

Reviewed fixture source: NTinkicht/OneCompany main, commit 97eea23b8c36c5cea5b4a17b9c60621fa4130c61.

This separately owned disposable repository belongs to kaporal159. The exact reviewed worker is project-local and may only create WU-B at docs/onecompany-fixture/WU-B.md on canonical branch onecompany-a4-wu-b and one PR. Owner permission to enable is distinct from being a named technical PR reviewer. No extra paid spend. Source OneCompany remains L1.

Before running, verify project-local policy and exact reviewed source/workflow blobs. Owner opt-in variables after installation: ONECOMPANY_A4_PRODUCER_ENABLED=true, ONECOMPANY_A4_APPROVED_DISPATCHER=NTinkicht (the specifically authorized connected writer, not a mandated reviewer), ONECOMPANY_A4_LOGICAL_ACTOR=fixture-bot. Do not enable arbitrary actions, credentials or another repository.

Trigger repository_dispatch event onecompany.a4-produce with client_payload {"work_unit":"WU-B","actor":"fixture-bot"}. Capture real Actions run ID. After PR creation dispatch .github/workflows/onecompany-a4-fixture-validation.yml against its PR head. Readme and installation PR alone do not qualify P1.
