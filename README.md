# ll - lawtexts listing

### Warning:
Unstable stuff, work in progress. Don't use if you don't know what you do !

### What is ll ?
**ll** is an simple web scrapper who extract data from ejustice.just.fgov.be
and expose it in open format.

### How to install ?
```sh
$ git clone https://github.com/Open-Law-Be/lawtexts_listing.git
$ python -m virtualenv lawtexts_listing/venv
$ cd lawtexts_listing
$ source venv/bin/activate
(venv) $ pip install requirements.txt
```

### How to use ?
- update database
```sh
(venv)$ python ./ll.py update
```

- export in csvfile
```sh
(venv)$ python ./ll.py export dt="law" since=01/11/1997 to="01/12/1998" out="../data/myfile.csv"
```
