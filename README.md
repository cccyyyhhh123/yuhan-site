# Yuhan — personal site

Four pages, hand-written HTML and one stylesheet. No framework, no build step.

| File | What it is |
| --- | --- |
| `index.html` | Home: the lake at sunset, who I am, two photographs |
| `quote.html` | Eight quotes, each with who said it and where |
| `project.html` | Ideas I might build, who each one is for, how I would build it |
| `about.html` | What I am learning, what I built, how to reach me |

## The idea

Same recipe as the sites we study in Web Technologies:

- one text style set on `body`, everything inside inherits it
- one centred column on `main` (48rem)
- one `.quote` card class reused on every quote
- the footer by `id`, because every quote has its own `<footer>`

Photographs are mine, taken on campus. The two screenshots are of
[Ledger](https://cccyyyhhh123.github.io/ledger/), the project I built for the course.

## Run it

Open `index.html`, or serve the folder:

```
python -m http.server 8000
```

## Credits

Written by Yuhan Cai. Photos: my own. Type: the system UI font stack.
