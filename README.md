# YourDB - Supabase-like Website Template

This is a Jekyll-based website template for GitHub Pages that resembles the Supabase website design. It's clean, modern, and ready to be customized for your project.

## Features

- Responsive design
- Dark theme similar to Supabase
- Complete homepage with sections for features, testimonials, pricing, etc.
- Ready for GitHub Pages deployment
- Easy to customize with Jekyll's data files

## Setup Instructions

### Local Development

1. Install Ruby and Jekyll (if you haven't already)
   ```bash
   gem install bundler jekyll
   ```

2. Clone this repository
   ```bash
   git clone https://github.com/yourusername/yourdb-website.git
   cd yourdb-website
   ```

3. Install dependencies
   ```bash
   bundle install
   ```

4. Run the local development server
   ```bash
   bundle exec jekyll serve
   ```

5. Open your browser and go to `http://localhost:4000`

### Deployment to GitHub Pages

1. Create a new repository on GitHub

2. Push your local code to the repository
   ```bash
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git branch -M main
   git push -u origin main
   ```

3. Go to your repository settings on GitHub, scroll down to the "GitHub Pages" section, and select your main branch as the source.

4. Your site will be available at `https://yourusername.github.io`

## Customization

### Site Information

Edit the `_config.yml` file to update basic site information like title, description, etc.

### Navigation

Edit the `_data/navigation.yml` file to update the navigation links.

### Features

Edit the `_data/features.yml` file to update the features section.

### Testimonials

Edit the `_data/testimonials.yml` file to update the testimonials section.

### Pricing

Edit the `_data/pricing.yml` file to update the pricing plans.

### Colors and Styling

The main colors and styling variables are defined in `_sass/_variables.scss`. Update these to match your brand colors.

## License

This template is available as open source under the terms of the [MIT License](LICENSE).
