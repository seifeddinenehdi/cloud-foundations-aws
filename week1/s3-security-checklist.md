# S3 Security Checklist (Week 1)

## Must-do settings
- [ ] Block Public Access (account + bucket)
- [ ] Enable default encryption (SSE-S3 or SSE-KMS)
- [ ] Use least-privilege bucket policies
- [ ] Avoid public ACLs (prefer policies)
- [ ] Turn on versioning (when appropriate)

## Monitoring & review
- [ ] Review access with IAM Access Analyzer (if available)
- [ ] Enable logging/CloudTrail events for visibility (when appropriate)
- [ ] Regularly audit who can read/write/delete
