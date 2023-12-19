# git-signing-test

Test SSH Signing of commits

Git client is configured to sign using SSH.

GitHub has the SSH key added as both an authentication key and a signing key.

Specify trusted SSH keys for signing so we dont get an error: cant check signature

MacOSX doesnt seem to pick up the relative paths in the Git config file, so email is not being set for Griffin specific projects. Set with git config command and use $HOME expansion of the shell

