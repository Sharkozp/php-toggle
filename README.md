# php-toggle

I created small script for switching PHP version in OSX

Right now it is supporting only 2 version - 7.0 and 7.1

## Quick Installation

```
curl -L https://raw.githubusercontent.com/Sharkozp/php-toggle/master/php-toggle > /usr/local/bin/php-toggle
```

## Installation with clone

```
git clone git@github.com:Sharkozp/php-toggle.git
```

## Make sure `php-toggle` is executable

```
cd php-toggle/
chmod +x php-toggle 
```

Add `/usr/local/bin` to your `$PATH`. If you use the Bash shell, you can do this by running this command:
```
echo 'export PATH="/usr/local/bin:$PATH"' >> $HOME/.bashrc
```
You may need to restart your shell for this to taake  effect, or refresh it with `source ~/.bashrc`.

If you want the global command then run:
```
ln -s `pwd`/php-toggle /usr/local/bin/php-toggle
```
Or
```
mv php-toggle /usr/local/bin/
```
