# Gerenciamento-de-notas-aluno

Funcionamento do Programa de Gestão de Notas

Este programa foi criado para facilitar o acompanhamento do desempenho de um aluno através do cálculo da média das suas notas e da verificação da sua situação académica.

Fluxo do Programa:

Registo das Notas (Função cadastrar_notas)

Inicia-se um ciclo onde são pedidas as notas ao utilizador

A introdução do valor -1 finaliza o processo de inserção

São validadas apenas notas entre 0 e 10, com alerta para valores inválidos

As notas aceites são armazenadas numa lista

Cálculo da Média (Função calcular_media)

Processa a lista de notas registadas

Soma todas as notas e divide pelo número de elementos

Retorna 0 caso não existam notas registadas

Avaliação do Resultado (Função determinar_situacao)

Compara a média calculada com o valor de aprovação (7.0)

Define "Aprovado" para médias iguais ou superiores a 7.0

Define "Reprovado" para médias inferiores a 7.0

Processamento Principal (Função sistema_notas)

Coordena a sequência de operações:

Chama o registo de notas

Solicita o cálculo da média

Obtém a situação académica

Apresenta os resultados finais com:

Listagem completa das notas

Valor da média calculada

Situação final do aluno

Características Técnicas:

Utiliza estruturas de repetição para entrada de dados

Implementa controlo de valores válidos

Organiza a lógica em funções especializadas

Apresenta resultados de forma clara e organizada

O sistema permite a análise rápida de diferentes cenários académicos, fornecendo uma ferramenta prática para avaliação do desempenho escolar.
