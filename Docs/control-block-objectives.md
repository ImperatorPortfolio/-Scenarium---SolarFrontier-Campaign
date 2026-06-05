# Solar Frontier Control Block Objectives

Solar Frontier v0.4.0 uses the generic Scenarium objective primitive:

- Objective type: `ControlBlockDestroyed`
- Target block name: `SCENARIUM_OBJECTIVE_CONTROL`
- Transition: `destroyed`

The campaign pack remains the authority for:

- conquest node ids
- reveal chain
- MES spawn group bindings
- faction ownership

The NPC pack provides the actual prefabs and must include a terminal block named `SCENARIUM_OBJECTIVE_CONTROL` in each objective base.

Future schema should express this per-node directly, but this update keeps compatibility with the current Campaign.xml format.
