# bit-remote-wakeup

A so called 'User Callback Script' for 'Back In Time' to Wake (up) on LAN a remote system before taking the actual backup.

## Warning

Status is WIP and WFM only!

## Install

Copy file either as ```user-callback``` into folder:

```
$HOME/.config/backintime/
```

or

(if you are using the
[```user-callback.multiple-scripts```](https://github.com/bit-team/user-callback/blob/master/user-callback.multiple-scripts)
script)

as
```user-callback.remote_wakeup```
into:


```
$HOME/.config/backintime/user-callback.d/
```


## Note

Back In Time calls **one** script only:

```
$HOME/.config/backintime/user-callback
```

You have to either rename any script or link to it.
