# php-toggle

I created small script for switching PHP version in OSX

Right now it is supporting only 2 version - 7.0 and 7.1

## Quick Installation

```
curl -L https://raw.githubusercontent.com/Sharkozp/php-toogle/master/php-toogle > /usr/local/bin/php-toogle
```

## Installation with clone

```
git clone git@github.com:Sharkozp/php-toogle.git
```

## Make sure `php-toogle` is executable

```
cd php-toogle/
chmod +x php-toogle 
```

Add `/usr/local/bin` to your `$PATH`. If you use the Bash shell, you can do this by running this command:
```
echo 'export PATH="/usr/local/bin:$PATH"' >> $HOME/.bashrc
```
You may need to restart your shell for this to take effect, or refresh it with `source ~/.bashrc`.

If you want the global command then run:
```
ln -s `pwd`/php-toogle /usr/local/bin/php-toogle
```
Or
```
mv php-toogle /usr/local/bin/
```
