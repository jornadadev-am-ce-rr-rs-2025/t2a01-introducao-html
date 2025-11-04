# T2A01 - Introdução ao HTML

## 📘 Tópicos abordados

- O que é HTML e sua função na Web\
- Estrutura base de um documento HTML (boilerplate)\
- Elementos essenciais:
  - `<html>`, `<head>`, `<body>`\
  - `<title>` dentro do `<head>`\
- Títulos e semântica (do `<h1>` ao `<h6>`)\
- Importância do uso correto das tags e suas limitações\
- Espaços em branco e identação
  - Colocar tags uma ao lado da outra **não altera a saída visual**\
- Atributos de tags (`lang`, `title`, etc.)\
- Quebra de linha (`<br>`)\
- Comentários (`<!-- comentário -->`)\
- Importância da semântica para acessibilidade e boas práticas

---

## 💡 Resumo

Nesta aula, aprendemos como o HTML estrutura o conteúdo de uma página e
qual o papel de cada elemento básico.\
Vimos que o HTML **não define estilos nem comportamentos**, mas organiza
as informações para que o navegador e outros agentes possam
interpretá-las corretamente.

Também falamos sobre **semântica**, destacando a importância de usar as
tags conforme o significado, e não apenas pela aparência.

---

## 🧩 Exemplo prático

```html
<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Minha Primeira Página</title>
  </head>
  <body>
    <h1>Olá, Mundo!</h1>
    <h2>Este é o meu primeiro documento HTML.</h2>
    <h5>
      Adicionando uma quebra de linha <br />
      com a tag br.
    </h5>
    <!-- Este é um comentário -->
     <h4>Lorem ipsum, dolor sit amet <br> <!-- <= isso é quebra de linha -->
     consectetur adipisicing elit. Tempora, ab?
  </body>
</html>
```

---

## 🧭 Próximos passos

Na próxima aula, vamos aprofundar o uso de **elemento parágrafo**,
**listas**, e **landmarks**, explorando como o HTML dá estrutura e
significado ao conteúdo.
