# gha-py-venv

A GitHub Action to setup Python virtual environment and install project dependencies.
Working only on Linux based environment.

## Usage

```yaml
steps:
  - name: Setup Python virtual environment
    uses: albr21/gha-py-venv@1.0.0
    with:
      requirements: requirements.txt
      requirements-dev: requirements-dev.txt
```

## Contributing

Check out the [CONTRIBUTING](CONTRIBUTING.md) file for guidelines on how to contribute to this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
