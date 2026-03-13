# Extraction Spec

Framework: `unlikely_intersections`

Required constants:

- `kappa_atypical`
- `sigma_counting`
- `kappa_compact`
- `rho_rigidity`
- `intersection_lock`
- `eps_coh`
- stitch key `sigma_star_can`

All constants are extracted from explicit formulas in `artifacts/constants_extraction_inputs.json`, promoted into the registry and stitch files, then consumed by the closure guard.
