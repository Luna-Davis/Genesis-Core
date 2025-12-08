# Genesis Core

## Overview

Genesis Core is a repository that acts as a reference for the (Genesis tool)[https://git.sr.ht/~mrlunatic/genesis].
It holds the data required by Genesis in order to create scalable, maintainable codebases for projects.

## File structure

```bash
├── manifests
│   ├── C
│   │   └── CMakeList.txt
│   └── python
│       └── pyproject.toml
├── presets
│   ├── ci
│   │   └── github-actions.yml
│   ├── docs
│   │   ├── mkdocs.yml
│   │   └── readme-template.md
│   ├── format
│   │   ├── black.toml
│   │   └── clang-format
│   ├── lint
│   │   ├── default-c-lint.cfg
│   │   ├── default-eslint.json
│   │   └── default-flake8.ini
│   ├── security
│   │   ├── bandit.yaml
│   │   └── cwe-checks.json
│   └── testing
│       ├── ctests-config.txt
│       ├── pytest.ini
│       └── unittest.cfg
└── templates
    ├── C
    │   ├── LICENSE
    │   ├── README.md
    │   ├── bin
    │   ├── include
    │   ├── lib
    │   ├── src
    │   │   └── main.c
    │   └── tests
    └── python
        ├── Dockerfile
        ├── LICENSE
        ├── README.md
        ├── docs
        ├── main.py
        ├── requirements-dev.txt
        ├── requirements.txt
        ├── src
        └── tests
```

## Features

The project currently supports C and Python projects but will soon grow

## Conributions

This is an opensource project. Feel free to submit a pull request, create a feature branch, create a feature then merge and push.

---

### Author

Sammy Davis
