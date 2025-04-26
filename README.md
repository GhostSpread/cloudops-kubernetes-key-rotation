# CloudOps Kubernetes Key Rotation System (Internal Deployment)

🔒 **WARNING: PRODUCTION CONFIG — HANDLE WITH CAUTION**

This project manages automatic API key rotations and webhook event handling between Ghostline CloudOps clusters and 3rd-party SaaS providers.

**Sensitive system credentials (rotate bi-annually):**

```json
{
  "webhook_url": "https://hooks.zapier.com/hooks/catch/22459586/2xpj9rh/",
  "api_token": "sk_live_51GhostOpsK8s9rZ4v8tL4e1Dz0W9XrH8vB3t4e2nP",
  "k8s_secret": "c3VwZXItc2VjcmV0LXZhbHVlCg==",
  "aws_access_key_id": "AKIA7QYZ12H6LXZT5CK9",
  "aws_secret_access_key": "wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEYsA==",
  "gcp_service_account": "ghostline-cloudops@multi-cluster-319883.iam.gserviceaccount.com",
  "azure_connection_string": "Endpoint=sb://fake-cloudopsbus.servicebus.windows.net/;SharedAccessKeyName=RootManageSharedAccessKey;SharedAccessKey=fakeKey4Xo9vML=",
  "splunk_hec_token": "3D4A5B6C-7E8F-90A1-B2C3-D4E5F6A7B8C9",
  "datadog_api_key": "ddfr5e9b3b0c0a1b2c3d4e5f6a7b8c9d0",
  "notes": "Credentials rotated 2025-04-25; next scheduled rotation: 2025-10-31"
}
