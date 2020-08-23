Homework 2.1
second line

# Local .terraform directories
**/.terraform/* - игнорировать все файлы из всех папок ".terraform"

# .tfstate files
*.tfstate - Игнорировать все файлы с имеющие в конце названия вхождение ".tfstate"
*.tfstate.* - Игнорировать все файлы имеющие в названии вхождение ".tfstate"

# Crash log files
crash.log - Игнорировать все файлы "crash.log"

# Exclude all .tfvars files, which are likely to contain sentitive data, such as
# password, private keys, and other secrets. These should not be part of version 
# control as they are data points which are potentially sensitive and subject 
# to change depending on the environment.
#
*.tfvars - Игнорировать все файлы имеющие в конце названия вхождение "tfvars"

# Ignore override files as they are usually used to override resources locally and so
# are not checked in
override.tf - Игнорировать все файлы "override.tf"
override.tf.json - Игнорировать все файлы "override.tf.json"
*_override.tf - Игнорировать все файлы имеющие в конце названия файла вхождение "_override.tf"
*_override.tf.json - Игнорировать все файлы имеющие в конце названия файла вхождение "_override.tf.json"

# Include override files you do wish to add to version control using negated pattern
#
# !example_override.tf - закомментировано (не должно применяться), но если бы применялось отменяло игнорирование для файлов "example_override.tf"

# Include tfplan files to ignore the plan output of command: terraform plan -out=tfplan
# example: *tfplan*

# Ignore CLI configuration files
.terraformrc - Игнорировать все файлы с названием ".terraformrc"
terraform.rc - Игнорировать все файлы c названием ".terraformrc"