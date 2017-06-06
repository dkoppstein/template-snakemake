# Snakemake Template

Template for the [Snakemake](https://snakemake.readthedocs.io/) workflow management system.

## Usage

```shell
# install Snakemake
conda install -c bioconda snakemake

# clone template
git clone https://github.com/sfischer13/template-snakemake.git
cd template-snakemake

# initialize project
vim config.yaml
conda create -n snakemake-project --file environment.yaml
source activate snakemake-project

# run project
snakemake -np
snakemake --use-conda
```

## License
Copyright (c) 2017 Stefan Fischer  
The source code is available under the **MIT License**.  
See [LICENSE](https://github.com/sfischer13/template-snakemake/blob/master/LICENSE) for further details.
