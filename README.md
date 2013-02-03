aggregator
==========

mysql active feed aggregator

### Requirement
+ build-essential
+ git-core

### Submodule
+ folly
+ double-conversion (for folly)

### how to install
```sh
sudo apt-get update
sudo apt-get install git-core build-essential
git clone https://github.com/devmario/aggregator.git
cd aggregator
git submodule init
git submodule update
./configure
sudo make & make install
```

### how to run
+ future action : run on service

```sh
aggregator
```

### make package
+ future action : for release version

```sh
sudo make dist
```
