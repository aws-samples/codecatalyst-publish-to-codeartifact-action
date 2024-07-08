## Publish To AWS CodeArtifact Workflow File

You can see the workflow.yaml file to see the complete code for using this action.

### How the "Publish to AWS CodeArtifact" action works:

The "Publish to AWS CodeArtifact" action works as follows at runtime:

- Checks if the PackageFormat, PackagePath, RepositoryName, DomainName and AWSRegion is specified, validates the configuration, and configures AWS credentials based on the Environment, Connection, and Role specified.
- Looks for package files to publish in the path configured in the PackagePath field in the WorkflowSource folder. If no source is configured in Sources, but an artifact is configured in Arifacts, then the action looks for the files in the configured artifact folder.
- Publishes the package to AWS CodeArtifact.


## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

