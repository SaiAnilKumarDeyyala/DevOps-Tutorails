# Terratest Demonstration with Azure

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
```


### Video Demonistration
For step by step demonistration watch this [Youtube Tutorail](https://youtu.be/tie0D44A9co?feature=shared)

# Terratest Resources

## Official Website

Visit the [Official Terratest Website](https://terratest.gruntwork.io/) for detailed information and documentation.

## GitHub Repository

Explore the source code and contribute to Terratest on the [GitHub Repository](https://github.com/gruntwork-io/terratest).

## Terratest Packages

Check out the [Terratest Packages on pkg.go.dev](https://pkg.go.dev/github.com/gruntwork-io/terratest/modules) for comprehensive documentation on the Terratest modules.
