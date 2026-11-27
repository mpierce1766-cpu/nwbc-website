# Northwest Baptist Church Website

A simple, mobile-friendly website for Northwest Baptist Church. It is plain HTML and CSS, so there is nothing to install or build. It is designed to be hosted free on GitHub Pages, with the church's own domain name pointed to it.

## Pages

| File | Page |
|---|---|
| `index.html` | Home |
| `about.html` | About Us (story, mission, beliefs) |
| `visit.html` | Service Times & Location |
| `give.html` | Give |
| `contact.html` | Contact Us |
| `404.html` | "Page not found" page |

Shared files:

- `css/style.css`: all colors, fonts, and layout. The site colors are at the top of this file.
- `js/main.js`: the small script that opens and closes the menu on phones.
- `images/`: put photos and the church logo here.

## Details already filled in

- Sunday Worship: 10:30 AM. Wednesday Bible Study: 6:30 PM. (There is no Sunday School.)
- Address: 11021 FM 1560 North, Helotes, TX 78023 (with Google Maps "Get Directions" links)
- Phone: 210-275-7753 (tap-to-call on phones)
- Email: graco51@yahoo.com (footer, Contact page, and the prayer request button)
- Pastor: Bob Gray, title Pastor, with his welcome message (home page and About page)
- Home page photo: the front of the church (`images/church-front-large.jpg` and `images/church-front-small.jpg`)
- Photo beside the pastor's message: side view of the church (`images/church-side.jpg`)
- About page: Our Story, What We Believe (KJV), and Our Mission
- Give page: giving note, give by mail, and give in person (online giving removed for now, 2026-11-27)
- Service Times page: parking, accessibility, and all four What to Expect boxes

## Placeholders to fill in

Every piece of church-specific information is shown as highlighted text in square brackets, like **[Sunday worship time]**. On the live site these appear with a yellow highlight so they are easy to spot. To find them all in the code, search for `[`.

**Not yet provided**
- Church logo (currently a simple cross icon) and preferred colors

## Hosting

The site runs on GitHub Pages (Settings, then Pages, then deploy from the `main` branch, root folder).

The church's domain is **northwestbaptistchurchsa.com**, registered at Cloudflare (so its DNS is managed at Cloudflare). The `CNAME` file in this folder tells GitHub Pages to serve the site at that address; do not delete it. `www.northwestbaptistchurchsa.com` redirects to the main address automatically.

Cloudflare DNS records (all set to **DNS only**, grey cloud):

| Type  | Name | Content |
|-------|------|---------|
| A     | @    | 185.199.108.153 |
| A     | @    | 185.199.109.153 |
| A     | @    | 185.199.110.153 |
| A     | @    | 185.199.111.153 |
| CNAME | www  | mpierce1766-cpu.github.io |

These IP addresses come from GitHub's guide, [Managing a custom domain for your GitHub Pages site](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site).
