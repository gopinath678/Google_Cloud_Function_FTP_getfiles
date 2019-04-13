# Google_Cloud_Function_FTP_getfiles

This is a Google Cloud Function that was written to retrieve all .zip files from a 3rd party FTP site. 

The function is triggered by an http request every 5 minutes from Google Cloud Scheduler.

It is deployed using Google Cloud Build from git repo merge triggers.

This is a simple and effective serverless way to pull files from FTP sites into GCP storage buckets on a cron schedule.

*NOTE* You will want to consider if clear text authentication credentials in your source code.  For production deployment, encrypted or obscured authentication credentials are recommended. 
