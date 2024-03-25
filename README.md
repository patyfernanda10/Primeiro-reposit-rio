# Primeiro-reposit-rio
Esse é o meu primeiro repositório

<b>O QUE É GIT?<b/>
O Git é um sistema de controle de versão distribuído, criado por Linus Torvalds em 2005. Diferentemente dos sistemas de controle de versão centralizados, como o SVN, o Git não depende de um servidor central para armazenar o repositório. Cada desenvolvedor possui uma cópia completa do histórico de alterações do projeto em seu próprio sistema. Isso permite um desenvolvimento mais ágil e independente.

<b>PRINCIPAIS FUNÇÕES DO GIT:</b>

<b>Controle de versão:</b> O Git rastreia todas as alterações feitas em um projeto ao longo do tempo. Isso inclui a adição, modificação e exclusão de arquivos. O histórico completo de alterações é armazenado em um repositório Git.

<b>Colaboração:<b/> O Git permite que vários desenvolvedores trabalhem em um projeto simultaneamente, mesmo em partes diferentes do código. As alterações podem ser mescladas de forma eficiente, evitando conflitos sempre que possível.

<b>Ramos (branches):<b/> Os ramos no Git permitem que você crie linhas de desenvolvimento separadas. Isso é útil para trabalhar em novos recursos ou corrigir bugs sem afetar o ramo principal do projeto. Os ramos podem ser mesclados posteriormente, combinando o trabalho de diferentes desenvolvedores.

<b>Reversão de alterações:<b/> Se algo der errado ou se você precisar voltar a uma versão anterior do seu projeto, o Git facilita a reversão de alterações. Você pode desfazer commits individuais ou até mesmo ramificações inteiras, retornando a um estado anterior.

COMANDOS BÁSICOS DO GIT:

Aqui estão alguns dos comandos básicos mais comumente usados no Git:
<b>git init:<b/> Inicializa um novo repositório Git em um diretório vazio;
<b>git clone [URL]:<b/> Cria uma cópia local de um repositório remoto existente;
<b>git add [arquivo]:<b/> Adiciona um arquivo específico à área de preparação (staging area), pronta para ser commitada;
<b>git commit -m "[mensagem]":<b/> Confirma as alterações adicionadas à área de preparação, criando um novo commit no histórico;
<b>git status:<b/> Mostra o estado atual do repositório, incluindo arquivos modificados, adicionados ou excluídos;
<b>git pull:<b/> Baixa as alterações mais recentes de um repositório remoto e mescla-as com o ramo atual;
<b>git push:<b/> Envia os commits locais para um repositório remoto, atualizando-o com as alterações mais recentes;
<b>git branch:<b/> Lista os ramos existentes no repositório.

<b>O QUE É GITHUB?</b>
O GitHub é uma plataforma baseada na web que utiliza o sistema de controle de versão Git. Ele permite que indivíduos e equipes trabalhem juntos em projetos, acompanhem as mudanças feitas no código-fonte, revertam para versões anteriores e gerenciem diferentes versões do software.

<b>PRINCIPAIS FUNÇÕES DO GITHUB:</b>
A função do GitHub é armazenar projetos de código aberto, ou seja, que podem ser editados por outros programadores em um trabalho coletivo.
O GitHub garante correções, atualizações e melhorias em novas versões, sendo possível acessar as anteriores e ver quais edições foram feitas, quando e por qual usuário.

<b>COMO SUBIR SEU PROJETO NO GITHUB</b>
O passo a passo abaixo pode ser feito no Prompt de comando do Windows*, PowerShell do Windows*, no Terminal do Visual Studio* e do Visual Studio Code*.

No terminal ou prompt digitar a sequência de comandos abaixo e ao lado explico o que faz cada um.

1- git init - para criar um diretório .git na pasta do projeto onde deseja subir;

2- git status - aqui nenhum arquivo e pasta estão adicionados tanto que aparecerá uma lista em vermelho;

3- git add . - todos os arquivos e pastas adicionados (se for para subir um arquivo é só digitar no terminal git add nome-file.extensão);

4- git satus - depois de executado o comando acima, mudará a cor de vermelho para verde;

5- git commit -m "mensagem" - colocar a mensagem (essas mensagens irão aparecer quando for subir o projeto num todo e/ou quando for realizar alterações) e verificar no repositório se está subindo o projeto;

6- Aqui você cria o repositório vazio no seu perfil do GitHub onde deve sempre colocar um resumo do que faz o seu projeto (além de boas práticas, para você mesmo não esquecer o que faz e lembre-se que empresas irão observar seus projetos documentados);

7- Depois é só copiar esse bloco de comandos que aparecerá na parte de baixo (são dois blocos de comandos, copiar o segundo) no seu recém-criado repositório e seu projeto estará no repositório do GitHub.

 git remote add origin linkdorepositório.git

 git branch -M main

 git push -u origin main

Obs: o primeiro comando do bloco acima muda de acordo com o link que é gerado pelo GitHub. Aparecerá quando logo a seguir quando criou o repositório vazio. É só copiar e colar para o terminal e executar. Daí o repositório estará com os arquivos e pastas no seu repositório no GitHub.

* Quando for logar sua conta Microsoft, ou outra qualquer, no VS deverá sincronizar a sua conta do GitHub e no VS Code além de sincronizar, deve também ter as extensões de Git instalado. Não se esqueça, também, que o aplicativo Git deve estar instalado na máquina e ainda o Windows reconhecer na parte de variáveis de ambientes do sistema para que os comandos Git funcionem em qualquer pasta.
