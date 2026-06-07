## Replication Data for "Formulations and solution approaches for the integrated lot-sizing and cutting stock problem applied to lattice slab production"

Description in EN after PT.

=======================================================================================

=======================================================================================

Readme-20260201-pt.txt

=======================

Este arquivo readme foi gerado em 2026-02-01 por Caroline de Arruda Signorini.

======================

INFORMAÇÕES GERAIS

*Título do Conjunto de Dados: Dados de replicação para: "Formulations and solution approaches for the integrated lot-sizing and cutting stock problem applied to lattice slab production"

*Informações do Autor/Investigador Principal

Nome: Caroline de Arruda Signorini

ORCID: 0000-0001-5343-6260

Instituição: Unesp

Email: caroline.signorini@unesp.br


Informações do Autor/Co-investigador Associado

Nome: Silvio Alexandre de Araujo

ORCID: 0000-0002-4762-2048

Instituição: Unesp

Email: silvio.araujo@unesp.br


Informações do Autor/Co-investigador Associado

Nome: Raf Jans

ORCID: 0000-0001-8510-5677

Instituição: HEC Montréal

Email: raf.jans@hec.ca


*Data de coleta dos dados: entre 2017-06-01 e 2018-06-01.

Localização geográfica da coleta de dados: São José do Rio Preto, São Paulo, Brasil

Informações sobre as fontes de financiamento que apoiaram a coleta dos dados: FAPESP, CAPES.

Palavras-chave: parâmetros; número de itens; número de objetos; comprimentos; custos.

===========================

VISÃO GERAL DOS DADOS E ARQUIVOS

*Lista de Arquivos: O conjunto de dados foi utilizado nos testes computationais para avaliar as formulações e estratégias propostas.  Ele está organizado em 27 classes, de acordo com a quantidade de diferentes comprimentos de itens, número de períodos, e o número de diferentes tamanhos para as treliças.  Além disso, 5 instâncias foram geradas para cada classe, resultando no total de 135 instâncias.

Tamanho e formato dos arquivos: os dados foram disponibilizados no formato .txt.

===========================

INFORMAÇÕES METODOLÓGICAS

*Descrição dos métodos utilizados para coleta/geração de dados: o conjunto de dados é composto por instâncias geradas aleatóriamente com base em informações fornecidas pro uma fábrica de pré-moldados.  Conjunto de dados reais não foram disponibilizados pela empresa.

*Informações específicas do instrumento ou software necessárias para interpretar os dados: Os experimentos foram realizados no Microsoft Visual Studio Express 2017 para Windows Desktop para rodar um projeto C++ com a tecnologia IBM Concert: versão 20.1 do CPLEX com as configurações padrão. Bibliotecas: "pch.h", ilcplex/ilocplex.h , ilconcert/iloexpression.h , stdio.h , stdlib.h , math.h , time.h , iostream , cstdlib , conio.h , fstream , vector , string.h , iomanip.  Macro necessária: ILOSTLBEGIN. Configurações do computador utilizado: desktop Dell 64-bit com Intel Core i7-8700 CPU @ 3.20 GHz e 16 GB RAM.

===========================

INFORMAÇÕES ESPECÍFICAS PARA OS DADOS: Cl**Ex++.txt que significa Class ** do Exemplo ++, onde ** varia entre 01 e 27, e ++ varia entre 01 e 05.

Variáveis: Conforme a disposição dos elementos no arquivo, são lidos os seguintes parâmetros:

I = conjunto de item (índice i);

P = conjunto de períodos (índice p);

L = conjunto de treliças de tamanho padrão (índice l);

KC[p] = conjunto de moldes disponíveis no período p;

WC = tamanho dos moldes (objetos);

N = número de seções em um molde;

WS[l] = tamanho da treliça l (objeto);

KS[l] = número de treliças l disponíveis no estoque no início do primeiro período;

w[i] = tamanho do item i;

d[i][p] = demanda para o item i no período p;

sc_mold[p] = custo de setup para um molde no período p;

sc_pat[p] = custo de setup para utilizar um padrão de corte em uma seção do molde no período p;

c_C[p] = custo de produção de uma seção do molde por unidade de comprimento no período p;

c_S[p] = custo de corte de treliça por unidade de comprimento no período p;

pc_S[l][p] = custo de compra por metro de treliça l no período p;

hC[i][p] = custo de estoque para i no período p;

hS[i][p] = custo de estoque para uma treliça de tamanho w[i] no período p.

==========================

INFORMAÇÕES DE COMPARTILHAMENTO/ACESSO

Licenças/restrições aplicadas aos dados: CCBY


=======================================================================================

=======================================================================================

Readme-20260201-en.txt

======================

This README file was generated on 2026-02-01 by Caroline de Arruda Signorini.

======================

GENERAL INFORMATION

Dataset Title: Replication Data for "Formulations and solution approaches for the integrated lot-sizing and cutting stock problem applied to lattice slab production"


Principal Investigator/Author Information

Name: Caroline de Arruda Signorini

ORCID: 0000-0001-5343-6260

Institution: Unesp

Email: caroline.signorini@unesp.br


Co-Investigator/Author Information

Name: Silvio Alexandre de Araujo

ORCID: 0000-0002-4762-2048

Institution: Unesp

Email: silvio.araujo@unesp.br


Co-Investigator/Author Information

Name: Raf Jans

ORCID: 0000-0001-8510-5677

Institution: HEC Montréal

Email: raf.jans@hec.ca



*Data collection date: 2017-06-01 to 2018-06-01

Geographic location of data collection: São José do Rio Preto, São Paulo, Brazil

Funding sources supporting data collection: FAPESP, CAPES.

Keywords: production planning; column generation; precast structures; parameters; number of items; number of objects; lenghts; costs.

===========================

DATA & FILE OVERVIEW

*List of Files: The dataset were used in the computational tests to evaluate the proposed formulations and solution strategies. It is organized into 27 classes, according to the number of different item lengths, the number of periods, and the number of different steel trusses lengths. In addition, 5 instances were generated for each class, resulting in a total of 135 instances.

File sizes and formats: the data is available in .txt files.

===========================

METHODOLOGICAL INFORMATION

*Description of methods used for data collection/generation: the dataset is composed of randomly generated instances based on information provided by a precast company.  Real datasets were not provided by the company.

*Specific instrument or software information needed to interpret the data: The experiments were performed using Microsoft Visual Studio Express 2017 for Windows Desktop to run the IBM Concert Technology in a C++ project and CPLEX version 20.1 with default settings. Libraries: "pch.h", ilcplex/ilocplex.h , ilconcert/iloexpression.h , stdio.h , stdlib.h , math.h , time.h , iostream , cstdlib , conio.h , fstream , vector , string.h , iomanip.  Macro necessary for portability: ILOSTLBEGIN. Computer configuration: Dell 64-bit desktop with Intel Core i7-8700 CPU @ 3.20 GHz and 16 GB RAM.

===========================

DATA-SPECIFIC INFORMATION FOR: Cl**Ex++.txt for Class ** from Example ++, where ** ranges from 01 to 27 and ++ ranges from 01 to 05.

Variables: According to the disposal of the elements in the file there are the following parameters:

I = set of items (index i);

P = set of periods (index p);

L = set of steel trusses with standard lengths (index l);

KC[p] = set of available molds in period p;

WC = length of molds (objects);

N = number of sections in a mold;

WS[l] = length of steel truss l (object);

KS[l] = number of steel trusses l available in stock at the beginning of the first period;

w[i] = length of item i;

d[i][p] = demand of item i in period p;

sc_mold[p] = setup cost of a mold in period p;

sc_pat[p] = setup cost for using a cutting pattern in a mold section in period p;

c_C[p] = mold section production cost per unit length in period p;

c_S[p] = steel truss cutting cost per unit length in period p;

pc_S[l][p] = purchase cost per meter of steel truss l in period p;

hC[i][p] = inventory cost of item i in period p;

hS[i][p] = inventory cost of steel truss of length w[i] in period p.

=======================================================================================

=======================================================================================

SHARING/ACCESS INFORMATION

Licenses/restrictions placed on the data: CCBY

