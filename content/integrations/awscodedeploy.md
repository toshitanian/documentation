---
title: Datadog-AWS CodeDeploy Integration
integration_title: AWS CodeDeploy
kind: integration
git_integration_title: amazon_codedeploy
newhlevel: true
---

{{< img src="integrations/awscodedeploy/monitor-aws-codedeploy-dashboard.png" alt="CodeDeploy default dashboard" >}}

## Overview

AWS CodeDeploy is a service that automates code deployment to instances in the cloud and on-premise.

Enable this integration to see AWS CodeDeploy deployment events and metrics in Datadog.

## Setup
### Installation

1. If you haven't already, set up the [Amazon Web Services integration first](/integrations/aws).
2. Install the integration [on the CodeDeploy tile](https://app.datadoghq.com/account/settings#integrations/amazon_codedeploy).
3. Add the `"codedeploy:List*"` and `"codedeploy:BatchGet*"` actions to your Datadog policy in AWS.

## Data Collected
### Metrics

{{< get-metrics-from-git >}}

### Events

The following events are generated by the integration:

* Successful deployments
* Failed deployments
* Stopped deployments
