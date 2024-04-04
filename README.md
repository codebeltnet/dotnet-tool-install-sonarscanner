# Install .NET Tool - Sonar Scanner

Install the latest version of [Sonar Scanner](https://www.nuget.org/packages/dotnet-sonarscanner) using `dotnet tool`.

> This action is part of the Codebelt ecosystem and ensures a consistent way of: 
> 
> - Defining your CI/CD pipeline 
> - Structuring your repository
> - Keeping your codebase small and feasible
> - Writing clean and maintainable code
> - Deploying your code to different environments
> - Automating as much as possible
>
> A paved path to excel as a DevSecOps Engineer.

## Usage

To use this action in your GitHub repository, you can follow these steps:

```yaml
uses: codebeltnet/dotnet-tool-install-sonarscanner@main
```

### Inputs

This action has no inputs.

### Outputs

This action has no outputs.

## Examples

### Install MinVer using `dotnet tool`

```yaml
steps:
  - name: Install Sonar Scanner
    uses: codebeltnet/dotnet-tool-install-sonarscanner@main
```

## Contributing to Install .NET Tool - Sonar Scanner

Contributions are welcome! 
Feel free to submit issues, feature requests, or pull requests to help improve this action.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
