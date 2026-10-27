# Shaufy Yana Ezani — Portfolio

Personal portfolio website for **Shaufy Yana Ezani**, a Full-Stack Developer based in Petaling Jaya, Selangor, working with C# .NET, SQL Server and Flutter.

Built with plain HTML, CSS and JavaScript. No frameworks or build step are needed.

**Live site:** https://my-portfolio-olive-eight.vercel.app/

## Links

| | |
|---|---|
| Portfolio | [my-portfolio-olive-eight.vercel.app](https://my-portfolio-olive-eight.vercel.app/) |
| Resume | [Google Docs](https://docs.google.com/document/d/1jGD0g9AjKWZRXMMFtfcZwkOhfNg4QzetajnnmVnIMBY/edit?usp=sharing) |
| LinkedIn | [Shaufy Yana Ezani](https://www.linkedin.com/in/shaufy-yana-ezani-87220326a) |
| GitHub | [@yanaezani](https://github.com/yanaezani) |
| Email | [yanaezani48@gmail.com](mailto:yanaezani48@gmail.com) |

## Featured projects

| Project | Description | Links |
|---|---|---|
| **Fleetros** | Fleet and vehicle rental management mobile app (Capacitor, Tailwind CSS) | [Figma](https://www.figma.com/design/396GjLeePpXWoLVgZihiBI/Car-Rental-Booking-UI-Design?node-id=50-104&t=ujwlEURF6IPJt293-1) · [Demo](https://drive.google.com/file/d/1iu5YGeGjRU0_FXegRpyp3Tzj4lMs-a8w/view?usp=sharing) |
| **Travel App** | Location-based travel mobile app (Flutter, Google Maps API) | [Code](https://github.com/yanaezani/travel-app) · [Flow](https://drive.google.com/file/d/1HoOKVxkyww8PmneXzTiKbCQg875o9D_8/view?usp=drive_link) · [Screenshots](https://docs.google.com/document/d/14uCtgw0LRa6y-he3ib5jFQi-JzsBAN13ZexhyNznYIU/edit?tab=t.0#heading=h.skps0lrdr16l) · [Figma](https://www.figma.com/design/hrlPiQx58ksSLifEbhX8gc/Travel-Mobile-APP-UI?node-id=0-1&t=ujwlEURF6IPJt293-1) |
| **FloraHub** | Smart plant hydration system, IoT + mobile (Flutter, Spring Boot, Grafana) | [Code](https://github.com/yanaazani/final_year_project) · [Prototype demo](https://youtu.be/HdVnUw3bS9o?si=BRpx4HeIlFgp1YK0) · [App demo](https://youtu.be/grQzcS69L74?si=wfyU5wesjrSRP1ja) |

## Project structure

```
.
├── index.html      # Page content and structure
├── css/
│   └── style.css   # All styles, grouped by page section
└── js/
    └── main.js     # Fade-in-on-scroll animation
```

## Running locally

Open `index.html` in a browser. To serve it locally instead, run:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Updating content

All content lives in `index.html`, which has a comment above each section (`<!-- Projects Section -->`, etc.).

- **Add a job or qualification:** copy an `<article class="timeline-item reveal">` block in the Experience or Education section. Entries are listed newest first.
- **Add a project:** copy an `<article class="project-card reveal">` block in the Projects section and update the title, date, description, tech tags and links.
- **Add a skill:** add an `<li>` to the right `skill-category` list.
- **Change colours:** edit the variables under `:root` at the top of `css/style.css`.

Any element with the `reveal` class fades in as it scrolls into view.
