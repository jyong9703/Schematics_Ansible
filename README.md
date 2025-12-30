# Schematics COS Action

This repo is an IBM Cloud Schematics Ansible Action template to:

1. Create a Cloud Object Storage (COS) bucket with a random suffix.
2. Create a directory prefix inside the bucket (`app/data/`).

## How to use

1. Set environment variables in your Schematics Action:

```bash
export COS_ACCESS_KEY_ID=<your-hmac-access-key-id>
export COS_SECRET_ACCESS_KEY=<your-hmac-secret-key>
export COS_ENDPOINT=<your-cos-endpoint>
export COS_REGION=<your-region>

