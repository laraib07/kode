# kode

A simple bash script to add an informative
header at the beginning your codes.

## Screenshots

![preview1](https://raw.githubusercontent.com/laraib07/kode/master/preview1.png)

![preview2](https://raw.githubusercontent.com/laraib07/kode/master/preview2.png)

### created by [Laraib07](https://github.com/laraib07)

## Installation
1.
```bash
apt update && apt upgrade -y
```

2.
```bash
apt install wget
```

3.
```bash
wget https://raw.githubusercontent.com/laraib07/kode/master/setup && chmod u+x setup
```

4.**[optional]**
if you are using this script on termux.
```bash
sed -i "0,/^bin.*/{s//bin=\$PREFIX\/bin/}" setup
```
5.
```bash
./setup
```
or
```bash
bash setup
```
