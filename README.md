# f5-remix
Remix of F5 for Kubernetes and openFaas that uses CronJobs, Serverless, React, and MongoDB.


# Manually run with openfaas-cli
```sh
git clone https://github.com/bsord/f5-remix
faas-cli deploy --image=f5-get-posts --name=f5-get-posts --handler=. --gateway=http://remote-site.com:8080 --lang=node16 --env=MYVAR=myval
```
## TODOS
 - [ ] Create function for getting posts from database
 - [ ] Update Readme on how to run the container or deploy manually with openfaas-cli
 - [ ] Automate build and versioning