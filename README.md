# certtest

Just a little repo to reproduce a bug in Cursive, from about 0.1.64 (the rework of Leiningen integration)

## Usage

Just open in IntelliJ IDEA with Cursive 0.1.64+ installed (tested on IDEA 14 and 15, and
all versions of Cursive to 0.1.70 - same problem)

Error message:
```
Error reading /Users/cmdrdats/storage/ext/certtest/project.clj
resources/Equifax_Secure_Certificate_Authority.pem (No such file or directory)
```

`lein repl` on command lein works.

## License

Not entirely sure this even needs a license - but here goes!

Copyright © 2015 Deon Moolman

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version. Probably doesn't count for the pem file under resources
though - who knows?
