# aws-cloudformation-website

An Amazon Web Services (AWS) CloudFormation document to facilitate the easy deployment of static websites to the cloud.

## Environment

- The [AWS Command-Line Interface](https://aws.amazon.com/cli/) (AWS CLI) `v1.11.44`

## Deployment

```bash
aws cloudformation deploy \
  --template cloudformation.template.json \
  --stack-name <example-stack> \
  --parameter-overrides SiteNameParameter=<example.com>
```

## One-Click Deployment

Deploy the latest version of this template (from the master branch) to your AWS Account 
with the click of a button!

[![Launch Stack button][2]][1]
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fechelon-solutions%2Faws-cloudformation-website.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fechelon-solutions%2Faws-cloudformation-website?ref=badge_shield)

  [1]: https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=static-website-stack&templateURL=https://s3.amazonaws.com/aws-cloudformation-website/cloudformation.template.json
  [2]: https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png (Launch Stack)


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fechelon-solutions%2Faws-cloudformation-website.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fechelon-solutions%2Faws-cloudformation-website?ref=badge_large)