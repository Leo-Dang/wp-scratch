# WordPress Scratch

A flexible WordPress project from scratch.

## Requirements

- [PHP][1] >= 5.5
- [MySQL][2] >= 5.5
- [WP-CLI][3] >= 0.24
- [Composer][4] >= 1.0

## Installation

1. Setup server config file (server block or virtual host) for your site. You do not need to create MySQL database, it will be created while installing WordPress.
2. Run these two commands on your command line respectively:

  ```bash
  $ composer create-project wpstack/wp-scratch /path/to/project/directory
  $ cd /path/to/project/directory && ./install
  ```
  
3. Follow instructions to finish the installation. It's easy!

From now on, to install a new site, you just need to setup a new server config file, go the `/path/to/project/directory` and run `./install` on command line.

## Important Notes

- Since we're using `$_SERVER['SERVER_NAME']`, please make sure `SERVER_NAME` is configured properly in your server config file.

## Contributing

Contribution is always welcome!


[1]: https://secure.php.net
[2]: http://dev.mysql.com/downloads/mysql/
[3]: http://wp-cli.org
[4]: https://getcomposer.org
