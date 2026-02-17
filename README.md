# Aprendendo Git

Esse reposítorio tem por objetivo compreender o GIT.

## Estudo

### Part 1

- Verifica versão do git
```sh
git version
```

- Cria repositório

```sh
# crie um diretório
mkdir learning_git

# abra o novo diretório
cd learning_git

# inicialize o repositório
git init

# crie um arquivo README com o título learning_git
echo "# learning_git" >> README.md

# Dizendo pro git "adiciona esse arquivo na minha intenção de envio"
git add README.md

# Na minha intenção de envio registre uma mensagem
git commit -m "first commit"

# Crie a branch main (principal)
git branch -M main

# Registre o endereço da onde o seu repositório será hospedado
git remote add origin git@github.com:<seuUsuario>/learning_git.git

# Envio das modificações e finalização da configuração do upstream
git push -u origin main
```

- Aprenda sobre o comando

```sh
git <comando> --help
```

### Part 2

```sh
# abrir o diretório
cd learning_git/

# verificar o estado atual depois da modificação
git status
```

- Verificação das as diferenças entre: remoto (repositório) e local.

```sh
git diff
```

- Adicionando README.md na área de stage (pré-lançamento)

```sh
git add README.md
```

- Registrando modificação:

```sh
git commit -m "Adicionando descrição no README.md"
```

- Envia para o servidor

```sh
git push
```

### Part 3

### Part 4
