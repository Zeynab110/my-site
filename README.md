# Portfolio Website

A modern, responsive portfolio website built with Jekyll, inspired by contemporary design principles.

## Features

- ✅ Home page with profile photo and introduction
- ✅ About page with background, qualifications, and activities
- ✅ Projects page with Project 1 and Project 2 (Hour of Code)
- ✅ Navigation bar and footer
- ✅ Social media icons (GitHub, Codecademy)
- ✅ Link to GitHub repository
- ✅ Fully responsive design for mobile and tablets
- ✅ Clean, modular code structure

## Setup Instructions

1. **Install Dependencies**
   ```bash
   bundle install
   ```

2. **Configure Your Information**
   
   Edit `_config.yml` and update:
   - `title`: Your name or portfolio title
   - `email`: Your email address
   - `description`: Your portfolio description
   - `github_username`: Your GitHub username
   - `codecademy_username`: Your Codecademy username
   - `repository_url`: Your GitHub repository URL

3. **Add Profile Photo (Optional)**
   
   Place your profile photo in `assets/images/` and update the `profile_photo` path in `_config.yml`:
   ```yaml
   profile_photo: /assets/images/profile.jpg
   ```

4. **Customize Content**
   
   Edit the following files to personalize your content:
   - `index.markdown`: Home page introduction
   - `about.markdown`: About page content
   - `projects.markdown`: Projects page content

5. **Run Locally**
   ```bash
   bundle exec jekyll serve
   ```
   
   Then visit `http://localhost:4000` in your browser.

6. **Deploy**
   
   This site can be deployed to GitHub Pages, Netlify, Vercel, or any static site hosting service.

## Project Structure

```
my-site/
├── _config.yml          # Site configuration
├── _layouts/            # HTML layout templates
│   ├── default.html
│   ├── home.html
│   └── page.html
├── _includes/           # Reusable components
│   ├── header.html
│   ├── navigation.html
│   └── footer.html
├── assets/
│   ├── css/
│   │   └── main.css     # Custom styles
│   └── images/          # Images and photos
├── index.markdown       # Home page
├── about.markdown       # About page
└── projects.markdown    # Projects page
```

## Customization

### Colors

The color scheme is defined in `assets/css/main.css` using CSS variables:
- `--dark-bg`: Background color
- `--accent-orange`: Primary accent color
- `--accent-yellow`: Secondary accent color

### Adding Projects

To add more projects, edit `projects.markdown` and add new project cards following the existing structure.

## License

This portfolio template is open source and available for personal use.

