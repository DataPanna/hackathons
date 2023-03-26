# Configure GPG
- check for existing gpg keys using ```gpg --list-secret-keys --keyid-format=long```
- or generate new ones using ```gpg --full-generate-key``` (be sure to select 4096 bits for use on GitHub)
- use ```gpg --list-secret-keys --keyid-format=long``` to ensure the key is generated and to get the ID for the next step
- using the {ID} from the previous command, run ```gpg --armor --exort {ID}``` to print out the public key that you need to load into your GitHub > Settings > SSH and GPG configuration.
- Finally, to use your GPG Key to sign your commits, you can set that to happen by default using ```git config --global commit.gpgsign true```
