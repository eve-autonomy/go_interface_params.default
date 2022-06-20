# go_interface_params

## Overview
This is a package for managing parameters to make [go_interface](https://github.com/eve-autonomy/go_interface) easier to use.

This package has 4 types of parallel directories for parameter management:
- `product`
  - This directory manages the parameters as connection settings to the on-demand delivery app in the production environment.
- `server_test`
  - This directory manages the parameters as connection settings to the on-demand delivery app in the staging environment.
- `local_test`
  - This directory manages the parameters as connection settings to the dummy of the on-demand delivery application that runs locally.
  - It is mainly used as a criterion for testing as OSS.
- `not_use`
  - This directory manages the parameters when not using the on-demand delivery application.

The list of parameter names managed in these directories is the same, only the values are different.

## Parameter details
See the [parameter description for go_interface](https://github.com/eve-autonomy/go_interface#parameter-description).

## Extensibility of this package
This package is a template as a parameter configuration.

If you want to rewrite the values in this package and use it, fork this repository to create a new one.
