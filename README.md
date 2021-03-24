# delete-files-older-than-10-days
in linux : delete files older than 10 days

delete :
```
find /tmp -maxdepth 1 -mtime +10 -type f -delete
```
or
```
find /tmp -maxdepth 1 -mtime +10 -type f -exec rm -fv {} \;
```

find only :
```
find /tmp -maxdepth 1 -mtime +10 -type f
```
Just it.
