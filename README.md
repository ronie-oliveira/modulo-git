# Curso Git e Github

## Comandos Git mais usados

Para alguns usuários, o git pode ter uma curva de apredizado acentuada. Mas você não precisa se preocupar: esta seção te guiará pelos comandos git mais usados no prompt de comando.

Se você preferir uma interface gráfica (GUI) para rodar os comandos, dê uma olhada no nosso tutorial com os melhores clientes GUI para Git.

Dito isto, vamos explorar alguns comandos essenciais do Git e suas funcionalidades.

## Comandos básicos do git

**git init**

Esse comando inicia  um novo repositório Git em um diretório. 
Aqui está como usar o git init de forma básica:

[git init (nome do projeto)]

**git add** 

Esse comando é usado para preparar alterações em arquivos, preparando-os
para o próximo commit:

git add [nome_do_arquivo]

**git commit**

Use esse comando para criar uma mensagem de commit para as alterações,tornando-as 
parte do hisstórico do seu projeto:

[git commit -m ("Adicionar novo recurso")]

**git status**

Esse comando exibe informações importantes sobre as modificaçõs e o status de 
preparação de seus arquivos.

[git status]

**git log**

Em sua forma básica, o git log permite visualizar uma lista cronológica do 
histórico de commits:

[git log]

**git diff**

Esse comando permite comparar as alterações entre o diretório de trabalho
e o commit mais recente. por exemplo, esse uso do git diff identifica as 
diferenças em um arquivo específico:

[git diff (arquivo.txt)]

Para comparar as alterações entre dois commits, use o seguinte:

[git diff (commit1 commit2)]

**git rm**

Esse comando remove arquivos do seu deretório de trabalho e 
prepara a remoção para o próximo commit.

[git rm arquivo1.txt]

**git mv**

Use esse comando para renomear e mover arquivos em seu diretório de  
trabalho. Aqui está o comando do git para renomear e mover arquivos:  

[git mv arquivo1.txt arquivo2.txt] 

para mover um arquivo para um diretório diferente, digite:

[git mv arquivo1.txt nova_pasta/]

## Comandos de branch e merge do Git

**git branch**

Use esse comando para gerenciar ramificações em seu repositório Git.
Aqui está o  uso básico do **git branch** para listar todas as ramificações 
existentes:

[git branch]

Para criar um branch do Git chamada "novo", use:

[git branch novo]

Para renomear um branch do Git, digte este comando:

[git branch -m nome-do-novo-branch]

**git checkout**

Esse comando permite alternar entre ramificações e
retaurar arquivos de diferentes commits.

veja abaixo como usar o git **checkout** para mudar para um 
branch existente:

[git checkout nome_do_branch]

Para descartar alterações em um arquivo específico e
revert-lo para o último commit, use:

[git checkout -- nome_do_arquivo]

**git merge**

Para mesclar um branch de novo ou tópico no branch 
principal do Git, use esse comando. Abaixo está um
exemplo de uso do **merge:**

[git merge nome_do_branch]


































