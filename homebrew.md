# Homebrew

## Install Homebrew

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Useful plugins or extensions

### [rmtree](https://github.com/beeftornado/homebrew-rmtree)

```bash
brew tap beeftornado/rmtree
```

## Useful commands

### List installed packages

```bash
brew list
```

### List installed main packages (not dependencies)

```bash
brew leaves
```

### List outdated packages

```bash
brew outdated
```

### Upgrade all packages

```bash
brew upgrade
```

### Remove a package and its dependencies

```bash
brew rmtree <package>
```

## Useful packages

### UNIX/Linux essentials

- [telnet](https://en.wikipedia.org/wiki/Telnet)
- [wget](https://www.gnu.org/software/wget/)
- [tree](http://mama.indstate.edu/users/ice/tree/)
- [htop](https://htop.dev/)
- [pstree](https://linux.die)
- [jq](https://stedolan.github.io/jq/)
- [ag](https://geoff.greer.fm/ag/)
- [fzf](https://github.com/junegunn/fzf)
- [gpg](https://gnupg.org/)

### Development tools

- [neovim](https://neovim.io/)
- [awscli](https://aws.amazon.com/cli/)
- [colima](https://colima.dev/)
- [docker](https://www.docker.com/)
- [go](https://golang.org/)
- [nodenv](https://github.com/nodenv/nodenv)
- [pgformatter](https://sqlformat.darold.net/)
- [pre-commit](https://pre-commit.com/)
- [git-cliff](https://github.com/orhun/git-cliff)
- [trivy](https://aquasecurity.github.io/trivy/)
- [k6](https://k6.io/)
- [yarn](https://yarnpkg.com/)
- [node](https://nodejs.org/)
- [openjdk](https://openjdk.java.net/)

### Databases or platforms

- [postgresql](https://www.postgresql.org/)
- [redis](https://redis.io/)
- [temporal](https://temporal.io/)
- [mailhog](https://github.com/mailhog/MailHog)
