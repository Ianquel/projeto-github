# projeto-github

Projeto criado durante o Workshop GitHub da COTI Informática.

Este repositório contém um projeto front-end simples desenvolvido em HTML, CSS e JavaScript, criado como exercício prático durante o workshop.

## Tecnologias

- HTML5 — marcação das páginas.
- CSS3 — estilos e responsividade.
- JavaScript (ES6+) — comportamento e interatividade.

Possíveis arquivos e pastas do projeto:

- `index.html` — página principal.
- `css/` — arquivos CSS (por exemplo `styles.css`).
- `js/` — arquivos JavaScript (por exemplo `main.js`).
- `assets/` — imagens e outros recursos estáticos.

## Como abrir e rodar o projeto no VS Code

1. Instale o Visual Studio Code (VS Code) se ainda não tiver: https://code.visualstudio.com/
2. Clone este repositório ou faça download e abra a pasta do projeto no VS Code:

   - Pela linha de comando:
     ```bash
     git clone https://github.com/Ianquel/projeto-github.git
     cd projeto-github
     code .
     ```
   - Ou abra a pasta pelo menu "File > Open Folder..." no VS Code.

3. (Recomendado) Instale a extensão Live Server no VS Code:

   - Vá em Extensions (ou pressione Ctrl+Shift+X) e busque por "Live Server" (desenvolvedor: Ritwick Dey).
   - Clique em "Install".

4. Abra o arquivo `index.html` e execute com o Live Server:

   - Clique com o botão direito no arquivo `index.html` e selecione "Open with Live Server", ou
   - Clique em "Go Live" na barra de status do VS Code.

   Isso iniciará um servidor local (ex.: http://127.0.0.1:5500) e abrirá o projeto no navegador. Alterações nos arquivos serão recarregadas automaticamente.

5. Alternativa sem Live Server (usando Python):

   - Se você tiver Python 3 instalado, no terminal rode:
     ```bash
     python -m http.server 8000
     ```
   - Abra no navegador: http://localhost:8000

6. Alternativa com http-server (Node.js):

   - Se tiver Node.js/NPM instalado, execute:
     ```bash
     npx http-server -p 8080
     ```
   - Abra no navegador: http://localhost:8080

## Estrutura sugerida

````
projeto-github/
├─ index.html
├─ css/
│  └─ styles.css
├─ js/
│  └─ main.js
└─ assets/
   └─ logo.png
````

## Contribuições

Este projeto foi desenvolvido durante um workshop, então contribuições são bem-vindas para fins de aprendizado. Para contribuir:

1. Crie um fork do repositório.
2. Crie uma branch com sua feature ou correção: `git checkout -b minha-branch`.
3. Faça commits claros e envie um Pull Request (PR).

## Licença

Sinta-se à vontade para usar este material para aprendizado. Se desejar publicar, adicione um arquivo `LICENSE` (por exemplo MIT).

---

*README atualizado para o repositório `projeto-github`.*
