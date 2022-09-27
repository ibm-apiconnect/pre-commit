# Pre-commit hook to validate product yaml

Sample pre-commit hook that can be used to validate API Connect product yaml before commiting using the [pre-commit framework](https://pre-commit.com/)

## Example configuration:

    repos:
    -   repo: https://github.com/ibm-apiconnect/pre-commit
        rev: '91c236c'
        hooks:
        -   id: validate-product
