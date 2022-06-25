#pipe
"pipe" command: `|` 
pipes the output of the previous command as an input to the next command

display all command in history which contains `sudo` keyword

`history | grep sudo`

# Redirection
`>` is redirect operator
Takes the output from the previous command and sends it to to a file that you give 
`pip freeze > requirements.txt`

`>>` it will append content to the end of the file won't override.