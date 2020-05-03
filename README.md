# kode

A simple bash script to add an informative
header at the beginning your codes.

**Supported languages :**
bash, c, c++, c#, css, java,
javascript, perl, php, python,
ruby, rust, swift, typescript.


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
wget https://raw.githubusercontent.com/laraib07    /kode/master/kode && chmod 755 kode
```
or

```bash
curl -O  https://raw.githubusercontent.com/lara    ib07/kode/master/kode && chmod 755 kode
```

4. Move kode to bin folder.

For termux
```bash
mv kode $PREFIX/bin
```

for linux desktop
```bash
sudo mv kode /usr/bin
```

5. To set author name and editor
**Necessary**

```bash
kode -a -e
```
