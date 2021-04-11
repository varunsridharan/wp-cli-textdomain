# WP Cli 
This CLI Package Provides WP Theme / Plugin Developers To Add TextDomains Easily

[![Latest Stable Version][latest-stable-version-img]][latest-stable-version-link]
[![Latest Unstable Version][latest-Unstable-version-img]][latest-Unstable-version-link]
[![Total Downloads][total-downloads-img]][total-downloads-link]
[![WP][wpcs-img]][wpcs-link]
[![License][license-img]][license-link]
[![composer.lock available][composerlock-img]][composerlock-link]

## Installation
The preferred way to install this extension is through [Composer][composer].

To install **WP-Cli library**, simply:

    $ composer require varunsridharan/wp-cli-textdomain
    
## Add Text Domain Usage

### Update Textdomains for all files inside a folder
```
$ ./vendor/bin/add-text-domain.bat -i your-textdomain your-folder-path
```

### Update Textdomains for a file
```
$ ./vendor/bin/add-text-domain.bat -i your-textdomain ./your-path/your-file.php
```

## CLI Arguments
| Argument | Description |
| -------- | ----------- |
| `-i` | if provided then changes will be saved in the same file where its updated if not it will provide the file output | 


## Make Pot Usage
#### CMD
```
$ ./vendor/bin/makepot.bat ./pot-config.json
```
#### JSON File `pot-config.json`
```json
{
  "src"     : "./",
  "dist"    : "languages/plugin-slug.pot",
  "domain"  : "project-text-domain",
  "exclude" : "comma seperated folders name",
  "headers" : {
	"Last-Translator" : "Author Name\n",
	"Language-Team"   : "LANGUAGE ll@example.com"
  }
}
```

---

<!-- START common-footer.mustache  -->

<!-- END common-footer.mustache  -->

[composer]: http://getcomposer.org/download/
[downloadzip]:https://github.com/varunsridharan/wp-cli-textdomain/archive/master.zip

[latest-stable-version-img]: https://poser.pugx.org/varunsridharan/wp-cli-textdomain/version
[latest-Unstable-version-img]: https://poser.pugx.org/varunsridharan/wp-cli-textdomain/v/unstable
[total-downloads-img]: https://poser.pugx.org/varunsridharan/wp-cli-textdomain/downloads
[Latest-Unstable-version-img]: https://poser.pugx.org/varunsridharan/wp-cli-textdomain/v/unstable
[wpcs-img]: https://img.shields.io/badge/WordPress-Standar-1abc9c.svg
[license-img]: https://poser.pugx.org/varunsridharan/wp-cli-textdomain/license
[composerlock-img]: https://poser.pugx.org/varunsridharan/wp-cli-textdomain/composerlock

[latest-stable-version-link]: https://packagist.org/packages/varunsridharan/wp-cli-textdomain
[latest-Unstable-version-link]: https://packagist.org/packages/varunsridharan/wp-cli-textdomain
[total-downloads-link]: https://packagist.org/packages/varunsridharan/wp-cli-textdomain
[Latest-Unstable-Version-link]: https://packagist.org/packages/varunsridharan/wp-cli-textdomain
[wpcs-link]: https://github.com/WordPress-Coding-Standards/WordPress-Coding-Standards/
[license-link]: https://packagist.org/packages/varunsridharan/wp-cli-textdomain
[composerlock-link]: https://packagist.org/packages/varunsridharan/wp-cli-textdomain
