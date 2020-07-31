## The Basics

This is a Proof of Concept for a new type of blog that can replace commonly-used big name proprietary and legacy technologies with something fast, flexible, open source, and downright **awesome**.

- Framework: [Hugo](https://gohugo.io/) - open source static site generator
- CMS: [Forestry](https://forestry.io/) - git-backed and markdwon-based content management
- Starter Template: [Hugo Parsa Theme developed by Themefischer](https://github.com/themefisher/parsa-hugo)
- Deployment: [Cloudflare Workers](https://workers.cloudflare.com) via [Wrangler](https://github.com/cloudflare/wrangler) and [GitHub Actions](https://github.com/features/actions)

Website: https://test-hugo.chaos.workers.dev

Admin Panel: https://test-hugo.chaos.workers.dev/admin

## Content Management

Examples of Forestry.io interface below:

![2020-07-30 08 54 51 app forestry io e7fb3ab88ef2](https://user-images.githubusercontent.com/9038904/88945565-fea32280-d242-11ea-9dcf-d43002a0d65b.png)

![2020-07-30 08 55 04 app forestry io 6441ac0965f7](https://user-images.githubusercontent.com/9038904/88945570-01057c80-d243-11ea-8b5c-b21050040d2a.png)

## Development

```bash
# clone the repository
git clone --recurse-submodules git@github.com:whoabuddy/hugo-parsa-forestry.git

# cd in the project directory
cd hugo-parsa-forestry

# Start local dev server
hugo server
```
