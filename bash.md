## detect version
* https://askubuntu.com/questions/450298/how-to-get-ubuntu-distributions-full-code-name

```bash
```

## detect architecture type
* http://stackoverflow.com/questions/106387/is-it-possible-to-detect-32-bit-vs-64-bit-in-a-bash-script

```bash
MACHINE_TYPE=`uname -m`
if [ ${MACHINE_TYPE} == 'x86_64' ]; then
  # 64-bit stuff here
else
  # 32-bit stuff here
fi
```


