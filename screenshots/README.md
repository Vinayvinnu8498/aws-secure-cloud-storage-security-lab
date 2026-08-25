# Evidence Screenshots

Add sanitized screenshots that demonstrate the security controls and test results used in this project.

Recommended evidence:

- S3 Block Public Access enabled
- Bucket owner enforced / ACLs disabled
- SSE-S3 encryption and versioning
- Public object access returning AccessDenied
- Developer successful read/write test
- Auditor read success and upload AccessDenied
- IAM policy validation with zero findings
- CloudTrail multi-region configuration
- CloudWatch metric filters and alarms
- SNS alert email
- DeleteObject event in CloudWatch Logs Insights
- S3 version recovery
- S3 Storage Lens dashboard

Before publishing, remove or blur passwords, access keys, secret keys, session tokens, MFA QR codes/secrets, and personal contact information.
