# GitHub_Backup
This script takes backups of all the repositories in a Github organization. The contents of all the repositories are downloaded in Zip format and saved to an S3 bucket folder i.e;

```
"Git-Backup/2023-10-30-October-Monday/Repo_name"
```

## Pre Requirements
* Python version >= 3.8
* pip version >= 22.0.x
* Working internet connection :wink:

## Usage
Execute the following to install required python dependencies:
```
$ pip install requirments.txt
```
The just execute the following command:
```
$ python github-backup.py
```