# Adding a Local Package to Another Project with PDM

Based on your repository, you have a package called `pop-common` that you want to use in other projects. PDM provides a convenient way to add local packages as dependencies to your projects.

## How to Add Your Local Package

To add your `pop-common` package to another project, you can use the `-e` flag (which stands for "editable" mode) with the `pdm add` command:

```bash
pdm add -e "file:///path/to/pop-common" --dev
```

Replace `/path/to/pop-common` with the actual path to your `pop-common` directory. For example:

```bash
pdm add -e "file:///C:/Users/username/projects/pop-common" --dev
```

On Windows, you might need to use the following format:

```bash
pdm add -e "file:///C:/Users/username/projects/pop-common" --dev
```

## Notes About This Approach

1. The `--dev` flag is optional. Use it if you want this to be a development dependency rather than a runtime dependency.

2. The `-e` (editable) flag means that changes to your local `pop-common` package will be immediately reflected in the projects that use it, without needing to reinstall.

3. This will add an entry in the `pyproject.toml` file of your project that looks something like:
   ```toml
   [project]
   dependencies = [
       # other dependencies...
       "pop-common @ file:///C:/Users/username/projects/pop-common"
   ]
   ```

4. If you don't want to use editable mode, you can omit the `-e` flag:
   ```bash
   pdm add "file:///path/to/pop-common" --dev
   ```

5. You might want to ensure your `pop-common` package is properly set up as a package with an appropriate `__init__.py` file (which you already have) and the required metadata in `pyproject.toml` (which you also have).

## Importing the Package

After adding the package to your project, you can import it in your code:

```python
from pop_common import data_utils, file_utils, utils
```

This setup allows you to maintain your common utilities in one place while using them across multiple projects.
