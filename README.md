# cloud-free-tier-hosting
The idea is to use Terraform to provision with free tier computation. Those machines/services can than be LoadBalanced (ref: xxx.github.com).

![Diagram](https://iili.io/JceXXn.png)


The job will be then picked by Puppet that will provision the generated machines with Docker.

## Requirements
R1: Install Terraform, Pupper.
R2: Dockerise your application in one container (make it simple, if possible).

## Future changes
Future changes will be made to support multiple containers being deployed and ran on the machines, up to machines limits (keep in mind that free tiered ones don't offer much - they are free at the end...)
