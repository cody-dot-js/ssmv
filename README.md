# ssmv (Screenshot Move)

Command line tool to move all macOS screenshots on your Desktop into a folder labeled screenshots_YYYY-MM-DD.

See also: [ssmv-today](https://github.com/dev-cprice/ssmv-today)

## Installation

In your terminal, run the following commands:

```sh
git clone https://github.com/dev-cprice/ssmv.git
cd ssmv
cp ssmv /usr/local/bin/ssmv
```

To add the thin Mac App, follow the above commands and then run:

```sh
cp -r ScreenshotMove.app /Applications
```

## Usage

Take as many screenshots as you want with `cmd+shift+3` or `cmd+shift+4`, then in your terminal, run `ssmv`:

### CLI (Command Line Interface)

```sh
# ex: 6 screenshots taken, located at ~/Desktop
$ ssmv
Making new folder at: /Users/YOUR_USERNAME/Desktop/2019-01-23
Moving 6 screenshots into /Users/YOUR_USERNAME/Desktop/2019-01-23
```

### Application

Run the `ScreenshotMove` app and a dialog will appear displaying how many screenshots it moved and to what folder, just like the CLI version.
