# landing-page-exercise

Uma landing page estática criada como exercício do curso Full Stack Digital College. O projeto demonstra uma página promocional simples construída com HTML, CSS e JavaScript, contendo seção principal (hero), cards em destaque, área "Sobre nós", galeria de produtos e um menu responsivo.

**Status:** Concluído (template estático)

**Tecnologias:** HTML5, CSS3, JavaScript, Font Awesome

**Preview rápido**
- Abra o arquivo `index.html` no navegador.
- Ou rode um servidor local e acesse `http://localhost:8000`.
- Demo (GitHub Pages): https://carlosreiker.github.io/landing-page-exercise

**Screenshots**

- **Desktop:**

	![Desktop preview](images/screenshots/screenshot%20desktop.gif)

- **Mobile:**

	![Mobile preview](images/screenshots/screenshot%20mobile.gif)

- **Menu (hambúrguer):**

	![Menu hambúrguer preview](images/screenshots/screenshot%20menu%20hamburguer.gif)

**Recursos/Características**
- Navbar responsiva com botão mobile.
- Seção "Home" com imagem de destaque, título e ações.
- Seção "Em alta" com cards e avaliação com ícones.
- Seção "Sobre nós" com imagens e textos.
- Galeria de produtos com cards.
- Footer simples com créditos.

**Como executar (local)**
1. Método rápido: abra `index.html` com seu navegador (duplo clique ou `Abrir com > Navegador`).
2. Servidor HTTP simples (recomendado para evitar problemas com imports/paths):

```bash
cd /caminho/para/landing-page-exercise
python3 -m http.server 8000
# então abra http://localhost:8000
```

Alternativa (VS Code): instale a extensão "Live Server" e clique em "Go Live".

**Estrutura do projeto**

- `index.html` : página principal da landing.
- `css/` : arquivos de estilos.
	- `variables.css`
	- `navbar.css`
	- `styles.css`
- `js/` : scripts JavaScript (ex. `script.js`).
- `images/` : imagens usadas no layout, subdivididas em `about/`, `products/`, `trending/`.
- `LICENSE` : licença do projeto.

**Licença**
Veja o arquivo `LICENSE` neste repositório.

**Autor**
Carlos Reiker

**Créditos**
- Ícones via Font Awesome (link incluído em `index.html`).

