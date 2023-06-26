# devops-netology
# Start work with Git (first)

# Игнорировать все файлы в корневой директории с расширением .terraform и дальше может быть любое другое расширение (дополнительно)
**/.terraform/*

# Исключить все файлы с расширением .tfstate
*.tfstate

# Исключить все файлы с расширением .tfstate и дальше может быть любое другое расширение (дополнительно)
*.tfstate.*

# Исключить файл crash.log из текущей директории
crash.log

# Исключить файл crash.*.log из текущей директории, где * - любое расширение
crash.*.log


# Исключить все файлы с расширением .tfvars
*.tfvars

# Исключить все файлы с расширением .tfvars.json
*.tfvars.json

# Исключить файл override.tf из текущей директории
override.tf

# Исключить файл override.tf.json из текущей директории
override.tf.json

# Исключить файл *_override.tf из текущей директории (вместо * может быть любое количество символов перед символом _)
*_override.tf

# Исключить файл *_override.tf.json из текущей директории (вместо * может быть любое количество символов перед символом _)
*_override.tf.json


# Отслеживать файл example_override.tf даже если он подпадает под исключение выше
!example_override.tf

# Игнорировать файлы tfplan
*tfplan*

# Игнорировать файлы конфигурации (CLI configuration files) в текущей директории с расширением .terraformrc
.terraformrc

# Игнорировать файлы конфигурации (CLI configuration files) в текущей директории с  расширением .terraformrc.rc
terraform.rc
