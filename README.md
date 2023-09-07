# IOT_CONNECT_AWS_IOT_CORE
How To Connect IOT Local to IOT Core in AWS
_______________________________________________

1. Fisrt You need to open menu IOT Core.
2. Create a new Policy, for example iam using name MyESP32-Policy and the data is right here
_______________________________________________________________________________________________
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Effect": "Allow",
      "Action": "iot:*",
      "Resource": "*"
    }
  ]
}

