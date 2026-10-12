# AWS Tech Guidance
- Use Python 3.11+ and the official `boto3` SDK.
- Always use AWS profile-based authentication (`aws configure --profile <name>`).
- Handle AWS client errors gracefully using `botocore.exceptions.ClientError`.
- Never hardcode AWS Access Keys or Secret Keys; use environment variables or IAM roles.
