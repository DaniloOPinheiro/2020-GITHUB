# GITHUB
"Este repositório tem como objetivo de armazenar alguns termos do próprio github"

### O QUE É FORK E PARA QUE SER ?

Fork

Explicando com minhas palavras, seria como se fosse uma curva que você faz e pega os arquivos para edita-lós e depois subir no repositório.No Github quando você clica em fork no repositório de alguém, ele pega o repositório completo dessa pessoa e copia para sua conta git, lá você poderá editar esses arquivos e depois devolver a essa pessoa com as suas edições,se a pessoa aceitar, suas alterações também entram no repositório dele.

### O QUE É REPOSITÓRIO E PARA QUE SER ?

Repositório

Repositório é o local aonde ficam os seus arquivos com os commits, branchs, etc. Tudo o que for referente ao git ficará nessa pasta, geralmente chamada .git que é o repositório.

### O QUE É BRANCH E PARA QUE SER ?

Branch

É ramificações que você faz para quando tiver desenvolvendo novas funcionalidades. Quando você inicia o git init você tem um branch padrão que é o master. Quando tiver trabalhando em equipe evite desenvolver no branch master pois poderá dar muitos conflitos. Sempre crie um branch para fazer suas modificações. Por exemplo, você vai desenvolver uma funcionalidade nova para listar os clientes do banco de dados e editar, você poderia criar um novo branch chamado clientes e trabalhar nesse branch para depois jogar ao master.

### O QUE É CLONE E PARA QUE SER ?

Clone

Como a própria palavra diz é um clone. Esse comando serve para você clonar repositórios de uma outra pessoa. No github você pode clonar repositórios digitando no console do seu sistema operacional $ git clone URL_DO_REPOSITORIO

### O QUE É TRACK E PARA QUE SER ?

Track

Creio que aqui você fala da área de untrack files. Quando você inicia o git e logo após isso você começa a editar arquivos nessa pasta que você iniciou o git ou também coloca novas arquivos então ele fica como untrack files (arquivos não trackeados) que é arquivos não "vigiados" pelo git, ou seja, que não estão ainda na pasta .git ou que estão e foram modificados. Quando você da um git add . ou git add arquivo.extensao ele entra para o track files que significa que o git ta olhando mas ainda não está no repositório git. Só depois que você da git commit -m "descrição do commit" é que ele sai dessa área e entra totalmente para o repositório git.
