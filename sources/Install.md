Carp is mainly developed on macOS, but it also works fine on Linux. Windows is
currently not supported - but please do [get in
touch](https://gitter.im/carp-lang/Carp) if you want to help out with that!

Please note that to install the current version of Carp, you’ll have
to have some familiarity with the command line, and be in the mood to
tinker a little bit!

### Building the Carp executable from source

1. Make sure you have [Stack](https://docs.haskellstack.org/en/stable/README/)
   installed.
2. Clone this repo to your machine.
3. Run `stack build` in the root of the project directory.
4. `stack install` will install the Carp command line tool for easy access on
   your system.
5. Make sure that the directory where stack installs executables is on your
   path, for instance by typing `export PATH=~/.local/bin:$PATH`. To make this
   permanent, you’ll have to add this to your `.bashrc`.

### Setting the `CARP_DIR` variable

The Carp executable must know where to find its core libraries and
other files. Set the environment variable `CARP_DIR` so
that it points to the root of the Carp repository.

Add `export CARP_DIR=~/Carp` to your `.bashrc` file. The directory should be
the one you cloned the repository in.

You should now be able to start Carp from anywhere using the command `carp`!
