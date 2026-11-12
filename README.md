# coolest-art-01 entry

"Paper, Taking Flight" — a giant origami crane transforms mid-flight into a
living white crane against a burning sunset, paper fragments turning to
feathers and embers over dark mountain silhouettes.

- `main.py` — Python 3.13, stdlib only; copies `art.png` to
  `$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output/entry.png`) and verifies
  the copy is byte-identical, so both runs write the same bytes.
- `art.png` — the art, 1024x1024, under 1 MiB.
- `LICENSE` — MIT.

Run locally: `MAKEFUN_OUTPUT_DIR=out python3 main.py`
