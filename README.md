Tux-FreeHost Panel
==================

Documentation
-------------
There is no *complete* documentation yet. However,
you can [follow](https://twitter.com/tuxfreehost) the project on twitter,
read [the blog](http://tux-fh.net/posts.html), post in
[the forum](http://forum.tux-fh.net), or come chat with us on #TuxFH @ Freenode.

Installation/management scripts
-------------------------------
You can use the installation/management [scripts](https://gist.github.com/Edelwin/7857978) which uses python3, or the
[python2 one](https://gist.github.com/NyanKiyoshi/9028494)

Manual installation/management
------------------------------
1. Installation
⋅⋅* Clonning the git repository
⋅⋅ ```bash
git clone https://github.com/Tux-FreeHost/tfhpanel.git
```
⋅⋅* Installing the dependencies for the tfhpanel
⋅⋅ ```bash
python setup.py develop
```
⋅⋅* Initialize the DB and add the default data
⋅⋅ ```bash
python tfh.py -c development.ini initdb
```

2. Management
⋅⋅* Run the developement server
⋅⋅```bash
pserve development.ini
```
