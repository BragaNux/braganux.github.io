# braganux.github.io

Código do meu portfólio, no ar em **[braganux.github.io](https://braganux.github.io)**, com a versão em inglês em **[braganux.github.io/en](https://braganux.github.io/en/)**.

Uma página em português e a mesma página em inglês, em HTML, CSS e JavaScript puros, sem framework nem build. Um botão PT | EN no topo troca de idioma. O tema claro e escuro segue o sistema, e todas as animações respeitam a opção de reduzir movimento.

## O que tem na página

- Abertura com as letras do nome subindo, frases sendo digitadas e a faixa das linguagens dos meus repositórios
- Gráfico com os 49 repositórios no tempo, desenhado em SVG a partir dos dados no próprio `index.html`, com as faixas de onde eu estava em cada época
- Cases dos projetos principais, com o fluxo de cada arquitetura e as telas do app Panela
- Mapa de habilidades clicável, que mostra em quais projetos usei cada tecnologia
- Linha do tempo da experiência que se desenha conforme a rolagem
- A cobrinha do gráfico de contribuições, gerada todo dia pelo workflow do repositório [BragaNux/BragaNux](https://github.com/BragaNux/BragaNux)

## Estrutura

```
index.html      página inteira em português: estilos, conteúdo e scripts
en/index.html   a mesma página em inglês
img/            foto, telas do Panela, ícones e as imagens de prévia para redes sociais
```

## Rodar localmente

```bash
python3 -m http.server 8000
```

Depois abra http://localhost:8000. O deploy é automático pelo GitHub Pages a cada push na `main`.
