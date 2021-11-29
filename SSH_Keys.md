In order to push your file into github. We have to connect our local machine into github.
We can do that using SSH keys

the command to generate ssh key is

```
ssh-keygen -t rsa -b 4096 -c "email address"
```
There are two keys generated 
key
key.pub

where key.pub is the public key.

We use private key every time we add a file from local machine to github.

We can add our SSH key in the "SSH keys" section

To start the SSH agent

```
eval "$(ssh-agent -s)"
agent pid 59566
```

After this we add SSH run command
