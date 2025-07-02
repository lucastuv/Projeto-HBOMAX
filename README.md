<img src="assets/images/readme-images/cover.png">

<h1 align="center">Site HBO Max</h1>
<h4 align="center">Clone com modificações</h4>

<p align="center">
  O projeto é um clone do site <a href="https://www.hbomax.com/br/pt">HBO Max</a>, com o intuito de reproduzir a interface, com algumas modificações, aplicando os temas abordados ao longo das aulas de CSS da plataforma da <a href="https://dio.me">Digital Innovation One</a>.
</p>
<p align="center">
  O clone do site HBO Max serve como desafio para os alunos da plataforma testarem seus conhecimentos e colocarem em prática os recursos de HTML e CSS abordados nos cursos.
</p>

<a href="https://micheleambrosio.github.io/hbomax/">
  <img src="assets/images/readme-images/cover-2.png">
</a>

## 📎 Sumário

- [✨ Features](#features)
- [📦 Temas abordados](#topics)
- [🏆 Desafio](#challenges)
- [🌈 Demonstração](#demo)
- [� Melhorias Implementadas](#melhorias-implementadas)
- [�💻 Desenvolvedor](#author)
- [🎨 Autora do Projeto Original](#original-author)
- [📜 Licença](#licença)

<h2 id="features">✨ Features</h2>

- Menu de navegação
- Cabeçalho com animação gradiente
- Cards com os planos de assinatura animados
- Lista de filmes e séries disponíveis na plataforma
- Formulário de login
- Rodapé com links importantes
- UI Responsiva

**🚀 Melhorias adicionadas por Lucas Pimenta:**
- Carrossel interativo de filmes/séries com autoplay
- Seção de estatísticas com contadores animados
- Depoimentos de usuários com rating em estrelas
- FAQ interativo com accordion
- Login social (Google/Facebook)
- Animações de entrada por viewport
- Efeito parallax no scroll
- Performance otimizada com Intersection Observer

*As features são visuais, não possuindo integração com nenhuma API. O intuito do projeto é reproduzir a interface do site original, com algumas modificações.*

<h2 id="topics">📦 Temas abordados</h2>

O projeto possui como intuito aplicar os conceitos abordados na Trilha de CSS da <a href="https://dio.me">DIO</a>, ministrada pela instrutora <a href="https://github.com/micheleambrosio">Michele Ambrosio</a>.

Recursos CSS presentes no projeto:

- Fundamentos do CSS
- Grid Layout
- Flexbox
- Responsividade
- Pseudo-elementos
- Pseudo-classes
- Transformações 2D e 3D
- Transições e animações
- Tratamento de campos inválidos no formulário

<h2 id="challenges">🏆 Desafio</h2>

Como parte do desafio final da Trilha de CSS, o desenvolvedor deve reproduzir [esse projeto](https://micheleambrosio.github.io/hbomax/), sem realizar uma consulta do código final do site, presente na branch `master` deste repositório.

Para auxiliar na reprodução, utilize a branch `template-desafio`. Faça um fork do projeto em sua conta do GitHub.

Dentro da branch `template-desafio`, você encontrará na pasta `assets/images` todos os arquivos de imagens que você irá precisar para utilizar no projeto.

Caso deseje, adicione as variáveis CSS abaixo, que contém todas as cores e gradientes utilizados no projeto:

```css
  :root {
    --primary-color: #020228;
    --secondary-color: #ff00e5;
    --tertiary-color: #b535f6;
    --btn-bg-color-gradient: linear-gradient(
      45deg,
      #9b34ef 0%,
      #490cb0 20%,
      transparent 50%
    );
    --btn-link-bg-color: #fff;
    --btn-link-color: #000;
    --card-bg-color: linear-gradient(0deg, transparent, #3b1e63);
    --divider-bg-color: linear-gradient(
      90deg,
      #5516ba,
      rgba(255, 0, 229, 0.5) 80%
    );
    --nav-bg-color: rgba(0, 0, 0, 0.3);
    --text-color: #fff;
    --link-color: #9e86ff;
    --form-bg-color: rgba(211, 211, 211, 0.06);
    --form-field-bg-color: rgba(0, 0, 0, 0.2);
    --form-field-border: 1px solid rgba(255, 255, 255, 0.7);
    --form-field-placeholder: rgba(255, 255, 255, 0.7);
    --form-field-error: rgb(255, 76, 76);

    scroll-behavior: smooth;
  }
```

*A propriedade `scroll-behavior: smooth` irá fazer com que os links que levam para uma outra sessão do site, da mesma página, faça uma transição suave ao realizar a rolagem.*

Para implementar a barra de rolagem personalizada, como no exemplo, adicione na sua folha de estilos o seguinte trecho CSS:

```css
  /* Custom Scroll */

  ::-webkit-scrollbar {
    width: 8px;
  }

  ::-webkit-scrollbar-thumb {
    background: var(--tertiary-color);
    border-radius: 10px;
  }

  ::-webkit-scrollbar-thumb:hover {
    background: var(--secondary-color);
  }
```

O resultado final do projeto deve contemplar todas as [features](#features) presentes no <a href="https://micheleambrosio.github.io/hbomax/">resultado final</a>.

As fontes utilizadas no projeto foram:

- [Raleway](https://fonts.google.com/specimen/Raleway)
- [Quicksand](https://fonts.google.com/specimen/Quicksand?query=quicksand)
  
```css
@import url("https://fonts.googleapis.com/css2?family=Raleway:wght@300;400;500;600;700&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;700&display=swap");
```

*Para melhor orientação, assista ao vídeo de instruções do desafio, que está disponibilizado no Módulo 3 da Trilha de CSS.*


<h2 id="demo">🌈 Demonstração</h2>

🔗 **Repositório GitHub:** [https://github.com/lucastuv/Projeto-HBOMAX](https://github.com/lucastuv/Projeto-HBOMAX)

🌐 **Demo Original:** Você pode acessar ao resultado final do projeto original [clicando aqui](https://micheleambrosio.github.io/hbomax/).


<h2 id="author">💻 Desenvolvedor</h2>
<p>
    <img align=left margin=10 width=80 src="https://avatars.githubusercontent.com/u/lucastuv?v=4"/>
    <p>&nbsp&nbsp&nbspLucas Pimenta<br>
    &nbsp&nbsp&nbsp<a href="https://github.com/lucastuv">GitHub</a>&nbsp;|&nbsp;<a href="https://linkedin.com/in/lucas-pimenta">LinkedIn</a></p>
</p>
<br/><br/>

<h2 id="original-author">🎨 Autora do Projeto Original</h2>
<p>
    <img align=left margin=10 width=80 src="https://avatars.githubusercontent.com/u/55519539?v=4"/>
    <p>&nbsp&nbsp&nbspMichele Queiroz Ambrosio<br>
    &nbsp&nbsp&nbsp<a href="http://instagram.com/programi_">Instagram</a>&nbsp;|&nbsp;<a href="https://github.com/micheleambrosio">GitHub</a>&nbsp;|&nbsp;<a href="https://www.linkedin.com/in/michele-ambrosio-a4899661/">LinkedIn</a>&nbsp;|&nbsp;<a href="https://www.twitch.tv/michele_ambrosio">Twitch</a></p>
</p>
<br/><br/>

## 🚀 Melhorias Implementadas

Este projeto foi desenvolvido por **Lucas Pimenta** como um estudo avançado baseado no template original da **Michele Ambrosio**. As seguintes melhorias foram implementadas:

### ✨ **Novas Features Adicionadas:**
- 🎬 **Carrossel de filmes/séries** com navegação automática e manual
- 📊 **Seção de estatísticas** com contadores animados
- ⭐ **Depoimentos de usuários** com layout responsivo
- ❓ **FAQ interativo** com accordion animado
- 🔐 **Página de login aprimorada** com validação e opções sociais
- 🎨 **Animações CSS avançadas** com Intersection Observer
- 📱 **Responsividade premium** otimizada para todos os dispositivos

### 🛠️ **Tecnologias Utilizadas:**
- HTML5 semântico
- CSS3 com Grid, Flexbox e Custom Properties
- JavaScript ES6+ com APIs modernas
- Intersection Observer para animações
- Mobile-first responsive design
- Performance otimizada

### 📁 **Estrutura do Projeto:**
```
├── index.html              # Página principal
├── signIn.html             # Página de login
├── assets/
│   ├── css/
│   │   ├── styles.css      # Estilos principais
│   │   ├── animations.css  # Animações organizadas
│   │   └── signin.css      # Estilos da página de login
│   └── images/             # Assets de imagem fornecidos
├── README.md               # Documentação
└── LICENSE                 # Licença MIT
```

## 📜 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

<p>

---
⌨️ Desenvolvido com ❤️ por [Lucas Pimenta](https://github.com/lucastuv) 🚀<br>
🎨 Baseado no projeto original de [Michele Ambrosio](https://github.com/micheleambrosio) 😊