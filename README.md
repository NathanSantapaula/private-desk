# Private Desk

Painel de gestão diária e metas para assessores de investimentos (XP / Rico), em um único arquivo HTML que roda offline no navegador.

## Como usar

Abra `index.html` no Chrome, Edge ou Firefox. Não precisa instalar nada.

Os dados ficam salvos no próprio navegador (`localStorage`). Para levar para outro computador, use **Configurações → Exportar backup (Excel)** e depois **Importar backup (Excel)**.

## O que tem

- **Rotina diária**: blocos com início e fim, checklist e hierarquia de prioridades, pausa automática, tipos de agenda editáveis (dias da semana), calendário para rever dias anteriores, arrastar para reordenar.
- **Metas & Ponderações**: metas com peso, meta e objetivo; Cesta de Investimentos por categoria; Cross-sell por item; NPS; Índice Comercial com micro metas; Nota MEREO (100% = 3, 200% = 5); widgets arrastáveis e edição em pop-up.
- **Visão dashboard**: consolidado visual com gráficos.
- **Pontos de melhoria** (lâmpada): prioridades e o que falta em cada área.
- **Configurações**: foto e perfil, marca XP ou Rico, tema Black ou White, metas e micro metas.
- **Backup em Excel (.xlsx)** com todos os dados, gerado e lido sem bibliotecas externas.

## Painel do líder (equipe)

1. Cada assessor exporta o backup em Excel (sai como `private-desk-<nome>.xlsx`) e salva numa pasta compartilhada do SharePoint/OneDrive, sempre por cima do mesmo arquivo.
2. O líder liga **Configurações → Painel do líder** e, na aba nova, carrega todos os arquivos da pasta de uma vez.
3. **Exportar consolidado (Power BI)** gera `private-desk-equipe.xlsx` com abas planas por assessor. No Power BI: Obter dados → SharePoint Online → esse arquivo.

O controle de acesso fica na pasta do SharePoint: só o líder deve ter leitura de todos os arquivos.

## App no Microsoft Teams

O pacote `teams/private-desk-teams.zip` instala o Private Desk como app na barra lateral do Teams. Ele abre este mesmo site, com o mesmo design.

1. No Teams: **Apps → Gerenciar seus apps → Carregar um app**.
2. Escolha **Carregar um app personalizado** e selecione o `.zip`. Se a opção não aparecer, a empresa bloqueia apps personalizados: use **Enviar um app para sua organização** e a TI aprova.
3. Abra o app e fixe na barra lateral (botão direito → Fixar).

## Privacidade

O Private Desk não envia dados para servidores. Tudo que o assessor preenche fica salvo no próprio navegador (ou no Teams) dele, e só sai dali quando ele exporta o backup em Excel.

## Termos de uso

Ferramenta interna de apoio à gestão diária, fornecida como está. XP e Rico são marcas dos seus respectivos donos.
