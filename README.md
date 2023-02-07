# CICD_Terraform_ECS_microservices (demo)
[ IaC CICD ECS Docker ]

This Terraform template sets up a CI/CD pipeline using AWS CodePipeline. As the source, it utilizes AWS CodeCommit, and builds are executed as Docker containers within an AWS ECS cluster.

The repository is cloned from this author: 
https://github.com/sd031/microservice-cicd-project-with-terraform


<br>

To implement the complete solution:

1. I followed the instructions outlined in https://docs.aws.amazon.com/codecommit/latest/userguide/setting-up-ide-c9.html to integrate Cloud9 with CodeCommit.
<br>

2. Launched an ECS cluster with 3 microservices, written with Go, Python3 and JS and deployed as Docker containers, by following the video tutorial at https://www.youtube.com/watch?v=fPkO3644kDU
<br>

3. Customized the Terraform files (variables.tf and main.tf) with my CodeCommit repository names, ECS cluster name, S3 Bucket name, etc.
<br>

4. Went to the "terraform_infra_deployment" folder and ran the Terraform commands.
<br>

```
terraform init
```
```
terraform validate
```
```
terraform apply
```
<br><br>

5. tested the pipeline by modifying the source code to see the process and result:

<br><br>
<p align="center" >
  <img width="700" alt="Screenshot 2023-02-07 at 20 54 12" src="https://user-images.githubusercontent.com/104728608/217363768-40a9c2e2-e097-47fa-b216-e5f8089f824d.png">
</p>
<br><br>

<br><br>
<p align="center" >
  <img width="700" alt="Screenshot 2023-02-07 at 19 59 13" src="https://user-images.githubusercontent.com/104728608/217353794-b219de0d-e1ee-4fad-8aa0-0a56ab0588ae.png">
</p>
<br><br>

<br><br>
<p align="center" >
  <img width="700" alt="Screenshot 2023-02-07 at 19 57 47" src="https://user-images.githubusercontent.com/104728608/217353712-f8c9a489-5ae0-4718-9b57-cf5f09b20bd0.png">
</p>
<br><br>

6. To see the changes, paste the dns endpoint of ELB (Elastic load balancer), launched at step 2 to your browser

<br><br>
<p align="center" >
  <img width="700" alt="Screenshot 2023-02-07 at 21 11 42" src="https://user-images.githubusercontent.com/104728608/217366743-978a17cd-253b-4c9e-b5ad-cc27236b157f.png">
</p>
<br><br>
