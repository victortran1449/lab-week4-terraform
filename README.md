# lab-week4-terraform

- Instructions on general set up.

- Command used to create a new SSH key pair.
ssh-keygen -t ed25519 -f ~/.ssh/lab4-key -C "lab4-key"

- Commands used to initialize, fmt, plan... configuration.
- To initialize
terraform init
terraform fmt
terraform validate
terraform plan -out plan-lab4
terraform apply plan-lab4