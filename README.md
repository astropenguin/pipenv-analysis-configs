# pipenv-analysis-configs
:penguin: Create IPython, Jupyter, matplotlib custom configs in a Pipenv's environment

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
