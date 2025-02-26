# Agents Course HF

Code and Notes for the HuggingFace Agents course

## Notebooks
Set up:
```bash
$ uv run ipython kernel install --user --env VIRTUAL_ENV $(pwd)/.venv --name=agents-course-hf
```

Start the server:
```bash
$ uv run --with jupyter jupyter lab
```


## Submodules
Set up:
```bash
$ git submodule add https://huggingface.co/spaces/cmontanari/hf-agents-course-unit-1
```

Update ref:
```bash
$ git submodule update --remote --recursive
```

## Traceability with phoenix-arize

Run:
```bash
$ python -m phoenix.server.main serve
```
