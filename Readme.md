Auto-Monitoring using AWS CloudWatch & Auto-Healing using AWS lambda

## Importance of a Moniotring Tool

**Problem Statement** -> In the microservice architecture, you're dealing with 1000's of API'S which are working in tandom with each other. There could be failures with related to API as a service, the authentication can fail, CPU utlization, or memory consumptions make application server to crash.

**Solution** -> Use a Tool to collect **logs**. Alert when something goes wrong -> Take Action to mitigate the issue -> Analyze to avoid such things in future.
