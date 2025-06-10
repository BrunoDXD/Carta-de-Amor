# Carta de Amor Digital

Uma página web romântica para o Dia dos Namorados com design elegante em tema escuro.

## Descrição

Este projeto é uma carta de amor digital interativa criada para o Dia dos Namorados. A página apresenta um design elegante com tema escuro e detalhes em rosa, contendo:

- Mensagem romântica personalizada
- Foto do casal
- Contador que mostra há quanto tempo o relacionamento começou
- Corações animados flutuando pela tela
- Botão de surpresa que revela uma mensagem especial e toca uma música

## Estrutura de Arquivos

```
carta_de_amor.html    # Arquivo principal HTML
img/                  # Pasta de imagens
  └── eueela.jpeg     # Foto do casal
msc/                  # Pasta de músicas
  └── O Meu Sangue Ferve Por Você Sidney Magal Neto.mp3
```

## Funcionalidades

- **Design Responsivo**: Adaptável a diferentes tamanhos de tela
- **Contador Dinâmico**: Calcula e exibe o tempo de relacionamento em anos, meses, dias, horas e segundos
- **Animações**: Corações flutuantes com tamanhos e velocidades variados
- **Reprodutor de Música**: Integrado à mensagem de surpresa
- **Tema Escuro**: Interface elegante com fundo escuro e detalhes em rosa

## Como Usar

1. Abra o arquivo `carta_de_amor.html` em qualquer navegador web moderno
2. O contador começará automaticamente a calcular o tempo desde 22/10/2020
3. Clique no botão "Clique para uma surpresa" para revelar a mensagem especial e tocar a música

## Personalização

Para personalizar esta carta para seu próprio uso:

- Substitua a imagem em `img/eueela.jpeg` por sua própria foto
- Edite as mensagens no arquivo HTML
- Altere a data no contador (linha 377: `const startDate = new Date('2020-10-22T00:00:00');`)
- Substitua o arquivo de música em `msc/` por sua própria música

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript