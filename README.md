# CloudFormation Template

Deploys a test environment with:
- S3 bucket for frontend
- ALB for API
- CloudFront distribution routing /api/* to ALB and static content to S3

For testing only; not production-secure.
