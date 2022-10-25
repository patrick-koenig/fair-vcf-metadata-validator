# fairvcf

This package checks the metadata of VCF files with respect to the following paper: https://f1000research.com/articles/11-231


### Installing the package:

```
pip install --index-url https://test.pypi.org/simple/ --extra-index-url https://pypi.org/simple/ fairvcf
```

### How to use the validator:

The package installs a CLI tool that can be used to check the VCF metdata with the following command:
```
$ fairvcf validate-metadata PATH_TO_VCF_FILE
```