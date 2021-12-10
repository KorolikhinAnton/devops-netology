# devops-netology
## Ignored files in terraform folder
1. Local .terraform directories
1. State files
1. Crash log files
1. Exclude all .tfvars files, which are likely to contain sentitive data, such as password, private keys, and other secrets. These should not be part of version control as they are data points which are potentially sensitive and subject to change depending on the environment.
1. Ignore override files as they are usually used to override resources locally and so
1. are not checked in
1. Include override files you do wish to add to version control using negated pattern
1. Include tfplan files to ignore the plan output of command: terraform plan -out=tfplan
1. Ignore CLI configuration files
