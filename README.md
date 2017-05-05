# lambda-ec2-control
NodeJS lambda to start and stop EC2 instances

## Setup
```
npm install
zip -r ec2_start_stop.zip *
```

## Parameters

Start an instance:
```
{
"action": "start"
"instanceId": "i-xxxx"
}
```

Stop an instance:
```
{
"action": "stop"
"instanceId": "i-xxxx"
}
```

Note: your Lambda will need a role with sufficient permissions to start and stop EC2 isntances.
