# Criando a chave ssh para o GitHub

 - Criando a chave ssh: ssh-keygen -t ed25519 -C <meu endereço de email>

 - Adicionar a chave no GitHub

 - Estartando o SSH : eval $(ssh-agent -s)

 - Passar a chave para o Agente SSH : ssh-add id_ed25519
Obs: passphrase: Nesse momento será solicitado a senha