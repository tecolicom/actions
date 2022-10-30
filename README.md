# TECOLI.COM GitHub Actions

## Use-Tools Actions

These are collection of actions to make easy various tool
installation.  Basically you can use tools just giving package manager
and package names.  They are installed and cached for future use.

For example, brew package tool can be installed as simple as this:

```yaml
- uses: tecolicom/actions-use-homebrew-tools@v1
  with:
    tools: rcs
```

You can replace `homebrew` and `tools` part to any other package.
Specified tools are installed at the first time.  As for later
execution, cached files are extracted from the archive if any other
environment is not changed.

If you have request to support other package manager, send an
[issue](https://github.com/tecolicom/actions/issues).

### Supporting Tools

- [actions-use-apt-tools](https://github.com/tecolicom/actions-use-apt-tools)
- [actions-use-homebrew-tools](https://github.com/tecolicom/actions-use-homebrew-tools)
- [actions-use-perl-tools](https://github.com/tecolicom/actions-use-perl-tools)
- [actions-use-python-tools](https://github.com/tecolicom/actions-use-python-tools)
- [actions-use-ruby-tools](https://github.com/tecolicom/actions-use-ruby-tools)

### Unified Interface

- [actions-use-any-tools](https://github.com/tecolicom/actions-use-any-tools)

### Back-End Action

- [actions-install-and-cache](https://github.com/tecolicom/actions-install-and-cache)
- [actions-install-and-archive](https://github.com/tecolicom/actions-install-and-archive)

## Node.js Tools

- [actions-install-node-modules](https://github.com/tecolicom/actions-install-node-modules)
