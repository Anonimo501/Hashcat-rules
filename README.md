# Hashcat-rules

## Uso con hashcat

hashcat --force password.list -r custom.rule --stdout | sort -u > mut_password.list

cat mut_password.list
