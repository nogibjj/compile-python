# compile-python
This is a repo for compiling and installing python from scratch

## Compile Python and Create VirtualEnv with It

`sudo apt-get install build-essential gdb lcov libbz2-dev libffi-dev libgdbm-dev liblzma-dev libncurses5-dev libreadline6-dev libsqlite3-dev libssl-dev lzma lzma-dev tk-dev uuid-dev zlib1g-dev`

`wget https://www.python.org/ftp/python/3.10.5/Python-3.10.5.tgz`

` ./configure --enable-optimizations`

`make -j 16`

`make altinstall `

### Create virtualenv and source

`/usr/local/bin/python -m venv ~/.venv`

`vim ~/.bashrc` and add line:  `source ~/.venv/bin/activate`

## References

* [Watch on YouTube](https://www.youtube.com/watch?v=gzh329Yzv8E)
* [Watch on O'Reilly Media](https://lnkd.in/eJQhY-t8)
