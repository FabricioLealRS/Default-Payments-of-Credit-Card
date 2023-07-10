# Análise de Inadimplência

Este repositório contém análises relacionadas à inadimplência em um contexto financeiro. O objetivo é explorar e compreender os dados relacionados à inadimplência, avaliando seus impactos financeiros positivos e negativos em uma empresa.

Conteúdo
O repositório contém os seguintes elementos:

Code: Esta pasta contém notebooks Jupyter utilizados para realizar as análises. Cada notebook aborda um aspecto específico da inadimplência, incluindo a exploração dos dados, modelagem e avaliação de resultados.

Dados: Nesta pasta estão disponíveis os conjuntos de dados utilizados nas análises. Os dados estão no formato CSV e contêm informações sobre o perfil dos clientes, como ID, limite de crédito, sexo, educação, estado civil, idade e histórico de pagamentos.

Organização do Repositório
O repositório está organizado de forma lógica e intuitiva, facilitando a navegação e o acesso aos diferentes elementos. Os notebooks estão nomeados de acordo com o assunto que abordam e são recomendados a serem seguidos em ordem numérica. Os arquivos de dados estão claramente identificados e prontos para uso. As visualizações são organizadas em pastas específicas, correspondentes aos notebooks relacionados.

Sobre o Conjunto de Dados
O conjunto de dados utilizado nesta análise contém informações sobre pagamentos inadimplentes, fatores demográficos, dados de crédito, histórico de pagamentos e extratos de faturas de clientes de cartões de crédito em Taiwan de abril de 2005 a setembro de 2005. Ele consiste em 25 variáveis que incluem informações como ID do cliente, limite de crédito, sexo, educação, estado civil, idade, status de pagamento e valores de faturas e pagamentos.

As características das features incluídas no conjunto de dados são as seguintes:

ID: ID de cada cliente (inteiro)
LIMIT_BAL: Valor do crédito concedido em dólares de Taiwan (float)
SEX: Gênero (1 = masculino, 2 = feminino) (inteiro)
EDUCATION: Nível de educação (1 = pós-graduação, 2 = universidade, 3 = ensino médio, 0, 4, 5, 6 = outros) (inteiro)
MARRIAGE: Estado civil (0 = outros, 1 = casado, 2 = solteiro, 3 = outros) (inteiro)
AGE: Idade em anos (inteiro)
PAY_0 a PAY_6: Status de pagamento em meses anteriores (-2 = nenhum consumo, -1 = pagamento integral, 0 = uso de crédito rotativo (pagamento mínimo), 1 = atraso no pagamento por um mês, 2 = atraso no pagamento por dois meses, ... 8 = atraso no pagamento por oito meses, 9 = atraso no pagamento por nove meses ou mais) (inteiro)
BILL_AMT1 a BILL_AMT6: Valor da fatura em meses anteriores em dólares de Taiwan (float)
PAY_AMT1 a PAY_AMT6: Valor do pagamento anterior em meses anteriores em dólares de Taiwan (float)
default.payment.next.month: Pagamento inadimplente (1 = sim, 0 = não) (inteiro)
Como Utilizar Este Repositório
Para utilizar este repositório, siga as seguintes etapas:

Clone este repositório em sua máquina local usando o comando git clone https://github.com/seu-usuario/nome-do-repositorio.git.

Acesse a pasta "Code" e abra os notebooks em uma plataforma de desenvolvimento Jupyter Notebook, como o Jupyter Notebook ou o Google Colab.

Siga as instruções em cada notebook para executar as análises e explorar os resultados.

Contribuição
Contribuições para este repositório são bem-vindas! Se você deseja adicionar novas análises, aprimorar as existentes ou fornecer correções, sinta-se à vontade para enviar um pull request.

Licença
Este repositório é distribuído sob a licença MIT. Consulte o arquivo LICENSE para obter mais informações sobre os termos da licença.
