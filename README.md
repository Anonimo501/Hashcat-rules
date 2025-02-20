# Hashcat-rules

## Mutaciones de contraseña (HASHCAT)

En el siguiente ejemplo password.list con tiene unicamente la palabra (password) pero puedes usar una lista de palabras para crear una lista mutada de contraseñas.


hashcat --force password.list -r custom.rule --stdout | sort -u > mut_password.list

cat mut_password.list

## Imagenes

![Image](https://github.com/user-attachments/assets/2e34f6c4-175b-46bd-8ccf-65a5ea9cfd9e)

![Image](https://github.com/user-attachments/assets/4be7c6ed-cf86-4539-aaf7-5ea3a1ce083f)
