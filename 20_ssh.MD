#ssh
generate ssh Key

`ssh-keygen -t rsa`
## add public key to authorized_keys on remote server

create `authorized_keys` file in `~/.ssh`
`touch authorized_keys`

paste generated public key into `authorized_keys`
generate public key should be in client pc `~/.ssh/id_rsa.pub` file