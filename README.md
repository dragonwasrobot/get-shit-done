# get-shit-done
Script for reducing distractions and improving focus.

```
usage: get-shit-done STATE [TIME]

Configure hosts file to either be in a work or play mode, for an optional timespan.

Parameters:
- STATE: work | play
- TIME: NUMBER[SUFFIX]
SUFFIX may be 's' for seconds (the default), 'm' for minutes, 'h' for hours or 'd' for days.

Example: remove the blacklisting for 30 minutes
$ sudo get-shit-done play 30m
```

Note that you need to run the script as `sudo` since it manipulates `/etc/hosts`.

This is a fork of https://gitlab.esy.fun/yogsototh/get-shit-done, which adds an optional `TIME` argument allowing the user to black or whitelist the configured websites for a limited timestan.
