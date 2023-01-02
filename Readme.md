Auto-Monitoring using AWS CloudWatch & Auto-Healing using AWS lambda

## Importance of a Monitoring Tool

**Problem Statement** -> In the microservice architecture, you're dealing with 1000's of API'S which are working in tandom with each other. There could be failures with related to API as a service, the authentication can fail, CPU utlization, or memory consumptions make application server to crash.

**Solution** -> Use a Tool to collect **logs**. Alert when something goes wrong -> Take Action to mitigate the issue -> Analyze to avoid such things in future.

## AWS Cloudtrail

### Cloudtrail records all the API calls.

Benefit - It records all the **details of your action** -> Writes it in the form of **logs** into the specified S3 bucket & Create Alarms if something goes wrong.

Details - **Who** called the API? What **time** it was called? What **Parameters** were requested? What **Response** elements were returned by AWS service?

By Default, AWS records all activities of past 90 days in an account using AWS Cloudtrail.
