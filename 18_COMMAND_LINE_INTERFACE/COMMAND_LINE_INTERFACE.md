# Command Line Interface — PYTHON_SKYFIELD

**Upstream:** https://github.com/skyfielders/python-skyfield

## Anticloud CLI

```bash
# Install
pip install anticloud-python-skyfield

# Run offline with PAX inference
anticloud-python-skyfield --offline --pax-local

# Run with AIOSS logging
anticloud-python-skyfield --aioss-log ./ledger.jsonl

# Single binary (after build)
./python_skyfield --config config.yaml
```

## Options

| Flag | Description |
| --- | --- |
| `--offline` | Disable all network calls |
| `--pax-local` | Use local PAX inference at 127.0.0.1:11434 |
| `--aioss-log PATH` | Write AIOSS audit chain to PATH |
| `--encrypt` | Enable AES-256 at rest for output files |
| `--gpu` | Force GPU inference |
| `--cpu` | Force CPU inference |
| `--config PATH` | Load configuration from YAML file |
