# carbon-credits-setup
Setup dos contêineres docker para a aplicação de créditos de carbono

## Instruções
1. É necessário ter o Docker e Docker Compose instalados
2. Clone esse repositório e seus submodulos: ```git clone --recurse-submodules git@github.com:all-minds/carbon-credits-workspace.git```
6. No fim, a estrutura de diretórios estará dessa forma:

+ carbon-credits-workspace (setup clonado)
	+ GatewayAPI (repositório clonado)
	+ OwnerAPI (repositório clonado)
	+ PropertyAPI (repositório clonado)
	+ sft-eng-front-end

Tendo feito isso, basta ir na raiz do setup clonado e rodar docker compose up.