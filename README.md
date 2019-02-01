vr
==========================

Script for vimmers.
Fetches all files in current directory matches
your query (space separated) and build regex,
and opens all matching files.

Installation
==========================

Make sure you are using POSIX compliant OS and
the `/usr/bin/local` allows your usename to access
to it.

```
$./installer
```

Usage
=========================

```
$vr [word1] [wprd2] [word3] ...
```

Basically, the situation you are on the vim editor is
taken into account. Such that:

If you are developing on rails project,

```
:! vr app contro par
```

as a result, it opens

```
./app/controller/parts_controller.rb
./app/controller/party_controller.rb
```


