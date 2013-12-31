git-hooks
========================

## About

This is a pre commit script that check committer.

## Installation

    sudo ./install.sh

## Usage

    $ git commit -m "msg"
    
    Author = USER_NAME <USER_EMAIL>
    Do you want to me to keep it this way? [Y/n] n
    Username:NEW_USER_NAME
    Email:NEW_USER_EMAIL
    Please commit that again...
    
    $ git commit -m "msg"
    
    Author = NEW_USER_EMAIL <NEW_USER_EMAIL>

## License

MIT
