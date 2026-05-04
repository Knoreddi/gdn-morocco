# Project Rules

These rules define the baseline collaboration and quality expectations for this project.

## 1) Change Management

- Every change must be committed with a clear, descriptive message.
- Group related file updates into a single coherent commit.
- Keep commits focused and easy to review.

## 2) Documentation

- Any new behavior should be documented in `README.md` or `docs/`.
- Update examples when configuration shapes change.
- Record key decisions and tradeoffs in `LESSONS_LEARNED.md`.

## 3) Configuration

- Never commit secrets.
- Keep `config/config.example.json` up to date with required keys.
- Prefer explicit defaults over implicit behavior.

## 4) Flow Definitions

- Represent orchestrations using JSON under `flows/`.
- Keep flow steps named and deterministic.
- Include lightweight validation metadata when possible.

## 5) Testing and Verification

- Add tests under `tests/` for behavior changes.
- Run local checks before committing.
- Document known limitations and assumptions.
