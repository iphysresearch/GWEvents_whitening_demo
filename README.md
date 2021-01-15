# GWEvents_whitening_demo

## Contents

A simple Python jupyter notebook [Home.ipynb](./Home.ipynb) that show you how to download GWOSC data with GWpy or load local `hdf5/*.hdf5` file from GWOSC with `readligo.py`。 Whitening codes by scratch are also included.

## Requirements

- GWpy

  - [Documentation](https://gwpy.github.io/docs/latest/)
  - [GitHub](https://github.com/gwpy/gwpy)
  - Installation
    
    The recommended way of installing GWpy is with Conda:
    
    ```python
    $ conda install -c conda-forge gwpy
    ```

    or with Pip:

    ```python
    $ python -m pip install gwpy
    # or
    $ pip install --upgrade gwpy
    ```

    Supported python versions: 3.6+.
    
    You can test your installation, and its version by

    ```python
    $ python -c "import gwpy; print(gwpy.__version__)"
    ```



## License

MIT