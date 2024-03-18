# ssh
public ssh keys

```bash
mkdir -p ~/.ssh/
touch ~/.ssh/authorized_keys
echo "ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIP+O9mwTSRtmsqwFRNo3NtP0r8OPDQpBRBhvZrl/dV5i john.jones@frank-key.co.uk" >> ~/.ssh/authorized_keys
echo "ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIID5+r8UHXoKg200Lo8AMr8GmYXw31Mp6MLn+rVbtqf0 john.jones@frank-key.co.uk" >> ~/.ssh/authorized_keys
