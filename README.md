# Hashcat-rules

## Mutaciones de contraseña (HASHCAT)

En el siguiente ejemplo password.list con tiene unicamente la palabra (password) pero puedes usar una lista de palabras para crear una lista mutada de contraseñas.


hashcat --force password.list -r custom.rule --stdout | sort -u > mut_password.list

cat mut_password.list
