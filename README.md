```
  usage: clonesite.py [-h] [-p PROXIES] [-o FOLDER] [-d MAXDEPTH] [-a ACTION]
                      [-m METHOD] [-x] [-j]
                      url

  Website cloner.

  positional arguments:
    url

  optional arguments:
    -h, --help   show this help message and exit
    -p PROXIES   ip:port
    -o FOLDER    Output folder
    -d MAXDEPTH  Depth of url (default 3)
    -a ACTION    Default action of the found forms
    -m METHOD    Method used in the found forms
    -x           Remove hidden inputs (default False)
    -j           Remove scripts inputs (default False)
 ```

Slightly modified from: https://github.com/tatanus/PHISHING/blob/master/SCRIPTS/clonesite.py
