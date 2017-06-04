## scpf  - Copy folders over ssh like a crazy maniac.
>Copying files from server to client in *nix is often done with scp or sftp.
>
>However most ppl knows that if they are going to download the whole webfolder it would take about 1 hour ++
> 
> This is what i aim to solve with scpf 
> 

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

### Usage ###
``` bash
scpf user@host.tcl /fullPath/To/RemoteDirectory /fullPath/To/LocalDirectory
```
