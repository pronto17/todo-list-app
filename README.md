# ![Logo](leaf.svg) MongoDB README

Whether you are brand new to the tech field, or a seasoned software engineer, you’ll need to know your way around a database — especially for careers in back-end or full-stack development , data science, machine learning, or database administration. MongoDB is a popular NoSQL document-oriented database management system. NoSQL, or “not only SQL”, databases are fast and flexible, scalable, and quick to get started with. They’re becoming increasingly popular in the industry, currently MongoDB is used by companies like Google, Verizon, eBay, and many more!


## Learning MongoDB
[Free MongoDB courses](https://learn.mongodb.com/) - practice your skills with hands on labs and quizzes, and earn MongoDB certification.

## Components

  - `mongod` - The database server.
  - `mongos` - Sharding router.
  - `mongo`  - The database shell (uses interactive javascript).


## Download MongoDB
  - https://www.mongodb.com/try/download/community
  - Using homebrew `brew tap mongodb/brew`
  - Using docker image `docker pull mongo`


## Running

  For command line options invoke:

  ```bash
  $ ./mongod --help
  ```

  To run a single server database:

  ```bash
    $ sudo mkdir -p /data/db
    $ ./mongod
    $
    $ # The mongo javascript shell connects to localhost and test database by default:
    $ ./mongo
    > help
  ```

## Installing Compass

  You can install compass using the `install_compass` script packaged with MongoDB:

  ```bash
    $ ./install_compass
  ```

  This will download the appropriate MongoDB Compass package for your platform
  and install it.

## Drivers

  Client drivers for most programming languages are available at
  https://docs.mongodb.com/manual/applications/drivers/. Use the shell
  (`mongo`) for administrative tasks.

## Bug Reports

  See https://github.com/mongodb/mongo/wiki/Submit-Bug-Reports.

## Packaging

  Packages are created dynamically by the [buildscripts/packager.py](buildscripts/packager.py) script.
  This will generate RPM and Debian packages.

## Learn MongoDB 

  Documentation - https://docs.mongodb.com/manual/
  Developer Center -  https://www.mongodb.com/developer/
  MongoDB University - https://learn.mongodb.com

## Cloud Hosted MongoDB

  https://www.mongodb.com/cloud/atlas

## Forums

  - https://community.mongodb.com

      Technical questions about using MongoDB.

  - https://community.mongodb.com/c/server-dev

      Technical questions about building and developing MongoDB.


## LICENSE

  MongoDB is free and the source is available. Versions released prior to
  October 16, 2018 are published under the AGPL. All versions released after
  October 16, 2018, including patch fixes for prior versions, are published
  under the [Server Side Public License (SSPL) v1](LICENSE-Community.txt).
  See individual files for details.
