# Terraform Demonstration with Azure

## Prerequisites
- [Go](https://golang.org/)
- [Terraform](https://www.terraform.io/)

## Steps

### 1. Authentication with Azure

#### Environment Variables
Define the following secrets as environment variables before running the Terraform scripts.

- **ARM_CLIENT_ID**
- **ARM_CLIENT_SECRET**
- **ARM_SUBSCRIPTION_ID**
- **ARM_TENANT_ID**


### 2. Initializing and Running Terratest

Run the following commands in your terminal:

```bash
# Initialize Go modules
cd test
go mod init test
go mod tidy

# Run Terraform tests
go test -v -timeout 30m
