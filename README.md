# MEPs — Mip Enhancement Proposals

Design documents for substantial changes to [mip](https://github.com/mip-org/mip),
the package manager for MATLAB.

A MEP describes a proposed change, its motivation, and its design in enough
detail that it can be discussed, refined, and — once accepted — implemented.
The process is deliberately lightweight; most changes to mip don't need a MEP.
See [MEP 1](meps/mep-0001.md) for when one is needed and how the process works.

## Index

| MEP | Title | Status |
|----:|-------|--------|
| [1](meps/mep-0001.md) | MEP purpose and process | Active |
| [2](meps/mep-0002.md) | Project environments (`mip env`) | Draft |
| [3](meps/mep-0003.md) | Run code in a project environment (`mip run`) | Draft |

## Proposing a MEP

1. Float the idea first in a [mip issue](https://github.com/mip-org/mip/issues)
   or a [meps issue](https://github.com/mip-org/meps/issues) to get early
   feedback before writing anything.
2. Copy [`mep-template.md`](mep-template.md) to `meps/mep-XXXX.md`, using the
   next unused number.
3. Fill it in and open a pull request against this repository. Once the draft
   is complete enough to discuss, it is merged with status **Draft**.
4. Discussion continues on the linked issue; revisions land as follow-up pull
   requests. When a decision is reached, the status changes to **Accepted** or
   **Rejected**, and eventually to **Implemented** once the change lands in mip.

See [MEP 1](meps/mep-0001.md) for the full process and the list of statuses.
