# Mastering Taproot — Interactive Bitcoin Script Programming

Interactive Jupyter companion for [Mastering Taproot](https://github.com/aaron-recompile/mastering-taproot), a complete developer guide to Bitcoin Taproot.

## What This Is

This is the **interactive companion** to the book. The main repo provides the manuscript and reference code; this repo provides runnable Jupyter notebooks:

- **Run**: Execute real Bitcoin Script examples step by step
- **Modify**: Adjust keys, scripts, tree structures, and see results instantly
- **Experiment**: Try "what if" scenarios
- **Visualize**: Explore Taproot data structures interactively

## Dependencies

```bash
# 1. Activate your environment
conda activate bitcoin_course   # or your project conda env

# 2. Install btcaaron (local dev version, recommended)
pip install -e /path/to/btcaaron

# 3. Install remaining dependencies
pip install -r requirements.txt
```

- **Chapters 1–4**: `bitcoin-utils` (Legacy / P2SH / SegWit)
- **Chapters 5–8**: `btcaaron` (Taproot semantic API)

More btcaaron examples in the `examples/` directory.

## Online Site

📖 [bitcoincoding.dev](https://bitcoincoding.dev)

## The Book

📚 [github.com/aaron-recompile/mastering-taproot](https://github.com/aaron-recompile/mastering-taproot)

## License

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
