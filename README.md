# create free server in dply.co from terminal

**dply started to use reCAPTCHA, rendering this tool useless (for now)**

- Use `dply -h/--help` to get help about the options.
- Use `dply list` to get lists of OS and region codes.

1. creating a free server --
```
dply create -n myserver -o ubuntu-17-04-x64 -r nyc1
```
2. getting info --
```
dply info
```
3. killing current server --
```
dply kill
```

+ `dply.conf` is of this form --
```
[dply]
useragent = XXX
cookie_rack.session = XXX
pub_sshkey = XXX
```
It should contain these informations.
