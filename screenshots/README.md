# Evidence Screenshots

This folder contains curated screenshots captured during the AWS Secure Cloud Storage Security Lab. Repetitive screenshots and images containing unnecessary personal information are intentionally excluded from the public portfolio.

## Current evidence

1. `01-auditor-read-access.jpg` — Auditor successfully reads the protected S3 object.
2. `02-auditor-write-denied.jpg` — Auditor upload attempt fails with **Access denied**, proving read-only least privilege.
3. `03-temp-acl-bucket-deleted.jpg` — Temporary ACL test bucket successfully removed during remediation.
4. `04-iam-users-admin-mfa.webp` — IAM user inventory and MFA configured for the cloud security administrator.
5. `05-cloudtrail-multiregion.webp` — CloudTrail logging enabled with **Multi-region trail = Yes** and log-file validation enabled.

## Additional evidence documented in the project

- S3 Block Public Access and Bucket Owner Enforced
- HTTPS-only bucket policy
- SSE-S3 encryption and versioning
- Anonymous object access returning `AccessDenied`
- Developer read/write test
- IAM policy validation with zero findings
- CloudWatch security alarms
- SNS alerting
- `DeleteObject` investigation in CloudWatch Logs Insights
- Version-based object recovery
- S3 Storage Lens dashboard

> Security note: Never publish AWS access keys, secret keys, session tokens, passwords, MFA QR codes/secrets, or other credentials. Screenshots in this public portfolio are selected with that rule in mind.
