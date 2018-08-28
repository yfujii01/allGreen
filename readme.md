# all green

1年間草を生やすワンライナー

mac専用

```
for i in {1..365} ; do d=`LANG=C date -v-${i}d "+%a %b %d %H:%M:%S %Y -0900"`; git commit --allow-empty -m "YEAH" --date="$d"; done
```
