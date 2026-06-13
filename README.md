# marineloads

A validated Python package for Airy wave theory and marine wave loads.

Built as a clean, tested library seeded from TMR4247 (NTNU) course material,
with BEM and experimental data as the validation backbone.

## Planned scope

- **v0.1** — Airy wave theory (`waves.py`): dispersion, kinematics, pressure
- **v0.2** — Wave loads (`loads.py`): Morison equation, MacCamy–Fuchs diffraction
- **v0.3** — Seakeeping: added mass and damping (A33/B33) extraction

## Installation

```bash
pip install -e ".[dev]"
```

## Running tests

```bash
pytest
```

## License

MIT
