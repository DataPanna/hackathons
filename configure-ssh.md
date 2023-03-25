# Using SSH at Hackathons
Hackathons provide an excellent opportunity to collaborate with other technologists, but you need a way to exchange ideas with each other. While an online document storage and co-authoring product can be helpful, there is no replacement for leveraging source control when coordinating on technology topics. Any when commiting code into a public source control repository, SSH is the safest and most useful tool for maintaining your identity. Once you are familiar with using SSH for source control contributions, it will be a simple leap to use SSH to participant in Service Maintenance on Servers and Cloud Endpoints.

## Setting up SSH for the first time
Most modern OS's now handle SSH pretty similarly, but these instructions are for a Debian-based distribution of Linux:

### Check to see if any SSH keys exist
- SSH keys typically live in your home directory in a folder called ".ssh" (i.e. ~/.ssh or /home/username/.ssh)
- To see if any SSH Keys already exist, use 
  - ```ls -a ~/.ssh```
  - If you receive the message "No such file or directory", then you have no ssh keys. If a list of files is returned, you likely already have keys generated.
  - If keys already exist you can use them (assuming the private key portion hasn't been exposed).

### Creating a new SSH key
- ssh-keygen will create a 3072-bit RSA key pair by default; you will load the public portion into your Source Control settings and use the private key during pushes
- run ```ssh-keygen```
