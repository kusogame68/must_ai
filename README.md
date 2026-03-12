```cmd
winget install --id Git.Git -e --source winget
cd must_ai
uv sync
uv run jupyter lab