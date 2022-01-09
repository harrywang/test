# jtn
Jekyll + Tailwind + Netlify https://medium.com/@mauddev/jekyll-tailwind-netlify-9496352b49ee

# Setup and Testing

NOTE: for Mac M1 users:

- follow https://www.earthinversion.com/blogging/how-to-install-jekyll-on-appple-m1-macbook/ to install jekyll ARM compatible version


then follow the instruction below:

- Install [Jekyll](https://jekyllrb.com) and [Bundler](https://bundler.io/).
- Clone the forked repo on your machine
- Enter the cloned folder via terminal and run `bundle install`
- (optional for Jekyll 3.0) run `bundle add webrick` according to https://github.com/github/pages-gem/issues/752
- Then run `bundle exec jekyll serve`
- Open it in your browser: `http://localhost:4000`

# Building

`npx tailwindcss -i ./assets/css/main.css -o ./assets/css/tailwind.css`


# Github Pages

you have to change `baseurl` and `url` in `_config.yml` to make the site work for Github Pages