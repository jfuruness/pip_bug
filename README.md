# Versions
* pip 20.0.2
* python 3.8
* ubuntu 20.04.3 LTS

# To reproduce:

This command succeeds:

```bash
pip3 install -e .
```

This command fails:

```bash
pip3 install -e .[test]
```

Both have the same dependencies. Am I doing something wrong, or is this a bug?
