# kode

A simple bash script to 

* Add a shebang (if required)
* Add an info header
* Add code template (can be toggled) 
* Make file executable
* Update last modified column of info header


**Supported languages :**
bash, c, c++, c#, css, java,
javascript, perl, php, python,
ruby, rust, swift, typescript.

![preview.gif](https://raw.githubusercontent.com/laraib07/kode/master/preview/preview2.gif)

### Author [Laraib07](https://github.com/laraib07) and [GetOutOfMyBakery](https://github.com/GetOutOfMyBakery)

## Installation
1.
```bash
apt update && apt upgrade -y
```

2.
```bash
apt install git
```

3. Clone this repo.
```bash
git clone https://github.com/laraib07/kode.git
```

4. Give kode necessary permission.

```bash
chmod 755 kode
```

5. Create a symlink of kode to bin folder.

For termux
```bash
ln -s $PWD/kode $PREFIX/bin/kode
```

for linux desktop
```bash
sudo ln -s $PWD/kode /usr/bin/kode
```

7. To set author name 

**Necessary**

```bash
kode -a name
```

8. I keep imoroving this script. So to update go to kode folder
and
```bash
git pull
```

## Screenshots

![preview1](https://raw.githubusercontent.com/laraib07/kode/master/preview/preview1.png)

![preview2](https://raw.githubusercontent.com/laraib07/kode/master/preview/preview2.png)

