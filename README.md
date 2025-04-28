# supagraph

This is a Jekyll-based website for GitHub Pages that resembles the Supagraph website design.

## Development

1. Install Ruby and Jekyll

   ```bash
   sudo apt update && sudo apt upgrade -y
   sudo apt install -y ruby-full build-essential zlib1g-dev

   export GEM_HOME="$HOME/.gems"
   export PATH="$GEM_HOME/bin:$PATH"
   source ~/.bashrc

   gem install bundler jekyll
   ```

2. Clone this repository

   ```bash
   git clone https://github.com/supagraph-ai/supagraph-ai.github.io.git
   cd supagraph-ai.github.io
   ```

3. Install dependencies

   ```bash
   bundle install
   ```

4. Run the local development server

   ```bash
   bundle exec jekyll serve --host 0.0.0.0 --port 4000
   ```

5. Open your browser and go to `http://localhost:4000`

## Reference

- [jekyll install](https://gist.github.com/craftslab/dd28d2fb5fe8d20cf320fad01ad376ce)
