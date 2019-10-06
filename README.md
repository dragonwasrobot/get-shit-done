# get-shit-done
Script for reducing distractions and improving focus.

```
usage: get-shit-done STATE [TIME]

Configure hosts file to either be in a work or play mode, for an optional timespan.

Parameters:
- STATE: work | play
- TIME: MINUTES

Example: remove the blacklisting for 30 minutes
$ sudo get-shit-done play 30
```

*Notes:*
- The script depends on the [hostess](https://github.com/cbednarski/hostess) tool.
- The script needs to be run as `sudo` as it manipulates `/etc/hosts`.
