# ESS130 - Public-facing Notebooks

## Install conda environment
```bash
conda env create -f environment.yml
conda activate ESS130-public
python -m ipykernel install --user --name ESS130-public --display-name "Python (ESS130-public)"
```

## Install Julia package

Install Julia v1.10.9
```bash
julia
```

Activate the environment
```julia
]
activate .
instantiate
build
```

Press backspace to get back to the Julia REPL prompt and run
```julia
using IJulia
jupyterlab("./dir")
```
