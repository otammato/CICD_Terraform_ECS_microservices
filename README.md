# CICD_Terraform_ECS_microservices
[ IaC CICD ECS Docker ]

The repository is cloned from this author: 
https://github.com/sd031/microservice-cicd-project-with-terraform



1. Integrate Cloud9 with CodeCommit like outlined here:
https://docs.aws.amazon.com/codecommit/latest/userguide/setting-up-ide-c9.html

2. Launch an ECS cluster as described in this video:
https://www.youtube.com/watch?v=fPkO3644kDU

3. Modify the Terraform variables.tf and main.tf files according to yours (CodeCommit Repo names, ECS cluster name, S3 Bucket name ..)

4. Navigate to "terraform_infra_deployment" folder and launch terraform commands:

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
5. test your pipeline:
<br><br>
<p align="center" >
  <img width="1070" alt="Screenshot 2023-02-07 at 19 59 13" src="https://user-images.githubusercontent.com/104728608/217353794-b219de0d-e1ee-4fad-8aa0-0a56ab0588ae.png">
</p>
<br><br>

<br><br>
<p align="center" >
  <img width="1031" alt="Screenshot 2023-02-07 at 19 57 47" src="https://user-images.githubusercontent.com/104728608/217353712-f8c9a489-5ae0-4718-9b57-cf5f09b20bd0.png">
</p>
<br><br>


