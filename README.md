
- 2023/03/11
- https://catalog.workshops.aws/cfn101/en-US/prerequisites/lab-resources
- 使用 `eu-west-2`, 使用 `2023q1`
- [取得 Resources 的 return value](https://catalog.workshops.aws/cfn101/en-US/basics/templates/resource-return-values#overview)
    - Ref
    - Fn::GetAtt
- 如果要測試 CloudFormation, 可參考 `taskcat` 及 `cfn-lint`, 或是參考這篇 [debug and test CloudFormation](https://catalog.workshops.aws/cfn101/en-US/basics/templates/linting-and-testing)

---

<h1 align="center">
AWS CloudFormation - Workshop
<br>
    <a href="https://cfn101.workshop.aws"><img alt="Website" src="https://img.shields.io/website?down_color=red&down_message=down&up_color=green&up_message=up&url=https%3A%2F%2Fcfn101.workshop.aws"></a>
    <a href="https://github.com/aws-samples/cfn101-workshop/actions"><img alt="GitHub Workflow Status" src="https://github.com/aws-samples/cfn101-workshop/workflows/Unit%20Tests/badge.svg"></a>
</h1>

This repository provides all the resources referenced in the [CloudFormation](https://cfn101.workshop.aws/) workshop as
well as the code used to build it.

## Usage
1. Clone the repository to your working directory or Download the ZIP file from GitHub.
2. Open the downloaded files in your code editor or IDE of your choice.

The working directory is located in [code/workspace](code/workspace) where you can follow along and write your code to.

In the [code/solutions](code/solutions), you can find the completed solution for each lab. This can be used as a
reference, in case you get stuck or things don't work as intended.

## Local development
To set-up a local development environment for changing the workshop, please follow the instructions in
[local development](docs/LOCAL_DEVELOPMENT.md) file.

## Contributing
Contributions are more than welcome. Please read the [code of conduct](CODE_OF_CONDUCT.md) and the
[contributing guidelines](CONTRIBUTING.md).

## License
This library is licensed under the MIT-0 License. See the [license](LICENSE) file.
