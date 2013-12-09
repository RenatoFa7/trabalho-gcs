<<<<<<< HEAD
testeee
=======
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
|_&lt;30/11/2013&gt;_|_&lt;1.1&gt;_|_&lt;Criação do controle de mudanças&gt;_  |_&lt;Domingos Neto&gt;_|



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

As baselines serão definidas em três fases.

|Fases               |Itens de Configuração da Baseline                          
|--------------------|-------------|
|Planejamento|Documentação (Artefatos do projeto)|
|Arquitetura o projeto|Código fonte contendo apenas a arquitetura do Projeto ,Camadas Garantia transacional|
|Release|Fontes do sistema pronto|


### 3.1.4 Estrutura do Repositório de Versões
|Diretório| SubDiretório |Artefatos
|---------|--------------|---------
|Documentos|Gerência de Confifuração|Modelo do Plano de Gerenciamento de configuração, Notas de Releases e Arquivo de aprovação dos documentos
           | Gerência de Projetos| Documento de Visão, Termo de Abertura, Plano de Projeto, Cronograma, Relatório de Status, Atas de reuniões e Arquivos de aprovação dos documentos
           | Requisitos| Especificação de Caso de Uso, Modelo de Caso de Uso, Glossário e Arquivos de aprovação dos documentos.
           | Análise e Projeto|  Manual de Implantação, Documento de Arquitetura, Modelo de Banco de Dados, Modelo de Análise e Projetos e Arquivos de aprovação dos documentos
 


3.2 Controle de Configuração e Mudança
--------------------------------------
### 3.2.1 Processamento e Aprovação de Solicitações de Mudança
As solicitações de mudanças das Baselines serão realizadas através da ferramenta Issues disponibilizada pela Google através do endereço do repositório na qual terá o seguinte fluxo.

**Status dos Issues**

|Atividade| Descrição |Artefatos
|---------|--------------|---------
|Aberto| Criação da solicitação| Todos
|Em Analise| Analise da solicitação| Analista de sistemas 
|Analisado |Aguardando desenvolvimento | Analista de sistemas
|Em desenvolvimento |Solicitação sendo desenvolvida | Desenvolvedor
|Desenvolvido |Aguardando teste | Desenvolvedor
|Em testes |Solicitação em teste| Testador
|Testado com erro |Aguardando desenvolvimento | Testador
|Testado sem erro |Solicitação esperando finalização pelo analista |Testador 
|Finalizado |Solicitação finalizada |Analista

### 3.2.2 Comitê de Controle de Mudança (CCB)
O comitê de Controle de Mudanças (CCM) será formado por Analista de sistemas e Gerente de Projetos


4. Padrões e Procedimentos
==========================
N/A



5. Treinamento e Recursos
=========================
Descrição dos treinamentos efetuados para os integrantes do Grupo.

|Treinamento |Objetivo |Público Alvo
|---------|--------------|---------
|Repositório| Treinamento ensina como acessar o repositório através de uma máquina cliente, como dar os comandos principais do repositório,  como incluir novos itens dentro do repositório e também como remover do mesmo.| Toda a equipe


6. Auditorias de Configuração
=============================
|Objetivos |Avaliar como se encontra a baseline em termos físicos e funcionais
|---------| ---------------|
Procedimentos| 1.	Identificar a baseline a ser auditada; 2.	Confirmar que todos os itens de configuração presentes na baseline foram previstos no Plano de Gerência de Configuração; 3.	Preparar um checklist para auditoria física avaliando a estrutura da baseline bem como a identificação unívoca dos itens de configuração.; 4.	Preparar um checklist para auditoria funcional avaliando se o item de configuração exerce sua funcionalidade segundo seu propósito.; 5.	Realizar a auditoria da Baseline.; 6.	Gerar um relatório listando as não-conformidades encontradas.


|Entrada| Critérios
|------|----------|
|      |Existe uma baseline estabelecida.|

 
|Entrada| Insumos
|------|----------|
|      |•	Baseline; •	Relatório de Estabelecimento de Baseline |

|Saidas| Critérios
|------|----------|
|      | •	Uma auditoria de baseline foi realizada

|Saidas| Produtos|
|------|----------|
|      |•	Checklist de auditoria da configuração funcional; •	Checklist de auditoria da configuração física; •	Relatório de não-conformidades da auditoria da configuração 

|Participantes |Responsável pela Execução |
|------|----------|
|      |•	Gerente de Configuração 

|Participantes |Responsável pela Aprovação | 
|------|----------|
|      |•	Domingos Neto.

|Participantes |Consultados |
|------|----------|
|      |•	Gerênte de Projeto
> 
**3 - Acompanhar Configuração**

|Objetivos |Acompanhar o estado de mudanças em baselines e de ações corretivas para problemas identificados. |
|------|----------|
|**Procedimentos**|1.	Avaliar situação de Planos de Mudança em Baseline que estão em andamento. Deve ser registrada a situação em que se encontra a implementação da mudança, se houver.; 2.	Avaliar o estado das ações corretivas das não-conformidades identificadas em audições para o estabelecimento de baseline ou em acompanhamentos das configurações anteriores. Deve ser registrado a situação em que se encontram as ações corretivas, se de fato houve problemas identificados.; 3.	Verificar se todas as baselines planejadas estão sendo criadas.; 4.	Verificar se os mecanismos de acesso, check-in e check-out estão sendo executados.|

|Entrada |Critérios |
|------|------------|
|      |•	Existe uma baseline estabelecida.; •	Houve uma auditoria de configuração na baseline estabelecida|

|Entrada |Insumos   |
|------|------------|
|      |•	Relatório de não-conformidades da auditoria da configuração.;•	Relatório de Acompanhamento da Configuração anterior.;•	Solicitação de mudança em baseline•	Plano de mudança em baseline | 

|Saida |Critérios |
|------|------------|
|      | •	Uma auditoria de baseline foi realizada. | 

|Saida |Produtos    |
|------|------------|
|      | •	Relatório de Acompanhamento da Configuração. | 


|Participantes |Responsável pela Execução |
|------|------------|
|      |•	Gerente de Configuração       | 

|Participantes |Responsável pela Aprovação |
|------|------------|
|      |•	Domingos Neto. |

|Participantes |Consultados |
|------|------------|
|      |•	Gerênte de Projeto, •	Administrador de Redes ou Responsável pela Infra-Estrutura|

>>>>>>> trabalho-Domingos
