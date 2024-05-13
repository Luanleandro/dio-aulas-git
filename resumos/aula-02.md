# 💻 Desfazendo Alterações no Repositório Local
```git restore --staged```
Com ele é possível alterar mensagens do último commit feito,
É recomendado usar git commit --amend apenas em commits que ainda não foram enviados ao repositório remoto.

```git reset --soft```
Nesse comando podemos Reorganizar Commits e Unificar commits,
ele permite redefinir o ponteiro HEAD para um commit específico, e mantém todos os arquivos de commits posteriores colocando-os na área de preparação.


```git reset --mixed```
Neste comando ele redefinirá o ponteiro HEAD para o commit especificado e irá atualizar a área de preparação deixando 
a vazia e colocando os arquivos que estavam nela como alterações não preparada(unstaged changes)


```git reset --hard```
Esse comando ele redefinirá o ponteiro HEAD a área de preparação(staging area) e o diretório de trabalho ao estado de um commit específico.
nesse modo ele descarta todas as mudanças não commitadas no diretório de trabalho e na área de preparação.