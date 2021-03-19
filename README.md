ll - lawtexts listing
=====================

What is ll ?
------------

**ll** is an simple web scrapper who extract data from ejustice.just.fgov.be
and expose it in open format.

# How to install ?
------------------
```
$ git clone https://github.com/Open-Law-Be/lawtexts_listing.git
$ python -m virtualenv lawtexts_listing/venv # python == python3
$ cd lawtexts_listing
$ source venv/bin/activate
(venv) $ pip install requirements.txt # pip  == pip3
```

# How to use ?
--------------

- update database
``` (venv)$ python main.py ```

- export in csvfile
``` (venv)$ python ./utils/export.py dt="law" since=01/11/1997 to="01/12/1998" out="../data/myfile.csv" ```
