# ssh
public ssh keys

```bash
mkdir -p ~/.ssh/
touch ~/.ssh/authorized_keys
echo "ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIMok4i+msZ/c2vdm+/WJwB5BqlfRtXUKHcDf7QGoPR03 john.jones@frank-key.co.uk" >> ~/.ssh/authorized_keys
echo "ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAILFEy2WbKBVPvQv9Ie/5BQzBaHBdq1rbGK2q0+781GDm john.jones@frank-key.co.uk" >> ~/.ssh/authorized_keys
