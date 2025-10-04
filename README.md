# Trabalho Prático 05 - Semanas 7 e 8

**Páginas de detalhes dinâmicas**

Nessa etapa, vamos evoluir o trabalho anterior, acrescentando a página de detalhes, conforme o  projeto escolhido. Imagine que a página principal (home-page) mostre um visão dos vários itens que existem no seu site. Ao clicar em um item, você é direcionado pra a página de detalhes. A página de detalhe vai mostrar todas as informações sobre o item do seu projeto. seja esse item uma notícia, filme, receita, lugar turístico ou evento.

Leia o enunciado completo no Canvas. 

**IMPORTANTE:** Assim como informado anteriormente, capriche na etapa pois você vai precisar dessa parte para as próximas semanas. 

**IMPORTANTE:** Você deve trabalhar e alterar apenas arquivos dentro da pasta **`public`,** mantendo os arquivos **`index.html`**, **`styles.css`** e **`app.js`** com estes nomes, conforme enunciado. Deixe todos os demais arquivos e pastas desse repositório inalterados. **PRESTE MUITA ATENÇÃO NISSO.**

## Informações Gerais

- Nome: Ítalo Eduardo Carneiro da Silva
- Matricula: 898961
- Proposta de projeto escolhida: (Organização e equipes) - Escolas
- Breve descrição sobre seu projeto: Este projeto é uma Landing Page  moderna e responsiva, desenvolvida para simular o website institucional da Escola Estadual fictícia Florentino Arnaldo Coelho.

O principal objetivo é demonstrar a aplicação prática de HTML, CSS e o framework Bootstrap para criar uma experiência de usuário (UX) clara e envolvente. A página destaca os pilares de uma instituição de ensino de excelência: Missão e Valores, Projetos de Destaque (como Iniciação Científica e Cultura) e um Fluxo de Pré-Matrícula direto.

O design foi pensado para transmitir confiança, profissionalismo e dinamismo, utilizando uma paleta de cores azul e um layout limpo para facilitar a navegação e a comunicação com a comunidade escolar.

## Print da Home-Page

<<  COLOQUE A IMAGEM AQUI >>

## Print da página de detalhes do item

<<  COLOQUE A IMAGEM AQUI >>

## Cole aqui abaixo a estrutura JSON utilizada no app.js

```javascript
const dados = [
  {
    "id": 1,
    "titulo": "Prefeitura Lança Plano de Mobilidade Urbana",
    "descricao": "Novo plano do transporte público.",
    "conteudo": "A Prefeitura apresentou nesta segunda-feira um novo plano de mobilidade urbana.",
    "categoria": "Cidades",
    "autor": "Joana Ribeiro",
    "data": "2025-03-30",
    "imagem": "img/mobilidade.jpg"
  }
]
```