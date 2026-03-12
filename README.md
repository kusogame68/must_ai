```cmd
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
winget install --id Git.Git -e --source winget
cd must_ai
uv sync
uv run jupyter lab