# 📘 Primeiros Passos com HTML

Este é um projeto introdutório com HTML que demonstra os conceitos básicos da linguagem, estrutura de uma página web e uso de elementos como listas, formulários, links e âncoras. O conteúdo está organizado em seções temáticas para facilitar o aprendizado e a navegação.

## 🔖 Índice de Tópicos

- [Estrutura Básica de um HTML](#estrutura-básica-de-um-html)
- [Listas Ordenadas e Não Ordenadas](#listas)
- [Trabalhando com Formulários](#trabalhando-com-formulários)
- [Como inserir Imagens](#imagens)
- [Como inserir Tabelas](#tabelas)
- [Como inserir Vídeos](#videos)
- [Links de Referência](#links-de-referência)

## 🧱 Estrutura Básica do HTML

O arquivo começa com a declaração `<!DOCTYPE html>` para indicar que a página segue o padrão **HTML5**. Ele é composto por:

- `<html>`: Elemento raiz da página.
- `<head>`: Contém informações *meta*, como charset, viewport e título.
- `<title>`: Define o nome exibido na aba do navegador.
- `<body>`: Inclui todo o conteúdo visível como textos, imagens, listas e formulários.

## 📝 Listas em HTML

O projeto apresenta a diferença entre:

- **Listas Ordenadas (`<ol>`)**: indicam sequência ou ordem.
- **Listas Não Ordenadas (`<ul>`)**: representam itens sem ordem específica.

## 🧾 Trabalhando com Formulários

Inclui exemplos práticos de:

- Campos de texto (`<input type="text">`)
- Botões de opção (`<input type="radio">`)
- Caixas de seleção (`<input type="checkbox">`)
- Botão de envio (`<input type="submit">`)

## 🖼️ Como inserir Imagens

Para inserir imagens, utiliza-se a tag `<img>` com o atributo `src` que especifica o caminho da imagem, que pode ser local (importante salvar na pasta `assets`). O formato da imagem também interfere.

> **Importante:** A diferença entre os arquivos **PNG** e **JPG**:  
> - **JPG** ocupa menos espaço por comprimir a imagem, mas perde qualidade e resolução.  
> - **PNG** é um arquivo mais pesado, mas suporta transparência, ideal para logos e labels.

**Uso recomendado:**  
- JPG para fotos  
- PNG para logos e labels

Ao diminuir a largura de uma imagem, a altura é ajustada proporcionalmente para evitar distorções.

## 📊 Como usar Tabelas

Para criar uma tabela em HTML, utiliza-se a tag `<table>` que contém as linhas (`<tr>`). Dentro das linhas, as células podem ser de cabeçalho (`<th>`) ou dados (`<td>`). Geralmente a primeira linha contém os cabeçalhos para identificar as colunas.

A aparência da tabela pode ser personalizada com CSS para melhorar a legibilidade e o estilo.

## 🎥 Como inserir Vídeos

Para inserir vídeos em uma página HTML, geralmente usamos a tag `<iframe>`, que permite incorporar vídeos de plataformas como o YouTube diretamente na página. Para isso, é necessário usar o link de incorporação (embed) fornecido pelo próprio YouTube, e não o link padrão do vídeo.

Assim, o vídeo fica visível e pode ser reproduzido dentro da página sem que o usuário precise sair do site.

## 🔗 Links de Referência

Links úteis para aprender mais sobre HTML e desenvolvimento web:

- [DIO](http://dio.me)
- [W3Schools - HTML](https://www.w3schools.com/html/)
- [MDN Web Docs - HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [W3C - Especificação HTML5.2](https://www.w3.org/TR/html52/)
- [Curso de HTML5 e CSS3 - Curso em Vídeo](https://www.youtube.com/watch?v=4dQtz1PpY9A)
- [HTML Básico - Programação Web - Gustavo Guanabara](https://www.youtube.com/watch?v=epDCjksKMok)
- [HTML para Iniciantes - Hora de Codar](https://www.youtube.com/watch?v=jgQjeqGRdgA)

## 🔗 Uso de Âncoras

O projeto utiliza o recurso de âncoras (`id`) e links internos (`<a href="#id">`) para navegação rápida entre seções da página.

## 🛠️ Tecnologias

- HTML5  
- Sem uso de CSS ou JavaScript neste módulo

## 🚀 Como usar

1. Copie o código para um arquivo `.html`.  
2. Abra no navegador.  
3. Navegue entre os tópicos usando o índice ou os botões "Voltar".

---

> Projeto educacional desenvolvido como parte do Módulo 1 da formação em HTML da **Bootcamp Santander**.
