# Projeto Lógica

Projeto Lógica 2018.2 - Caixa Eletrônico utilizando model checking

Grupo: Marcus Vinicius, André Matos, Pedro Wanderley, Gustavo Cavalcante


Requisitos para rodar: NuSMV

- Como compilar o modelo:

Dentro do terminal do NuSMV, rodar os comandos:

read_model -i caixaEletronico.smv

flatten_hierarchy 

encode_variables

build_model

- Para rodar as especificaçoes:

check_ctlspec
