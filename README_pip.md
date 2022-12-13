# Important: Pip install is different for CPU versus GPU

If you're on a GPU machine:

```bash
pip install deepconsensus[gpu]==1.0.1
# To make sure the `deepconsensus` CLI works, set the PATH:
export PATH="/home/${USER}/.local/bin:${PATH}"
```

If you're on a CPU machine:

```bash
pip install deepconsensus[cpu]==1.0.1
# To make sure the `deepconsensus` CLI works, set the PATH:
export PATH="/home/${USER}/.local/bin:${PATH}"
```

## Documentation, quick start, citation

All other documentation is on GitHub: [https://github.com/google/deepconsensus](https://github.com/google/deepconsensus).
