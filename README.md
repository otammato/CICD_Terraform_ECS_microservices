# CICD_Terraform_ECS_microservices
[ IaC CICD ECS Docker ]

The repository is cloned from this author: 
https://github.com/sd031/microservice-cicd-project-with-terraform


<br>

1. Follow the instructions outlined in https://docs.aws.amazon.com/codecommit/latest/userguide/setting-up-ide-c9.html to integrate Cloud9 with CodeCommit.
<br>

2. Launch an ECS cluster by following the video tutorial at https://www.youtube.com/watch?v=fPkO3644kDU
<br>

3. Customize the Terraform files (variables.tf and main.tf) with your CodeCommit repository names, ECS cluster name, S3 Bucket name, etc.
<br>

4. Go to the "terraform_infra_deployment" folder and run the Terraform commands.
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

5. test the pipeline by modifying the source code to see the process and the result:

<br><br>
<p align="center" >
  <img width="960" alt="Screenshot 2023-02-07 at 20 43 11" src="https://user-images.githubusercontent.com/104728608/217361634-572a11dd-65df-4128-8b0d-5fbc838e2140.png">
</p>
<br><br>

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


