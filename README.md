# MockingJay JMeter Hacks

This JMeter Test Plan is an attempt at capturing some best practices in order to reduce the turn-around time to run continuous executions. I will be using the MockingJay application to run Load Tests.

Here are a few hacks that I have listed that are worth diving into. I will be providing a few write-ups supplemented with examples.

## Lets get started
These instructions will get you a copy of the test plans and all required folders and/or configuration files.

You will need the following installed before you can continue:

```shell
    Apache JMeter 5.0
    Plugins Manager 1.3
```

## Problem Statements

### 1. Exclusive Data Consumption
If an application utilised exclusive data that cannot be reused again, this situation becomes a bottleneck when designing, debugging or executing tests. We have to start updating the `csv` files regularly or maintain a lot of data. 

**Solution**: 

### 2. Efficient Log Writing
When running multiple tests and juggling between running tests, debugging and test analysis, the last thing you want is to have your logs and results overwritten. 

**Solution**: 

### 3. Automated Test Reports
After execution the test analysis is critical. However due to the comprehensive approach in collating and creating a report, we at times miss the critical aspects. In addition, we want to focus on particular metrics while ignoring the others.

**Solution**: 

### 4. Remote Load Generators Health Check
When running a distributed load test, it is important to ensure you have all your JMeter agents running on all the machines before kicking off a test. It is Time consuming to manually ensure all the agents are up and running before a test. 

**Solution**: 
