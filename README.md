# SSH public keys of Renuo employees

## New co-worker

Generate an SSH key

```sh
ssh-keygen -t ed25519 -C "<your name>@renuo.ch"
```

and then add the **public** key to this repo
[via PR](https://github.com/renuo/ssh-public.renuo.ch/new/main).

_You can find more information about configuring your SSH agent
[on Github](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent#adding-your-ssh-key-to-the-ssh-agent)_

## Server operator

Install a new key onto a server by copying some of the Renuo public keys
into `~/.ssh/authorized_keys`.

## Tip of the day

Enable login via SSH key on a remote machine (password login needed first)

```sh
ssh-copy-id <user>@<host>
```
