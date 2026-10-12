# Vetora · Cadastro

Fluxo de cadastro em etapas para uma plataforma de cursos de tecnologia (marca fictícia, projeto de portfólio).

## Funcionalidades

- **Conta:** validação em tempo real de nome, e-mail e senha, medidor de força e requisitos visíveis.
- **Verificação de e-mail:** código de 6 dígitos com avanço automático, colar o código inteiro e reenvio com contagem regressiva.
- **Filtro por objetivo de carreira:** o estudante descreve a meta e o foco; o filtro marca objetivo, nível e áreas de interesse e sugere o cargo de entrada e os próximos passos.
- **Rotina de estudo:** horas por semana, dias e período.
- **Resultado:** trilha sugerida com estimativa de semanas e resumo do cadastro.
- Tema claro e escuro automático, layout responsivo e navegação por teclado com mensagens de erro anunciadas para leitores de tela.

## Tecnologias

HTML5, CSS3 (Grid, Flexbox, variáveis CSS) e JavaScript puro, sem frameworks.

## Como executar

Abra o arquivo `index.html` no navegador. Não há dependências nem etapa de build.

## Estrutura

```
index.html   marcação das etapas
style.css    tokens de cor, tipografia e componentes
script.js    validação, navegação entre etapas e filtro de carreira
```

## Observação

Projeto demonstrativo: nenhum dado é enviado a servidor. O código de verificação aparece na própria tela.
