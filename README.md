# Minimal Mistakes Jekyll
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/limyunkai19/minimal-mistakes-jekyll/blob/master/LICENSE)

Ready to use Jekyll template with Minimal Mistake theme. Instants blog without knowing git and command line. Just fork it to use for your GitHub Pages.

Demo: <https://limyunkai19.github.io/minimal-mistakes-jekyll/>

## Getting Started
### Installation for Your GitHub Pages
[Fork](https://help.github.com/articles/fork-a-repo/#fork-an-example-repository) Minimal Mistakes Jekyll to your own Repository.

Publish the site with GitHub Pages on:
- <https://username.github.io> (recommended)
    + rename the forked repository to username.github.io
    + your site should be available at <https://username.github.io> after renaming


- <https://username.github.io/repositoryname>
    + rename the forked repository to a name you like, for example my-awesome-blog
    + go to setting, publish your `master` branch with GitHub Pages, detail steps at [here](https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/#enabling-github-pages-to-publish-your-site-from-master-or-gh-pages)
    + your site should be available at <https://username.github.io/my-awesome-blog>

After the sites had been published continue to [Usage](#usage) section to add content to your site.

### Installation for Local Development
This section is for those who wish to develop their site locally and use git to commit changes for the site. It assumes the knowledge of command line. You may [skip](#file-structure) this section if you don't know git or don't want to touch the command line.

**Prerequisites**

- Git
- [Jekyll](https://jekyllrb.com/docs/installation/) and [Bundle](http://bundler.io/#getting-started)

**Installation**

Make sure all prerequisites are installed and you had forked the repository.

Run the following command in your terminal:

```sh
# Clone your forked repository
git clone https://github.com/username/minimal-mistakes-jekyll.git

# Change directory
cd minimal-mistakes-jekyll

# Build the site using Jekyll and serve the site
bundle exec jekyll serve
```

Your site should be available at <http://localhost:4000>.

Develop your site, commit new changes and push to GitHub master branch, any new changes will be reflected on GitHub Pages in a few seconds after you push the commits.

## File Structure

## Usage

## Customization

## Credits

## To Do
- Complete this readme
- Add static pages including 404
