# Blogging Website

This is a simple, user-friendly blogging website built with HTML, Tailwind CSS, Google Fonts, and Font Awesome. It features a clean, modern, and responsive design.

## Features

- Homepage listing latest blog posts
- Individual blog post pages
- Responsive and accessible design
- Easy to customize and extend

## Hosting and Domain Setup

This website is designed to be hosted easily on user-friendly platforms such as [Netlify](https://www.netlify.com/) or [Vercel](https://vercel.com/).

### Deploying on Netlify

1. Create a free account on Netlify.
2. Connect your GitHub repository or drag and drop the `blogging-website` folder in the Netlify dashboard.
3. Netlify will automatically deploy your site.
4. You can set up a custom domain in the Netlify dashboard under "Domain settings".

### Deploying on Vercel

1. Create a free account on Vercel.
2. Import your project from GitHub or use the Vercel CLI.
3. Vercel will build and deploy your site automatically.
4. Configure a custom domain in the Vercel dashboard.

### Local Testing

To test the website locally, you can use a simple HTTP server. For example, with Python 3 installed, run:

```bash
cd blogging-website
python3 -m http.server 8000
```

Then open your browser at `http://localhost:8000`.

## Customization

- Add new blog posts by creating new HTML files similar to `post.html`.
- Update the homepage (`index.html`) to link to new posts.
- Customize styles using Tailwind CSS utility classes.

## License

This project is open source and free to use.
