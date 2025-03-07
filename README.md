<h1 align="center">PHP CLI Demo</h1>

<p align="center">PHP command-line tool demonstration</p>

<p align="center">
    <img alt="Preview" src="/art/preview.png">
    <p align="center">
        <a href="https://github.com/tedblanc/php-cli-demo/actions"><img alt="Build Status" src="https://github.com/tedblanc/php-cli-demo/workflows/CI/badge.svg"></a>
        <a href="https://packagist.org/packages/tedblanc/php-cli-demo"><img alt="Latest Stable Version" src="https://poser.pugx.org/tedblanc/php-cli-demo/v"></a>
        <a href="https://packagist.org/packages/tedblanc/php-cli-demo"><img alt="License" src="https://poser.pugx.org/tedblanc/php-cli-demo/license"></a>
    </p>
</p>

## Install

This CLI application is a small game written in PHP and is installed using [Composer](https://getcomposer.org):

```
composer global require tedblanc/php-cli-demo
```

Make sure the `~/.composer/vendor/bin` directory is in your system's `PATH`.

<details>
<summary>Show me how</summary>

If it's not already there, add the following line to your Bash configuration file (usually `~/.bash_profile`, `~/.bashrc`, `~/.zshrc`, etc.):

```
export PATH=~/.config/composer/vendor/bin:$PATH
```

If the file doesn't exist, create it.

Run the following command on the file you've just updated for the change to take effect:

```
source ~/.bash_rc
```
</details>

## Use

All you need to do is call the `play` command to start the game:

```
demo play
```

## Update

```
composer global update tedblanc/php-cli-demo
```

## Delete

```
composer global remove tedblanc/php-cli-demo
```