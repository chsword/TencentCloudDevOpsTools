# Release Tools

## Current Feature List

1. [x] Deploy files to Cos
2. [ ] Refresh cdn
3. [ ] Deploy scf (Tencent cloud function)

## Features

### 1. Deploy to Cos


[Add tasks] => search "Deploy to Tencent Cloud Cos" => [Add]

![Setting](./screenshots/deploy-to-cos.png)

![Run result](./screenshots/deploy-to-cos-run.png)

## Other practices

1. Add Variable Group
   1. Pipelines => Library => [+ Variable Group]
   2. Variables=>[+Add]  your SecretId & SecretKey with secret
2. Pipelines Link Variable Group
   1. Pipelines => Releases => [your release] => Variables => [Variable Group] => [Link variable group]
3. Tasks => [Add a agent job]