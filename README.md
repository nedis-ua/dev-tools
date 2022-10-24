# Dev Tools

## Install git hook:

```shell
wget -O /tmp/setup -q https://raw.githubusercontent.com/nedis-ua/dev-tools/master/git/install-spotless-git-hook.sh \
    && chmod 755 /tmp/setup \
    && /tmp/setup -q \
    && rm -rf /tmp/setup
```

## Environment setup

### Git

```shell
git config user.name "nedis-ua"
```

```shell
git config user.email johndoe@example.com
```
