# Week 0 — Billing and Architecture

 1. Install aws CLI using the below command in git pod, also used aws cloudshell to interact with various services.

     curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
     unzip awscliv2.zip
     sudo ./aws/install
2. Used Gitpod.yml to auto install the aws cli on load and commited the changes in the repo.

   tasks:
  - name: aws-cli
    env:
      AWS_CLI_AUTO_PROMPT: on-partial
    init: |
      cd /workspace
      curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
      unzip awscliv2.zip
      sudo ./aws/install
      cd $THEIA_WORKSPACE_ROOT

3. Finished watching all the videos including the security and billing, completed the quiz.
4. Created Napkin and Logical diagram in lucid.
   https://lucid.app/lucidchart/df5d0d57-d81f-4432-a5c0-b733cdbe5f46/edit?viewport_loc=-154%2C29%2C1995%2C960%2C0_0&invitationId=inv_43835d1b-a108-4c9b-9158-47960e311a0f

   https://lucid.app/lucidchart/f0393bad-6100-42c1-9a5a-fca3664e8202/edit?viewport_loc=-201%2C-110%2C2560%2C1232%2C0_0&invitationId=inv_1e09359d-f771-4906-b4f4-55ee268b93f4

5. Set global variables in gitpod 
   
   https://github.com/abiddhanani/aws-bootcamp-cruddur-2023/blob/main/Screenshots/Globalvariables.png
  
6. Use AWS Console to create admin user and create budgets, explored billing to review free tier limit cost management.

7. Create SNS Topic and subscription and created the alaram using the cli. added the Json file in repo
   https://github.com/abiddhanani/aws-bootcamp-cruddur-2023/blob/main/Screenshots/Credits.png
   
   https://github.com/abiddhanani/aws-bootcamp-cruddur-2023/blob/main/Screenshots/Topic.png

8. Used cloud trail to find the api call logs
9. using create organization to handle multiple accounts for an org.
10. Used aws well arch tool to review different componets of application.
