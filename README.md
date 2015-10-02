# Repositório criado para o Curso de Git
Após ter criado o arquivo `teste.txt` e adicionado-o ao repositório local com o comando `git add teste.txt`, ele estará pronto para ser commitado. Uma vez commitado, este arquivo será enviado para o repositório remoto.

### Fazendo o _commit_
Para fazer o commit de `teste.txt` foi utilizado o seguinte comando:

```sh
$ git commit -m "Primeiro commit"
```

### Criando o repositório no Github
Após criado o repositório remoto no Github, é necessário que o repositório local se comunique com esse repositório. Para tanto, deve-se criar um canal de comunicação entre eles através do comando:
```sh
$ git remote add origin https://github.com/thyagoaoliveira/Curso-Git.git
```

### Realizando o primeiro _push_
Criado o canal de comunicação, vamos realizar o envio do arquivo `teste.txt` e de outros arquivos que por ventura estejam no repositório local para o repositório remoto. Então utilizaremos o seguinte comando:

```sh
$ git push origin master
```

Realizados estes comandos, o arquivo `teste.txt` estará tanto no repositório local quanto no repositório remoto.
