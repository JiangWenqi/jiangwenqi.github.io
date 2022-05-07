# Install Ruby

```bash
brew install ruby
echo 'export PATH="/usr/local/opt/ruby/bin:$PATH"' >> ~/.zshrc
source ~/.zshrc
```

# Install `bundler`, `jekyll`

```bash
gem install --user-install bundler jekyll
source ~/.zshrc
```

# Run it

```bash
cd your_project_directory
bundle install
bundle exec jekyll serve
```

## Check it on: `localhost:4000`

---

# Problems

1. failed to load command: `jekyll`
    
    Ruby 3.0 no longer comes with `webrick`: `bundle add webrick`


# References
https://github.com/sproogen/modern-resume-theme/blob/master/_config.yml