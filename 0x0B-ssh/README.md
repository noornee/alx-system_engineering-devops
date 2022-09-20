| filename | description |
| -------- | ----------- |
| `0-use_a_private_key` | a Bash script that uses ssh to connect to your server using the private key `~/.ssh/school` with the user `ubuntu`. |
| `1-create_ssh_key_pair` | Creates an RSA key pair |
| `2-ssh_config` | SSH client configuration using a private key and refusing to authenticate using a password |
| `100-puppet_ssh_config.pp` | Sets up the client SSH configuration file to connect to a server without typing a password |
