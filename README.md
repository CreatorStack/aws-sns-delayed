# aws-sns-delayed

Schedule or delay message publication on an AWS SNS topic using a
simple Step Functions state machine

## Usage

```json
{
   "delay_timestamp": "xxxxxxxxxxx" #ISO-8601 extended offset date-time format
   "sns_topic": "topic arn"
   "message": "stringified message"
}
```

## Blog Post

For more information on how to use this sample stack, please read this
blog post:

> https://alestic.com/2019/05/aws-delayed-sns-step-functions/

![sns-delayed architecture diagram](https://alestic.com/img/blog/2019-05-04-aws-sns-delayed-architecture.png)
