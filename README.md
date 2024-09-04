<p align="right">
    <a href="https://github.com/just-the-docs/just-the-docs/actions/workflows/ci.yml"><img src="https://github.com/adimail/ioit-acm-techsig/actions/workflows/ci.yml/badge.svg" alt="CI Build status"></a>
</p>
<br><br>
<p align="center">
    <h1 align="center">IOIT ACM Technology Special Interest Group</h1>
</p>

### Get Involved

We believe in the power of collaboration. Whether you're a beginner looking to learn or an experienced developer wanting to give back, we welcome your contributions! 

To get started:
1. Explore the website to discover our resources and community initiatives.
2. Check out our [Contribution Guide](#contributing) to learn how you can help improve and expand this project.

Join us in our mission to empower the next generation of developers and build a thriving tech community!

This website is a theme for generating static websites with [Jekyll]. You can write source files for your web pages using [Markdown], the [Liquid] templating language, and HTML.[^1] Jekyll builds your site by converting all files that have [front matter] to HTML.

This website builds is built using the Just the Docs theme.

# Contributing

Thank you for your interest in contributing to our Ruby project! This guide will help you set up your development environment and get started with contributing.

## Prerequisites

Before you begin, ensure you have the following installed:
- Ruby (version 3.0.0 or higher)
- RubyGems
- Bundler
- Git

## Getting Started

### 1. Fork the Repository

Start by forking this repository to your GitHub account.

### 2. Clone Your Fork

```bash
git clone https://github.com/your-username/ioit-acm-techsig.git
cd ioit-acm-techsig
```

### 3. Install Ruby

#### macOS
```bash
brew install rbenv
rbenv init
rbenv install 3.2.0
rbenv global 3.2.0
```

#### Ubuntu/Debian
```bash
sudo apt-get update
sudo apt-get install -y build-essential libssl-dev libreadline-dev zlib1g-dev
curl -fsSL https://github.com/rbenv/rbenv-installer/raw/main/bin/rbenv-installer | bash
rbenv install 3.2.0
rbenv global 3.2.0
```

#### Windows
Download and install Ruby using the [RubyInstaller](https://rubyinstaller.org/).

### 4. Install Bundler

After installing Ruby, install Bundler:
```bash
gem install bundler
```

### 5. Install Project Dependencies

```bash
bundle install
```

### 6. Run the Project

```bash
bundle exec jekyll serve
```

Open your web browser and navigate to `http://localhost:4000` to see the Jekyll site in action.

## Making Contributions

1. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. Make your changes and commit them:
   ```bash
   git add .
   git commit -m "Add your meaningful commit message here"
   ```

3. Push your changes to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```

4. Open a pull request from your fork to the main repository.

## Tips

Use github desktop to easily navigate the code repository

## Reporting Issues

If you encounter any bugs or have suggestions, please open an issue in the GitHub repository.
