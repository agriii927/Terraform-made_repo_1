# Example of initialising repo in Terraform
Auto built by Terraform example repo named ${reponame} with configured branches and added users
## To run this terraform script use following commands:
1. Generate OAuth token in GitHub
2. Set the environmental variable:
```bash
export GITHUB_TOKEN="your_oath_token"
```
3. Run Terraform commands:
```bash
terraform init
terraform apply
```