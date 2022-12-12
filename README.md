# sampcode
Iremos disponibilidar filterscript para adicionar em seu servidor. Ao ligar o servidor você poderá gerênciar ele pelo site e ver as estatisticas de players, basicamente você pode gerenciar tudo do seu servidor.

# Como instalar
- Baixe a versão mais atualizada de nosso sistema, em releases.
- Adicione o .amx do filterscript na pasta filterscripts.
- Adicione essa linha no seu server.cfg: ```filterscripts manageserver```. Caso já tenha o filterscripts definido adicione ```manageserver``` na frente dos demais fs.
- É importante que o fs manageserver seja o primeiro FS a ser definido, pois vai carregar primeiro e qualquer erro que tiver nos outros plugins ou fs será detectado, e apontado no log.

# Observações
- Ao ligar o servidor, qualquer erro apontado o servidor não será desligado. Caso tenha algum erro apenas o filterscript não será carregado.
- Caso a nossa API esteja offline ou em manutenção o filterscript não vai iniciar, pois precisa enviar um HTTP-GET para nossa API.
- Caso tenha mais de um servidor ligado no mesmo ```SA-MP dedicated server``` ou ```samp-.so``` (APLICATIVO DE INICIAR O SERVIDOR) o filterscript não vai iniciar. Só pode ter no máximo um servidor por porta ligado no mesmo IP.
- Não é preciso adicionar nenhum tipo de plugin ou include no gamemode. Pois o arquivo .amx já vem totalmente compilado.

# ChangeLog
- Pelo site será possível gerenciar configurações de dentro do servidor, até mesmo configurações do AC.
