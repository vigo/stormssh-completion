# Bash Completion for StormSSH

Complete your commands like a Boss! while using [StormSSH][01]

## Installation

You can download bash script and add it to your environment. All you need
is to source it!

    cd /path/to/your/env/
    curl -O https://raw.githubusercontent.com/vigo/stormssh-completion/master/storm
    
    # add it to you .bashrc or so,
    source /path/to/your/env/storm

or, you can download it from `brew`:

    brew install homebrew/completions/stormssh-completion

## Usage

Completes your **Host** names in required commands such as; `clone` `delete`
`edit` `move` `update`

    $ storm [TAB]
    add         clone       delete_all  list        search      version     
    backup      delete      edit        move        update      web
    
    # completes your Hosts :)
    $ storm clone [TAB]
    you_connection_name1    you_connection_name3  you_connection_name5      you_connection_name7
    you_connection_name2    you_connection_name4  you_connection_name6      you_connection_name8

## Contribute

Please let me know if you need some more options. Please create an issue
and make a request. Also If you like to improve or add more features
please fork it and you know the rest :)

1. Fork it ( https://github.com/vigo/stormssh-completion )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request


## Contributes

* [Uğur "vigo" Özyılmazel][c1], Creator, maintaier


## License

This project licensed under MIT.


[01]: https://github.com/emre/storm
[c1]: https://github.com/vigo/