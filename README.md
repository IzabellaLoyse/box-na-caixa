# 📦 Box na Caixa

- Mini projeto para o desenvolvimento avançado de SASS

# 💡 Guia de instalação

## 📌 Pré-requesitos

Antes de começar, você precisará ter instalado em sua máquina as seguintes ferramentas:

- [Git](https://git-scm.com)
- [Node.js](https://nodejs.org/en/)

## ⚙️ Instalação

Clone o projeto e acesse a sua pasta

```
# Clone o repositório
$ git clone <projeto>

# Acesse a pasta do projeto no terminal
$ cd pasta
```

Verifique se a instalação do Node.js foi executada corretamente:

```
# Verifica a versão atual do Node.js instalada
$ node -v

# Verifica a versão atual do NPM instalada
$ npm -v
```

Logo após a instalação do Node.js, precisaremos instalar a bliblioteca Node-sass
que irá compilar os arquivos .scss do projeto

- [Node-sass](https://www.npmjs.com/package/node-sass)

```
# Instala globalmente o Node-sass
$ npm install -g node-sass
```

## 🔮 Compilando o CSS do projeto

Após a instalação da biblioteca, iremos compilar o arquivo (.scss/.sass) para que seja gerado o arquivo .css do projeto

```
# Gera o CSS do projeto a partir do arquivo .scss
$ node-sass <input> [output]

# Exemplo
$ node-sass src/style.scss dest/style.css
```

Caso deseja que as alterações feitas nos arquivos .scss sejam compiladas após as modificações.
Devemos seguir o comando `$node-sass --watch` como mostrado no exemplo

```
# Assiste as alterações em um arquivo ou diretório
$ node-sass --watch sass/styles.scss css/styles.css
```
