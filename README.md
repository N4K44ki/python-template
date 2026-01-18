python-template
===============

Basic usage
-----------
0) Initialize git
   ```
   rm -rf .git
   git init
   ```


1) Create and sync the environment
   ```
   uv sync
   ```

2) edit code for your use

3) code check
   ```
   uv run poe check
   uv run poe check-fix
   ```

4) first commit
   ```
   git add .
   git commit -m "initial commit"
   git push -u origin main
   ```
Notes
-----

- Use uv run to ensure the virtual environment is active.
- Update project name and description in pyproject.toml.
