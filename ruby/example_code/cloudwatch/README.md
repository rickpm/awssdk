# CloudWatch code examples for the SDK for Ruby

## Overview

Shows how to use the AWS SDK for Ruby to work with Amazon CloudWatch.

*CloudWatch provides a reliable, scalable, and flexible monitoring solution that you can start using within minutes.*

## ⚠ Important

* Running this code might result in charges to your AWS account.
* Running the tests might result in charges to your AWS account.
* We recommend that you grant your code least privilege. At most, grant only the minimum permissions required to perform the task. For more information, see [Grant least privilege](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#grant-least-privilege).
* This code is not tested in every AWS Region. For more information, see [AWS Regional Services](https://aws.amazon.com/about-aws/global-infrastructure/regional-product-services).

### Single actions
Code excerpts that show you how to call individual service functions.

* [Create an alarm](./cw-ruby-example-create-alarm.rb) (`CreateAlarm`)

* [Show alarms](./cw-ruby-example-show-alarms.rb) (`DescribeAlarms`)

* [Disable alarm actions](./cw-ruby-example-alarm-actions.rb) (`DisableAlarmActions`)



### Scenarios
Code examples that show you how to accomplish a specific task by calling multiple functions within the same service.

* [Manage alarms](./cw-ruby-example-alarm-basics.rb)

* [Disable alarm actions](./cw-ruby-example-alarm-actions.rb)

* [Add metrics](./cw-ruby-example-metrics-basics.rb)
## Run the examples

### Prerequisites


For prerequisites, see the [README](../../README.md#Prerequisites) in the `ruby` folder.


### Instructions
<!--custom.instructions.start-->
The easiest way to interact with this example code is by invoking a [Scenario](#Scenarios) from your command line. For example, `ruby some_scenario.rb` will invoke `some_scenario.rb`.
<!--custom.instructions.end-->


### Tests
<!--custom.tests.start-->
The example code in this directory is not currently tested.

## Contribute
Code examples thrive on community contribution!

To learn more about the contributing process, see [CONTRIBUTING.md](../../../CONTRIBUTING.md)
<!--custom.tests.end-->


## Additional resources

* [CloudWatch User Guide](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html)
* [CloudWatch API Reference](https://docs.aws.amazon.com/AmazonCloudWatch/latest/APIReference/Welcome.html)
* [SDK for Ruby CloudWatch reference](https://docs.aws.amazon.com/sdk-for-ruby/v3/api/Aws/Cloudwatch.html)


---

Copyright Amazon.com, Inc. or its affiliates. All Rights Reserved.

SPDX-License-Identifier: Apache-2.0