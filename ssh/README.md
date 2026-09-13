# SSH

Scripts and configuration for connecting to a remote server via SSH
using key-based authentication.

## Files

- 0-use_a_private_key: Bash script that connects to the server using
  the private key ~/.ssh/school and the ubuntu user.
- 1-create_ssh_key_pair: Bash script that generates a 4096-bit RSA SSH
  key pair named "school", protected by the passphrase "betty".
- 2-ssh_config: SSH client configuration file that uses the private
  key ~/.ssh/school and disables password authentication.
