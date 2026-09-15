# Stats Preview Card Component

Solução para o desafio **Card de Prévia de Estatísticas**, da disciplina de Design e Desenvolvimento Frontend (ADS - Unipar).

## 🎯 Sobre o desafio

O objetivo era construir um componente de card com:

- Um lado com título, descrição e uma lista de estatísticas;
- Outro lado com uma imagem/ilustração com sobreposição de cor;
- Layout responsivo (empilhado no mobile, lado a lado no desktop).

## 🛠️ Tecnologias utilizadas

- HTML5 semântico (`main`, `article`, `section`, `aside`, `dl`/`dt`/`dd`)
- CSS3 (Flexbox, variáveis CSS, media queries para responsividade)

## 📱 Responsividade

- **Mobile:** imagem no topo, conteúdo abaixo, tudo centralizado.
- **Desktop (a partir de 1040px):** imagem à direita, conteúdo à esquerda, alinhado ao início.

## 🎨 Paleta de cores

| Cor | Uso |
|---|---|
| `hsl(233, 47%, 7%)` | Fundo da página |
| `hsl(244, 38%, 16%)` | Fundo do card |
| `hsl(277, 64%, 61%)` | Destaque no título e nos números |
| `hsl(0, 0%, 100%)` | Título e valores das estatísticas |
| `hsla(0, 0%, 100%, 0.75)` | Parágrafo de descrição |
| `hsla(0, 0%, 100%, 0.6)` | Rótulos das estatísticas |

## 📁 Estrutura do projeto

```
stats-preview-card/
├── index.html
├── style.css
├── images/
│   └── image-header-desktop.svg
└── README.md
```

> Observação: a imagem lateral foi construída como uma ilustração SVG abstrata
> (rede de pontos conectados), no lugar de uma foto, para evitar o uso de
> imagens de terceiros com direitos autorais.

## ▶️ Como visualizar

Basta abrir o arquivo `index.html` em qualquer navegador, ou usar a extensão
"Live Server" no VS Code.

## 👤 Autor

Projeto desenvolvido como trabalho acadêmico — Curso de Análise e
Desenvolvimento de Sistemas (Unipar).
