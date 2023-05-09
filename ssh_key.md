# Git Config for specifying the SSH key you are using

To use SSH key to push/pull repos without typing username/password, one can use SSH link: [Source][1]
```bash
git@github.com:<Username>/<Project>.git
```

When there are multiple keys in your ~/.ssh folder, you may want to specify the one you want to use: [Source][2]
```bash
git clone git@provider.com:userName/projectName.git --config core.sshCommand="ssh -i ~/location/to/private_ssh_key"
```

[1]: <https://stackoverflow.com/questions/14762034/push-to-github-without-a-password-using-ssh-key#14765857> "Push to GitHub without a password using ssh-key"
[2]: <https://stackoverflow.com/questions/41714882/git-how-to-clone-with-ssh-key-username#59074070> "Git how to clone with SSH key, username"
