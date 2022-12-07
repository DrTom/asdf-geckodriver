# asdf-geckodriver

[geckodriver](https://github.com/mozilla/geckodriver) plugin for the [asdf version manager](https://asdf-vm.com).


## Context

The goal of this project is primarily to support testing CI infrastructure.


## Install


```shell
asdf plugin add geckodriver https://github.com/DrTom/asdf-geckodriver.git
```

geckodriver:

```shell
# Show all installable versions
asdf list-all geckodriver

# Install specific version
asdf install geckodriver 0.32.0

# Set a version globally (on your ~/.tool-versions file)
asdf global geckodriver 0.32.0

# Now geckodriver commands are available
geckodriver --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.


## Notes

See also https://github.com/DrTom/asdf-firefox.
