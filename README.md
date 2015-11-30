# provision-linux-user
Provision a new user on a linux system with a minimal set of configuration.
- `vi` focused
- one-key aliases
- universal shell config

## Dependencies
- `ssh` to enable settings on the remote hosts
- `scp` to copy files to the remote host

## Usage
```txt
Usage: provision-linux-user <remote>

Options:
  -h, --help   output usage information

Examples:
  $ provision-linux-user usr@127.0.0.1   # provision a new user on localhost
  $ provision-linux-user myremote        # provision a new user on "myremote"

Docs: https://github.com/yoshuawuyts/provision-linux-user
Bugs: https://github.com/yoshuawuyts/provision-linux-user/issues
```

## Files
- `~/.bash_profile`
- `~/.profile`
- `~/.inputrc`
- `~/.shrc`

## License
[MIT](https://tldrlegal.com/license/mit-license)
