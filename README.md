# TECOLI.COM GitHub Actions

## Use-Tools Actions

These are collection of actions to make easy various tool
installation.  Basically you can use tools just giving package manager
and package names.  They are installed and cached for future use.

For example, brew package tool can be installed as simple as this:

```yaml
- uses: tecoli-com/actions-use-homebrew-tools@v0
  with:
    tools: rcs
```

You can replace `homebrew` and `tools` part to any other package.
Specified tools are installed at the first time.  As for later
execution, cached files are extracted from the archive if any other
environment is not changed.

If you have request to support other package manager, send an
[issue](https://github.com/tecoli-com/actions/issues).

### Supporting Tools

- [actions-use-apt-tools](https://github.com/tecoli-com/actions-use-apt-tools)
- [actions-use-homebrew-tools](https://github.com/tecoli-com/actions-use-homebrew-tools)
- [actions-use-perl-tools](https://github.com/tecoli-com/actions-use-perl-tools)
- [actions-use-python-tools](https://github.com/tecoli-com/actions-use-python-tools)
- [actions-use-ruby-tools](https://github.com/tecoli-com/actions-use-ruby-tools)

### Unified Interface

- [actions-use-any-tools](https://github.com/tecoli-com/actions-use-any-tools)

### Back-End Action

- [actions-install-and-cache](https://github.com/tecoli-com/actions-install-and-cache)
- [actions-install-and-archive](https://github.com/tecoli-com/actions-install-and-archive)

## Node.js Tools

- [actions-install-node-modules](https://github.com/tecoli-com/actions-install-node-modules)
