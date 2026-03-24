# Disney+ Clone

Recriação da landing page do Disney+ com foco em fidelidade visual, pipeline de build automatizado com Gulp e estilização avançada em SCSS.

## 🚀 Demo

🔗 [Acessar projeto ao vivo](https://clone-disneyplus-vinnmac.vercel.app)

---

## 📋 Sobre o projeto

Este projeto replica a interface da landing page do Disney+, demonstrando domínio de ferramentas modernas de front-end como pré-processadores CSS e automação de tarefas com Gulp. O foco foi na fidelidade visual ao produto original e na organização profissional do código.

---

## 🛠️ Tecnologias utilizadas

- **HTML5** — estrutura semântica
- **SCSS** — pré-processador CSS com variáveis, mixins e aninhamento
- **JavaScript** — interatividade
- **Gulp** — automação de build (compilação SCSS, minificação de CSS/JS, otimização de imagens)
- **Vercel** — deploy contínuo

### Dependências de desenvolvimento
- `gulp` — task runner
- `gulp-sass` — compilação SCSS
- `gulp-clean-css` — minificação de CSS
- `gulp-uglify` — minificação de JavaScript
- `gulp-imagemin` — otimização de imagens
- `sass` — compilador SCSS

---

## 📁 Estrutura do projeto

```
clone_disneyplus/
├── src/
│   └── styles/        # Arquivos SCSS fonte
├── assets/
│   └── fonts/         # Fontes customizadas
├── gulpfile.js        # Configuração das tasks do Gulp
├── package.json
└── index.html
```

---

## ▶️ Como rodar localmente

**Pré-requisitos:** Node.js instalado

```bash
# Clone o repositório
git clone https://github.com/VinnMac/disney-plus-clone

# Entre na pasta
cd disney-plus-clone

# Instale as dependências (inclui Gulp e todos os plugins)
npm install

# Modo desenvolvimento com watch (recompila ao salvar)
npm run dev

# Gerar build de produção
npm run build
```

> `npm run dev` → executa `gulp watch` — recompila automaticamente ao salvar  
> `npm run build` → executa `gulp` — gera os arquivos finais otimizados

---

## 📚 O que aprendi

- Configuração e uso do **Gulp** para automatizar tarefas repetitivas
- Organização de projetos com separação entre código fonte e build
- Uso de **SCSS** com variáveis, mixins e importações modulares
- Otimização de assets (CSS, JS e imagens) para produção
- Técnicas de layout responsivo para replicar interfaces complexas

---

## 👨‍💻 Autor

**Vinícius Machado**
- GitHub: [@VinnMac](https://github.com/VinnMac)
- LinkedIn: [vinn-machado](https://www.linkedin.com/in/vinn-machado/)

---

*Projeto desenvolvido durante o curso Desenvolvedor Full Stack Python — EBAC*
