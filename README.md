# Minimal Markdown Blog

This is a simple, Git-based blog system that uses Markdown files for content and GitHub Pages for hosting.

## How to Use

1. Fork this repository.
2. Update the `YOUR_USERNAME` and `YOUR_REPO` placeholders in `index.html` with your GitHub username and repository name.
3. Enable GitHub Pages in your repository settings, using the `main` branch as the source.
4. To add a new blog post:
   - Create a new Markdown file in the `posts` directory.
   - Name it with the format `YYYY-MM-DD-title-slug.md`.
   - Add front matter at the top of the file:
     ```
     ---
     title: Your Post Title
     date: YYYY-MM-DD
     tags: tag1, tag2
     ---
     ```
   - Write your post content in Markdown below the front matter.
5. Commit and push your changes.

Your blog will be available at `https://YOUR_USERNAME.github.io/YOUR_REPO/`.

For example mine is at: `https://jsameijeiras.github.io/jsa/`.

## Customization

You can customize the appearance of your blog by modifying the CSS in `index.html`.

## License

This project is open source and available under the [MIT License](LICENSE).
