# [Info]
## git log
## git config --list 
## git config --global user.name "username"
## git config --global user.email "emailuser"
## git status
## git commit  -m "</>"
## git commit  -am "</>" # Adiciona todos o arquivos alterado modificados.
## git add -A
## git add 
## git branch 
## git diff # Detalhamento integral  do que foi feito em todos os arquivos
## git diff --name-only

# [Revertendo modificações]
## git reset -soft  <id do commit>  # retorna 1 estado antes do penúltimo commit
## git reset -mixed <id do commit> # Tambem retorna ao penúltimo estado, porém ter de se fazer um novo commit
## git reset -hard <id do commit> # Anula tudo e volta para o penúltimo commit
## git checkout HEAD -- <NOME DO ARQUIVO> # Reverte somente as modificações de um único ## arquivo

# [Enviar para o remoto]
## git push -u origin <nome da branch >


# [Sobre Branch's]
## git checkout <nome da branch>
