# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Lecture code repository for **SC6106 Smart Contract** course. The project uses a Python/Flask web app structure (`app.py`, `templates/`, `static/`) to demonstrate smart contract concepts.

## Environment & Package Management

This project uses **uv** for Python environment and dependency management.

```bash
# Create/sync virtual environment
uv sync

# Add a dependency
uv add <package>

# Run the app
uv run python app.py

# Run a script
uv run python <script.py>
```

## Smart Contract Context

This is an educational repository for a smart contract course. Code may interact with Ethereum/Solidity tooling (e.g., web3.py, brownie, hardhat). When writing or modifying code, consider blockchain-specific concerns such as gas costs, immutability, and transaction semantics.
