<a href="https://jekyll-themes.com">
<img src="https://img.shields.io/badge/featured%20on-JT-red.svg" height="20" alt="Jekyll Themes Shield" >
</a>

# [Website](https://monika-with-a-k.github.io/)

This is the repository for my public [website](https://monika-with-a-k.github.io/)

# CV Template

Fork of this [Jekyll template](https://github.com/sharu725/online-cv/fork) by [sharu725](https://github.com/sharu725)

## Installation

- [Fork](https://github.com/sharu725/online-cv/fork) the repository;
- Go to settings and set master branch as Github Pages source;
- Your new site should be ready at `https://<username>.github.io/online-cv/`;
- Printable version of the site can be found at `https://<username>.github.io/online-cv/print`. Use a third party link https://pdflayer.com/, https://www.web2pdfconvert.com/ etc to get the printable PDF.

Change all the details from one place: `_data/data.yml`.

### To preview/edit locally with docker

```sh
docker-compose up
```

_docker-compose.yml_ file is used to create a container that is reachable under <http://localhost:4000>.
Changes _\_data/data.yml_ will be visible after a while.

### Local machine

- Get the repo into your machine

```bash
git clone https://github.com/sharu725/online-cv.git
```

- Install required ruby gems

```bash
bundle install
```

- Serve the site locally

```bash
bundle exec jekyll serve
```

- Navigate to `http://localhost:4000`
