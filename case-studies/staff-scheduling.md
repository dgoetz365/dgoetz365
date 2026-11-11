# Staff scheduling

My scheduling work connects availability, assignments, shift changes, and schedule visibility. It includes implementing and iterating on workflows, validation, review states, and guidance for the people using the tools.

Scheduling is a state-management problem as well as a calendar problem. A requested change, an approved change, a saved draft, and the schedule someone should act on are distinct states. Constraints must be checked again when a decision is applied, because the underlying schedule may have changed since the request was made.

The engineering work emphasizes clear transitions, appropriate views, publication safeguards, and tests for changes that compete or arrive out of order. The enablement work explains those states to users and supports the rollout. Related implementations share a product lineage; I do not count every variation as a separately invented platform.

This account omits actual rosters, availability, locations, communications, staffing policies, and access arrangements. It describes contributions rather than asserting sole ownership of every component.

## Inspect an independent example

[Staffing Scheduler](https://github.com/dgoetz365/staffing-scheduler) uses a fictional science exhibition and volunteer roster. Assign a qualified, available volunteer; see an overlapping assignment rejected; publish a complete schedule; then request and review a reassignment while the earlier publication remains intact.

The public implementation and tests are new. They demonstrate constraint checking and change review, not the internal system's staffing policy or current deployment status.

[All work notes](../WORK.md) · [Profile](../README.md)
