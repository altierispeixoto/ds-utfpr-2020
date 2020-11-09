# create conda environment from yml file
conda env create -f environment.yml

# list all the conda environment available
conda info --envs  

# Create new environment named as `envname`
conda create --name envname

# Remove environment and its dependencies
conda remove --name envname --all

# Clone an existing environment
conda create --name clone_envname --clone envname