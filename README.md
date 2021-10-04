<h1 align="center">
  <img alt="RSSpaper logo" src="media/newsreader-banner.png">
</h1>

Generate a static page with the latest news from your favorite feeds. Is it an RSS client? Yes, except that it generates an **HTML/PWA** that you can read or **install on your tablet or mobile** and to **update the news you must run it again**.

## Screenshots

### Light theme

![demo preview](media/demo.jpg)

### Sepia theme

![demo preview](media/sepia-mode.png)

### Dark theme

![demo preview](media/dark-mode.png)

## Demo

<p align="center">
  <a href="https://rsspaper.andros.dev/">👉 My own feed generated daily with Github Actions 👈</a>
</p>

### PageSpeed Insights

![demo preview](media/pagespeed-insights.png)


## Run

1) Create a file `config.yaml` with the following content. You can also use `config.yaml.example` as a base config and change it to fit your needs.

``` yaml
# Change the title, it's for you. Maybe you see "My newspaper"?
title: RSSPAPER

# Options: light, sepia or dark
theme: light

# Options: daily, weekly or all
edition: weekly

feeds:
  - https://programadorwebvalencia.com/feed/
  - https://republicaweb.es/feed/
```

2) Download the latest version of RSSpaper (`rsspaper-{version}-standalone.jar`).

https://github.com/tanrax/RSSPAPER/releases

(Both `jar` and `config.yaml` must be in the same directory)

3) Now you can execute.

```sh
java -jar rsspaper-{version}-standalone.jar
```

Great 🎉. You already have your 📰 own Static RSS Newspaper 📰.

That's it, now you just have to open `dist/index.html`.
