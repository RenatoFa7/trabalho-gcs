<Nome do Projeto>
=================
Plano de Gerenciamento de Configuração
======================================
Versão &lt;1.0&gt;
------------------

Histórico de Versões
--------------------

|Data                |Versão       |Descrição               |Autor          |
|--------------------|-------------|------------------------|---------------|
|_&lt;03/12/2013&gt;_|_&lt;1.0&gt;_|_&lt;Versão inicial&gt;_|_&lt;Renato&gt;_|
|_&lt;dd/mm/aaaa&gt;_|_&lt;1.1&gt;_|_&lt;Criação do controle de mudanças&gt;_  |_&lt;DOmingos Neto&gt;_|



1. Introdução
==============

   O AGESC é um sistema de gestão de materiais. Com a utilização da metodologia workflow e configuração dos setores de consumo e armazenamento dos produtos, é possível garantir a rastreabilidade de cada item em toda a 
sua movimentação. Através dos parâmetros de consumo, tempo de entrega e efetivação e do processo de compras, é possível planejar as aquisições de forma mais assertiva, reduzindo os custos operacionais e de Aquisição.


1.1 Finalidade
---------------
Fazer com que o hospital possa ter controle das movimentações dos diversos tipos ,Solicitação de compras, Autorização de entrega, Autorização de recebimento Conferência , Estocagem, Autorização de abastecimento,Expedição e transporte,  Dispensação, Inventário ,Interação medicamentosa, emissões de relatórios, Receita Avulsa.


1.2 Escopo
----------
Este Plano de Gerenciamento de Configuração é destinado para todos os integrantes da equipe responsável pelo desenvolvimento do sistema AGESC na disciplina de Gestão de Configuração de Software, e abrange todo o controle e gerenciamento da configuração do projeto AGESC  – Sistema de Gestão de Materiais Hospitalar. 

1.3 Definições, Acrônimos e Abreviações
---------------------------------------

|Termo               |Significado                          
|--------------------|-------------|
|   SCRUM            |É um processo ágil que permite manter o foco na entrega do maior valor de negócio, no menor tempo possível.|
|GC|Gerência de Configuração|
|Baseline  |  Conjunto de itens de configuração que conseguiram um estado comprovado de estabilidade.                      |
|CM  |Controle de Mudanças.                        |
|Artefatos  |São documentos, componentes de software (inclusive código-fonte) e qualquer informação necessária para a execução de uma atividade ou produzida por esta dentro de um processo de software.                        |
|Realeses |É uma versão de um sistema que é distribuída para o consumidor. Porém, um release não se restringe apenas ao código-fonte de um sistema, pode ser um arquivo de configuração, arquivos de dados, manual do usuário, instalador do programa dentre outros (SOMMERVILLE, 2006);     | 
1.4 Referências
---------------
   Template de Plano de Gerenciamento de Configuração.
 Plano de Gerenciamento de Configuração  do Projeto - Agesc - Sistema de Gestão de Materiais Hospitalar, Versão 1.0.
Cronograma - Agesc - Sistema de Gestão de Materiais Hospitalar.

1.5 Visão Geral
---------------
|Sessão               |Descrição                          
|--------------------|-------------|
|2|São relacionados os papéis, as responsabilidades das atividades e as ferramentas dentro da GC.                |
|3|É apresentado como serão criadas e controladas as Baselines.|
|4|São abordados os detalhes sobre quando o Plano de Gerenciamento de Configuração deve ser atualizado.|
|5|Descreve as ferramentas de software, o pessoal e o treinamento necessários para implementar as atividades de CM especificadas.|
|6|Descreve de que forma o software desenvolvido fora do ambiente do projeto será incorporado.|


2. Gerenciamento de Configuração de Software
============================================

2.1 Organização, Responsabilidades e Interfaces
---------------------------------------------
|Papéis              |Responsável  | Responsabilidade                      
|--------------------|-------------|---------------|
|Gerente de Configuração|Antonio Renato|Estabelecer Políticas de GC Escrever Plano de GC Configurar Ambiente de GC Criar Espaços de Trabalho de Integração Criar Baselines Promover Baselines
|CM|Domingos Neto|Estabelecer Processo de Controle de Mudanças Revisar Solicitação de Mudança
|Desenvolvedor|Antonio Renato Domingos Neto|Seguir os padrões e procedimentos definidos no Plano de Gerência de Configuração
|Todos os Papéis|Antonio Renato Domingos Neto|Enviar Solicitação de Mudança Atualizar Solicitação de Mudança


2.2 Ferramentas, Ambiente e Infra-estrutura
-------------------------------------------------
|Ferramenta          |Tipo         | Descrição     | Versão                     
|--------------------|-------------|---------------|---------
|Google Code||É um projeto de hospedagem de desenvolvimento de softwares criado pelo Google que fornece sistema de controle de versão usando Subversion. Localizado através do Endereço: “https://code.google.com/p/agesc/”|
|Subversion|Controle de Versão.|Sistema de controle de versão.|1.4.6
|TortoiseSVN|Acesso ao repositório|Cliente para o Subversion integrado ao Windows. |1.4.8.121
--

|Tipo              |Ferramenta  | Versão                      
|--------------------|-------------|---------------|
|Sistema Operacional (Desenvolvimento)|Windows 7|2009
|Cronograma|Microsoft Office Project|2013
|Antvírus|Avira|2013
|Controle de Versão|Subversion|1.7
|Plataforma de Desenvolvimento|Ferramenta: Delphi.|2013
|Banco de Dados|Oracle|11 G
|Relatórios|Fast Report|4.0
--
|Ambiente            | Descrição  | Transição                      
|--------------------|-------------|---------------|
|Desenvolvimento|É o ambiente que servirá para o desenvolvimento do Sistema.|O componente atingirá a maturidade quando os requisitos forem supridos e testados pelos desenvolvedores através dos testes unitários.
|Integração|É o ambiente que servirá para os testes de integração.|Quando a comunicação entre os módulos atinge o um estagio satisfatório de funcionamento, ou seja, não deverão existir erros de integração entre os subsistemas.
|Banco de Dados|É o ambiente onde conterá o Banco de dados.|Ambiente que conterá o Banco de dados do sistema.  
--
|Qtd          |Ambientes         | Configuração Hardware|Configuração Hardware                     
|--------------------|-------------|---------------|---------
|3|Desenvolvedor|Processador: Core I3 Memória RAM: 4 GB Hard Disk: 360 GB IP 192.168.0.2 |Windows 7 Professional ,Delphi XE 2013,GIT, TortoiseSVN,Office 2007 ,Cliente Oracle  11 G,Fast Report 4.0,Avira 2013'
|1|Integração|Processador: Core I3 Memória RAM: 4 GB Hard Disk:  360 GB IP 192.168.0.2|Windows 7 Professional ,Delphi XE 2013,GIT, TortoiseSVN,Office 2007 ,Cliente Oracle  11 G,Fast Report 4.0,Avira 2013'
|1|Banco de Dados|Processador: Core I3 Memória RAM: 4 RAM Hard Disk:  360 GB IP 192.168.0.2|Windows 7 Professional ,Delphi XE 2013
 

3. O Programa de Gerenciamento de Configuração
==============================================

3.1 Identificação da Configuração
---------------------------------
### 3.1.1 Métodos de Identificação
--
|Sessão               |Descrição                          
|--------------------|-------------|
|TAB|Termo de Abertura|
|PPR|Plano de Projeto|
|CRN|Cronograma|
|MTD|Metodologia|
|RAT|Relatório de Status|
|ARN|Atas de Reuniões|
|DVS|Documento de Visão|
|ECU|Especificação de Caso de Uso|
|MCU|Modelo de Caso de Uso|
|GLS|Glossário|
|MIM|Manual de Implantação|
|ARQ|Documento de Arquitetura|
|MAP|Modelo de Análise e Projetos|
|PBD|Modelo de Banco de Dados|
|MIN|Manual de Instalação (implantação)|
|PLT|Plano de Testes|
|PRT|Projeto de Testes|
|PET|Planilha de Execução de Testes|
|PGC|Plano de Gerência de Configuração|
|NRT|Notas de Release|
|RSM|Registro das Solicitações de Mudanças|
|RIP|Relatório Individual de atuação no Projeto|
|PPT|Apresentação PowerPoint do Projeto|
|FRM|Artefatos (Código fonte) camada onde ficam as telas do sistema.|
|RPT|Artefatos (Código fonte) camada onde ficam os relatórios gerados pelo sistema|
|BLD|Builds do sistema|
|RLS|Reliases do Sistema|


### 3.1.2 Itens de Configuração


 Item (ou Tipo de Item)  | Responsável na equipe| Inclusão em Baseline |
|----------------------------------------|-----------------------------|----------------------|
|Gerente de Configuração|Renato|Estabelecer Políticas de GC Escrever Plano de GC Configurar Ambiente de GC Criar Espaços de Trabalho de Integração Criar Baselines Promover Baselines
|CM|Domingos Neto|Estabelecer Processo de Controle de Mudanças Revisar Solicitação de Mudança
| Todos os Papéis| Antonio Renato Domingos Neto |Enviar Solicitação de Mudança Atualizar Solicitação de Mudança



### 3.1.3 Baselines do Projeto

_[As baselines funcionam como um padrão oficial no qual os trabalhos subseqüentes são baseados. Somente mudanças autorizadas podem ser efetuadas nas baselines._
_Descreva em que pontos do ciclo de vida do projeto ou produto as baselines devem ser estabelecidas. As baselines mais comuns devem ser definidas ao final de cada uma das fases de Iniciação, Elaboração, Construção e Transição. Elas também podem ser geradas no final de iterações ocorridas dentro das várias fases ou com freqüência ainda maior._
_Descreva quem autoriza uma baseline e o que ela contém.]_

### 3.1.4 Estrutura do Repositório de Versões
_[Descreva a organização de diretórios do seu repositório e que itens/arquivos devem ser armazenados em cada diretório.]_

3.2 Controle de Configuração e Mudança
--------------------------------------

### 3.2.1 Processamento e Aprovação de Solicitações de Mudança
_[Descreva o processo pelo qual os problemas e as mudanças são submetidos, revisados e dispostos. Inclua como funciona a transição de estados de uma solicitação de mudança]_

### 3.2.2 Comitê de Controle de Mudança (CCB)
_[Descreva a participação e os procedimentos para processar solicitações e aprovações de mudança a serem seguidos pelo CCB. Informe quem são os membros do CCB e suas responsabilidades.]_



4. Padrões e Procedimentos
==========================
_[Descreva os padrões e procedimentos que devem ser seguidos no projeto. Crie subseções se achar necessário, para organizá-los melhor.]_



5. Treinamento e Recursos
=========================
_[Descreva as ferramentas de software, o pessoal e o treinamento necessários para implementar as atividades de CM especificadas.]_



6. Auditorias de Configuração
=============================
_[Descreva o cronograma das auditorias de configuração e o que será verificado. Informe também como serão reportados os problemas encontrados e onde sera feito o acompanhamento dos itens corretivos.]_
