# amazon-eks-ami-git-auto-sync

- The `amazon-eks-ami` repository contains resources and configuration scripts for building a custom Amazon EKS AMI with HashiCorp Packer(WIP). This is the same configuration that Amazon EKS uses to create the official Amazon EKS-optimized AMI.


## What does it?

- It will get all the changes from the official repo <https://github.com/awslabs/amazon-eks-ami> and create a PR with last changes.
- Once a week it will run `automatically` and apply new changes.


