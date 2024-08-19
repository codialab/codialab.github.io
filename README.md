# CODIA Lab

#### 1. Create a conda environment

`conda env create -f codialab.github.io/build_env/conda_jekyll.yml -p ./website_env`

`conda activate ./website_env`

#### 2. Install necessary packages

```bash
gem install jekyll  # Simple, blog-aware, static site engine
gem install jekyll-paginate  # for multipage blog listings
gem install jekyll-feed  # for Atom (RSS-like) feed
gem install jekyll-sitemap  # for web crawlers
```

#### 3. Build and serve the website

```bash
cd codialab.github.io/
bundler install
bundle exec jekyll serve --livereload
```
#### 4. Adding content

Each directory contains a README describing the
necessary formatting.

##### Personal page:

[Personal page README](_people/README.txt)

Markdown file under:

`_people/`

Portrait (PNG/JPG) under:

`img/`

##### Publication page:

[Publication page README](_data/publications/README.txt)

YAML file under:

`_data/publications`

##### Project page:

[Project page README](_projects/README.txt)

Markdown file under:

`_projects/`

##### News (post) page:

[News page README](_posts/README.txt)

Markdown file under:

`_posts/`

##### New institute / lab

[Institute page README](_institutes/README.txt)

Markdown file under:

`_institutes/`

Logo (PNG/JPG) under:

`img/`
