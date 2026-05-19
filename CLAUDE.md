# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repo is

A scratch/scaffold repo with two independent dummy Python apps under `demo1/` and `demo2/`. Each is a self-contained hello-world script using only the Python standard library.

The two demos do not share code or dependencies — treat them as separate sandboxes that happen to live in the same repo.

## Running

```sh
python demo1/main.py
python demo2/main.py
```

## What's not here (by design, currently)

- No tests, test runner, or CI.
- No dependency manifest (`requirements.txt`, `pyproject.toml`). The apps are stdlib-only — if you add a dependency, also add a manifest rather than relying on the ambient environment.
- No linter or formatter config.

If a task expands either demo beyond hello-world, set up these pieces as needed rather than assuming they already exist.
