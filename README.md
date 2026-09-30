# triad

Python environment for brian2 simulations, managed with [uv](https://docs.astral.sh/uv/).

```bash
uv sync
uv run jupyter lab
```

`numpy<2.4` is pinned because brian2 2.9.0 needs `ndarray.ptp`, which NumPy 2.4 removed.
