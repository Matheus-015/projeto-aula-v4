# 🚀 Portfólio Avançado v4 - Multi-page + Responsividade

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Flexbox](https://img.shields.io/badge/Flexbox-1572B6?style=for-the-badge)

Quarta versão do portfólio desenvolvido no curso.
Agora o projeto conta com responsividade completa, três páginas conectadas, currículo detalhado, além de boas práticas de organização com CSS modularizado.

# ✨ Novas Funcionalidades
- **📱 Layout** responsivo com media queries

# 🛠️ Tecnologias Utilizadas
- HTML5 semântico
- CSS3 com variáveis e media queries
- Flexbox para layout responsivo
- Google Fonts (Krona One + Montserrat)
- Metodologia BEM para nomenclatura

# 🎯 Conceitos Aplicados
````css
@media (max-width: 1200px) {
  .apresentacao {
    flex-direction: column-reverse;
    padding: 5%;
  }
}
````

# 📁 Estrutura do Projeto
```text
projeto-aula-v4/
├── index.html           # Página inicial (Home)
├── about.html           # Página "Sobre mim"
├── curriculo.html       # Página de currículo
├── css/
│   └── style.css        # Estilos globais e responsividade
├── assets/
│   ├── github.png       # Ícone do GitHub
│   ├── linkedin.png     # Ícone do LinkedIn
│   ├── twitch.png       # Ícone da Twitch
│   └── imagem.png       # Imagem de perfil
└── README.md
````

# 🔧 Como Executar
```text
git clone https://github.com/Matheus-015/projeto-aula-v4.git
````

# 📊 Evolução do Projeto
- v1 → Estrutura HTML básica
- v2 → Layout com Flexbox e estilização
- v3 → Multi-páginas + variáveis CSS
- v4 (atual) → Responsividade, currículo detalhado e refinamento visual
