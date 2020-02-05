# GSoC mini-hist

## Installation

The recommended way of setting up a development environment:

```bash
python3 -m venv .env            # Make a new environment in ./.env/
source .env/bin/activate        # Use the new environment
pip install -r requirements.txt # Install the package requirements
flit install --symlink          # Install the package in editable mode
```

> If you want to use conda, go ahead. Also feel free to use a different
directory name, etc. We will be requiring Python 3 here, at least 3.6 or
better. And I'm using flit instead of setuptools since it is much simpler for
simple examples like this one.

You'll need to run `source .env/bin/activate` if you open a new shell. You can
use `deactivate` to turn off the environment in your current shell (or just
open a new one).

The final line installs the package into your environment so that you can run
the code from anywhere as long as the environment is activated.

If, while working on the project, you need any other python packages, such as
for plotting, *add them to the requirements.txt*.

## Code

The library is in `/hist`. You will be editing it to expand the histogram features,
or plotting features, or both. Select one of the below tasks (or do both if you
really want to, but only one required for full consideration).

### Features to add

TODO

### Plots to add

TODO

## Notebooks

TODO

## Tests

This is mostly there to verify you understand basic testing procedures. Testing
is already set up, all you have to do is **add tests for the features you add**. I
am lightly recommending native pytest-style testing, but if you have a
preference for a different style, go for it as long as pytest can still run it.

If you focus on plotting, at least add one non-plotting feature + test, but the
plots themselves are notoriously hard to test, so don't worry too much about
that unless you have a good idea for a way to test a plot.

