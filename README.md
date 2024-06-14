# git-config
Guide to connect your github to local git.

**Step 1**: Open Terminal <br>
**Step 2**: Generating ssh key
```shell
ssh-keygen -t ed25519 -C [your email id of github]
```
**Step 3**: starting ssh agent
```shell
eval "$(ssh-agent -s)"
```
**Step 4**: adding public and private ssh keys to ~/.ssh
```shell
ssh-add ~/.ssh/id_ed25519 
```


