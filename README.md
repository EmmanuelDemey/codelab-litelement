# 📚 💻 Codelab Litlement

## URL

## Description

## Corrections 

### Final project repository

https://github.com/EmmanuelDemey/claat-litelement

### Sub modules  

Add submdule folder and step branch
```sh
git submodule add -b step1 --force https://github.com/EmmanuelDemey/claat-litelement corrections/step1
git submodule sync
git submodule update --init --recursive --remote
# OU
git submodule update --remote
```


### Codelab

To run the support for the codelab

```shell
./generate-labs.sh
npm i http-server
cd docs
http-server
```