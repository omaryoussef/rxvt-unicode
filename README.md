# Build Instructions

Install the following if on Ubuntu or use equivalent on other OSes:

    sudo apt-get install libperl-dev
    sudo apt-get install libxft-dev

Clone libev (Or libevent) and libptytty into working directory of this repo.

Configure with:

    ./configure --enable-everything --enable-256-color

Compile with

    make
    sudo make install

See `README.configure` for more details and configuration options.

# Extra

A sample .Xdefaults is provided copy it to your home directory and use:
    
    xrdb ~/.Xdefaults

to load the configurations

## Enable Perl extensions.
Clone urxvt-perls:

    https://github.com/muennich/urxvt-perls

And move all perl scripts to `/usr/lib/urxvt/perl/`.
