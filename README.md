# devops-netology
Changed for fix branch

не подвержены системе контроля версий
1. все файлы и каталоги находящиеся после каталога .terraform
2. все файлы с расширением tfstate (в начале, середине и конце); 
оканчивающиеся на .tfvars и .tfvars.json
оканчивающиеся на  что-то_override.tf, что-то_override.tf.json
3. Логи с именем crash.log и crash.что-то.log
4. файлы override.tf, override.tf.json, .terraformrc, terraform.rc
