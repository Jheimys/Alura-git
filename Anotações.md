#1.BRANCH

- Criar uma branch: `git branch nome`
- trocar de branch: `git checkout nome_branch`

#2.MERGE
O Merge une as **branch**.

**_Exemplo:_**
Suponha que temos as branches master e titulo.

Suponha também que terminamos nosso trabalho na **_branch titulo_**, agora devemos juntar o trabalho realizado com a **_branch master_** para isso fazemos os seguintes passos:

- Verifique se estamos na **branch master**
- digite: `git merge titulo` ou `git rebase titulo`

#3.PULL

Junta o trabalho de pessoas diferentes
`git pull local master`

# 4.Revert

Para desfazer um commit use:`git revert +hash_do_commit`

para visualizar o hash do commit bastar fazer um **git log**

# 5.Tag

o comando `git tag 'nome que quiser'` indica que o trabalho está sendo finalizado

**_Ex:_**
` git tag v0.1.0 -m "messagem que quiser"`
