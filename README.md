# terraform-azure-apache
Script para a criação de uma máquina virtual com acesso externo e apache

Para execução do Script você deve instalar 

[Terraform](https://www.terraform.io/downloads)

[Cli do Azure](https://docs.microsoft.com/pt-br/cli/azure/install-azure-cli)

Após instalado você deve conectar ao seu Azure através do cli do Azure que instalou

[Az Login](https://docs.microsoft.com/pt-br/cli/azure/authenticate-azure-cli)

Após contectar execute os comando abaixo para criação da máquina :

terraform init

terraform plan

terraform apply -auto-approve (para não perguntar)

Após finalizar a criação acesse o [Apache](http://20.107.26.111/)

Não esqueça de destruir a vm para não ser cobrado.

Qualquer dúvida mande mensagem

Vamos que vamos, bora lá