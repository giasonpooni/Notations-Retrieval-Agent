# Notations Retrieval Agent

**Inspect authored system graphs, retrieve typed subgraphs and check eligibility for explicit numerical calls.**

[Run](#install-and-run) · [Kernel boundary](docs/KERNEL.md) · [Research profile](#research-profile) · [Scope](docs/SCOPE.md)

## Notation Systems

**Frontier Tooling and Instrumentation for Digital Futures.** We develop computational instruments and operational tooling connecting scientific methods, specialized computation and human expertise.

[Notations Systems Terminal](https://github.com/giasonpooni/Notations-Systems-Terminal) composes supported investigations. This provider retains its typed graph, retrieval and eligibility implementation. ESM retains governed evidence; Cartesian Graphics develops interactive worlds, simulation technology and digital IP with separate creative state and approval. [Organization profile](https://github.com/giasonpooni/Notations-Systems-Terminal/blob/b41b84922d4963a9206202029afd1e78b9451f9c/PUBLIC_POSITIONING.md).

## Identity and scope

| Identity | Value |
| --- | --- |
| Capability | **System Graph** |
| Current repository | `Notations-Retrieval-Agent` |
| Existing provider | Schematics Retrieval Agent / SRA |
| Library / CLI | `schematics` / `sra` |
| Proposed NET family | `system.graph` |
| Implemented boundary | Authored typed function/factor graphs, retrieval, eligibility annotations and explicit companion calls |

This is a function-graph plus factor-graph representation for observer setup on declared nonlinear plants. OpenUSD is a projection. It is not schematic-image OCR, a general twin platform or a Blender/Godot editor plugin. Modules do not import JSPT, PLSR, RCI or CSE at load time.

[Notations Inference Schematics Engine](https://github.com/giasonpooni/Notations-Inference-Schematics-Engine) is a separate project, not a silent rename or replacement of SRA. Integration must preserve existing records, pins and eligibility semantics.

## Routing and projections

```mermaid
flowchart TD
  S["Authored typed schematic"] --> V{"Validate graph"}
  V -->|"malformed"| X["Refuse input"]
  V -->|"valid"| G{"Declared kernel eligibility"}
  V -->|"typed queries"| R["Retrieve subgraphs and blankets"]
  G -->|"not eligible"| A["Annotations with reasons"]
  G -->|"eligible and invoked"| K["Explicit companion adapter"]
  K -->|"sample or refusal"| A
  K -->|"kernel unavailable: NOT_CHECKED"| A
  A --> J["JSON graph and call records"]
  R --> J
  J --> P["Mermaid and USDA projections"]
```

The question is: **which subgraphs may call which kernel, and what remains unresolved?** Eligibility is not a completed numerical call. Unknown plants remain `UNRESOLVED`; fixture matrices and rendered edges do not establish a current result. Projections grant no operating authority.

## Install and run

Python 3.12/3.13:

```sh
git clone https://github.com/giasonpooni/Notations-Retrieval-Agent.git
cd Notations-Retrieval-Agent
uv run --python 3.13 python examples/quickstart.py
uv run --python 3.13 python examples/unknown_plant.py
uv run --python 3.13 --with pytest pytest -q
```

CLI:

```sh
uv run --python 3.13 sra --fixture-A -o results
uv run --python 3.13 --extra jspt sra --call-jspt -o results
uv run --python 3.13 sra --rci-digest rci-displacement-digest-fixture -o results
```

`--extra jspt` installs the pinned `sensitivity` package into the calling environment. Without it, an unavailable kernel returns `NOT_CHECKED`. Fixture A does not open PLSR.

For all pinned companion adapters, including JSPT-to-PLSR:

```sh
uv run --python 3.13 --dev --extra kernels pytest -q -m live
```

Explicit live tests require dependencies and fail when absent. The default suite excludes live tests; missing-dependency cases simulate absence even when extras are installed.

Historical pin retained: `giasonpooni/Jacobian-Sensitivity-Propagation-Testbed@7399ab03087b27683620b4c57f97b2ac14546c7f`.

Dependent numerical routes require a current content-bound Jacobian adapter record. Legacy annotations remain readable, but stale/unbound matrices do not enable covariance, structure or Lyapunov calls. Binding is not execution authentication. See [kernel contract](docs/KERNEL.md).

## Research profile

**Question:** what graph structure and numerical evidence must be present before a composed operation is eligible? Use authored known/unknown plants and available/unavailable companion cases as bounded specimens.

Evaluate retained uncertainty, refusal reasons, dependency closure and actual downstream outcomes—not only subgraph size. Retrieval must not drop external coupling or convert an annotation into physical truth. Proposed automation and information-efficient context need held-out comparisons and total cost measurements.

[Research protocol](https://github.com/giasonpooni/Notations-Systems-Terminal/blob/b41b84922d4963a9206202029afd1e78b9451f9c/RESEARCH_PROGRAMME.md). Python/Julia/Rust/C++ and CUDA providers remain separately qualified implementations, not automatic capabilities of this graph layer.

## Documentation and compatibility

[Kernel](docs/KERNEL.md) · [Scope](docs/SCOPE.md) · [Map](docs/MAP.md) · [Stack role](docs/STACK_ROLE.md) · [Contributing](CONTRIBUTING.md)

Existing `schematics`, `sra`, NET / `net` / `ciw`, flags, source pins, schema and evidence/specification/execution/verification identities remain. `system.graph` is not newly registered by this text. No source, tests, dependencies, licence, permissions, deployment or release changes; no new runtime qualification is claimed.

## License

[MIT](LICENSE). Existing source and third-party notices remain in force. Public-interest and private-IP positioning does not transfer rights or establish nonprofit status.
