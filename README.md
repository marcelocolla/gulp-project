# Tecnologias utilizadas
* [node.js] - evented I/O for the backend
* [Gulp] - the streaming build system
* [jQuery] - The Write Less, Do More, JavaScript Library.


# Instalação
##### Você precisa instalar [node.js]:
```sh
$ node -v
$ npm -v
```
##### Você precisa instalar SASS:

*** Sass linux ***
```sh
$ sudo su -c "gem install sass"
```

*** Install Sass ***
```sh
$ gem install sass
$ sudo gem install sass
$ sass -v
```
Obs.: Mais detalhes sobre a instalação do sass pode ser consultado na url http://sass-lang.com/install

Você precisa instalar Gulp globalmente:

```sh
$ npm i -g gulp
```

Clonar aplicação
```sh
$ git clone [git-repo-url] folder-name
$ cd folder-name
$ npm i
$ gulp
```

# Plugins

Plugins utilizados na aplicaçãa:

* Slick Slider - http://kenwheeler.github.io/slick/
* Light Gallery - http://sachinchoolur.github.io/lightGallery/


----
# Development

Antes de mais nada acesse a pasta da sua aplicação. Localize os arquivos 'package.json e gulpfile.js'.

Abra o Terminal favorito e executar esses comandos;

Ao fazer o clone da aplicação ou iniciar ela por a primeira vez é necessário a instalação das suas dependencias:
```sh
$ sudo npm i
```

Após suas dependencias devidamente instaladas podemos começar:
```sh
$ gulp
```

Deixar o gulp ouvindo as alterações na sua aplicação;
```sh
$ gulp watch
```

(optional) Criar um servidor local;
```sh
$ gulp server
```


License
----
MIT


**Free Software, Hell Yeah!**

[node.js]:http://nodejs.org
[jQuery]:http://jquery.com
[Gulp]:http://gulpjs.com
