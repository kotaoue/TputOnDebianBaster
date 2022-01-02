# TputOnDebianBaster
Check the tput behavior on debian:baster.

## Result
```ShellSession
$ docker build -t tput_debian .
$ docker run --name test_tput_debian -it tput_debian /bin/bash
root@CONTAINER-ID:/# tput cols
270
```

## Links
* https://github.com/GoogleContainerTools/skaffold/issues/6254
