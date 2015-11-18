# graphite-cloud-formation
A CloudFormation template for Graphite + Statsd.

## Features
- Use Docker: https://github.com/hopsoft/docker-graphite-statsd.
- Private Docker Hub.
- Backup with a Snapshot, restoring from a Snapshot.
- htpasswd.
- Add domain from Route 53.
- Add existing Security Groups, SubnetIds.


## Create a stack
`aws cloudformation create-stack --stack-name VinhLH --template-body file:///your-path/cloud-formation/graphite-docker-cloud-formation.json`
