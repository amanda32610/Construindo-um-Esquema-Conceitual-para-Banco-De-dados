# Construindo-um-Esquema-Conceitual-para-Banco-De-dados

Sistema de Gestão de Ordens de Serviço - Oficina Mecânica:
Este projeto apresenta um esquema conceitual de banco de dados para um sistema de gerenciamento de ordens de serviço (OS) em uma oficina mecânica. O objetivo é representar as entidades e relacionamentos envolvidos no fluxo de atendimento de clientes, execução de serviços e controle de peças e mão-de-obra.

Contexto:
Clientes levam veículos à oficina para consertos ou revisões.
Os veículos são designados a uma equipe de mecânicos.
Os mecânicos identificam os serviços, estimam o valor com base em peças e mão-de-obra, e preenchem uma OS.
O cliente autoriza a execução e a equipe executa os serviços.

Entidades principais:
Cliente: CPF, nome, endereço.
Veículo: Placa, modelo, ano.
Ordem de Serviço (OS): Número, data de emissão, valor, status, data de conclusão.
Mecânico: Código, nome, endereço, especialidade.
Serviço: Valor (com base em tabela de mão-de-obra).
Peça: Valor.
Mão-de-obra: Valor (referência de cálculo para serviços).
