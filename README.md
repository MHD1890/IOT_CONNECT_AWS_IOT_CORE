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
______________________________________
3. And the menu IOT Core, choode IOT Things and this example iam using name MyESP32
4. Next Iam create the shadow name MyESP32-Shadow
5. Next create.
6. Then you can download my github code for your tester.
