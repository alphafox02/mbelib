mbelib 1.3.1

Redirect all printf to stderr (	Change all printf to fprintf(stderr,)
Increment to 1.3.1 to make it easy to differentiate if this particular version is installed

PATENT NOTICE

    This source code is provided for educational purposes only.  It is
    a written description of how certain voice encoding/decoding
    algorythims could be implemented.  Executable objects compiled or
    derived from this package may be covered by one or more patents.
    Readers are strongly advised to check for any patent restrictions or
    licencing requirements before compiling or using this source code.

mbelib 1.3.0

        mbelib supports the 7200x4400 bit/s codec used in P25 Phase 1,
        the 7100x4400 bit/s codec used in ProVoice and the "Half Rate"
        3600x2250 bit/s vocoder used in various radio systems.

Example building instructions on Ubuntu:

    sudo apt update
    sudo apt install git make cmake # Update packages
    git clone https://github.com/lwvmobile/mbelib
    cd mbelib                           # Move into source folder
    mkdir build                         # Create build directory
    cd build                            # Move to build directory
    cmake ..                            # Create Makefile for current system
    make                                # Compiles the library
    sudo make install                   # Library is installed into computer
