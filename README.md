1. Install/Upgrade setuptools pip install -U setuptools
2. Create the pyproject.toml file in the root folder — https://gist.github.com/kavya006/e5ebfb80584c3d0a99becc16c0059fde
3. Install/Upgrade the python package build: pip install -U build
4. Use build to package the project python -m build. Re-run this command everytime the configuration file (pyproject.toml) changes.
5. Install in editable mode for ease in development: pip install -e .