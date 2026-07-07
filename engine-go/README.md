# engine-go

The cumulative, **tested** numerical engine. Grows roughly one package per sprint. This is the portfolio centerpiece — and the part that trains paycheck skills: clean, benchmarked, invariant-tested Go.

> Before your first push: rename the module path in `go.mod` from `github.com/meeru/...` to your real GitHub handle.

## Testing philosophy — assertions are physics
Every integrator/solver is tested against a conserved quantity:
- ODE integrators → energy / momentum conservation
- quantum statevector → norm stays 1

A drifting invariant means a bug. Your QA instinct, pointed at physics — that's the edge.

## Packages
- `integrate/` — numerical ODE integrators: Euler, RK4, … (starts Sprint 1)
