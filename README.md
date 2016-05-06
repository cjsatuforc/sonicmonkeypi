# sonicmonkeypi
PI (and other small Linux) incarnation of my Android app "Sonic Monkey", the ambient drone noise machine.

# Required
      *nix with /bin/sh
      
      Perl (3+?) - sudo apt-get install perl
      
      curl       - sudo apt-get install curl 
      
      sox        - sudo apt-get install sox

      FreeSound.org API key, from 
      freesound.org/help/developers/

# Setup
      1. Place API key in token.txt
      2. Optional: Edit keywords.txt

# Run: Using built-in + keywords.txt:

      perl sonicmonkeypi

# Run: Add keyword 'monkeys' this time only:

      perl sonicmonkeypi monkeys

# Run: Use only keyword 'monkeys':

     perl sonicmonkeypi =monkeys

# Bugs:
      Many. Almost no error checking. No cache expirey yet either!
