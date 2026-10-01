# Teixonobre Photos

🌐 [English](README.md) | **Português**

Site de uma página para uma empresa fictícia de fotografia e vídeo. Foi desenvolvido como **projeto da disciplina de Front-end**, recriando um layout fornecido pelo professor usando apenas **HTML e CSS**.

## Funcionalidades

- **Cabeçalho** com o nome da empresa e menu de navegação (Sobre, Serviços, Fotos, Contato)
- **Seção principal (hero)** com foto de fundo em largura total, camada escura, texto centralizado e botão "Ver mais"
- **Seção Sobre** com botão de chamada para ação ("Contratar agora")
- **Seção de Serviços** com quatro cartões (fotografia, edição de filmes, captação de imagens e tratamento de imagens), cada um com ícone e descrição
- **Galeria de fotos** em CSS Grid de 6 colunas: 3 fotos na primeira linha e 2 fotos centralizadas na segunda, com bordas arredondadas e efeito ao passar o mouse
- **Seção de contato e empresa** com endereço, telefone, e-mail e uma breve descrição da empresa
- **Rodapé** com direitos autorais e link "Voltar para o topo"
- Rolagem suave (`scroll-behavior: smooth`)

## Tecnologias

- HTML5
- CSS3 (Flexbox, CSS Grid, transições, `object-fit`)
- [Google Fonts](https://fonts.google.com/): Cormorant Garamond (títulos) e Montserrat (texto)
- [Font Awesome 6](https://fontawesome.com/) para os ícones dos serviços

## Estrutura do projeto

```
.
├── index.html
├── estilo.css
├── README.md
├── README.pt-BR.md
└── img/
    ├── logo.png
    ├── foto para 2 seção.png      # fundo da seção principal
    ├── foto flor branca.jpg
    ├── foto paisagem.jpg
    ├── foto guitarra.jpg
    ├── foto borboleta.jpg
    ├── foto boneca.jpg
    ├── telefone icone pequeno.png
    └── mail icone pequeno.png
```

## Como executar

1. Baixe ou clone este repositório.
2. Verifique se a pasta `img` está no mesmo diretório que o `index.html`.
3. Abra o `index.html` no navegador ou use a extensão **Live Server** no VS Code.

> É necessária conexão com a internet para carregar o Google Fonts e o Font Awesome.

## Paleta de cores

| Cor | Hex | Uso |
|-----|-----|-----|
| Azul-marinho | `#071526` | Cabeçalho, rodapé, textos |
| Verde | `#174D3B` | Seção "Sobre" |
| Dourado | `#C58A3A` | Efeitos hover e destaques |
| Roxo | `#4B174F` | Ícones dos serviços |
| Creme | `#F3EBDD` | Texto do rodapé |

## Possíveis melhorias

- Tornar o layout totalmente responsivo para tablets e celulares (media queries)
- Vincular os itens do menu às seções da página
- Adicionar os ícones de redes sociais (Facebook, Instagram e GitHub)
- Substituir os textos de exemplo (Lorem ipsum) e os dados de contato por conteúdo real

## Autor

Desenvolvido por **[Seu nome]** como atividade da disciplina de Front-end.
