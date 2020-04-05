# kode

A simple bash script to add an informative
header at the beginning your codes.

**Note** : currently it support c , c++ 
python and bash.

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

4.
```bash
./setup
```
or
```bash
bash setup
```

5. Move kode to bin folder.

For termux
```bash
mv kode $PREFIX/bin
```

for linux desktop
```bash
sudo mv kode /usr/bin
```

**NOTE** : In linux distro , to change 
author name or text editor ,you need root 
privilege.
In termux you dont need any root privilege.

6. You no longer need setup.
you can delete it with 
```bash
rm -f setup
```

