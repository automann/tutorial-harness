# tutorial-harness

**This name is reserved for an active project. This `0.0.x` release is a
placeholder and contains no functionality — do not install or depend on it.**

`tutorial-harness` will be the governance runtime CLI of the
`large-tutorial-creator` project: an agent-neutral system for producing
book-length, progressive technical tutorials under enforced governance
workflows. The project is under active development; its source and governance
repository is currently private, and this repository is the public home of the
npm distribution.

The first real release will be `tutorial-harness@3.0.0` (the version continues
the `large-tutorial-creator` skill's release train, currently at `2.7.1`),
providing:

- `tutorial-harness pr-tail …` — fail-closed PR-tail classification,
  provider inspection, and controlled mutation planning;
- `tutorial-harness mold …` — deterministic instantiation and validation of
  downstream tutorial-repository governance skeletons;
- `tutorial-harness job …` — the Chapter Job workflow state machine;
- `tutorial-harness setup` / `doctor` — authoring-environment provisioning
  and diagnosis.

Release announcements and public documentation will appear in this repository
as the 3.0.0 release approaches.
