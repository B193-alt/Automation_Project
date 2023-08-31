# Automation_Scipt
Apache2 Logs Automation Script
This Bash script automates management of Apache2 logs on Linux systems. It archives logs, uploads to S3, updates an HTML inventory, and sets up a daily cron job.
Usage
Clone the repository.

Make the script executable: chmod +x automation.sh

Edit variables (name, s3_bucket, docroot).

Run: ./automation.sh

Cron Job
A cron job is set to run the script daily at 12:00 AM IST
