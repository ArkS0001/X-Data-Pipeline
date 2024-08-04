To create a free-tier eligible Amazon EC2 micro instance, follow these steps:

    Sign In: Log into your AWS Management Console.
    Navigate to EC2: Go to the EC2 dashboard.
    Launch Instance:
        Click "Launch Instance."
        Choose an Amazon Machine Image (AMI).
        Select the "t2.micro" instance type (free-tier eligible).
    Configure Instance:
        Configure the instance settings.
        Add storage (default settings usually suffice).
        Add tags if needed.
    Configure Security Group:
        Set up a security group with appropriate rules (e.g., allow SSH for Linux instances).
    Review and Launch:
        Review the configuration and click "Launch."
        Choose or create a key pair for SSH access.
    Launch: Click "Launch Instances."

After the instance is launched, you can connect to it using the public IP address and your key pair. Make sure to monitor usage to avoid charges beyond the free tier.
