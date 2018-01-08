# install_gcp
## Playbooks Ansible para a criação de instancias no Google Cloud
Playbook Ansible que faz a criação de um disco, de uma instancia CentOs e atacha o disco na mesma. O exemplo foi usado para a criação de um ambiente MongoDB com maquinas zeradas.

## Dados da Criação:
* Criado por: Anselmo Borges
* Criação: 07.01.2018
* Ultima atualização: 07.01.2018

## Pré-requisitos:
* Ansible instalado
* Credential file criado e baixado para onde será executado o Playbook

## Considerações:
O mesmo foi criado para execução de uma máquina por vez (devido ao disco), caso necessário duplique a criação do disco e insira 2 entradas ou quantas for necessárias no parametro "instance_name". O script tambem faz a conferencia do status do serviço SSH.

## Duvidas:
* anselmoborges@gmail.com
* http://www.anselmodba.com
