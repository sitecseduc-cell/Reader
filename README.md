# 📄 Reader - Leitor de PDF Minimalista

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
[![Tailwind CDN](https://img.shields.io/badge/Tailwind-CDN-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![pdf.js](https://img.shields.io/badge/pdf.js-Mozilla-FF5722?logo=mozilla&logoColor=white)](https://mozilla.github.io/pdf.js/)
[![Static Site](https://img.shields.io/badge/Site-Estático-brightgreen)](https://pt.wikipedia.org/wiki/S%C3%ADtio_web_est%C3%A1tico)

**Reader** é um leitor de PDF minimalista, construído totalmente em Vanilla JavaScript, HTML e Tailwind CSS. Ele usa a biblioteca `pdf.js` da Mozilla para renderizar arquivos PDF diretamente no navegador, sem a necessidade de um backend.

A aplicação é 100% client-side: o usuário seleciona um arquivo PDF local, e o JavaScript o processa e exibe, página por página. Nenhum dado é enviado para um servidor.



---

## 📜 Tabela de Conteúdos

* [Sobre o Projeto](#-sobre-o-projeto)
* [Principais Funcionalidades](#✨-principais-funcionalidades)
* [Tecnologias Utilizadas](#-tecnologias-utilizadas)
* [Como Usar (Localmente)](#-como-usar-localmente)
* [Como Fazer o Deploy](#-como-fazer-o-deploy)

---

## 📖 Sobre o Projeto

Este projeto foi criado para ser um visualizador de PDF leve, portátil e que funcione online ou offline. Ele demonstra o poder da biblioteca `pdf.js` da Mozilla para carregar e renderizar documentos complexos diretamente em um elemento `<canvas>` do HTML, oferecendo uma experiência de leitura fluida com controles de paginação básicos.

Toda a lógica está contida no `index.html` e é executada no navegador do usuário.

## ✨ Principais Funcionalidades

* **Upload de PDF Local:** Permite que o usuário carregue um arquivo PDF do seu próprio computador (`<input type="file">`).
* **Renderização no Canvas:** Exibe as páginas do PDF em um elemento `<canvas>` do HTML5.
* **Controles de Paginação:** Inclui botões de "Próxima Página" e "Página Anterior".
* **Contador de Páginas:** Mostra o número da página atual e o total de páginas do documento (ex: "Página 1 de 10").
* **Interface Limpa:** Estilizado com Tailwind CSS (via CDN) para um visual moderno.
* **Zero Dependências de Build:** Não requer `npm`, `node` ou qualquer processo de build. Tudo é carregado via CDN.
* **100% Estático:** Roda em qualquer servidor web simples ou até mesmo localmente.

## 🛠️ Tecnologias Utilizadas

* **HTML5**
* **Tailwind CSS (via CDN):** Para estilização da interface.
* **Vanilla JavaScript (ES6+):** Para toda a lógica de manipulação de DOM e paginação.
* **Mozilla `pdf.js` (via CDN):** A biblioteca principal que faz todo o trabalho de "parse" e renderização do PDF.
* **Lucide Icons (via CDN):** Para os ícones da interface.

---

## 🏃 Como Usar (Localmente)

Este projeto é 100% client-side e **não requer um servidor web** para funcionar (ao contrário de projetos que usam `fetch` para carregar dados JSON).

1.  Clone o repositório:
    ```bash
    git clone [https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git](https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git)
    cd SEU-REPOSITORIO
    ```

2.  Abra o arquivo `index.html` diretamente no seu navegador (ex: clicando duas vezes no arquivo).

3.  Clique no botão "Carregar PDF" (ou no ícone de upload) e selecione um arquivo PDF do seu computador.

4.  O PDF será carregado e renderizado, e você poderá usar os botões de paginação para navegar.

## 🚀 Como Fazer o Deploy

Este projeto é um **Site Estático**. Você pode fazer o deploy em qualquer serviço de hospedagem de sites estáticos, como **Vercel**, **Netlify** ou **GitHub Pages**.

1.  Envie seu repositório para o GitHub.
2.  Importe o repositório na Vercel ou Netlify.
3.  **Não é necessário um "Comando de Build" (Build Command)**. Deixe este campo em branco.
4.  **Não é necessário um "Diretório de Saída" (Output Directory)**.
5.  Clique em "Deploy".

A aplicação estará online e pronta para ser usada.
