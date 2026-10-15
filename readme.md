# 🏎️ Oracle Red Bull Racing — Sorteio Oficial VIP (Projeto Acadêmico)

!\[HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge\&logo=html5\&logoColor=white)

!\[Tailwind CSS](https://img.shields.io/badge/Tailwind\_CSS-38B2AC?style=for-the-badge\&logo=tailwind-css\&logoColor=white)

!\[JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)

\---

## 📅 Informações Acadêmicas

* **Instituição de Ensino:** Faculdade Municipal de Palhoça (FMP)
* **Curso:** Análise e Desenvolvimento de Sistemas (ADS)
* **Fase:** 1ª Fase
* **Data da Entrega:** 15 de Outubro de 2026
* **Disciplina:** Desenvolvimento Web / Front-End Inicial

\---

## 📖 História e Conceito do Site (Fictício)

Este projeto consiste em uma **Landing Page fictícia de captura e engajamento** inspirada na equipe de Fórmula 1 **Oracle Red Bull Racing**.

### A História por trás do Projeto

A proposta do site é simular uma campanha publicitária oficial da equipe Red Bull Racing durante a temporada de Fórmula 1. O objetivo do portal é atrair fãs do automobilismo mundial oferecendo a oportunidade de concorrer a um **Passe VIP Paddock Club**, que concede acesso aos boxes, *Meet \& Greet* com os pilotos (Max Verstappen e Isack Hadjar), além de brindes exclusivos e acesso aos dados de telemetria da equipe em tempo real.

> \*\*Nota:\*\* Este é um projeto \*\*100% fictício\*\*, desenvolvido estritamente para fins acadêmicos e pedagógicos durante o primeiro semestre do curso de ADS, sem qualquer vínculo comercial com a Red Bull GmbH ou a Formula One World Championship Limited.

\---

## 🎨 Paleta de Cores (Tabela HEX)

A identidade visual foi construída com base nos tons oficiais de azul, vermelho e amarelo da Oracle Red Bull Racing:

|Representação Visual|Nome da Cor|Código HEX|Utilização no Projeto|
|:-:|:-:|:-:|-|
|`#030814`|**rbNavy**|`#030814`|Fundo principal da página e elementos de alto contraste.|
|`#0a1226`|**rbBlue**|`#0a1226`|Fundo de seções secundárias e overlays.|
|`#0f1b36`|**rbCard**|`#0f1b36`|Cards de conteúdo, containers e caixas de formulário com desfoque.|
|`#ed1c24`|**rbRed**|`#ed1c24`|Botões de ação principais (CTA), bordas em destaque e badges.|
|`#fdb913`|**rbYellow**|`#fdb913`|Destaques de texto, detalhes e selos do evento.|
|`#ffcc00`|**rbGold**|`#ffcc00`|Acentos secundários e gradientes de iluminação.|

\---

## 🏷️ Tags HTML e Bibliotecas Utilizadas

### Tags HTML5 Implementadas:

* `<!DOCTYPE html>`: Declaração do documento HTML5.
* `<html>`: Elemento raiz configurado em Português do Brasil (`pt-BR`) e com rolagem suave (`scroll-smooth`).
* `<head>`: Metadados, scripts CDN e estilizações globais.
* `<meta>`: Configuração de *charset* (UTF-8) e responsividade para dispositivos móveis (*viewport*).
* `<title>`: Título da aba do navegador.
* `<script>`: Importação do Tailwind CSS via CDN e configuração do Javascript customizado.
* `<link>`: Importação dos ícones do Font Awesome e fontes do Google Fonts.
* `<style>`: Estilos CSS customizados embutidos (efeitos de iluminação, gradientes de texto e animações de *hover*).
* `<body>`: Container principal do conteúdo visível.
* `<div>`: Divisões estruturais e containers do layout responsivo.
* `<span>`: Elementos de texto e indicadores de estilo inline (ex: bolinhas decorativas).
* `<section>`: Divisão semântica das seções (Top Bar, Hero, Experiências/Prêmios, Footer).
* `<img>`: Exibição das imagens de fundo, carros e cards dos pilotos.
* `<h1>`, `<h2>`, `<h3>`, `<h4>`: Hierarquia semântica de títulos.
* `<p>`: Parágrafos descritivos.
* `<strong font-semibold>`: Destaque de palavras-chave.
* `<form>`: Estrutura do formulário de captura de lead.
* `<label>`: Rótulos acessíveis dos campos de entrada do formulário.
* `<input>`: Campos de entrada de dados (`text` para nome e `email` para e-mail).
* `<button>`: Botão de envio (*submit*) com animação.
* `<i>`: Exibição de ícones vetoriais da biblioteca Font Awesome.
* `<a>`: Links de navegação e ancoragem interna (`#garanta-acesso`).
* `<footer>`: Rodapé com direitos autorais.

### Bibliotecas e Recursos Externos:

1. **Tailwind CSS (v3 CDN):** Framework de CSS utilitário para layout responsivo (Grid/Flexbox) e estilização ágil.
2. **Font Awesome (v6.4.0):** Biblioteca de ícones vetoriais.
3. **Google Fonts:**

   * **Syne:** Utilizada para títulos e cabeçalhos de alta visibilidade (*display font*).
   * **Inter:** Utilizada no corpo de texto para legibilidade otimizada (*sans-serif*).

\---

## 🔍 Detalhamento do Código por Blocos e Linhas Importantes (`index.html`)

Abaixo está o mapeamento detalhado da estrutura do arquivo principal do site:

```text
Linhas 01 - 04  : Declaração DOCTYPE e tag <html> configurada com rolagem suave (scroll-smooth).
Linhas 05 - 12  : Tag <head> contendo charset, viewport, título e carregamento do Tailwind CSS e Font Awesome.
Linhas 13 - 15  : Conexão e pré-carregamento das fontes "Syne" e "Inter" via Google Fonts.
Linhas 17 - 35  : Bloco <script> de customização do tema no Tailwind (configuração das cores customizadas rbNavy, rbRed, etc).
Linhas 37 - 81  : Bloco <style> com classes customizadas de CSS (glow-red, text-gradient, card-racing, bg-grid).
Linha  83       : Abertura da tag <body> com classe de seleção customizada e anti-aliasing de fonte.
Linhas 85 - 97  : Strip/Faixa de Branding Fixa (Sticky Topbar) com o nome da equipe e badge "PADDOCK CLUB".
Linhas 99 - 222 : Seção "Hero" Principal:
   - Linhas 102 - 110 : Imagem de fundo do carro de F1 com efeito de camada escura (overlay gradient) para legibilidade.
   - Linhas 115 - 125 : Selo/Emblema centralizado da marca "RED BULL RACING F1 TEAM".
   - Linhas 128 - 135 : Título principal com gradiente de texto ("ENTRE NO PADDOCK") e subtítulo explicativo.
   - Linhas 138 - 220 : Layout Tríptico em Grid (3 Colunas no Desktop):
        • Coluna 1 (Linhas 141 - 158) : Card em destaque do Piloto 1 (Max Verstappen #1).
        • Coluna 2 (Linhas 161 - 200) : Formulário de captura com validação simples e tela de confirmação rápida.
        • Coluna 3 (Linhas 203 - 220) : Card em destaque do Piloto 2 (Isack Hadjar #6).
Linhas 224 - 289 : Seção de Experiências / Grid de Prêmios VIP (4 Cards + Card Bônus em Grid Responsivo).
Linhas 291 - 295 : Rodapé (Footer) com os direitos fictícios da página.
Linhas 297 - 306 : Script JS inline (função registrarFan) que oculta o formulário e exibe a mensagem de confirmação sem dar refresh.
```

\---

## 🚀 Como Executar o Projeto

## 

## 👨‍💻 Desenvolvido por Pedro Henrique Sell

Aluno do curso de **Análise e Desenvolvimento de Sistemas (ADS)** da **Faculdade Municipal de Palhoça (FMP)** — 1ª Fase (2026).

