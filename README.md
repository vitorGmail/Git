# curso-git

### _Principais comando aprendidos:_
-----------------------------------------------------------------------------------------------------------------
para saber o status atual do repositorio local                      --> git status
adiciona todos os arquivos pendentes à staging area                 --> git add .
confirma/salva as alterações do projeto                             --> git commit -m "Mensagem"
limpa o terminal git                                                --> clear
cria uma nova branch                                                --> git branch 'nomeDaBranch'
cria e faz a troca para uma branch nova                             --> git checkout -b 'nomeDaBranch'
deleta uma branch                                                   --> git branch -d 'nomeDaBranch'
envia o projeto pro servidor                                        --> git push
pega arquivos do servidor e faz um merge automatico na branch atual --> git pull
-----------------------------------------------------------------------------------------------------------------

### _Diferença entre git pull e git fech:_
-----------------------------------------------------------------------------------------------------------------
O git fetch  atualiza as referências locais com relações às remotas, mas não faz o merge com o branch local.
Enquanto o git pull equivale a fazer git fetch (download dos ultimos commits) + git merge (incorpora os commits com o branch local).
-----------------------------------------------------------------------------------------------------------------

### _Git Stash, rebase e share pic:_
-----------------------------------------------------------------------------------------------------------------
GIT STASH: arquiva alterações que você fez na cópia de trabalho durante um determinado período, para que você possa trabalhar em outra coisa, depois voltar e fazer a reaplicação mais tarde.

GIT REBASE: assim como git merge, tem a função de "mesclar" as alterações de uma branch com outra, porém o rebase tem recursos poderosos para reescrever o histórico.

SHARE PIC ou CHERRY-PICKING (?): permite ao usuário escolher os commits que deseja mandar à uma branch. Assim, ele pode analisar os commits em outra branch do repositório e escolher aquelas que são úteis para ir para sua branch.