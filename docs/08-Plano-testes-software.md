# Plano de testes de software

O plano de testes de software do sistema EcoDump foi elaborado a partir da especificação funcional do projeto, visando garantir que os requisitos levantados estejam devidamente implementados e funcionando conforme esperado. A seguir, são apresentados os principais casos de teste, com seus respectivos requisitos associados, passos de execução e critérios de êxito.

Todos os testes foram executados por integrantes da equipe de desenvolvimento e validados por usuários reais da empresa Alternativa Transportes LTDA, representando os perfis de operadores, administradores e gestores.


| **Caso de teste**  | **CT-001 – Cadastrar nova caçamba**  |
|:---: |:---: |
| Requisito associado | RF-001 – Permitir o registro de uma nova caçamba no sistema com dados como localização, capacidade, data de instalação e status. |
| Objetivo do teste | Verificar se o usuário consegue cadastrar corretamente uma nova caçamba no sistema. |
| Passos | - Acessar o sistema EcoDump no navegador; - Efetuar login como usuário autenticado; - Navegar até a seção “Cadastro de Caçambas”; - Preencher os campos obrigatórios (localização, capacidade, status, data de instalação);
Clicar em “Salvar”. |
| Critério de êxito | - A caçamba é exibida na lista de caçambas cadastradas com os dados informados. |
| Responsável pela elaboração do caso de teste | Arthur Braga Ribeiro |

<br>

| **Caso de teste**  | **CT-002 – Editar informações de uma caçamba**  |
|:---: |:---: |
| Requisito associado |  RF-002 – Permitir a alteração dos dados de uma caçamba já cadastrada. |
| Objetivo do teste | Garantir que o sistema permita editar informações como status ou localização de uma caçamba.|
| Passos | - Acessar o sistema EcoDump; - Efetuar login como administrador; - Navegar até a lista de caçambas; - Selecionar uma caçamba e clicar em “Editar”; - Alterar o campo “status” para “em manutenção”; - Salvar a alteração. |
| Critério de êxito | - A alteração é refletida na listagem e salva no banco de dados.. |
| Responsável pela elaboração do caso de teste | Arthur Braga Ribeiro. |

<br>

| **Caso de teste**  | **CT-003 – Buscar caçambas com filtros**  |
|:---: |:---: |
| Requisito associado | RF-004 – Permitir a pesquisa de caçambas usando filtros como localização, capacidade e status. |
| Objetivo do teste |Verificar se o sistema retorna corretamente os resultados filtrados conforme os critérios.|
| Passos |Acessar o sistema; - Efetuar login como usuário autenticado; - Ir à página de listagem de caçambas; - Utilizar o filtro “Localização: Contagem” e “Status: disponível”;
Clicarzem “Buscar”.
Critério de êxito: A lista apresenta apenas as caçambas que correspondem aos filtros aplicados.
Responsável pela elaboração do caso de teste: Arthur Braga Ribeiro |
| Critério de êxito | - A lista apresenta apenas as caçambas que correspondem aos filtros aplicados.e | Arthur Braga Ribeiro. |

<br>

| **Caso de teste**  | **CT-004 – Visualizar localização em mapa interativo**  |
|:---: |:---: |
| Requisito associado |  RF-009 – Exibir a localização das caçambas em um mapa interativo. |
| Objetivo do teste |  Validar se as caçambas cadastradas são exibidas corretamente no mapa com seus respectivos marcadores.|
| Passos |Efetuar login no sistema; - Acessar a seção “Mapa de Caçambas”;
Verificar se o mapa é exibido; - Confirmar se as caçambas são exibidas com marcadores de status|
| Critério de êxito | - Todas as caçambas cadastradas aparecem no mapa com suas localizações corretas. |
| Responsável pela elaboração do caso de teste | Arthur Braga Ribeiro. |

<br>

| **Caso de teste**  | **CT-002 – Gerar relatório de uso das caçambas**  |
|:---: |:---: |
| Requisito associado |  Gerar relatórios sobre o uso das caçambas, com exportação para PDF ou CSV.|
| Objetivo do teste | Verificar se o administrador consegue gerar e exportar relatórios com dados precisos.|
| Passos | Acessar o sistema como administrador; - Navegar até a área de relatórios; - Escolher o intervalo de datas e status; - Clicar em “Gerar relatório”; - Selecionar “Exportar como PDF”. |
| Critério de êxito | O sistema gera e permite o download do relatório contendo os dados esperados. |
| Responsável pela elaboração do caso de teste | Arthur Braga Ribeiro. |
