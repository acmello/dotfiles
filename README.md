# dotfiles.
> *My [setup](https://github.com/diessica/setup) and [favourites](https://github.com/diessica/favourites) are also worth-checking! ;-)*

These are my very personal **system preferences**; **command-line tools**, **tweaks** and **utils**.

Productivity is quite a subjective topic, so perhaps my flow won't work for you in the same way it works for me. Actually, I'm not even sure whether it is the most productive way to work, but, as a huge fan of productivity stuff, I try hard to be more comfortable on my computer everyday.

I guess productivity is more about comfort than anything else, after all.

## the path to comfort
- Get this project. Using [Git](http://www.git-scm.com/):
```sh
$  git clone https://github.com/diessica/dotfiles.git ~/.dotfiles
```
- Run the installation file.
```sh
$  cd ~/.dotfiles
$  sh install
```
- Tell Git who you are in a `.gitlocal` file. 
```sh
git config -f ~/.gitlocal user.email "{email}"
git config -f ~/.gitlocal user.name "{name}"
```


## what's included?
An entire environment, with software preferences (hot corners, Finder, Safari...), hardware settings (trackpad, screen...), npm global packages, gems, terminal tweaks... **Everything well-documented and specified** in [`settings.md`](https://github.com/diessica/dotfiles/blob/master/settings.md) file.

# to-do
- [ ] Config symlinks.
- [ ] Organise aliases by folder.
- [ ] Set up an awesome git-changelog.
- [ ] Implement modular installation, specially for linking dotfiles.

---

# thanks

We can learn about productivity just looking at the way people work everyday. I was highly inspired by [Holman](https://github.com/holman), [Mathias Bynens](https://github.com/mathiasbynens/dotfiles), [Deny Dias](https://github.com/denydias/dotfiles) and a lot of other people's workflow.

I can't agree more with [Holman](https://github.com/holman)'s thoughts on dotfiles: [dotfiles are meant to be forked](http://zachholman.com/2010/08/dotfiles-are-meant-to-be-forked).

###### LICENSE

[MIT](http://diessica.mit-license.org/) © [Diéssica Gurskas](http://diessi.ca)