Noobot Alpha ver 1.0

BOT Criado por Pedro Micheletto Palhares pelo Watson Conversation com o Intuito
de auxiliar os novos funcionários em seu primeiro dia na IBM.

Upando o APP no Bluemix:

Conecte e efetue login no Bluemix.

cf api https://api.ng.bluemix.net
cf login -u ppalha@br.ibm.com -o "BMX Clan" -s BMX_Workspace
Se você estiver usando um ID federado, use a opção -sso.

cf login -u ppalha@br.ibm.com -o "BMX Clan" -s BMX_Workspace -sso
Em your_new_directory, reimplemente seu app no Bluemix usando o comando cf push. Para obter mais informações sobre o comando cf push, veja Fazendo upload de seu aplicativo.

cf push
