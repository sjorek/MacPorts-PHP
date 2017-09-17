# MacPorts-PHP
The repository is for missing PHP-related MacPorts, like “composer”.

## Usage

1. Install MacPorts from https://www.macports.org.
2. Clone this repository to your desired location and add it to macports'
   `sources.conf`.

## Example - install it in your user's home-directory under Documents:

```bash
cd ${HOME}/Documents
git clone https://github.com/sjorek/MacPorts-PHP
sudo bash -c "cat <<EOF >>/opt/local/etc/macports/sources.conf

file:///Users/${USER}/Documents/MacPorts-PHP [nosync]

EOF"
```

## List of (currently) provided MacPorts

    composer                       @1.5.2          php/composer
    composer-php                   @1.5.2          php/composer
    composer-php53                 @1.5.2          php/composer
    composer-php54                 @1.5.2          php/composer
    composer-php55                 @1.5.2          php/composer
    composer-php56                 @1.5.2          php/composer
    composer-php70                 @1.5.2          php/composer
    composer-php71                 @1.5.2          php/composer
    composer-php72                 @1.5.2          php/composer
    composer_select                @1.0            sysutils/composer_select

## What if composer has been updated and this repository does not reflect this?

Look at [the contribution guidelines.](CONTRIBUTING.md)
