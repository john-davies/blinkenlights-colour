# Blinkenlights Colour

This is my repository of the basic software for the Blinkenlights project ( http://blinkenlights.net/ ). The files are taken directly from the download links on that site ( http://blinkenlights.net/project/developer-tools ).

*The same software also exists in a GitHub repository ( https://github.com/blinkenlights/blinkenlights ) but that version lacks the files ( `configure` etc. ) needed to build the software. There are some build instructions but they seem to refer to a CVS checkout which I have no further details of. As far as I can see the code files are identical to those on the Blinkenlights website.*

I have made some additions to the basic code:

- Enable colour packets to be processed correctly.

Build instructions are contained in the README files in each section.

# Simple Test Setup

Once the software has been built and installed then the following is a very simple test to check for correct operation:

- `blinkensim -l` gives a list of themes available
- `blinkensim hdl-640x480` starts the simulator in a new window ( *Haus des Lehrers (Berlin) (18x8) on 640x480* )
- Some test movies can be found in `blib-1.1.7/test/movies`
- `bsend camel-18x8.blm` - shows an animation in the simulator window (  *add the "-l" option to loop the movie* )

Most commands have basic help by using the `-?` option
