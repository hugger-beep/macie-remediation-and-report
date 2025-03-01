# macie-remediation-and-report



# Organization Structure:

#├── Management Account (Root)

#├── Security/Audit Account (Macie Administrator)

    ├── Macie Administrator Configuration
  
    ├── Findings Bucket (s3://xxxx-macie-findings)
  
    ├── Logging Bucket (s3://xxx-macie-logs)
  
    ├── Lambda Functions for Remediation

#├── Member Accounts

     ├── Data Buckets (containing sensitive data)
