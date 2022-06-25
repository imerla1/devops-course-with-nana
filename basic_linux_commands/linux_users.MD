# Linux Users

## 3 User Categories
 - **Superuser Account **  
    - **Root** User - Unrestricted permissions
      - For administrative task: Need to login as **Root** or execute commands as root (`sudo` command)
      - Can have only 1 **Root** user Per computer
  - **User Account** (Regular or standard User)
    - A regular User We creat to login
    - Each Regular User has its own `home` Directory E.g Tom => `/home/tom`
    - Can have Multiple regular **users** 
  - **Service Account**
    - Relevant for Linux Server Distros
    - Each Service Will get its own user
    - E.G mysql user will start mysql application
    - Best Practice for Security
    - Can have Multiple **Service Users**

# Groups and permissions
User Level
- Give permissions to specific user directly

Group Level
- Give Permissions to Group

# Create New User 
`adduser [username]`
# change password of a user
`passwd [username]`

# Switch User
`su - [username]`

Without specificing any user you will login as root user `su -`

# Create New Group
`groupadd <groupname>`
By default, system assigns the next available **GID** from the range of group **IDs** specified in the **login.defs** file
## check list of groups
`cat /etc/group` 

# add User to the group
`usermod -g <groupname> <username>`
# add User to the multiple groups
`usermod -G <groupname> <username>`
