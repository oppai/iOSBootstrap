iOSBootstrap [![Circle CI](https://circleci.com/gh/oppai/iOSBootstrap.svg?style=svg)](https://circleci.com/gh/oppai/iOSBootstrap)
===============
## How to use
Clone this repository! And replace name following command
```
grep -rl 'iOSBootstrap' * | xargs sed -e -i "s/iOSBootstrap/MyProject/g"
```

## install
```
bundle install --path ./bundle
bundle exec pod install
```

## test
```
./script/run_test.sh
```
