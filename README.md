# Guia de estudos: entrada na área de dados

Página estática com um plano de estudos para quem quer conseguir um estágio ou vaga júnior em dados em cerca de 6 meses. O conteúdo vai de Excel, SQL e Python até projetos de portfólio, com checklist de progresso e rotina semanal editável.

🔗 **Site:** 

## Funcionalidades

- **Checklist por fase:** marque cada tarefa ao concluir e acompanhe a barra de progresso geral.
- **Escolha de caminho:** na Fase 3, siga Análise/BI ou Engenharia de Dados. O progresso conta só o caminho escolhido.
- **Rotina semanal editável:** altere dia, horário, foco e horas de estudo, adicione ou remova linhas e restaure o padrão quando quiser.
- **Backup e restauração:** copie seus dados e cole em outro navegador ou dispositivo para continuar de onde parou.
- **Tema claro e escuro:** segue a preferência do sistema.

## Fases do guia

1. **Fundamentos:** Excel básico, SQL e Python.
2. **Dados de verdade:** pandas, visualização, estatística aplicada e primeiro projeto.
3. **Escolha do caminho:** Análise/BI ou Engenharia de Dados.
4. **Portfólio e estágio:** GitHub, LinkedIn, currículo e candidaturas.

## Como os dados são salvos

Tudo fica no `localStorage` do navegador. Não há servidor, conta nem coleta de dados. Isso significa que:

- o progresso é **por navegador e por dispositivo**;
- limpar os dados do navegador apaga o progresso;
- para levar seus dados para outro lugar (ou se proteger contra perda), use **Copiar backup** e **Restaurar backup**, no fim da página.

## Tecnologias

HTML, CSS e JavaScript puros em um único arquivo. A única dependência externa é o Google Fonts (Bricolage Grotesque e Atkinson Hyperlegible).

## Estrutura

```
.
├── index.html   # página completa (HTML, CSS e JS)
└── README.md
```