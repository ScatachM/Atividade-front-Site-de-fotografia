# Teixonobre Photos

🌐 **English** | [Português](README.pt-BR.md)

A one-page website for a fictional photography and video company. It was built as a **Front-end course project**, recreating a layout provided by the teacher using only **HTML and CSS**.

## Features

- **Header** with the company name and a navigation menu (Sobre, Serviços, Fotos, Contato)
- **Hero section** with a full-width background photo, a dark overlay, centered text and a "Ver mais" button
- **About section** with a call-to-action button ("Contratar agora")
- **Services section** with four cards (photography, film editing, image capture and image editing), each with an icon and a description
- **Photo gallery** in a 6-column CSS Grid: 3 photos on the first row and 2 centered photos on the second, with rounded corners and a hover effect
- **Contact and company section** with address, phone, email and a short company description
- **Footer** with copyright and a "Voltar para o topo" (back to top) link
- Smooth scrolling (`scroll-behavior: smooth`)

## Technologies

- HTML5
- CSS3 (Flexbox, CSS Grid, transitions, `object-fit`)
- [Google Fonts](https://fonts.google.com/): Cormorant Garamond (headings) and Montserrat (body text)
- [Font Awesome 6](https://fontawesome.com/) for the service icons

## Project structure

```
.
├── index.html
├── estilo.css
├── README.md
├── README.pt-BR.md
└── img/
    ├── logo.png
    ├── foto para 2 seção.png      # hero background
    ├── foto flor branca.jpg
    ├── foto paisagem.jpg
    ├── foto guitarra.jpg
    ├── foto borboleta.jpg
    ├── foto boneca.jpg
    ├── telefone icone pequeno.png
    └── mail icone pequeno.png
```

## How to run

1. Download or clone this repository.
2. Make sure the `img` folder is in the same directory as `index.html`.
3. Open `index.html` in your browser, or use the **Live Server** extension in VS Code.

> An internet connection is needed to load the Google Fonts and Font Awesome files.

## Color palette

| Color | Hex | Use |
|-------|-----|-----|
| Navy | `#071526` | Header, footer, text |
| Green | `#174D3B` | "Sobre" section |
| Gold | `#C58A3A` | Hover effects and highlights |
| Purple | `#4B174F` | Service icons |
| Cream | `#F3EBDD` | Footer text |

## Possible improvements

- Make the layout fully responsive for tablets and phones (media queries)
- Link the menu items to the page sections
- Add the social media icons (Facebook, Instagram and GitHub)
- Replace the placeholder (Lorem ipsum) text and contact details with real content

## Author

Developed by **[Your name]** as an assignment for the Front-end course.
