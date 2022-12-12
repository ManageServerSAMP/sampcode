# sampcode
Iremos disponibilidar filterscript para adicionar em seu servidor. Ao ligar o servidor você poderá gerênciar ele pelo site e ver as estatisticas de players, basicamente você pode gerenciar tudo do seu servidor.

# Como instalar
- Baixe a versão mais atualizada de nosso sistema, em releases.
- Adicione o .amx do filterscript na pasta filterscripts.
- Adicione essa linha no seu server.cfg:
```
filterscripts manageserver
```. Caso já tenha o filterscripts definido adicione ```manageserver``` na frente dos demais fs.
- É importante que o fs manageserver seja o primeiro FS a ser definido, pois vai carregar primeiro e qualquer erro que tiver nos outros plugins ou fs será detectado, e apontado no log.
