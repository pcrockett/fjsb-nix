fjsb-nix
========

A Nix plugin for [fj-sandbox][1]. Adds a `sandbox-install` command which allows you to install software for only a specific sandbox, rather than globally for all sandboxes.

Usage
-----

```bash
# Install the plugin
git clone https://github.com/pcrockett/fjsb-nix
install-fjsb-plugin ./fjsb-nix

# Install cowsay for the "personal" sandbox only
sandbox-install personal cowsay
```

[1]: https://github.com/pcrockett/fj-sandbox
