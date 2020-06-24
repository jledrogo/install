# IT.Rocks Install scripts

Installation scripts to initialize your it.rocks development / running environment

## DISCLAIMER

These scripts are made for systems :

- with apache installed from the standard repositories (or not already installed)
- with no other already installed web server than apache (things may not work)
- with mysql installed from the standard repositories (or not already installed)
- with no php installed : it will add specific repositories to allow several versions of php to be installed together

## What it does

Have a look to the script content before downloading it, and study what it does.
You may run part of these steps manually with your own adaptation, if needed.

## Mint 19.3 "Tricia"

```bash
wget -O install https://raw.githubusercontent.com/itrocks/install/master/mint-lamp/install
bash install
rm install
```
