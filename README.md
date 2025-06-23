
# QSW Viewer

📅 A minimalist, full-screen viewer of the current Quarter, Sprint, and Week. Designed for dashboards, Agile boards, or personal use. Sprints are calculated in six-week blocks by default (change with `?weeks=NUMBER`).

## 🔗 Live Example

[https://\<your-username\>.github.io/\<repo-name\>](https://<your-username>.github.io/<repo-name>)

## 🎨 Usage

### Default view

`https://<your-site>.github.io/`

### Themed view

`https://<your-site>.github.io/?fancy=sunset`

### Custom background and text colors

`https://<your-site>.github.io/?bg=black\&fg=white`

### Image/GIF background

`https://<your-site>.github.io/?img=https://example.com/wave.gif`

### Add links

`https://<your-site>.github.io/?links=Firepoker|https%3A%2F%2Ffirepoker.app%2F%23%2Fgames%2Fnew`

### Custom sprint length

`https://<your-site>.github.io/?weeks=4`

### QSW override

`https://<your-site>.github.io/?q=3&s=1&w=1`

When any of the `q`, `s`, or `w` parameters is present, the displayed Quarter,
Sprint, and Week won't be calculated from the current date.

### Fancy + Links

`https://<your-site>.github.io/?fancy=neon\&links=Board|https%3A%2F%2Ftasks.com`

## 🧪 Available themes

* `sunset`
* `neon`
* `ocean`
* `calm`

## 🛠 Tech

* 🧼 Pure HTML + JS
* 🧩 GitHub Pages compatible
* 🪶 No framework dependencies
* ⏰ Local clock under the QSW display (updates every minute)

