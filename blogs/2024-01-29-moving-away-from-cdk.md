---
title: "Moving away from CDK"
url: "https://sst.dev/blog/moving-away-from-cdk"
date: "2024-01-29"
feed_url: "https://sst.dev/blog"
---
SST is building Ion, a new deployment engine that moves away from AWS CDK and CloudFormation, instead leveraging Terraform providers and Pulumi's deployment engine. The team cites CDK/CloudFormation design flaws like cyclical dependencies, slow deployments, and resource linking challenges, which Ion addresses by executing code locally with direct AWS SDK calls.
