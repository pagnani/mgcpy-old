# Building docs

We currently use Sphinx

If you only want to get the documentation, note that pre-build versions can be found at

    https://mgc.neurodata.io

## Instructions

### Python Dependencies

You will need to install all the dependencies as defined in `requirements.txt` file. The above can be installed by entering:

    pip3 install -r requirements.txt

in the `docs/` directory.

### Pandoc dependency

In addition, you need to install `pandoc` for `nbsphinx`. If you are on linux, you can enter:

    sudo apt-get install pandoc

If you are on macOS and have `homebrew` installed, you can enter:

    brew install pandoc

Otherwise, you can visit [pandoc installing page](https://pandoc.org/installing.html) for more information.

## Generating the documentation

To build the HTML documentation, enter:

    make html

in the `docs/` directory. If all goes well, this will generate a `build/html/` subdirectory containing the built documentation.
