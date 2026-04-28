# sim-plugin-calculix

Calculix driver for [sim-cli](https://github.com/svd-ai-lab/sim-cli),
distributed as an out-of-tree plugin.

CalculiX driver for sim.

## Install

```bash
sim plugin install calculix
```

Other paths:

```bash
pip install git+https://github.com/svd-ai-lab/sim-plugin-calculix@v0.1.0
pip install https://github.com/svd-ai-lab/sim-plugin-calculix/releases/download/v0.1.0/sim_plugin_calculix-0.1.0-py3-none-any.whl
pip install -e .
```

After install:

```bash
sim plugin doctor calculix
sim plugin sync-skills
```

## Development

```bash
git clone https://github.com/svd-ai-lab/sim-plugin-calculix
cd sim-plugin-calculix
uv sync
uv run pytest
```

## License

Apache-2.0.
