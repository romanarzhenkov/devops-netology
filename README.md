Homework 2.1
second line

"**/.terraform/*" - игнорировать все файлы из всех папок ".terraform"

"*.tfstate" - Игнорировать все файлы с имеющие в конце названия вхождение ".tfstate"

"*.tfstate.*" - Игнорировать все файлы имеющие в названии вхождение ".tfstate"

"crash.log" - Игнорировать все файлы "crash.log"

"*.tfvars" - Игнорировать все файлы имеющие в конце названия вхождение "tfvars"

"override.tf" - Игнорировать все файлы "override.tf"

"override.tf.json" - Игнорировать все файлы "override.tf.json"

"*_override.tf" - Игнорировать все файлы имеющие в конце названия файла вхождение "_override.tf"

"*_override.tf.json" - Игнорировать все файлы имеющие в конце названия файла вхождение "_override.tf.json"

"# !example_override.tf" - закомментировано (не должно применяться), но если бы применялось отменяло игнорирование для файлов "example_override.tf"

".terraformrc" - Игнорировать все файлы с названием ".terraformrc"

"terraform.rc" - Игнорировать все файлы c названием ".terraformrc"