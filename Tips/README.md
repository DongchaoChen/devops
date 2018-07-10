## Tips

### Docker on Windows Tips
- In Windows, it is quite common to use git pash running commands, but unfortunately it isn't working nicely together with docker, so try below script
```
if [[ "$OS" == "Windows_NT" ]]; then
  docker_cmd="winpty docker"
fi

# Another example
$ docker run -it ubuntu bash
$ the input device is not a TTY. If you are using mintty, try prefixing the command with 'winpty'

$ winpty docker run -it ubuntu bash
```
