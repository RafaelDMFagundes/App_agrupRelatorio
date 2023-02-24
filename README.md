# App_agrupRelatorio

Para começar a descrição do projeto, lembro que essa demando foi posto para criar ALV em ABAP. Depois de realizado, estou criando também em FIORI, construindo a modelagem dos dados em CDS View.

O propósito deste documento é descrever os requisitos para o desenvolvimento de um relatório e criação de documentos no SAP, com a intenção de atender aos processos de: 
Agrupamento de faturas.

DESCRIÇÃO DO PROCESSO:
Atualmente as faturas de franquias no *** ao entrarem no sistema geram um aviso de débito. 
No final de cada período estes avisos de débito são agrupados, de forma automática, gerando uma única fatura com vencimento e condição de pagamento pré-estabelecidos.

No SAP serão criadas faturas através da interface. O objetivo será selecionar estas faturas e realizar uma compensação destas gerando uma única fatura. 
Os valores de busca, bem como os novos valores para o novo documento a ser criado serão informados na tela de seleção.


O programa deve selecionar as partidas em aberto e os campos adicionais de chave de referência e letra de cambio de acordo com as tabelas abaixo.

OBS: Falta alguns detalhes para finalizar esse projeto.


