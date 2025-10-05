# delta.khk.org

This project is now built with [Hugo](https://gohugo.io/), a fast and flexible static site generator written in Go. Hugo makes it simple to create content in Markdown and render it with customizable templates. Here are some useful links to get started:

* [Quick Start](https://gohugo.io/getting-started/quick-start/)
* [Configuration](https://gohugo.io/getting-started/configuration/)
* [Front Matter](https://gohugo.io/content-management/front-matter/)
* [Templates](https://gohugo.io/templates/overview/)

Checkout the section *Why Hugo?* below for more.

---

### Development

Before you begin, make sure to [install Hugo](https://gohugo.io/installation/).

```bash
# Clone the repository
$ git clone git@github.com:KappaEtaKappa/delta.khk.org.git
$ cd delta.khk.org

# Start the Hugo development server (http://localhost:1313 by default)
$ hugo server -D
```

Hugo will watch the current directory for changes and automatically rebuild and live-reload the site in your browser.

---

### Pushing to Production

It's best to make small, contained changes. Once you've committed your change(s), submit a pull request. Collaborate with other contributors to review and merge your code into production.

If you're new to git, check out [Git No Deep Shit!](http://rogerdudler.github.io/git-guide/). Here’s a quick workflow:

```bash
# Clone the repository
$ git clone <repo>

# Start a new branch
$ git checkout -b my_new_feature

# Add and commit your changes
$ git add --all
$ git commit -m "<description of changes>"

# Push your branch to GitHub
$ git push --set-upstream origin my_new_feature
```

Once your branch is pushed, open a pull request on GitHub. After review, changes merged into `main` will be automatically built and deployed to production (typically within 15 minutes).

---

### Hosting

This site is hosted with [GitHub Pages](https://pages.github.com/). You can view or change deployment settings in the [repository settings](https://github.com/KappaEtaKappa/KappaEtaKappa.github.io/settings).

DNS for `khk.org` and all subdomains is configured on [WPlex.com](https://www.wplex.com/). You’ll need to work with a webmaster to make DNS changes.

If you want to host this site elsewhere, Hugo makes it easy: just run `hugo` to generate the static site and upload the `/public` directory to your server.

---

### Why Hugo?

KHK Delta has gone through many iterations of websites: Wordpress, Drupal, and Jekyll among them. While CMS systems make management easy, they also come with heavy maintenance, security vulnerabilities, and hosting headaches.

Hugo offers a sweet spot:

* **Markdown-based content** — simple, portable, and future-proof.
* **Data-driven content** — structured member data in YAML/JSON/TOML is first-class.
* **Ease** — Hugo is modern and so much easier than other stacks.
* **Security** — no databases, PHP, or plugins to worry about.
* **Flexibility** — easy theming and styling without being tied to a bulky CMS.
* **Free hosting** — with GitHub Pages, updates are just a `git push` away.

As a computer engineering fraternity, it’s fitting that our site is built and maintained by us, with tools that are both powerful and developer-friendly.

— Joe Dailey
