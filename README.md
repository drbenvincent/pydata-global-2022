# pydata-global-2022
Notebooks supporting my PyData Global 2022 talk, [What-if? Causal reasoning meets Bayesian Inference](https://global2022.pydata.org/cfp/talk/FQBSP8/).

Link to the talk on YouTube will be added when it's available.

## Environment setup

```bash
conda env create -f environment.yml
conda activate whatif
python -m ipykernel install --user --name whatif
```

**NOTE:** I ran `pip install git+https://github.com/pymc-labs/CausalPy.git` to get the development version. The current release if 0.0.4, so I'm using a later (development) version than this.