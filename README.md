<div align="center">

# Kissan-Code

### Learn programming through familiar village work.

![HTML](https://img.shields.io/badge/HTML-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?logo=css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

[Explore](#explore) · [Run locally](#run-locally) · [How it works](#how-it-works) · [Contribute](#contributing)

</div>

Kissan-Code introduces computer-science ideas through farming, livestock, water management, crafts and other everyday activities. The main page contains **100 interactive flashcards** and a multiple-choice quiz. A separate Urdu reference page presents village-work examples alongside coding concepts.

## Explore

| Feature | How to use it |
| --- | --- |
| Flip a flashcard | Click a village activity to reveal its programming analogy |
| Filter by topic | Choose a category above the card grid |
| Shuffle | Mix the cards in the currently selected category |
| Quiz | Match a coding concept to an activity, read feedback and continue |
| Urdu reference | Open [`village-coding-concepts.html`](village-coding-concepts.html) |

The examples are learning analogies, intended as an accessible introduction rather than an executable programming course.

## Run locally

Download the repository or clone it:

```sh
git clone https://github.com/adeelfalaksher900-creator/Kissan-Code.git
cd Kissan-Code
```

Open `index.html` in a modern browser. No package installation, account, API key or backend is required.

For an HTTP preview, Python 3 can serve the folder:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Visit **http://127.0.0.1:8000**. Google Fonts are requested by the main page; the browser's fallback fonts apply when that service is unavailable.

## How it works

The application consists of two standalone HTML documents. The main page embeds its card data, CSS and JavaScript. Browser event handlers render the grid, filter and shuffle cards, flip their faces and update the in-memory quiz score. Reloading the page starts a new session.

| File | Contents |
| --- | --- |
| `index.html` | Interactive cards, topic filters, shuffle and quiz |
| `village-coding-concepts.html` | Urdu village-work reference |
| `README.md` | Usage and contributor guide |

## Publish

Serve this folder with any static website host, using `index.html` as the entry page. There is no build command or generated output directory.

## Contributing

Useful contributions include clearer analogies, Urdu and Roman Urdu language review, keyboard interaction improvements and quiz corrections. Submit a focused pull request for the owner's review. Keep a card's activity, concept and explanation consistent, and check category filters and quiz feedback after changing the dataset.

No automated test suite or package manifest is currently included. A repository-wide license file has not been added; confirm reuse terms with the owner before redistribution.
