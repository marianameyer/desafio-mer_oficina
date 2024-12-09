#Desafio Modelo Entidade Relacionamento de uma Oficina Mecânica

Este desafio tem como principal objetivo a criação de um MER do zero. O arquivo .png do modelo encontra-se no mesmo repositório.

##1.Objetivo:

Criar o esquema conceitual para o contexto de oficina com base na narrativa fornecida durante as aulas do *Bootcamp* de "Análise de Dados com Power BI" oferecido pela DIO em parceria com a Suzano.

##2.Narrativa:

Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica, onde os Clientes levam veículos para conserto ou para revisões periódicas.
Cada veículo é designado a uma equipe de mecânicos, que identifica os serviços a serem executados e preenche uma OS com data de entrega e os serviços executados.
A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra.
O valor de cada peça também irá compor a OS.
A mesma equipe que faz a avaliação executa os serviços.
Os mecânicos possuem código, nome, endereço e especialidade.
Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.
