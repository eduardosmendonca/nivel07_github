## GIT

- commit: é a linha do tempo do projeto, cada alteração ao fazer um commit seria o histórico do que foi feito

- git init: inicia um novo repositório no git (o que fala aquo é: esse repositório será versionado pelo git), é a primeira coisa a ser feita

- git config --global user.name "eduardo": para configurar o seu nome no git

- git config --global user.email "eng.eduardomendonca@gmail.com": para configurar o email no git

- git config --list: para saber qual nome e email está configurado

- git add .: adiciona todos os arquivos que sofreram alteração

- git add index.html: adiciona o arquivo index.html que sofreu alteração

- git commit -m "created index.html": serve para escrever o que foi realizado, após fazer o git add, neste exemplo foi criado o arquivo index.html. boa prática é colocar mensagem curta e objetiva

- git log: para ver o log do que ja foi commitado

- git log --oneline: uma forma mais enxuta de ver os logs

- git log -n 3: para ver os ultimos 3 commits, o 3 é um exemplo, pode ser qualquer número

- git status: serve para ver como está o status dos arquivos, se tem modificação ou se está tudo commitado

- depois de alguma coisa alterada e quiser fazer um commit, refaz o processo: git add . > git commit -m "mensagem de alteração"

- no git log tem um (HEAD -> master), isso quer dizer onde está sua aplicação, qual foi seu ultimo commit

- git diff: mostra o que foi alterado em cada arquivo, isso da p comparar o que mudou

- git restore projeto/index.html: esse comando restaura a modificação realizada no arquivo index.html dentro da pasta projeto, fazendo com que ela volte para a ultima versão sem alteração.

- git restore .: restaura todos os arquivos

- git restore --staged .: volta todos os arquivos alterados após fazer um git add(posição unstage) para a posição anterior(working directory)

- git commit --amend -m "change title page index.html": para alterar o que foi escrito no ultimo commit, o que está entre aspas é o que será escrito após executar esse comando

- git reset --soft HEAD~1: este comando desfaz o ultimo commit, resetando ele
