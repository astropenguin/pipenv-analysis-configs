# pipenv-analysis-configs
:penguin: Create IPython, Jupyter, matplotlib custom configs in a Pipenv's environment

## Features

- Create custom configs in a Pipenv's environment
- Supported Python packages
    - IPython (default profile)
    - Jupyter (default kernel using IPython's profile)
    - matplotlib (matplotlibrc and style directory)

## Usage

### Basic usage

```shell
$ mkdir proj && cd proj
$ pipenv --python 3.7
$ pipenv install ipython
```

```shell
$ git clone https://github.com/astropenguin/pipenv-analysis-configs etc
$ etc/configure
```

### Using hooks

```shell
$ cd proj
$ mkdir hooks
$ echo 'hook-pre' > hooks/hook-pre
$ echo 'hook-post' > hooks/hook-post
$ etc/configure
```

## Real-world examples

+ [astropenguin/pipenv-analysis-startup](https://github.com/astropenguin/pipenv-analysis-startup)
