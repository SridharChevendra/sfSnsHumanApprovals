# AWS Stepfunctions SNS Human Approvals

Step by step instructions to setup AWS stepfunctions SNS API for Human Approvals.

![Sample Workflow](Images/stepfunctions_graph_flow.png)

### Description
AWS Step Functions supports over 200 AWS service integrations. As of today, it includes direct integration with over 220 AWS services and more than 10,000 APIs. This demonstrates accessing Amazon SNS API instead of using other compute layers such as Lambda.

## Getting Started
### Pre-requisites
* AWS Account with appropriate permissions
* Services in scope
  - AWS Step functions
  - Amazon SNS
  - Amazon API Gateway
  - AWS Lambda
  
  

#### Environment setup
#### 1. Clone GitRepo to local machine
Create a folder named "stepfunctionsSns"

```
mkdir stepfunctionsSns && cd stepfunctionsSns

```
Clone the GitRepo to your local machine.
```
git clone https://github.com/SridharChevendra/GenAI-DriverAssistant.git
cd GenAI-DriverAssistant
```

#### 2. AWS stack deployment
