---
title: About
permalink: /about/
---

<!-- This blog is demo blog for [Kiko Plus](https://github.com/AWEEKJ/Kiko-plus)

This theme is inspired by [Kiko](http://github.com/gfjaru/Kiko) theme, powered by [Jekyll](http://jekyllrb.com), hosted on [Github Pages](https://pages.github.com).

## Features

- Disqus comment system
- Google analytics
- Pagination support
- Custom tags
- SEO support


## Installation

#### Method 1: new master's repository (The Best)

1. First [fork](https://github.com/AWEEKJ/Kiko-plus/fork) it.
2. Change your forked repository name _Kiko-plus_ to __USERNAME.github.io__ where
   __USERNAME__ is your github user name.
3. Access your new blog via [https://username.github.io](https://username.github.io).
4. [See configuration](#configuration).

#### Method 2: gh-pages in existing repository

1. Create a new branch called _gh-pages_ in the repository where you want to add a template [managing branches](https://help.github.com/articles/creating-and-deleting-branches-within-your-repository/).
2. From command line run `git clone https://github.com/AWEEKJ/Kiko-plus.git` - this will clone _Kiko-plus_ template to your computer.
3. Create new branch `git checkout -b gh-pages` where _gh-pages_ will be your branch name.
4. Add remote, which is your repo from the first step, to your new branch `git remote add gh-pages https://github.com/<yourName>/<yourMaster>/gh-pages`. _yourName_ is your account name and _yourMaster_ is your repository.
5. Push new branch to remote `git push gh-pages`.
6. Update `_config.yml` file by changing `baseurl: "<branchName>"` _branchName_ is your branch name where _gh-pages_ resides. See [configuration](#configuration).

#### Method 3: run it locally

1. Download [zip](https://github.com/AWEEKJ/Kiko-plus/archive/master.zip) or clone it `git clone https://github.com/AWEEKJ/Kiko-plus`.
2. Go inside folder and run `jekyll serve` or `bundle exec jekyll s` or `rake preview`. This will build a website which you can access [https://localhost:4000](https://localhost:4000). You need to have [Jekyll](https://jekyllrb.com/docs/installation/) installed to do this.


## Configuration

All configuration is done via `_config.yml` file which you will find in your main repo folder. Change this `<something>` to yours.

- Change this to your blog name.

```yml
name: <blog-name>
```

- Change this to your domain. **NOTE**- if running locally change this to `url: "https://localhost:4000"`.

```yml
url: "https://<your-name>.github.io"
```

- Change this to your branch name where _gh-pages_ resides. !NOTE apply only if you used __Method 2__ for installation.

```yml
baseurl: "/<branch-name>"
```

- These configuration in `author:` is for links to icons in footer. Modify `_includes/footer.html` to add more link icons.

```yml
author:
  name:             your-name
  facebook:         your-id
  twitter:          your-id
  github:           your-id
  linkedin:         your-id
  medium:           your-id
  tumblr:           your-id
  email:            your-id@your-email.com
```

- Change this to your Google Analytic ID.

```yml
google-analytics:
  id:               your-id
```

- Change this to your Disqus ID.

```yml
disqus:
  id:               your-id
```

## Rakefile Usage

```bash
$ rake post title="A Title" [date="2015-08-16"] [tags=[tag1,tag2]]
$ rake draft title="A Title" [date="2015-08-16"] [tags=[tag1,tag2]]
$ rake preview
```

## License

This theme is released under MIT License. -->

Hi, My name is Aden Seeley. I am a studio portrait photographer working primarily with film photography from the Rochester area. I have been photographing for close to seven years. I have been trained at school, as well as being mostly a self taught photographer. I strive as a photographer to work with the human form, connecting with the person to find who they are as opposed to photographing just their outer layers of skin. Beginning to work in the performing arts and dance fields, I’ve worked primarily with performance ballet dancers to capture the grace and movement of their art in order to create something truly beautiful. Working with the ballerinas that I have has allowed me to fully understand where I want to be in the field of photography, and has allowed me to transfer the grace and fast paced movements to influence my photography elsewhere in personal and client work.
