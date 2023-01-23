
# Deployer.php launcher

Launches deployer from the dependencies of the current folder. This allows for each project to have it's own version of deployer, and you can run different versions of deployer for different projects.


## Installation

Install dep-launcher with composer globally

```bash
composer global require  dreamproduction/dep-launcher
```

Make sure that your global composer bin folder is part of your `$PATH` variable. Usually you can accomplish this by adding the following line to `.bashrc` or `.zshrc`:

```bash
PATH=$(composer global config bin-dir --absolute --quiet):$PATH
```

Also make sure to not have deployer installed globally by other methods.
## Usage/Examples
Just run `dep` as usually

```bash
dep deploy dev
```
