iOSBootstrap
===============
## How to use
clone this repository!
And replace name following command
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
