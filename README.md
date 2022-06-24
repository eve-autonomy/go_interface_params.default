# go interface parameters

## Overview
This is a package for managing parameters to use [go_interface](https://github.com/eve-autonomy/go_interface) more easily.

This package has 4 types of parameter set in each directory depending on purposes.
- `product` directory
  - This is for on-demand delivery app in the **production** environment.
- `server_test` directory
  - This is for on-demand delivery app in the **staging** environment.
- `local_test` directory
  - This is a set of test parameter for on-demand delivery application that runs locally.
  - This is used as a criterion for test before `go_interface` is released as OSS.
- `not_use` directory
  - When on-demand delivery is not required, this is set.

The list of parameter names managed in these directories is the same, only the values are different.

## Parameter details
See the [parameter description for go_interface](https://github.com/eve-autonomy/go_interface#parameter-description).

## Extensibility of this package
This package is a template as a parameter configuration.

If you want to rewrite the values in this package and use it, fork this repository to create a new one.
