# Blackjack Counting Course

Materials for teaching blackjack basic strategy and card counting.

## Structure

- **`trainer/`** — interactive basic-strategy trainer (`blackjack_trainer.html`).
  Open the file directly in a browser; no installation needed.

- **`simulations/`** — Python simulations used to generate the numbers discussed
  in class.
  - `blackjack_sim.py` — house-edge / EV simulator (basic strategy, Hi-Lo, Omega II).
  - `bankroll_bot_sim.py` — bankroll and risk-of-ruin simulator, built on the same
    rules/strategy engine.

  Both scripts are self-contained (neither imports the other) and both support
  `--help` for the full list of options. See the `Usage`/`Inputs` section at the
  top of each file for examples.

- **`slides/`** — lecture slides.

## Quick start

```bash
cd simulations
python blackjack_sim.py --strategy hilo
python bankroll_bot_sim.py --strategy hilo
```
