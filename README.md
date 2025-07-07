# My-Shell-Project

## 📚 Project Explanation

This project is a Bash script to help AWS users quickly list resources running in their AWS account. It is designed for DevOps engineers, cloud administrators, or anyone who wants a fast way to check their cloud inventory.

Below is an explanation of how this project works from start to finish.

---

### 💡 What This Script Does

- Lists resources from various AWS services in a given AWS region.
- Automates the process of running AWS CLI commands for different services.
- Helps users avoid manually navigating the AWS Management Console.
- Outputs resource identifiers such as:
  - EC2 instance IDs
  - S3 bucket names
  - RDS instance names
  - Lambda function names
  - …and more!

---

### ✅ Why Use This Script?

- Saves time by quickly gathering cloud inventory.
- Useful for troubleshooting, audits, or documentation.
- Teaches how to use AWS CLI commands for resource management.
- Helps maintain visibility into your AWS environment.

---

### 🛠️ Prerequisites

Before running this script, you must:

✅ **Install AWS CLI**

- The AWS Command Line Interface (CLI) allows you to interact with AWS services directly from your terminal.
- Install it following AWS instructions:
  - [AWS CLI Installation Guide](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)

---

✅ **Configure AWS CLI**

- After installing, run the following command to set up your credentials:

```bash
aws configure
