# scpf #
>Copy folders over ssh like a crazy maniac.

Most *nix users knows that scp is verry good for files, but like every other utility it does 1 file at a time.
However what about a webfolder with 9999 files - that would take an insane amout of time to download.
This is what I aim to solve with scpf.

### Requirements ###
* Bash
* openssh client
* tar

### Installation ###
``` bash
git clone https://bitbucket.org/dm0nk/scpf /tmp/scpf
cp /tmp/scpf/scpf /usr/local/bin/scpf
chmod +x /usr/local/bin/scpf
```
