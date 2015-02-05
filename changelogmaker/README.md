GCLM GitChangeLogMaker
----------------------

Exemple d'utilisation

```sh
$ cp gclm.sh /path/to/your/gitproject/
$ cd /path/to/your/gitproject/
$ chmod +x gclm.sh
$ ./gclm.sh > CHANGELOG.txt
$ rm gclm.sh
```

* Generate a simple changelog from GIT tags
* Ignore merge commits

```
[last-tag] / YYYY-MM-DD
- commit message
- commit message
- commit message


[previous-tag] / YYYY-MM-DD
- commit message
- commit message
- commit message

```
