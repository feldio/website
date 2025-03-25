# My Hugo Site

This is a simple Hugo site project structure. Below are the details on how to set up and run the site.

## Project Structure

```
my-hugo-site
├── archetypes
│   └── default.md
├── content
│   └── _index.md
├── layouts
│   ├── _default
│   │   ├── baseof.html
│   │   ├── list.html
│   │   └── single.html
│   └── partials
│       └── header.html
├── static
│   └── css
│       └── styles.css
├── config.toml
└── README.md
```

## Getting Started

1. **Install Hugo**: Make sure you have Hugo installed on your machine. You can download it from [Hugo's official website](https://gohugo.io/getting-started/installation/).

2. **Clone the Repository**: Clone this repository to your local machine using:
   ```
   git clone <repository-url>
   ```

3. **Navigate to the Project Directory**:
   ```
   cd my-hugo-site
   ```

4. **Run the Hugo Server**: Start the Hugo server to view your site locally:
   ```
   hugo server
   ```

5. **Open Your Browser**: Go to `http://localhost:1313` to see your site in action.

## Customization

- **Content**: Add new content files in the `content` directory. You can create new pages or posts using the default archetype located in `archetypes/default.md`.
- **Layouts**: Modify the layout files in the `layouts` directory to change the appearance of your site.
- **Styles**: Update the CSS in `static/css/styles.css` to customize the look and feel of your site.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.