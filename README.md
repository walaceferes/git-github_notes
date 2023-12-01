# git-github_notes

#### git stash
Se você não quer commitar suas alterações, mas também não quer perdê-las, você pode guardar as alterações em um "stash". Isso permite que você as recupere mais tarde. Use o seguinte comando:

    git stash

O git stash salva a suas alteraçoes em uma memoria cache, e literalmente as desfaz no arquivo original. Lembrando que os dados não se perdem dessa memoria, mesmo que você mude de branch. Caso precise remotar as alterações que realizou, mude para branch a qual você utilizou o git stash e retome as alterações que salvou nessa cache usando o seguinte comando:

    git stash apply

