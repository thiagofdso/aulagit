# aulagit
Repositório para o Projeto 1 do curso Code Education de GIT

## Passo a passo para criação do repositório
1. Criei o repositório remoto aulagit no GitHub
2. Criei a pasta local aulagit
   * mkdir aulagit
3. Iniciei o repositório local
   * cd aulagit
   * git init

## Passo a passo para criação do readme.
1. Criei o arquivo usando o notepad do windows.
   * notepad README.md
2. Adicionei o arquivo na lista de arquivos a serem commitados.
   * git add README.md
3. Fiz o commit do arquivo README.md
   * git commit -m "Adicionando arquivo README.md"
4. Adicionei o repositório remoto
   * git remote add origin git@github.com:thiagofdso/aulagit.git   
4. Enviei o arquivo para o repositório
   * git push origin master

## Passo a passo para criação de tags (releases)
1. Criando primeira tag
   * git tag 0.1.0
   * git push origin master --tags
2. Modificando e criando segunda tag
   * notepad README.md
   * git add README.md
   * git commit -m "Adicionando passo a passo de tags"
   * git push -u origin master
   * git tag 0.1.1
   * git push origin master --tags