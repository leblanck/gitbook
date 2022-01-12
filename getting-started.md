---
description: Software and GitHub Setup
---

# Getting Started

### New Computer Setup

The majority of setup can be done by following the README on the bustIT Github repo: [https://github.com/leblanck/bustit](https://github.com/leblanck/bustit)

The following list of software either are not in brew, or have not been added to the array in that repo (yet).

Use `brew search --casks` for additional software/casks that are available

![Current macOS working setup](.gitbook/assets/Screen\_Shot\_2020-02-25\_at\_2.27.15\_PM.png)

### GitHub SSH Setup

Adapted from the following article. Please see article for more information.

{% embed url="https://help.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh" %}

#### Check For Existing Keys

1. In terminal, run: `$ ssh-keygen -t rsa -b 4096 -C "your_email@example.com"`
2. Press enter to accept the default save location of `~/.ssh/id_rsa`
3. Enter a secure passphrase (If need save it in 1Password)

#### Add Key to SSH Agent

1. Start SSH Agent in background: `$ eval "$(ssh-agent -s)"`
2.  Add the following to `/.ssh/config` ; if it does not exist create it using: `touch /.ssh/config`

    ```bash
    Host *
      AddKeysToAgent yes
      UseKeychain yes
      IdentityFile ~/.ssh/id_rsa
    ```
3. Add SSH private key to ssh-agent and store in keychain: `$ ssh-add -K ~/.ssh/id_rsa`

#### Add Key to Github

Follow this article if needed: [https://help.github.com/en/articles/adding-a-new-ssh-key-to-your-github-account](https://help.github.com/en/articles/adding-a-new-ssh-key-to-your-github-account)
