# snapshotalyzser-2020
This demo project uses Python to interact with AWS EC2 instances

## About
This project is a demo, and uses boto3 to manage AWS EC2 instance snapshots.

## Configuring
shotty uses the configuration file created by the AWS cli. e.g.
'aws configure --profile shotty'

## Running
'pipenv run python src/shotty.py <command> <subcommand>
<--project=PROJECT>'

*command* is instances, volumes, or snapshots
*subcommand* depends on command
*project* is optional
