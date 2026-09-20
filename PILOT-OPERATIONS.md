# Pilot B — independently owned A4 execution

Reviewed fixture source: NTinkicht/OneCompany main, commit d7f29071afe58def01e19b9205ee5b48842b1b7a.

This separately owned disposable repository belongs to kaporal159. The exact reviewed worker is project-local and may only create WU-B at docs/onecompany-fixture/WU-B.md on canonical branch onecompany-a4-wu-b and one PR. Owner permission to enable is distinct from being a named technical PR reviewer. No extra paid spend. Source OneCompany remains L1.

Leave Actions repository variable ONECOMPANY_EMERGENCY_STOP absent/false for normal operation; true or an unrecognized value skips new runner jobs. Cancel an already running GitHub Actions job separately if needed.

Before running, verify project-local policy and exact reviewed source/workflow blobs. Owner opt-in variables after installation: ONECOMPANY_A4_PRODUCER_ENABLED=true, ONECOMPANY_A4_APPROVED_DISPATCHER=NTinkicht (the specifically authorized connected writer, not a mandated reviewer), ONECOMPANY_A4_LOGICAL_ACTOR=fixture-bot. Do not enable arbitrary actions, credentials or another repository.

Trigger repository_dispatch event onecompany.a4-produce with client_payload {"work_unit":"WU-B","actor":"fixture-bot"}. Capture real Actions run ID. After PR creation dispatch .github/workflows/onecompany-a4-fixture-validation.yml against its PR head. Readme and installation PR alone do not qualify P1.
