# AWSKeygen

This tool generates a new AWS access/secret access key pair through the STS service. These are temporary keys that can be used to interact with AWS services via command line tools or APIs.

The advantage of generating temproary keys using AWS STS is that there is no need for a client (i.e. user or application) to set long-term or hardcode secret keys to utilize AWS services.
