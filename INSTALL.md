# CryptoFeed installation
 
The CryptoFeed library is intended for use by Python developers.

Several ways to get/use CryptoFeed:


* Git - `git clone https://github.com/arashdm2020/CryptoFeed`
* Zipped source code - Download [github.com/arashdm2020/CryptoFeed/archive/master.zip](https://github.com/arashdm2020/CryptoFeed/archive/master.zip)

## Installation with Pip

The safe way to install and upgrade the CryptoFeed library:

    pip install --user --upgrade CryptoFeed

CryptoFeed supports many backends as Redis, ZeroMQ, RabbitMQ, MongoDB, PostgreSQL, Google Cloud and many others.
CryptoFeed is usually used with a subset of the available backends, and installing the dependencies of all backends is not required. 
Thus, to minimize the number of dependencies, the backend dependencies are optional, but easy to install.

See the file [`setup.py`](https://github.com/arashdm2020/CryptoFeed/blob/master/setup.py#L60)
for the exhaustive list of these *extra* dependencies.

* Install all optional dependencies  
  To install CryptoFeed along with all optional dependencies in one bundle:


If you have a problem with the installation/hacking of CryptoFeed, you are welcome to:
* open a new issue: https://github.com/arashdm2020/CryptoFeed/issues/


