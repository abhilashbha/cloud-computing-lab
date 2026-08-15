# Experiment 3 – Create EC2 Instance in AWS

## Aim

To create an EC2 instance in Amazon Web Services (AWS).

## Procedure

1. Sign in to the AWS Management Console.
2. Open the **EC2** service.
3. Select **Launch instance**.
4. Enter a name for the instance.
5. Select an appropriate AMI.
6. Select an appropriate instance type.
7. Create or select a key pair.
8. Configure network and storage settings.
9. Launch the instance.
10. Verify that the instance is running.
11. Use the AWS connection instructions to connect to the instance.

## SSH Connection

The AWS console provides the connection command for the selected instance. A typical Linux SSH command has this form:

```bash
ssh -i "YOUR_KEY.pem" USERNAME@YOUR_PUBLIC_DNS
```

Never commit the private key to GitHub.

## Verification

After connecting to a Linux instance, basic commands can be used to verify the environment:

```bash
whoami
uname -a
pwd
ls
```

## Result

An EC2 virtual server can be created and accessed through AWS.

## Cost and Security

AWS pricing and free-tier eligibility can change. Verify the current AWS console before launching resources, and stop/terminate resources when they are no longer required.

## Screenshots

Add actual screenshots when available:

```text
screenshots/
├── ec2-dashboard.png
├── launch-instance.png
├── instance-running.png
└── connect-to-instance.png
```
