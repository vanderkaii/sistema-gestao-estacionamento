cmake_minimum_required(VERSION 4.1)
project(sistema_gestao_estacionamento C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(sistema_gestao_estacionamento
        avencas.c
        avencas.h
        historico_permanente.c
        historico_permanente.h
        historico_sessao.c
        historico_sessao.h
        infracoes.c
        infracoes.h
        main.c
        motor_de_pesquisa.c
        motor_de_pesquisa.h
        persistencia_bin.c
        titulos_avulsos.c
        titulos_avulsos.h)
