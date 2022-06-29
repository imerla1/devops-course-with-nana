#ssh
generate ssh Key

`ssh-keygen -t rsa`
## add public key to authorized_keys on remote server

create `authorized_keys` file in `~/.ssh`
`touch authorized_keys`

paste generated public key into `authorized_keys`
generate public key should be in client pc `~/.ssh/id_rsa.pub` file

by default ssh commands search for private key in .ssh/id_rsa but if you have multiple ssh private keys you have to excplicitly pass private key location to `ssh`

`ssh -i .ssh/id_rsa root@servername` 

copy file from **local to remote**
`scp <source> <target>`
`scp`