# Cleaning Data for Effective Data Science

Cleaning Data training course

# Installation

In the best case, you can get this repository running (on
Unix-like systems, such as Linux and macOS) with only:

```sh
$ git clone https://github.com/DavidMertz/CleaningDataVideo.git
$ cd CleaningDataVideo
$ curl -LsSf https://astral.sh/uv/install.sh | sh
$ uv run jupyter lab
```

In practice, there are some dependencies that you are likely to hit which `uv`
alone will not resolve.  I.e. a few link libraries and tools are likely not to
be present when libraries explicitly included in `pyproject.toml` want them.

Some likely candidates, and how to install them in Linux/macOS are shown.
System that use installers other than `apt` probably also spell library names
slightly differently.

```sh
$ brew install openblas        # macOS
$ apt install libopenblas-dev  # Debian-based
$ apt install gfortran  
$ apt install cmake
$ apt install libxsimd-dev     # Chips with SIMD
```
