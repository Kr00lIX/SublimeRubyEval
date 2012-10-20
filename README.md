RubyEval
========

Evaluate selections in ♥♥♥Ruby♥♥♥, and print it to editor.

## Installation

```
$ cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages
$ git clone https://github.com/jugyo/SublimeRubyEval.git RubyEval
```

## Usage

The `ruby_eval` command is binded to `Ctrl + Shift + e`.

## Customize

In your Preferences.sublime-settings:

```
{
  …
  "ruby_eval": {
    // "ruby": "/usr/local/bin/ruby"
    "ruby": "~/.rbenv/versions/2.0.0-dev/bin/ruby"
  }
  …
}
```

The Default is `ruby`.
