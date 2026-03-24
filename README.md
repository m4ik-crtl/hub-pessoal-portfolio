# 💻 Hub Pessoal / Portfólio Single-Page

Um hub pessoal moderno, responsivo e minimalista, ideal para desenvolvedores de software, engenheiros e designers. Desenvolvido com uma estética "Dark/Neon Cyber" e efeitos avançados de **Glassmorphism** (vidro fosco).

## ✨ Funcionalidades

- **Design Dark Mode Nativo:** Fundo escuro de alto contraste focado na legibilidade e conforto visual, com detalhes luminosos em verde neon.
- **Glassmorphism:** Cards com efeito de vidro fosco, transparências e reflexos dinâmicos ao passar o mouse (shimmer effect).
- **Background Animado:** Bolhas de luz ambiente (blobs) flutuantes e animadas em puro CSS, criando uma atmosfera tecnológica profunda.
- **Animações de Entrada (Staggering):** Os cards entram na tela de forma suave e sequencial usando Vanilla JavaScript.
- **Totalmente Responsivo:** Layout em CSS Grid que se adapta perfeitamente a smartphones, tablets e monitores ultrawide.
- **Tipografia Híbrida:** Uso estratégico da fonte `Poppins` para títulos limpos e `Fira Code` (monoespaçada) para detalhes técnicos e tags, simulando a interface de um editor de código.

## 🚀 Tecnologias Utilizadas

Este projeto foi construído sem frameworks pesados, garantindo máxima performance e carregamento instantâneo:

- **HTML5:** Semântica e estruturação do hub.
- **CSS3:** Variáveis nativas, Flexbox, CSS Grid, animações (`@keyframes`), filtros (`backdrop-filter`, `blur`) e degradês.
- **JavaScript (Vanilla JS):** Lógica simples para controle das animações de entrada do DOM.
- **[FontAwesome 6.5](https://fontawesome.com/):** Para os ícones de redes sociais e categorias.
- **[Google Fonts](https://fonts.google.com/):** Fontes `Poppins` e `Fira Code`.

## 🛠️ Como usar e executar

Como é um projeto puramente estático (apenas Front-End base), você não precisa instalar nenhuma dependência como Node.js ou npm.

1. Faça o clone ou o download deste repositório.
2. Extraia os arquivos.
3. Dê um duplo clique no arquivo `index.html` para abri-lo diretamente no seu navegador padrão.
4. (Opcional) Utilize a extensão *Live Server* do VS Code para visualizar as edições em tempo real.

## 🎨 Como Personalizar

Você pode facilmente adaptar este template para o seu próprio uso modificando o arquivo HTML:

- **Alterar o nome e cargo:** Edite os textos dentro da tag `<header class="header">`.
- **Mudar os links sociais:** Vá até o card de "Contato" e substitua as `<span>` por tags de âncora `<a>` com os seus links:
  ```html
  <a href="URL_DO_SEU_LINKEDIN" target="_blank" class="tag"><i class="fab fa-linkedin"></i> LinkedIn</a>
- **Alterar Cores:** As cores base estão definidas nas classes .blob1, .blob2 e nos estilos .glass-card dentro da tag <style>. Você pode trocar os códigos Hex (ex: #00ff88) pelas cores do seu gosto.

## 📝 Licença
Este projeto é de código aberto. Sinta-se livre para usar, modificar e distribuir como quiser!

---
Gostaria que eu te ajudasse a transformar as `<span>` da área de contato em links clicáveis de verdade para o seu LinkedIn, GitHub e E-mail?
