hcsv
====

A Thor tool to dump Postgresql hstore data to a CSV. Based on [seamusabshere](https://github.com/seamusabshere)'s [hcsv](http://seamusabshere.github.io/2013/09/25/super-easy-way-to-dump-hstore-to-csv/) script.

Installation
-----

Move or symlink hcsv into your PATH.

Usage
--------

Dump an entire table:

    hcsv dump mydb mytable

Dump selected data from a table:

    hcsv dump mydb mytable --cols column1,column2 --hstores hstore1,hstore2 --keys key1,key2 --limit 100

Get help:

    hcsv
    hcsv help
    hcsv help dump
