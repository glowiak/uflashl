# uFlashl - flash games and apps launcher for UNIX/POSIX


# Dependiences
  - i386 version of wine
  - curl
  - cpio
  - xz
  - UNIX/POSIX/Linux/BSD system (or wsl on windows)
  - bash

# Size
Archive is 244,2 MB; Extracted took 617.2 MB on your disk.

# Download
Current 0.1 release: [click here](https://github.com/glowiak/uflashl/releases/download/0.1/uflashl-0.1.cpio.xz)

# Installation
Just extract archive. Want terminal? Type this in installation dir:
  - xz -d uflashl-0.1.cpio.xz
  - mkdir uflashl
  - cd uflashl
  - cpio -i < ../uflashl-0.1.cpio

# Usage
After installation you can finnaly play those flash games etc. Open terminal in directory with extracted files and learn the syntax:
  - ./uflashl help      - display help
  - ./uflashl list      - display list of available app and games (internet required)
  - ./uflashl install <appname>     - install app or game
  - ./uflashl launch <appname>      - launch app or game
  - ./uflashl delete <appname>      - delete app or game
