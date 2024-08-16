Frosit MySQL homebrew tap - for easy installation of all MySQL versions
=======================================================================

> NOTE: under development/testing. use at own risk.

_All formula are extracted from the official [homebrew-core](https://github.com/Homebrew/homebrew-core) repository._

This tap is to make it easier to install older mysql versions that are no longer available in the official homebrew-core repository.

__This tap is not officially supported by Homebrew.__

## Versions

* [mysql@5.7](https://dev.mysql.com/doc/relnotes/mysql/5.7/en/)
* [mysql@8.0](https://dev.mysql.com/doc/relnotes/mysql/8.0/en/)
* [mysql@8.1](https://dev.mysql.com/doc/relnotes/mysql/8.1/en/)
* [mysql@8.2](https://dev.mysql.com/doc/relnotes/mysql/8.2/en/)
* [mysql@8.3](https://dev.mysql.com/doc/relnotes/mysql/8.3/en/)
* [mysql@8.4](https://dev.mysql.com/doc/relnotes/mysql/8.4/en/)
* [mysql@9.0](https://dev.mysql.com/doc/relnotes/mysql/9.0/en/)

## How do I install these formulae?

Install the tap `brew tap frosit/homebrew-mysql` and then `brew install <formula>`.

```bash
brew install frosit/mysql/mysql@5.7 -s
brew install frosit/mysql/mysql@8.1 -s # broken
brew install frosit/mysql/mysql@8.2 -s
brew install frosit/mysql/mysql@8.3 -s
brew install frosit/mysql/mysql@8.4 -s
brew install frosit/mysql/mysql@9.0 -s
```

> The `-s` flag is to install from source. This is required for the mysql formulae as they are not pre-built.

Or `brew tap frosit/homebrew-mysql` and then `brew install <formula>`.

Or, in a [`brew bundle`](https://github.com/Homebrew/homebrew-bundle) `Brewfile`:

```ruby
tap "frosit/mysql"
brew "<formula>"
```

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
