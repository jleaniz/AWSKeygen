# AWSKeygen

This tool generates a new AWS access/secret access key pair through the STS service as described in https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_temp.html. These are temporary keys that can be used to interact with AWS services via command line tools or APIs.

The advantage of generating temproary keys using AWS STS is that there is no need for a client (i.e. user or application) to set long-term or hardcode secret keys to utilize AWS services.

Requirements:
- The AWS account must be configured to use federated identities via SAML 2.0
- Set the idpentryurl variable to the apprpriate SAML authentication URL
