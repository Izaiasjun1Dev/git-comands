# [Info]()
## git log
## git config --list 
## git config --global user.name "username" ``configurações locais``
## git config --global user.email "emailuser" ``configuraçoes locais``
## git status
## git commit  -m "</>"
## git commit  -am "</>" `` Adiciona todos o arquivos alterado modificados.``
## git add -A
## git add 
## git branch 
## git diff ``Detalhamento integral  do que foi feito em todos os arquivos``
## git diff --name-only
# [Revertendo modificações]()
## git revert --no-edit id do commit
## git reset -soft  id do commit ``retorna 1 estado antes do penúltimo commit``
## git reset -mixed id do commit ``Tambem retorna ao penúltimo estado, porém ter de se fazer um novo commit``
## git reset -hard id do commit ``Anula tudo e volta para o penúltimo commit``
## git checkout HEAD -- <NOME DO ARQUIVO> ``Reverte somente as modificações de um único arquivo``

# [Enviar para o remoto]()
## git push -u origin "nome da branch"
```sem aspas```<br>
Ao se enviar documentos para o remoto é importante sempre fazer o comando git pull para sempre fazer commits com todos os repo. iguais
# [Sobre Branch's]()
## git checkout `nome da branch`

# [Deletando branchs]()
## git push origin :teste

# [Atualizando repositorios]()
## git pull origin ``nome da branch``