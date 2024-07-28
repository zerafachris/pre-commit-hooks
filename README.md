A collection of [pre-commit](https://pre-commit.com) hooks for better Python programming.

## Usage
### Submodule cloning
To use the utilities in this repository, follow these steps:

1. Change directory to your repository root
2. Create a submodule in the target repository: ```git submodule add https://github.com/zerafachris/pre-commit-hooks pre-commit-hooks```
3. Create a new conda environment called pre-commit and install the pre-commit hooks called `pre-commit`

### Submodule re-initialization
If the submodule has already been initialised on your package, use `git submodule update --init --recursive` instead


# Running the pre-commits
Run the pre-commit hooks manually by running the following command:
1. Activate the pre-commit environment ```mamba activate pre-commit```
2. Run the pre-commit via ```pre-commit run --all-files --config pre-commit-hooks/.pre-commit-config.yaml```
 
# Supported Hooks
See a collection of all supported [pre-commit hooks](https://pre-commit.com/hooks.html).

# Additional Resources
For more information on pre-commit and how to leverage it for improving your Python development workflow, visit the pre-commit documentation Further reading on [pre-commit](https://pre-commit.com/).