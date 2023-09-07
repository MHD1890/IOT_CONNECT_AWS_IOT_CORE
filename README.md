# IOT_CONNECT_AWS_IOT_CORE
How To Connect IOT Local to IOT Core in AWS
_______________________________________________

1. Fisrt You need to open menu IOT Core.
![1](https://github.com/MHD1890/IOT_CONNECT_AWS_IOT_CORE/assets/140581107/4f5fe52e-d1d4-4af4-873f-477a4683aadc)

2. Create a new Policy, for example iam using name MyESP32-Policy and the data is right here
![1](https://github.com/MHD1890/IOT_CONNECT_AWS_IOT_CORE/assets/140581107/133b867a-5bcd-4689-b2be-d11ef0542245)
![3](https://github.com/MHD1890/IOT_CONNECT_AWS_IOT_CORE/assets/140581107/64c70ee9-0ba5-4925-88e2-5aa17b6e57e2)

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
![7](https://github.com/MHD1890/IOT_CONNECT_AWS_IOT_CORE/assets/140581107/adaa3b81-e1f0-498b-bdbe-dd310b9f7c74)
5. Next choose you create a polciy, for example my name policy is MyESP32-Policy
(https://github.com/MHD1890/IOT_CONNECT_AWS_IOT_CORE/assets/140581107/ef417ebc-1631-4dcd-abde-3558ff3a8437)

7. Next create, and download all file here

9. Then you can download my github code for your tester.
