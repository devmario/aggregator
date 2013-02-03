aggregator
==========

mysql active feed aggregator

### Requirement
+ build-essential

```sh
sudo apt-get install build-essential
```

### Submodule
+ folly
+ double-conversion (for folly)

### how to install
```sh
sudo apt-get update
sudo apt-get install git-core
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
