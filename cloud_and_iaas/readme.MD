# Create Digital Ocean Droplet
- create droplet
- add ssh key
- In networking create firewall rule to allow ssh
- assing firewall rules to specific Droplets
  - `Networking`- >`firewall` -> `droplets`  

# Create User for Service
- `adduser <username>`
- add User to sudo group
  - `usermod -aG sudo <username>`

- Created .ssh folder with ssh key for new User
    - add `ssh.pub` key in `~/.ssh/authorized_keys`

# Deploy Java-React-App into droplet

- clone https://github.com/pmendelski/java-react-example
- build jar file 
  - `./gradlew build` 
- scp that jar file to the server
  - `scp build/libs/java-react-example.jar root@host:/root` 
- Run the server
  - `java -jar java-react-example.jar`
- Open port 7071