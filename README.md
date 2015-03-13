#Scripts to handle simulation jobs

* `q2start`: a submit script generator for SGE (see `master` branch)
* `llstart`: a submit script generator for IBM's load leveler (see `master` branch)
* `lstart`: a minimal job manager written in bash for clusters without a queueing system
* `mstart`: a submit script generator for Moab (see lanl branch)

and

* `all`: a script to run a command everywhere
* `findhost`: find hostname matching a pattern
* `mpilist`: find a host which is free
* `showjobs`: summarize running jobs
* `sshscript`: remember working dir after ssh. To make it work add the following line to your `~/.bashrc`
```
[[ -r ~/.mypath ]] && cd $(cat ~/.mypath) && rm -f ~/.mypath
```

##Issues

Report bugs on the [github issues site](https://github.com/junghans/job-tools/issues)

