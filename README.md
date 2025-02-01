# lab-week4-terraform

Command used to create a new SSH key pair.
- ssh-keygen -t ed25519 -f ~/.ssh/lab4-key -C "lab4-key"

Commands used to initialize, fmt, plan... configuration.
- terraform init
- terraform fmt
- terraform validate
- terraform plan -out plan-lab4
- terraform apply plan-lab4