
1. In order to start with Terraform, you need to make sure that you can connect to your Terraform to your AWS account
    Open VSCode, and then open terminal
    input:
        aws configure
2. After your aws account credentials have been verified, then verify your Terraform,
    input:
        terraform --version
        
3. Once it's verified create a folder where you're going to run your terraform files.
4. Open up VSCode and in the terminal
    cd ("to the folder that you created)
5. Then click the file drop down in VSCode and select new file
        input:
            0-auth.tf, this will create your first terraform file. Which will allow you to run terraform

6. Head to github.com/chewbaccawaf/class7
        fork the repo to your own repo
7. Afterwards head to your github and open the 0-auth.tf file and copy its contents
8. Go back to VSCode and in the 0-auth.tf file you created paste the contents that you copied.
9. Make sure to save it.
10. Next in your terminal in VSCode, make sure to cd into the folder that you created where your terraform file is.
11. Once you're in the directory
        input:
            terraform init
                this creates a terraform folder and terraform.lock.hcl(leave it alone sinc this allows you to interact with terraform)
12. Then you would need to check your syntax
    input:
        terraform validate
13. If everything checks out then you would
    input:
        terraform plan, which will display changes that are going to take place
14. The next step would be to 
    input:
        terraform apply, this will apply the changes that were displayed by terraform plan(you may want to start praying...js)













# hw10-20-2025
