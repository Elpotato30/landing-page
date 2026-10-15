# 🏎️ Oracle Red Bull Racing — Sorteio Oficial VIP (Projeto Acadêmico)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-online-222222?style=for-the-badge&logo=github&logoColor=white)

🔗 **Site publicado:** https://elpotato30.github.io/landing-page/

---

## 📅 Informações Acadêmicas

* **Instituição de Ensino:** Faculdade Municipal de Palhoça (FMP)
* **Curso:** Análise e Desenvolvimento de Sistemas (ADS)
* **Fase:** 1ª Fase
* **Disciplina:** PRÁTICA DE PROGRAMAÇÃO WEB 
* **Data da Entrega:** 15 de Outubro de 2026
* **Autor:** Pedro Henrique Sell

---

## 📖 História e Conceito do Site (Fictício)

Este projeto é uma **landing page fictícia de captura de leads e engajamento**, inspirada na equipe de Fórmula 1 **Oracle Red Bull Racing**.

### A história por trás do projeto

A proposta simula uma campanha publicitária da equipe durante a temporada de F1. O objetivo da página é atrair fãs de automobilismo e convidá-los a se cadastrar para **concorrer a um Passe VIP Paddock Club**, que inclui *Meet & Greet* com os pilotos (Max Verstappen e Isack Hadjar), tour no pit garage, acesso a um lounge VIP, kit de brindes e acesso a telemetria e rádio da equipe.

> **Nota:** Este é um projeto **100% fictício**, feito para fins acadêmicos e pedagógicos no primeiro semestre do curso de ADS. Não possui vínculo comercial com a Red Bull GmbH nem com a Formula One World Championship Limited. O sorteio **não existe** e os dados digitados no formulário **não são enviados nem armazenados**.

### Objetivo da página (jornada do usuário)

1. O visitante chega e vê o título **"ENTRE NO PADDOCK"** sobre a foto do carro.
2. Conhece os dois pilotos nos cards laterais.
3. Preenche **nome** e **e-mail** no formulário central.
4. Recebe uma tela de **confirmação** sem recarregar a página.
5. Rola até as **experiências** do sorteio e pode voltar ao formulário pelo botão **"Participar Agora"**.

---

## 🖼️ Pré-visualização

> _Adicione aqui um print da página, por exemplo `docs/preview.png`, com a sintaxe `![Prévia do site](docs/preview.png)`._

---

## 🎨 Paleta de Cores (Tabela HEX)

Definida no `tailwind.config` dentro do `index.html`:

| Nome da Cor | Código HEX | Utilização no Projeto |
|-|:-:|-|
| **rbNavy** | `#030814` | Fundo principal da página, faixa do topo e overlays do hero |
| **rbBlue** | `#0a1226` | Fundo da seção de prêmios e gradientes |
| **rbCard** | `#0f1b36` | Cartão do formulário, cards de prêmios e selo "PADDOCK CLUB" |
| **rbRed** | `#ed1c24` | Botões de ação (CTA), brilho do formulário, ícones e destaques |
| **rbYellow** | `#fdb913` | Destaques de texto, ícones, grade de pontos e gradiente do título |
| **rbGold** | `#ffcc00` | Acento secundário (declarado na paleta) |

Cores extras usadas pelo Tailwind: tons de `slate` para textos secundários e `emerald` para o ícone de confirmação.

## 🔤 Tipografia

* **Syne** (700, 800, 900): títulos e elementos de destaque (classe `font-display`).
* **Inter** (300 a 700): corpo de texto, para boa legibilidade (classe `font-sans`).

---

## 🏷️ Tags HTML e Bibliotecas Utilizadas

### Tags HTML5 implementadas

* `<!DOCTYPE html>`: declaração do documento HTML5.
* `<html lang="pt-BR" class="scroll-smooth">`: raiz do documento, em português do Brasil e com rolagem suave.
* `<head>`: metadados, CDNs e estilos globais.
* `<meta>`: `charset` (UTF-8) e `viewport` (responsividade em celulares).
* `<title>`: título da aba do navegador.
* `<script>`: Tailwind via CDN, configuração do tema e JavaScript da página.
* `<link>`: Font Awesome e Google Fonts (`preconnect` + folha de estilos).
* `<style>`: CSS customizado (brilho, gradiente de texto, cards e grade de fundo).
* `<body>`: conteúdo visível.
* `<div>`: containers e estrutura do layout (faixa do topo, grid, cards).
* `<span>`: textos curtos, bolinhas decorativas e selos.
* `<section>`: seções semânticas (Hero e Prêmios).
* `<img>`: foto do carro (fundo) e fotos dos pilotos.
* `<h1>`, `<h2>`, `<h3>`, `<h4>`: hierarquia de títulos.
* `<p>`: parágrafos descritivos.
* `<strong>`: destaque de "Oracle Red Bull Racing" no texto de apresentação.
* `<form>`: formulário de captura (`onsubmit="registrarFan(event)"`).
* `<label>`: rótulos dos campos, ligados aos inputs por `for`/`id`.
* `<input>`: campos `type="text"` (nome) e `type="email"` (e-mail), ambos `required`.
* `<button>`: botão de envio (`type="submit"`).
* `<a>`: link de âncora interna (`#garanta-acesso`).
* `<i>`: ícones do Font Awesome.
* `<footer>`: rodapé com copyright.

### Bibliotecas e recursos externos

1. **Tailwind CSS (CDN):** utilitários para layout responsivo (Grid/Flexbox), cores, espaçamentos e efeitos.
2. **Font Awesome 6.4.0:** ícones (bandeira quadriculada, ticket, troféu, coroa, presente etc.).
3. **Google Fonts:** Syne e Inter.
4. **Imagens externas:** foto do carro (hero) e fotos dos pilotos, carregadas por URL.

---

## 🧩 Recursos de CSS Customizado (`<style>`)

| Classe | O que faz |
|-|-|
| `.glow-red` | Sombra/brilho vermelho ao redor do formulário |
| `.text-gradient` | Texto com gradiente branco → amarelo → vermelho (palavra "PADDOCK") |
| `.card-racing` | Card com vidro fosco (`backdrop-filter`) e efeito *hover* (sobe e ganha borda vermelha) |
| `.driver-hero-full` | Cards dos pilotos com foto de fundo e *hover* com borda amarela |
| `.bg-grid` | Fundo de pontos amarelos sutis no hero |

---

## 🔍 Estrutura e Detalhamento do Código (`index.html`)

O arquivo está organizado em blocos, identificados pelos comentários do próprio HTML:

```text
<head>
  ├─ meta charset / viewport / title
  ├─ Tailwind CSS (CDN)
  ├─ Font Awesome (CDN)
  ├─ Google Fonts: Syne & Inter
  ├─ <script> tailwind.config → cores customizadas (rbNavy, rbRed...) e fontes
  └─ <style> → .glow-red, .text-gradient, .card-racing, .driver-hero-full, .bg-grid

<body>
  ├─ FAIXA DE BRANDING NO TOPO (sticky)
  │     nome da equipe + selo "PADDOCK CLUB OFFICIAL PASS" (oculto no mobile)
  │
  ├─ HERO SECTION
  │     ├─ Imagem do carro ao fundo + degradês para legibilidade
  │     ├─ Selo vetorizado "RED BULL RACING F1 TEAM"
  │     ├─ Título "ENTRE NO PADDOCK" e texto de apresentação
  │     └─ Estrutura em 3 colunas (id="garanta-acesso", grid de 12 colunas)
  │           ├─ Coluna 1 (3/12): card do Max Verstappen (#1, Holanda)
  │           ├─ Coluna 2 (6/12): formulário "Inscrição no Sorteio VIP"
  │           │     • campos nome e e-mail (required)
  │           │     • tela de confirmação (id="msgSucesso", inicia oculta)
  │           │     • selos "Sorteio 100% Gratuito" e "+120 mil membros"
  │           └─ Coluna 3 (3/12): card do Isack Hadjar (#6, França)
  │
  ├─ SEÇÃO "O QUE VOCÊ PODE GANHAR" (4 cards + card bônus)
  │     Meet & Greet · Tour no Pit Garage · Paddock VIP Lounge · Kit de Brindes
  │     Bônus: Telemetria & Rádio ao Vivo (botão "Participar Agora")
  │
  ├─ FOOTER mínimo (direitos fictícios)
  │
  └─ <script> → função registrarFan(event)
```

### Função JavaScript

```js
function registrarFan(event) {
    event.preventDefault();                 // impede o recarregamento da página
    const form = event.target;
    const msgSucesso = document.getElementById('msgSucesso');

    form.classList.add('hidden');           // esconde o formulário
    msgSucesso.classList.remove('hidden');  // mostra "Inscrição Confirmada!"
}
```

A validação dos campos (preenchimento obrigatório e formato de e-mail) é feita pelo próprio navegador, por meio dos atributos `required` e `type="email"`.

---

## 📱 Responsividade

O layout usa os *breakpoints* do Tailwind (`sm`, `md`, `lg`):

* **Mobile:** tudo em 1 coluna. O formulário vem **primeiro** (`order-1`) e os pilotos depois, para priorizar a conversão. O selo do topo fica oculto.
* **Tablet (`md`):** cards de prêmios em 2 colunas.
* **Desktop (`lg`):** hero em 3 colunas (piloto, formulário, piloto) e prêmios em 4 colunas.

---

## 🚀 Como Executar o Projeto

Não há instalação nem *build*: é um único arquivo HTML.

**Online:** acesse https://elpotato30.github.io/landing-page/

**Localmente:**

1. Baixe ou clone o repositório:
   ```bash
   git clone https://github.com/elpotato30/landing-page.git
   ```
2. Abra a pasta e dê um duplo clique em `index.html` (ou use a extensão **Live Server** do VS Code).

> **Requisito:** conexão com a internet, pois Tailwind, Font Awesome, Google Fonts e as imagens são carregados de fontes externas.

### Estrutura de arquivos

```text
.
├── index.html   # Página completa (HTML + CSS customizado + JavaScript)
└── README.md    # Documentação do projeto
```

---

## ✅ Funcionalidades Implementadas

- [x] Faixa de branding fixa no topo (*sticky*)
- [x] Hero com imagem de fundo, degradês e brilho vermelho
- [x] Layout em 3 colunas com cards de pilotos e formulário central
- [x] Formulário com validação nativa do HTML5
- [x] Tela de confirmação sem recarregar a página
- [x] Grid de prêmios com efeitos de *hover*
- [x] Rolagem suave até o formulário (`#garanta-acesso`)
- [x] Layout responsivo (mobile, tablet e desktop)
- [x] Publicação no GitHub Pages

## 🔮 Melhorias Futuras

- [ ] Guardar os cadastros de verdade (por exemplo com um serviço de formulários ou um back-end)
- [ ] Mostrar mensagens de erro personalizadas e limpar o formulário
- [ ] Adicionar menu de navegação e mais seções (pilotos, equipe, história)
- [ ] Hospedar as imagens no próprio repositório (pasta `assets/`)
- [ ] Melhorar acessibilidade (`aria-*`, contraste dos textos pequenos, foco visível)
- [ ] Incluir aviso de privacidade (LGPD) caso o formulário passe a coletar dados reais

---

## 📚 Créditos e Aviso Legal

* Marca, nome da equipe, fotos dos pilotos e do carro pertencem aos seus respectivos proprietários e são usados **apenas para fins educacionais**.
* Ícones: [Font Awesome](https://fontawesome.com). Fontes: [Google Fonts](https://fonts.google.com). Estilos: [Tailwind CSS](https://tailwindcss.com).
* Os números "+120 mil membros" e a existência do sorteio são **fictícios**.

---

## 👨‍💻 Desenvolvido por Pedro Henrique Sell

Aluno do curso de **Análise e Desenvolvimento de Sistemas (ADS)** da **Faculdade Municipal de Palhoça (FMP)** — 1ª Fase (2026).
