# jepsen.etcdemo

A Clojure application leveraging [Jepsen](http://jepsen.io) to test [etcd](https://coreos.com/etcd/). Created during [Jepsen Training](http://jepsen.io/services) following the [Jepsen-IO Tutorial](https://github.com/jepsen-io/jepsen/tree/master/doc/tutorial).

## Usage

```
lein run test --username admin --nodes-file ~/nodes
```

## License

Copyright © 2018 Eric P. Wilson

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
