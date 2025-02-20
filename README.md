# Hashcat-rules

## Mutaciones de contraseña (HASHCAT)

En el siguiente ejemplo password.list con tiene unicamente la palabra (password) pero puedes usar una lista de palabras para crear una lista mutada de contraseñas.
Recordemos que esta es una buena forma de crear diccionarios personalizados.

## Imagenes

hashcat --force password.list -r custom.rule --stdout | sort -u > mut_password.list

<img width="513" alt="Image" src="https://github.com/user-attachments/assets/a45a3e65-6520-4dfe-8461-743a771d5329" />

cat mut_password.list

<img width="184" alt="Image" src="https://github.com/user-attachments/assets/effdae40-3cd4-4a60-8b72-0b11c7c91e9d" />
