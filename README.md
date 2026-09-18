# secure-data-vault-aws

Secure AWS data storage lab demonstrating S3 hardening, IAM least-privilege, and CloudTrail-based Splunk detection.

## Status
🚧 Work in progress

## Architecture
See `/diagrams` for the current architecture flow: S3 bucket → IAM roles/policies → CloudTrail → S3 log bucket → Splunk.

## Structure
- `/policies` — IAM policy JSON files (least-privilege, bucket policies, etc.)
- `/diagrams` — Architecture diagrams
- `/splunk-detections` — Splunk detection rules / searches built against CloudTrail logs
- `/screenshots` — Console screenshots documenting the build

## Goals
- Harden an S3 bucket for secure data storage
- Apply least-privilege IAM roles and policies
- Enable CloudTrail (management events) to log account activity
- Ship those logs to Splunk and build detections on top

# secure-data-vault-aws
# secure-data-vault-aws
