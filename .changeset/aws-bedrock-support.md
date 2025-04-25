---
"task-master-ai": minor
---

Added support for using Anthropic models via AWS Bedrock. Users can now choose between direct Anthropic API access or AWS Bedrock integration by configuring the appropriate environment variables:

- Added `ANTHROPIC_API_PROVIDER` to switch between 'anthropic' (default) and 'bedrock'
- Added AWS Bedrock configuration options:
  - `AWS_ACCESS_KEY_ID`
  - `AWS_SECRET_ACCESS_KEY`
  - `AWS_REGION`
- Updated documentation with AWS Bedrock setup instructions and troubleshooting tips
- Added AWS Bedrock SDK dependency (@anthropic-ai/bedrock-sdk) 