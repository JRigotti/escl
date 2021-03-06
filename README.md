# escl
![](https://img.shields.io/npm/v/escl.svg)

A high-level command line wrapper around the
[elasticsearch.js](https://github.com/elastic/elasticsearch-js) client.

[![asciicast](https://asciinema.org/a/Y0tbnAEyuOy68o0uCpB4zgXtQ.png)](https://asciinema.org/a/Y0tbnAEyuOy68o0uCpB4zgXtQ)

## Installation
``` shell
npm install -g escl
```

## Requirements
[Make sure you have elasticsearch up and
running](https://www.elastic.co/guide/en/elasticsearch/reference/current/getting-started.html).

## Getting started
[Setup your client](docs/setting-up-client.md) and if everything is fine the
following command in your terminal

``` shell
$ escl _info
```

should output a response in a similar format as below:

```
{
  "name": "XXXXX",
  "cluster_name": "elasticsearch",
  "cluster_uuid": "aq2tteqwbddy_8s9dnd",
  "version": {
    "number": "6.3.0",
    "build_flavor": "default",
    "build_type": "zip",
    "build_hash": "424e937",
    "build_date": "2018-06-11T23:38:03.357887Z",
    "build_snapshot": false,
    "lucene_version": "7.3.1",
    "minimum_wire_compatibility_version": "5.6.0",
    "minimum_index_compatibility_version": "5.0.0"
  },
  "tagline": "You Know, for Search"
}
```

Check the [examples folder](docs/examples/) for more commands.

## Documentation
- [Which commands can I execute](docs/commands.md)
- [Passing options to commands](docs/options.md)
- [Customize your escl with .esclrc file](docs/esclrc.md)

## Disclaimer
This is side project I've built in my spare time with the purpose of helping me
out with repetitive tasks I use to perform in Elasticsearch. It's not encouraged
and advised to be used in a production environment and/or where sensitive data
is being handled.

## Contributing
Contributions and improvements in accord with the project philosophy are gladly
accepted. Make sure to check the [contributing](CONTRIBUTING.md) guide for
more info.
