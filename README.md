# Make initial-ramdisk
Usage:
```
mkinitrd -k [kernel version]
```

> Error codes:

| Exit code	| Cause									|
| ---		| ---									|
| 1		| Important command not found.						|
| 2		| Missing or without read permissions for important file or directory.	|
| 3		| Failed building hook.							|
| 4		| Bad usage of option.							|
| 5		| Failed building ramdisk.						|
