# Power BI Update — Fevereiro 2026

A atualização de **fevereiro de 2026** do Power BI Desktop (versão **2.151.1052.0**) trouxe diversos aprimoramentos voltados para experiência do usuário, inteligência artificial, modelagem de dados e melhorias em visualizações.

Abaixo estão os principais destaques desta versão.

---

# 📊 Relatórios e Experiência do Usuário

## Input Slicer (Disponibilidade Geral)

O visual **Input Slicer**, anteriormente conhecido como *text slicer*, alcançou **disponibilidade geral (GA)**.

Esse recurso permite que usuários **digitem ou colem valores diretamente em um segmentador** para filtrar dados.

Principais capacidades:

- filtragem por correspondência exata
- filtragem por correspondência parcial ("contém")
- entrada manual de múltiplos valores

Isso facilita análises rápidas e filtragens personalizadas em relatórios.

---

## Colar valores em segmentações

Agora é possível **colar uma lista de valores diretamente em um slicer** a partir da área de transferência.

Benefícios:

- seleção múltipla rápida
- filtragem de grandes listas de valores
- maior produtividade na exploração de dados

---

## Atualizações no visual de Cartão

O **novo visual de cartão padrão** recebeu melhorias importantes:

- aumento do limite de **5 para 10 callouts**
- interação aprimorada entre visuais

Agora, ao **selecionar o nome de uma categoria no cartão**, os outros visuais da página podem ser filtrados automaticamente.

---

## Compatibilidade de Fontes

Fontes padrão, como **Segoe UI**, agora são exibidas corretamente em dispositivos que não utilizam o sistema **Windows**.

Essa melhoria aumenta a consistência visual de relatórios em diferentes plataformas.

---

## Melhorias no Azure Maps

O visual **Azure Maps** recebeu melhorias de performance e novas funcionalidades.

Novidades incluem:

- suporte a **gráficos de pizza diretamente no mapa**
- novos **endpoints regionais**, incluindo suporte específico para **Brasil** e **Coreia**

Essas melhorias ajudam a reduzir latência e melhorar o desempenho em análises geoespaciais.

---

# 🤖 Copilot e Inteligência Artificial

## Expansão do limite de caracteres

O limite de entrada para prompts no **Copilot** foi ampliado de **500 para 10.000 caracteres**.

Isso permite:

- instruções mais detalhadas
- prompts mais complexos
- análises mais completas com IA

---

## Copilot em aplicativos

O Copilot também recebeu melhorias na experiência conversacional dentro de aplicativos.

Agora os usuários podem pedir ao Copilot para:

- localizar relatórios relevantes
- resumir conteúdos disponíveis em um aplicativo
- identificar dados relevantes para análise

---

# 🧱 Modelagem e DAX

## Novas funções DAX

Duas novas funções DAX foram introduzidas:

### TABLEOF()

Retorna uma **referência à tabela associada a uma coluna ou medida**.

Essa função ajuda a tornar expressões mais claras e facilita a manipulação de metadados.

### NAMEOF()

Retorna **o nome de um objeto como texto**.

Benefícios:

- maior segurança em expressões DAX
- melhor manutenção de código
- redução de erros ao renomear objetos

---

## Modelos Semânticos Compostos

Está em **versão prévia (Preview)** a capacidade de combinar tabelas **Direct Lake** com tabelas **Import** dentro de um único **modelo semântico composto**.

Isso oferece maior flexibilidade na arquitetura de dados e possibilita:

- modelos híbridos
- melhor balanceamento entre performance e flexibilidade
- integração mais eficiente com Microsoft Fabric.

---

# ⚠️ Avisos de Descontinuação

A atualização também trouxe avisos importantes sobre descontinuação de recursos.

## Hierarquias nos Scorecards

Esse recurso será removido em **15 de abril de 2026**, incluindo a funcionalidade de **mapa de calor associada**.

---

## Importação Legada de Excel/CSV

Mudanças anunciadas:

- **31 de maio de 2026** — remoção de pontos de entrada para importação legada
- **31 de julho de 2026** — interrupção da atualização automática de modelos criados por esse método

---

## Driver Simba Vertica

O processo de descontinuação do **driver Simba Vertica** começou em fevereiro de 2026.

A Microsoft recomenda a migração para o **driver ODBC oficial do Vertica**.

---

# 🌎 Eventos e Comunidade

## FabCon Americas 2026

O evento **FabCon Americas 2026** ocorrerá de **16 a 20 de março em Atlanta**.

O evento terá foco em:

- Microsoft Fabric
- Power BI
- Inteligência Artificial aplicada a dados

---

## Power BI Dataviz World Championship

Também foram anunciados os **quatro finalistas do campeonato mundial de visualização de dados**, que competirão ao vivo durante a FabCon.

---

# 💡 Insights para Profissionais de BI

Alguns impactos práticos desta atualização incluem:

- maior flexibilidade na filtragem de dados com Input Slicer
- melhorias na interação entre visuais
- avanços no uso de IA com Copilot
- novas possibilidades de modelagem híbrida com Direct Lake

Essas melhorias reforçam o foco do Power BI em **produtividade, inteligência artificial e arquitetura moderna de dados**.
