= download server directory =
* http://stackoverflow.com/questions/273743/using-wget-to-recursively-fetch-a-directory-with-arbitrary-files-in-it
```bash
wget -r -nH --cut-dirs=2 --no-parent --reject="index.html*" http://...
```
