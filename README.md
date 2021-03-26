# Terraform

Create a new folder, and in that folder,  save terraform file. 
From the folder directory open terminal and run the following command to download and install terraform using home brew: 
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)”
Download terraform from https://www.terraform.io/downloads.html
Extract and change directory to the new folder
Run brew install terraform in the terminal
Run terraform init (This will initialize Terraform and create two more folders as well as a state file).
Run: terraform plan (This will perform a dry-run and will prompt a detailed summary of what resources is about to create).
Then create the resources with: terraform apply
