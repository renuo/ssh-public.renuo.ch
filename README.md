# SSH public keys of Renuo employees

## New co-worker

Generate an SSH key

```sh
ssh-keygen -t ed25519 -C "<your name>@renuo.ch"
```

and then add the **public** key to this repo
[via PR](https://github.com/renuo/ssh-public.renuo.ch/new/main).

## Server operator

Install a new key onto a server by copying some of the Renuo public keys
into `~/.ssh/authorized_keys`.

## Tip of the day

Enable login via SSH key on a remote machine (password login needed first)

```sh
ssh-copy-id <user>@<host>
```
