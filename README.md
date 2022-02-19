# f5-remix
Remix of F5 for Kubernetes and openFaas that uses CronJobs, Serverless, React, and MongoDB.


# Manually run with openfaas-cli
```sh
faas-cli deploy --image=bsord/f5-get-posts --name=f5-get-posts --gateway=https://fn.yourfqnd.tld --env=MONGO_URI=mongodbstringurihere
```
## TODOS
 - [ ] Create function for getting posts from database
 - [ ] Update Readme on how to run the container or deploy manually with openfaas-cli
 - [ ] Automate build and versioning