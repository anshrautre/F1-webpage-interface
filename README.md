# Formula 1 – Drivers & Teams Interface

A front-end Formula 1 themed website built with **HTML and CSS**. The project presents selected F1 drivers and racing teams in a simple, visual interface, with a navigation bar, driver cards, team sections, and hover-based effects.

## Features

- **Navigation bar** with links to the Home, Drivers, Teams, and About sections.
- **Driver section** displaying driver images and details such as name, age, racing number, and Grand Prix podium information.
- **Driver dropdown content** with team information.
- **Teams section** featuring Mercedes, Ferrari, and Red Bull Racing.
- **Hover effects** that reveal additional driver details and alternate team-car images.
- **F1-inspired styling** using a blue and sky-blue colour palette, borders, spacing, and positioned elements.
- External fonts and icons loaded from Google Fonts and Remix Icon.

## Technologies Used

- HTML5
- CSS3
- Google Fonts (Roboto)
- Remix Icon

## Project Structure

```text
F1-Interface/
├── index.html
├── style.css
└── Videos & imgs/
    └── hero-video.mp4
```

Keep the HTML and CSS filenames aligned with the link in `index.html`. Place the hero video in the project folder and update the `<source>` path to a relative path, for example:

```html
<source src="Videos & imgs/hero-video.mp4" type="video/mp4">
```

The current HTML contains a local Windows file path for the video, so that path must be changed before the project will work on another computer.

## How to Run

1. Download or clone this repository.
2. Make sure `index.html` and `style.css` are in the same folder.
3. Add the hero video to the project folder and update its source path as described above.
4. Open `index.html` in a web browser.

No package installation or build process is required.

## What I Practised

While building this project, I practised:

- Structuring a multi-section webpage with HTML.
- Styling layouts using CSS properties such as `position`, `display`, `margin`, `padding`, and `border`.
- Using CSS pseudo-classes such as `:hover` to create interactive visual effects.
- Working with background images and external image resources.
- Linking navigation items to page sections using HTML IDs.

## Note

This is a learning and front-end practice project. Driver details and team information are example content in the page and may not reflect the latest official Formula 1 statistics. Images, fonts, icons, and other externally hosted assets require an internet connection.

---

**Built as an HTML & CSS practice project.**
