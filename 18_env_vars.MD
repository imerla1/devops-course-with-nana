# Enviroment variables

print all system **Env varaibles**
`printenv`

Print specific env variable
`printenv <Key>`

Create ENV var
`export <key>=<value>`

Delete Env var
`unsert <var_name>`

if we wan't to permanently add **Env var** we must add it into 
`~/bashrc` or whatever Terminal we use
**Note** `~/.bashrc` is user specific each user has different `~/.bashrc` file

# Persisting env var system wide.
if we want to create system wide env var we should add it into
`/etc/enviroment`
But don't do it :) let Linus and Linux do staff :)