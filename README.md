# 🔍 Index

<p align="center">
  <a href="#description">Project Description</a> •
  <a href="#authors">Authors</a> •
  <a href="#license">License</a> •
  <a href="#support">Support</a>
</p>

# Description

EDream is a new social network based on **dreams**!

You will be able to **publish your own dreams** once a day and **share** it with friends! People can react, interact and comment their followers’ posts ♥. You will also be able to see people who have dreamt similar things and discuss its **meaning**! **💭**

✍🏼 You can also **journal** your own sleeping habits. Record your symptoms and feelings and receive personalized **mensual ```statistics``` and professional advices 💤**.

🔐 EDream cares about your **privacy**! Configure your settings and notifications in the ```control panel```.


# Authors

* Patricia Hernando Fernández
* Houssam Eddine Baba Bendermel
* Rodrigo Pérez Ubierna
* Sandra Díaz Aguilar

### License
[![License](https://img.shields.io/badge/License-EPL_1.0-red.svg)](https://opensource.org/licenses/EPL-1.0) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC_BY--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

### Building for source

For production release:

```sh
gulp build --prod
```

Generating pre-built zip archives for distribution:

```sh
gulp build dist --prod
```

### Docker

BeDream is very easy to install and deploy in a Docker container.


```sh
cd bedream
docker build -t <youruser>/bedream:${package.json.version} .
```

This will create the image and pull in the necessary dependencies.
Be sure to swap out `${package.json.version}` with the actual
version of BeDream.

# Support

### FAQ ⁉
[Check our Wiki](https://github.com/RodrigoPerezUbierna/BeDream/wiki) 

### Email us! 💌
> [Patricia](mailto:phf1001@alu.ubu.es) &nbsp;&middot;&nbsp;
> [Houssam](mailto:bhx1005@alu.ubu.es) &nbsp;&middot;&nbsp;
> [Rodrigo](mailto:rpu1002@alu.ubu.es) &nbsp;&middot;&nbsp;
> [Sandra](mailto:sda1003@alu.ubu.es) 
