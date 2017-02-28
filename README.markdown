## Sublime Text 2 plugin: Ruby Extract Variable

A lightweight plugin that creates a variable from the highlighted text and inserts it on the line above, and replaces your expression with the variable name

### Shortcut Keys

**Windows / OSX / Linux:**

 * `ALT+V` - Extract Variable

#### How to perform the Extract Variable refactoring in a Ruby file.
1. Select the expression you wish to put into a method and hit the Shortcut Key (`Alt+V`)
2. Type the name of the new variable


### Installation

You have two options, the easier of which is to install this package through Package Control.

####Package Control

1. Ensure Package Control is installed and Sublime Text 2 has been restarted.
2. Open the Command Palette (Command+Shift+P on OS X, Control+Shift+P on Linux/Windows).
3. Select "Package Control: Install Package"
4. Select Ruby Extract Variable when the list appears.

Congratulations! The package is now installed on your system. 

#### Git

``` bash
$ git clone git://github.com/shadowradiance/ruby-extract-variable.git RubyExtractVariable
```

Further instructions below.

#### Windows XP, 7 and 8
Execute the commands below one by one in your Command prompt.

``` bash
$ cd "%APPDATA%\Sublime Text 2\Packages"
$ git clone git://github.com/shadowradiance/ruby-extract-variable.git "RubyExtractVariable"
```

#### Linux
Execute the commands below one by one in your terminal.

``` bash
$ cd ~/.config/sublime-text-2/Packages/
$ git clone git://github.com/shadowradiance/ruby-extract-variable.git RubyExtractVariable
```


#### Limitations

The plugin does not support multiple selections. 
If you select more than one block, only the first one will be used.

#### Special Thanks ####

This plugin is heavily inspired by: 

- https://github.com/patcorwin/ExtractAsVariable
- https://github.com/pashamur/ruby-extract-method
- https://code.tutsplus.com/tutorials/how-to-create-a-sublime-text-2-plugin--net-22685

