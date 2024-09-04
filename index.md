---
title: Home
layout: home
nav_order: 1
description: "Special Interest Group at IOIT ACM student chapter focuses on building an community of developers, programmers and hackers"
permalink: /
---

# IOIT ACM Technology SIG
{: .fs-9 }

Special Interest Group at IOIT ACM student chapter focuses on building an community of developers, programmers and hackers.
{: .fs-6 .fw-300 }
---

#### Table of content

- [Resources](/docs/resources/)
- [Meetups](/docs/meetups/)

---

{: .new }
> You can access the resources by the speakers at the events on this website. Developers can contribute to this project, see the [Contribution guide](#contributing)

## About the Project

Welcome to IOIT ACM Student Chapter Technology SIG platform, build to inspire and support students on their programming journey! 

### Our Mission

We've created this website with a clear purpose:
- To provide a launchpad for aspiring programmers
- To offer curated resources on latest technologies
- Allowing students to work togather on a community project
- To share insights from industry experts through SIG events

### What We Offer

- **Resources**: collection of learning materials.
- **Community Building**: We're dedicated to fostering a vibrant, supportive community of developers. Connect, learn, and grow with fellow enthusiasts.

### Get Involved

We believe in the power of collaboration. Whether you're a beginner looking to learn or an experienced developer wanting to give back, we welcome your contributions! 

To get started:
1. Explore the website to discover our resources and community initiatives.
2. Check out our [Contribution Guide](#contributing) to learn how you can help improve and expand this project.

This website is a theme for generating static websites with [Jekyll]. You can write source files for your web pages using [Markdown], the [Liquid] templating language, and HTML.[^1] Jekyll builds your site by converting all files that have [front matter] to HTML.

> Just the Docs is &copy; 2017-{{ "now" | date: "%Y" }} by [Patrick Marsceill](https://patrickmarsceill.com).

# Contributing

Thank you for your interest in contributing to this project! This guide will help you set up your development environment and get started with contributing.

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

----

## Warning: NOT a noob lesson but a must watch

This video is about learning, relearning and programming

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/N2bXEUSAiTI?si=v9ATzlEfQDf1GhGt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe>
</div>


[Jekyll]: https://jekyllrb.com
[Markdown]: https://daringfireball.net/projects/markdown/
[Liquid]: https://github.com/Shopify/liquid/wiki
[source file for this page]: https://github.com/adimail/ioit-acm-techsig/blob/main/index.md
