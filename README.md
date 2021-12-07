# Dados Públicos CNPJ-com-Spark
Esse estudo  consiste em ler, manipular, tratar e salvar um conjunto de dados volumosos utilizando como ferramenta o Spark.

Os dados públicos do CNPJ estão disponíveis para download.

Para facilitar o download o arquivo foi dividido em partes menores.

A RFB informa aos usuários das informações disponibilizadas sobre os dados cadastrais do CNPJ - DADOS ABERTOS, que a partir da divulgação do mês de março de 2021, passará a contar as seguintes novidades:
1. A atualização será mensal;
2. Contará com novo layout;
3. O formato do arquivo deve ter o padrão de carga automática em Bancos de Dados Relacionais (RDBMS – Relational Database Management Systems); usando ponto e vírgula (;) como separador de atributos;
4. Será apresentado o novo campo: Ente Federativo Responsável – EFR , no Layout Principal (Dados Cadastrais): Será preenchido para os casos de Órgãos e Entidades do grupo de Natureza Jurídica 1XX. Para as demais naturezas, esse atributo fica em branco.
5. Foi criado o campo Faixa Etária, no Layout Sócios: Baseada na data de nascimento do CPF de cada sócio, será criado o valor para o campo "Faixa Etária" conforme a regra abaixo:
- 1 para os intervalos entre 0 a 12 anos;
- 2 para os intervalos entre 13 a 20 anos;
- 3 para os intervalos entre 21 a 30 anos;
- 4 para os intervalos entre 31 a 40 anos;
- 5 para os intervalos entre 41 a 50 anos;
- 6 para os intervalos entre 51 a 60 anos;
- 7 para os intervalos entre 61 a 70 anos;
- 8 para os intervalos entre 71 a 80 anos;
- 9 para maiores de 80 anos.
- 0 para não se aplica.

dados: https://www.gov.br/receitafederal/pt-br/assuntos/orientacao-tributaria/cadastros/consultas/dados-publicos-cnpj
