# Declara-o-de-Imposto-de-Renda

A aplicação centraliza informações cadastrais, informes de rendimentos bancários e notas fiscais, preparando os dados de forma estruturada para o preenchimento do programa oficial da Receita Federal.

📝 Visão Geral
Manter a organização financeira para a declaração anual é um desafio para muitos contribuintes. Este projeto automatiza a consolidação de múltiplas fontes de dados (bancos, holerites e dados de dependentes) em um único ambiente intuitivo e validado por tabelas de referência.

🚀 Funcionalidades Técnicas
Módulo do Titular: Cadastro completo com validação de dados (CPF, Título de Eleitor, Endereço e Dependentes).

Consolidador de Informes Bancários: Estrutura para listar saldos e rendimentos de diferentes instituições financeiras com soma automática de patrimônio.

Gestão de Notas e Holerites: Registro cronológico de entradas (Receitas de CNPJ, Salários) para acompanhamento mensal.

Banco de Dados de Instituições: Tabela de referência com códigos e nomes das principais instituições financeiras para garantir a integridade dos dados.

🛠️ Competências Aplicadas
Neste projeto, utilizei técnicas avançadas de estruturação de dados em Excel:

Validação de Dados: Uso de listas suspensas integradas a tabelas de referência para evitar erros de digitação.

Segregação de Dados: Organização do fluxo de informações em abas específicas (Input de dados vs. Tabelas de consulta).

Fórmulas de Consolidação: Funções para soma dinâmica de valores provenientes de diferentes fontes bancárias.

Design de Interface (UX): Foco em uma navegação clara e intuitiva para o usuário final.

📊 Estrutura do Projeto
TITULAR: Dados pessoais e do cônjuge/dependentes.

INFORMES: Centralização de rendimentos por banco.

NOTAS: Registro de entradas mensais e categorias de receita.

TABELA: Base de dados com códigos de compensação bancária.
