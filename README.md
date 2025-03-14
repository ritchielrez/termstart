<p align="center"><img src=".assets/gruvbox-dark.png" /><p>

<p align="center">The idea is to have a minimal but functional home page for your browser.</p>

<p align="center"> <a href="https://ritchielrez.github.io/termstart" target="_blank"><img src="https://forthebadge.com/images/badges/check-it-out.svg"/></a></p>

---

<p align="center"> <img src="https://forthebadge.com/images/badges/built-with-love.svg"/> <img src="https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg"/> <img src="https://forthebadge.com/images/badges/powered-by-black-magic.svg"/> </p>

## Installation

### As an extension

1. Clone this repository
   - `git clone https://github.com/ritchielrez/termstart`

#### Firefox

1. Go to `about:debugging`.
2. Click `This Firefox`.
3. Click `Load Temporary Add-on`.
4. Select `index.html` from the cloned directory.

#### Chrome / Chromium / Brave / ...

1. Go to `chrome://extensions`.
2. Enable `Developer Mode` in the top-right corner of the page.
3. In the top-left corner of the page, click `Load Unpacked`.
4. Select the cloned folder.

### As a startpage

If you use a browser which doesn't support adding 3rd party extensions, you can simply add `https://ritchielrez.github.io/termstart` as your startpage.

## Usage

| Command/key   | What it does                    | Example                   |
| :-:           | :-:                             | :-:                       |
| `Enter/Space` | Focus prompt                    |                           |
| `ls`          | list links                      |                           |
| `clear`       | clear the "terminal"            |                           |
| `help`        | show available commands         |                           |
| `open`        | open a link                     | `open github`             |
| `search`      | search for a term on ddg/google | `search "github"`         |
| `search -c`   | change search engine            | `search -c ddg or google` |
| `del`         | deletes added site              | `del github`              |
| `add`         | add a site                      | `add github github.com`   |
| `theme`       | change theme                    | `theme gruvbox-dark`      |
| `themes`      | list all themes                 |                           |
| `engine`      | change search engine            | `engine google`           |
| `engines`     | list all search engines         |                           |

## Themes

Look into the `css/themes.css` file to learn about all the available themes.

## Contributing

Feel free to open issues, suggesting features or other things!

See [CONTRIBUTING.md](https://github.com/yrwq/termstart/blob/main/CONTRIBUTING.md)
