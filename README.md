# NeuroPlatform documentation

This repository contains the documentation for the FinalSpark NeuroPlatform.

## Contributing

Contributions from NeuroPlatform users are welcome. Please feel free to open issues, or add pull requests to request updates to the documentation.

This documentation uses **jupyter-book**. Contributing is as simple as adding some jupyter notebooks with markdown cells and some formatting.
See the official [jupyter-book documentation](https://jupyterbook.org/en/stable/file-types/notebooks.html) for more information.

Please use the provided `pre-commit` hook to ensure that the documentation is formatted correctly before committing changes.

Run the following command to install the pre-commit hook:

```bash
pre-commit install
```

before committing changes.

## Building the documentation

Install jupyter-book and run the following command to build the documentation:

```bash
pip install jupyter-book
jb build neuroplatform-docs
```

and access the built documentation in the `_build/html/index.html` file.
