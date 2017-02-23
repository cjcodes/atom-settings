# Installation
`apm install --packages-file packages.list`

# Backup
Without version locking:
`apm list --installed --bare | sed "s/@.*$//g" > packages.list`

With version locking:
`apm list --installed --bare > packages.list`
