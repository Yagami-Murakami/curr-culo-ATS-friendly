# Mega prompt — JobMatch ATS

Crie uma aplicação web chamada **JobMatch ATS**, em português do Brasil, usando **shadcn/ui** como referência de design.

## Objetivo

A aplicação compara uma descrição de vaga com o currículo do usuário e retorna:
- percentual de match;
- palavras-chave encontradas;
- palavras-chave ausentes;
- versão ATS-friendly do currículo pronta para copiar ou exportar.

## Regra obrigatória

A aplicação nunca pode inventar experiência, formação, cargo, projeto ou competência. Ela pode reorganizar e melhorar a clareza do que já existe. Palavras ausentes devem aparecer como recomendações/lacunas, não ser adicionadas automaticamente ao currículo.

## Layout

Paleta:
- azul-marinho: #0B1630
- azul principal: #2F6DF6
- ciano: #1FC7D4
- fundo: #F5F7FB
- verde para termos encontrados
- vermelho suave para lacunas

Usar cards, bordas suaves, sombras discretas, espaçamento generoso e tipografia Inter.

## Tela principal

Hero com:
- título sobre currículos barrados pelo ATS;
- explicação curta;
- CTA "Analisar meu currículo";
- aviso de que o sistema não inventa experiências;
- mockup do resultado com score e keywords.

## Área de análise

Dois campos grandes lado a lado no desktop e empilhados no celular:
1. Descrição da vaga
2. Currículo

Botão principal: **Analisar compatibilidade**.

## Resultado

Mostrar:
- score percentual e barra de progresso;
- quantidade de palavras encontradas e ausentes;
- chips verdes para encontradas;
- chips vermelhos para ausentes;
- texto explicando o nível de aderência.

## Currículo ajustado

Gerar versão limpa em texto simples, com seções claras e sem tabelas ou colunas. Reorganizar somente o conteúdo fornecido pelo usuário.

Botões:
- Copiar texto
- Exportar PDF

## Privacidade

Processar os textos localmente no navegador na primeira versão, sem armazenamento ou login.

## Responsividade e acessibilidade

- funcionar bem no celular;
- foco visível;
- contraste adequado;
- respeitar prefers-reduced-motion;
- labels e textos de ajuda claros.

## Critérios de aceite

- entrada de vaga e currículo;
- análise funcional;
- score funcional;
- keywords encontradas e ausentes;
- geração ATS-friendly sem invenções;
- exportação por PDF;
- responsividade.
