# Counter templates

Here's a bunch of counter badge templates (just copy/paste onto
submod/spritepack.) Before creating your own tag, check this list and see if
there's one already. If not, feel free to add!

> [!NOTE]
> In badge URL part, you can see things like \:owner or \:repo (generally, in
> format of `:something`) &mdash; it's a *variable* and you need to replace it
> with a corresponding value, e.g. repository owner name or repository name.

## 📥 Downloads

> [!NOTE]
> On GitHub repositories where there are no releases or latest release has no
> assets beside source code packages, download count is unavailable! In this
> case, consider just adding a static badge with yellow N/A part.

### Dynamic counter

> [!NOTE]
> Only applicable to GitHub repositories with created releases that have
> downloadable assets (see note above.)

Dynamically monitors downloads count of all releases in a GitHub repository.

![downloads counter](https://img.shields.io/github/downloads/:owner/:repo/total?label=📥+downloads)

### Static badge

Static counterpart which simply indicates that downloads can't be counted. Use
this as an alternative to the above counter when repository is known not to have
countable releases.

![unknown downloads count](https://img.shields.io/badge/📥_downloads-N%2FA-yellow)

## ⭐ Stars

> [!NOTE]
> Only applicable to GitHub repositories.

Dynamically monitors stargazers count of a GitHub repository.

![stars counter](https://img.shields.io/github/stars/:owner/:repo?label=⭐+stars)
![release date](https://img.shields.io/github/release-date/multimokia/MAS-Submod-Nightmusic?label=⏳+release)

## 📆 Release

> [!NOTE]
> Only applicable to GitHub repositories with created releases.

Dynamically monitors latest release date of a GitHub repository.

![](https://img.shields.io/github/release-date/:owner/:repo?label=📆+release)