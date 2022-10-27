# Projeto AWS CloudFormation cfn-Init cfn-Sinal

## Nesse projeto foram criados dois templates no formato yml para criar e atualizar as instâncias em execuçãoe,através do WaitCondition é enviado um sinal para que a isntância em execução possa gerar,executar e atachar uma Policy do IAM criando também uma página da webdo servidor apache com a mensagem"Hello World Apache (HTTPD) atrvés da linha de comando determinada no script.

# Resume: WaitCondition para bloquear o template até receber um sinal do cfnl-signal e anexar uma Creationpolicy

### `/var/log/cloud-init.log`
### `/var/log/cfn-init.log`