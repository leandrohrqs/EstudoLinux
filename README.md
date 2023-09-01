<h1 align = center>Estudo de Linux</h1>

# O que é "terminal" e  "shell"

- É possível abrir o terminal com `ctrl + alt + t`;

- Terminal é a interface gráfica do shell;

- Assim que o comando é executado no terminal, o shell roda ele;

## Sintaxe

- O comando é escrito da seguinte forma: **`COMANDO -OPÇÕES ARQUIVOS/DIRETÓRIOS`**;

- Caso não haja opções, pode se escrito da seguinte forma: **`COMANDO ARQUIVOS/DIRETÓRIOS`**;

## Estrutura de diretórios do Linux

- bin: Pasta que contem arquivos binários;

- boot: arquivos que auxiliam na inicialização do sistema;

- dev: arquivos que representam todos os dispositivos de entrada do sistema;

- etc: arquivos de configuração;

- home: possui o diretório dos usuários;

- lib: contem arquivos de bibliotecas que são compartilhadas entre outros aplicativos;

- media: responsável pelas pastas dos dispositivos montados no pc, por exemplo: usb;

- opt: possui arquivos das aplicações que não são oficiais do sistema;

- sbin: possui arquivos binários de inicialização do sistema;

- tmp: possui arquivos temporários;

- usr: contém arquivos utilizados apenas no modo leitura;

- var: contém arquivos de log;

## Comando `cd`

- O comando é utilizado para navegar entre pastas

- Para navegar para o diretório `/home/<seu nome de usuário>`, use o seguinte comando:

  - `cd /home/<seu nome de usuário>`


- Para navegar para o diretório `/etc`, use o seguinte comando:

  - `cd /etc`


- Para navegar para o diretório anterior, use o seguinte comando:

  - `cd ..`


- Para navegar para o diretório raiz, use o seguinte comando:

  - `cd /`

- O comando `cd -` volta um diretório e mostra qual era o diretório anterior que você estava trabalhando

### Exemplo:

- Você está no diretório `/` utiliza o `cd var`
após isso utilizar o `cd -` você estará no diretório `/` porém se utilizar novamente o `cd -`, irá para o diretório `var` e não para o anterior do sistema, e sim o que você estava trabalhando

### Exemplo no terminal:

`leandro@leandro-VirtualBox:/$ `

`leandro@leandro-VirtualBox:/$ cd etc`

`leandro@leandro-VirtualBox:etc/$ cd -`

`leandro@leandro-VirtualBox:/$ cd -`

`leandro@leandro-VirtualBox:etc/$ `