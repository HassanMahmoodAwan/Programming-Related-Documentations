# UV Package Manager Documents.

Its a python package manager similar to npm in node js. 10-100x faster then pip as build in RUST. Manages VENV by its own. For stand-alone script, it create venv own its place/dir. 

***

### INSTALLATION

```py

    pip install uv
```

### For Help

```py

    uv
```

***

## FOR PROJECTS

``` py

    uv init project-name
    uv add pandas request
    uv run main.py
```

***For Building Projects:***

```py
    uv build
```

***

## FOR SCRIPTS

``` py

    # 1st way.
    uv run --with 'flask' --with 'pandas' script.py

    # 2nd way.
    uv add --script main.py 'flask' 'pandas' 'request'
    uv run main.py
```
