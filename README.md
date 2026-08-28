# AF Advocacia | Site Institucional

> Site institucional premium do escritório **AF Advocacia Bancária** — focado em demandas bancárias, design moderno ultra-clean, glassmorphism e responsividade 100% para mobile, tablet e desktop.

---

## ✨ Visão Geral

Site **one-page** (página única) com navegação fixa, animações suaves, tema claro/escuro automático (light/dark mode) e layout premium inspirado em escritórios de advocacia de alto padrão.

Todo o conteúdo e arquitetura foi construído para transmitir **confiança, credibilidade e profissionalismo** — com a paleta de cores:
- 🎨 **Preto / Off-black (#0B0B0B)
- 💰 **Dourado AF (#C09540)**
- 🧾 **Off-white (#F2EFE9)**
- 🌙 **Tema escuro nativo + tema claro automático por sistema**

---

## 📑 Seções do Site

| # | Seção | Conteúdo |
|---|---|---|
| 1 | **Navbar Fixa** | Logo AF Advocacia, links âncora, botão CTA WhatsApp e toggle mobile (hambúrguer) |
| 2 | **Hero** | Headline, subtítulo, CTA WhatsApp + imagem hero |
| 3 | **Quem Somos** | Apresentação do escritório + vídeo em loop institucional |
| 4 | **Números** | Destaques: +4 Anos · 300+ Casos concluídos · 94% Satisfação |
| 5 | **Áreas de Atuação** | 4 cards com especialidades bancárias |
| 6 | **Nossos Diferenciais** | Cards com ícones |
| 7 | **Sócios** | Apresentação do sócio fundador + foto + números |
| 8 | **Contato** | Formulário + informações + WhatsApp |
| 9 | **Footer** | Informações do escritório + links rápidos |

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso |
|---|---|
| **HTML5 Semântico** | Estrutura da página |
| **CSS3 Nativo** | Todo o estilo, animações e responsividade (sem frameworks) |
| **JavaScript Nativo** | Interação (menu mobile, scroll suave, tema claro/escuro) |
| **CSS Grid + Flexbox** | Layouts dinâmico |
| **Variables** | Glassmorphism | Efeitos de blur + backdrop-filter |
| **Media Queries** | 3 breakpoints: 500px / 1024px / 1400px |
| **object-fit / object-position | Imagens responsivas |

> ✅ **100% sem dependências externas** — nenhum framework, nenhum Node_modules, nem biblioteca externa. Funciona em qualquer navegador moderno.

---

## 🎯 Recursos Principais

- 🌓 **Tema claro/escuro automático** — segue a preferência do sistema operacional
- 📱 **100% responsivo** — perfeito em iPhone 390x852, iPad 768x1024 e desktops grandes
- ✨ **Animações suaves** — scroll reveal, sublinhados dourados, hover effects
- 🔝 **Navegação fixa com blur** (glassmorphism) com sublinhado animado no item ativo
- 🎬 **Vídeo em loop** institucional na seção Quem Somos
- 📊 **Números em destaque** com tipografia premium
- 💬 **CTA WhatsApp** em pontos estratégicos (navbar, hero, contato, footer)
- 🔒 **Favicon e meta tags de redes sociais** (OG tags)

---

## 🖥️ Como Rodar Localmente

O site é **100% estático** — não precisa de compilar nada. Você tem 2 opções:

### Opção 1 — Servidor Node.js (recomendado, incluso no projeto)
```bash
# Na pasta do projeto
node servidor.js
```
Acesse 👉 **http://localhost:5500**

### Opção 2 — Extensão Live Server (VS Code)
1. Instale a extensão **Live Server** no VS Code
2. Clique com o botão direito em `index.html` → **Open with Live Server**

### Opção 3 — Simplesmente abrindo o arquivo
Dê 2 cliques no `index.html` — abre direto no navegador.

---

## 📂 Estrutura de Pastas

```
site-adliam/
├── index.html              ← Página principal (todo o site)
├── servidor.js           ← Servidor local Node.js (opcional)
├── .gitignore        ← Ignora servidor.js, node_modules, etc.
├── README.md
└── imagens/
    ├── adliam imagem colorida.jpg
    ├── image.png
    ├── imagem hero adliam.jpeg
    ├── primeira imagem.jpg
    └── video logo loop.mp4    ← Vídeo institucional em loop
```

---

## 🚀 Deploy / Hospedagem

Funciona em **QUALQUER** hospedagem estática**, sem configuração extra**, pois o site usa apenas arquivos HTML/CSS/JS + imagens.

### Hospedagens recomendadas:

| Hospedagem | Como subir |
|---|---|
| **GitHub Pages** | Ative Pages na aba Settings → Pages → Branch `main` |
| **Netlify** | Arraste a pasta na dashboard |
| **Vercel** | Conecte o repositório e clique Deploy |
| **Vercel** | `vercel --prod` |
| **Hostinger / cPanel / FTP | Envie todos os arquivos para a pasta `public_html` |

### Arquivos que PRECISAM estar na hospedagem:
- `index.html`
- Pasta `imagens/` inteira

---

## 📱 Responsividade — Breakpoints

| Largura máxima | Dispositivo | Layout |
|---|---|---|
| **≤ 500px** | Celulares (iPhone 12/13/14: 390x852) | 1 coluna em todas as seções |
| **≤ 1024px** | Tablets (iPad 768x1024) | 1 coluna em seções de texto + 2 colunas em áreas |
| **≥ 1025px** | Desktops e notebooks | Grid completo, 2 e 4 colunas |

Ordem garantida em mobile, assegurada pelo CSS:
- ✅ **Quem Somos**: 1) Frases → 2) Vídeo → 3) Números
- ✅ **Áreas**: 1 abaixo do outro
- ✅ **Sócios**: 1) Título + texto → 2) Imagem → 3) Números

---

## 👨💻 Autor

Projeto construído para **AF Advocacia Bancária**.

Repositório GitHub: [ronilson-neto28/siteAdliam](https://github.com/ronilson-neto28/siteAdliam)

---

## 📞 Contato

Para ajustes, dúvidas ou manutenção no site, entre em contato pelo WhatsApp do escritório (disponível no próprio site).

---

<div align="center">
  <sub>AF Advocacia Bancária · Todos os direitos reservados © 2026</sub>
</div>
