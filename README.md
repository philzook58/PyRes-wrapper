# PyRes-wrapper

PyRes is a simple python resolution theorem prover for first order logic. This is a wrapper to pip install it as a python package. See <https://github.com/eprover/PyRes>

Installation

```bash
git submodule init
git submodule update
python3 -m pip install -e .
```

Execution

```bash
python3 -m PyRes.pyres-fof -tifbp -HPickGiven5 -nlargest PyRes/EXAMPLES/PUZ001+1.p
```
