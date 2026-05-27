# Levantamento de Requisitos e Escopo do Sistema

# 1. Técnicas de Elicitação Utilizadas
Para o levantamento dos requisitos do Sistema de Indicadores Hospitalares, a equipe utilizou diferentes técnicas de elicitação
com o objetivo de compreender as necessidades dos usuários e identificar os principais problemas enfrentados durante a análise dos dados hospitalares.

## Entrevistas e Conversas Informais
Foram realizadas conversas com pessoas envolvidas no processo de análise hospitalar para compreender dificuldades enfrentadas na coleta, organização e interpretação dos dados.

## Brainstorming
A equipe realizou reuniões internas para discutir soluções possíveis, funcionalidades prioritárias e formas de automatizar processos atualmente manuais.

## Análise do Processo Atual
Foi realizado o estudo do fluxo atual de tratamento dos dados hospitalares, observando como as planilhas são utilizadas e quais etapas apresentam maior tempo de execução.

## Pesquisa de Sistemas Semelhantes
Foram analisadas soluções existentes para identificar funcionalidades comuns e boas práticas relacionadas à geração de indicadores e visualização de dados.

# 2. Requisitos Levantados

## Requisitos Funcionais (RF)

RF01 – O sistema deve permitir autenticação através de login.
RF02 – O sistema deve permitir upload de planilhas contendo dados hospitalares.
RF03 – O sistema deve processar automaticamente os dados enviados.
RF04 – O sistema deve gerar indicadores hospitalares automaticamente.
RF05 – O sistema deve apresentar gráficos e relatórios para visualização dos resultados.
RF06 – O sistema deve permitir filtragem por períodos específicos.
RF07 – O sistema deve organizar informações por setores hospitalares.
RF08 – O sistema deve permitir compartilhamento de indicadores entre setores autorizados.

## Requisitos Não Funcionais (RNF)

RNF01 – O sistema deve possuir interface intuitiva e de fácil utilização.
RNF02 – O processamento das planilhas deve ocorrer em tempo adequado.
RNF03 – O sistema deve restringir acesso apenas a usuários autorizados.
RNF04 – O sistema deve garantir integridade dos dados enviados.
RNF05 – O sistema deve estar disponível em ambiente web.
RNF06 – O sistema deve permitir expansão futura para novas funcionalidades.


# 3. Escopo do Sistema

## O sistema irá:

- Receber planilhas contendo dados hospitalares;
- Automatizar o processamento das informações;
- Gerar indicadores hospitalares automaticamente;
- Produzir gráficos e relatórios;
- Organizar dados por setores e períodos;
- Permitir acesso restrito aos usuários autorizados;
- Facilitar a visualização de métricas hospitalares.

## O sistema não irá:

- Realizar integração com equipamentos hospitalares;
- Substituir prontuários eletrônicos existentes;
- Executar diagnósticos médicos;
- Realizar atendimento clínico;
- Fazer coleta automática de dados externos nesta versão inicial;
- Desenvolver aplicativo mobile nesta etapa do projeto.


# 4. Delimitação do Projeto

O escopo foi definido considerando o tempo disponível para desenvolvimento durante a disciplina, priorizando funcionalidades essenciais relacionadas à automatização da análise hospitalar
e geração de indicadores. Funcionalidades mais complexas serão consideradas para futuras versões.
