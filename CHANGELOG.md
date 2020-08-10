# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.0] - 2019-11-13

### Added

- Página “Análise” contendo: Elementos gráficos (Gauge, Gráficos e Cards) que variam suas cores predominantes (Vermelho/Amarelo/Verde) de acordo limites de custo estipulados; Filtros por Local (Planta), Medição (Água, Vapor, Energia Elétrica, Ar comprimido, Combustível), Equipamento e Sensores
- Página “Detalhamento” contendo gráficos que apresentam os dados da planta industrial, a página contém a mesma divisão da página de análise 
- Coletor de dados da plataforma online Utility Drive, os dados alimentam a página de análise desenvolvida
- Página Administração permitindo o registro de novos sensores
- Sistema de Login e Senha

## [1.0.0] - 2017-06-20

### Added

- Adicionado controle de níveis de acesso (Visualizador/Gestor/Administrador)
- Página de Administração permitindo: Criação, alteração e remoção de usuários; Criação, alteração e remoção de sensores/equipamentos/utilidades/plantas
- Página para criação de relatórios instantâneos e programáveis: permite a programação de envios automáticos e instantâneos de relatórios; A criação de Layouts de acordo com os sensores desejados; Exportar os relatórios nos formatos PDF,CSV,XLSX; Selecionar dados de um período específico.   
- Página de Gerenciamento de dados que permitiu com que usuários Gestores realizassem o Download e Excluísse os dados presentes no banco de dados
- Customização do usuário: Permite selecionar imagens como logos para cada usuário.

## [2.0.0] - 2020-08-10

### Added

- Novo visual da plataforma CLQuickium
- Adição de novas tabelas no banco de dados
- Nova Página de visualização dos Gráficos: 
	- Permite a opção de visualização um ou dois  gráfico por linha do layout
	- Permite a seleção do período desejado e a quantidade de dados desejada
	- Treeview disponibilizando a seleção dos sensores/equipamentos/nodes/locais
	- Permite de seleção dos sensores por utilidade/medição
	- Permite visualizar dados brutos, convertidos e monetários 
- Nova Página de gerenciamento de dados:
	- Permite baixar/deletar dados brutos, convertidos e monetários
	- Treeview para seleção dos dados
	- Permite baixar dados de sensores individuais ou grupos.
- Nova Página de Relatórios
	- Permite adicionar linhas referentes a equipamentos e plantas
- Nova Página de Alarme: Permite a criação de alarmes para sensores de acordo com um trigger configurado, ao ser acionado o alarme um e-mail é enviado para os endereços cadastrados.
- Nova Página de cadastro de dispositivos e calibração:
	- Ao cadastrar dispositivos automaticamente a alteração é enviada para a API e posteriormente para o Gateway
	- Novos Parâmetros para os nodes, dispositivos e sensores
	- calibração dos sensores pode ser realizada fornecendo 5 pontos X,Y no site, fornecendo arquivo CSV com pontos X e Y, e fornecendo a equação.
- Nova Página de configuração dos usuários: Novo visual e adição de um novo nível de acesso chamado master
- Página de Consumo de dados: Página disponibilizando o uso de Armazenamento e 
Download Realizado no Mês Atual
- Página de log
- Novo modelo de organização de features chamados PLUGINS - Permite o controle de features para cada usuário através da disponibilização de plugins
- Desenvolvimento Plugin Custo: Plugin contendo nova página de visualização de custos com novo visual e adicionado a opção de visualização de sensores com custos Zeros
- Desenvolvimento Plugin Relatório: Plugin que envolve as features do Relatório
- Desenvolvimento Plugin Alarmes: Plugin que envolve as features do Alarme
- Desenvolvimento Plugin White Label: Plugin permite alteração de cores e logotipo da plataforma visualizada pelos clientes.


