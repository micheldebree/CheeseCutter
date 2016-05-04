# Build Cheesecutter on OSX

*UNDER CONSTRUCTION*

## Prerequisites

- XCode
- Homebrew
- SDL

## Setup development

    brew install acme
    brew install ldc
    brew install dmd
    
    
## Build

### Make executables
    make -f Makefile.mac
    
### Make CheeseCutter.app
    make -f Makefile.mac release
    
### Make Cheesecutter.dmg    
    make -f Makefile.mac dist
     
