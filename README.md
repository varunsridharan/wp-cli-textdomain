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
    
## Usage

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


---

## Contribute
If you would like to help, please take a look at the list of
[issues][issues] or the [To Do](#-todo) checklist.

## License
This project is licensed under **General Public License v3.0 license**. See the [LICENSE](LICENSE) file for more info.

## Copyright
2017 - 2018 Varun Sridharan, [varunsridharan.in][website]

If you find it useful, let me know :wink:

You can contact me on [Twitter][twitter] or through my [email][email].

## Backed By
| [![DigitalOcean][do-image]][do-ref] | [![JetBrains][jb-image]][jb-ref] |  [![Tidio Chat][tidio-image]][tidio-ref] |
| --- | --- | --- |

[twitter]: https://twitter.com/varunsridharan2
[email]: mailto:varunsridharan23@gmail.com
[website]: https://varunsridharan.in
[issues]: issues/
[composer]: http://getcomposer.org/download/
[downloadzip]:https://github.com/varunsridharan/wp-cli-textdomain/archive/master.zip

[do-image]: https://vsp.ams3.cdn.digitaloceanspaces.com/cdn/DO_Logo_Horizontal_Blue-small.png
[jb-image]: https://vsp.ams3.cdn.digitaloceanspaces.com/cdn/phpstorm-small.png?v3
[tidio-image]: https://vsp.ams3.cdn.digitaloceanspaces.com/cdn/tidiochat-small.png
[do-ref]: https://s.svarun.in/Ef
[jb-ref]: https://www.jetbrains.com
[tidio-ref]: https://tidiochat.com

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
