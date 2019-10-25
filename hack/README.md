# Hack directory

This package contains various scripts that are used by Helm Broker developers.

## Purpose

This directory contains tools, such as Go fmt, Go lint, and Go vet, that help to maintain the source code compliant to Go best coding practices. It also includes utility scripts that generate code, and scripts executed on CI pipelines.

### Directory structure

The directory has the following structure:

```
  ├── boilerplate                  # Header used in code generation
  ├── ci                           # Chart-test source
  ├── examples                     # Example Kubernetes objects                                
  ├── release                      # Release pipeline scripts
```