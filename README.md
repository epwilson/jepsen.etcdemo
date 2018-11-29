# jepsen.etcdemo

A Clojure application leveraging [Jepsen](http://jepsen.io) to test [etcd](https://coreos.com/etcd/). Created during [Jepsen Training](http://jepsen.io/services) following the [Jepsen-IO Tutorial](https://github.com/jepsen-io/jepsen/blob/3649a5ec2c9c293a87e3e6d4fa17b16954eb4246/doc/tutorial/index.md).

## Usage

Assuming the file `~/nodes` exists with a list of hosts (one per line) to test the database (etcd) on and password-free SSH is configured for the username `admin` across those hosts:

```
lein run test --username admin --nodes-file ~/nodes --concurrency 4n --time-limit 60
```

To start a web server that will display test results:

```
lein run serve
```

## License

Copyright © 2018 Eric P. Wilson

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
