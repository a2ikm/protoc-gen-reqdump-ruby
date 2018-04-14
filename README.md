# protoc-gen-reqdump-ruby

This is a ruby port of [yugui/protoc-gen-reqdump](https://github.com/yugui/protoc-gen-reqdump).

# How to setup

```
$ git clone https://github.com/a2ikm/protoc-gen-reqdump-ruby.git
$ cd protoc-gen-reqdump-ruby
$ bundle install
```

# How to use

```
$ protoc -I. --plugin=path/to/protoc-gen-reqdump-ruby/protoc-gen-reqdump --reqdump_out=. target.proto
```
