# Backup to S3

This project automates the backup of local files to an AWS S3 bucket using a bash script and cron job.

## Script Details

- **backup_to_s3.sh**: This script creates a compressed backup of specified local files and uploads it to an S3 bucket.

## Usage

1. **Set Up Environment**:
   - Install AWS CLI and configure it with your credentials.
   - Update the `SOURCE_DIR`, `DEST_DIR`, and `BUCKET_NAME` variables in the script.

2. **Run Script**:
   ```sh
   ./backup_to_s3.sh
